## G.VAR.03  变量遮蔽功能应当合理使用

**【级别】** 建议

**【描述】**

变量遮蔽功能在功能上属于一种继承式可变。他会覆盖之前的变量绑定，而创建一个新的同名的变量绑定。

1. 在同一个作用域中，非必要时不宜通过新变量声明遮蔽旧变量声明的方式来修改变量。
2. 在子作用域内修改“哨兵变量”时，应该避免使用变量遮蔽功能，防止引起逻辑bug。
3. 如果使用变量遮蔽，禁止用不同类型的变量遮蔽前一个变量，如果实现同一个 `trait` 的可以例外。

**【反例】**

```rust
let x = 2;
let x = x + 1; // 将会改变x的值

let x = &x; // 只是改变引用级别

let x = y; // 更早的绑定
let x = z; // 遮蔽了更早的绑定

// or

fn main() {
    let mut a = 0;
    {
        // 这里使用变量遮蔽逻辑已经被改变
        let a = 42;
    }
    
    a; // use a again
}
```

**【正例】**

```rust
let x = 2;
let y = x + 1; // 不改变x的值，声明新的变量y

let y = &x; // 不改变x的绑定，声明新的变量

let w = z; // 使用不同的名字

// or

fn main() {
    let mut a = 0;
    {
        // do something
        a = 42;
    }
    a;// use a again
}
```

**【例外】**

在某些场景，可能会临时准备或处理一些数据，但在此之后，数据只用于检查而非修改。

那么可以将其通过变量遮蔽功能，重写绑定为不可变变量，来表明这种 临时可变，但后面不变的意图。

```rust
// 不建议用法
let data = { 
    let mut data = get_vec();
    data.sort();
    data // 虽然后面不再改动，但代码语义上没有表现出来先改变，后不变那种顺序语义
};

// Here `data` is immutable.
```

```rust
// 建议用法
let mut data = get_vec();
data.sort(); // 临时需要排序
let data = data; //  由编译器确保后面不再改动

// Here `data` is immutable.
```

**【Lint 检测】**

| lint name                                                    | Clippy 可检测 | Rustc 可检测 | Lint Group | level |
| ------------------------------------------------------------ | ------------- | ------------ | ---------- | ----- |
| [shadow_reuse](https://rust-lang.github.io/rust-clippy/master/#shadow_reuse) | yes           | no           | restriction   | allow |
| [shadow_same](https://rust-lang.github.io/rust-clippy/master/#shadow_same) | yes           | no           | restriction   | allow |
| [shadow_unrelated](https://rust-lang.github.io/rust-clippy/master/#shadow_unrelated) | yes           | no           | restriction   | allow |

