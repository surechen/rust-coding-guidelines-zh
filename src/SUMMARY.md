# Rust 编码规范

- [概述](./overview.md)
    - [为什么需要 Rust 编码规范](./safe-guides/overview/why.md)
    - [编码规范基本约定](./safe-guides/overview/convention.md)
- [代码风格](./safe-guides/code_style.md)
    - [命名](./safe-guides/code_style/naming.md)
        - [P.NAM.01](./safe-guides/code_style/naming/P.NAM.01.md)
        - [P.NAM.02](./safe-guides/code_style/naming/P.NAM.02.md)
        - [P.NAM.03](./safe-guides/code_style/naming/P.NAM.03.md)
        - [P.NAM.04](./safe-guides/code_style/naming/P.NAM.04.md)
        - [P.NAM.05](./safe-guides/code_style/naming/P.NAM.05.md)
        - [P.NAM.06](./safe-guides/code_style/naming/P.NAM.06.md)
        - [P.NAM.07](./safe-guides/code_style/naming/P.NAM.07.md)
        - [P.NAM.08](./safe-guides/code_style/naming/P.NAM.08.md)
        - [P.NAM.09](./safe-guides/code_style/naming/P.NAM.09.md)
        - [G.NAM.01](./safe-guides/code_style/naming/G.NAM.01.md)
        - [G.NAM.02](./safe-guides/code_style/naming/G.NAM.02.md)
    - [格式](./safe-guides/code_style/fmt.md)
        - [P.FMT.01](./safe-guides/code_style/fmt/P.FMT.01.md)
        - [P.FMT.02](./safe-guides/code_style/fmt/P.FMT.02.md)
        - [P.FMT.03](./safe-guides/code_style/fmt/P.FMT.03.md)
        - [P.FMT.04](./safe-guides/code_style/fmt/P.FMT.04.md)
        - [P.FMT.05](./safe-guides/code_style/fmt/P.FMT.05.md)
        - [P.FMT.06](./safe-guides/code_style/fmt/P.FMT.06.md)
        - [P.FMT.07](./safe-guides/code_style/fmt/P.FMT.07.md)
        - [P.FMT.08](./safe-guides/code_style/fmt/P.FMT.08.md)
        - [P.FMT.09](./safe-guides/code_style/fmt/P.FMT.09.md)
        - [P.FMT.10](./safe-guides/code_style/fmt/P.FMT.10.md)
        - [P.FMT.11](./safe-guides/code_style/fmt/P.FMT.11.md)
        - [P.FMT.12](./safe-guides/code_style/fmt/P.FMT.12.md)
        - [P.FMT.13](./safe-guides/code_style/fmt/P.FMT.13.md)
        - [P.FMT.14](./safe-guides/code_style/fmt/P.FMT.14.md)
        - [P.FMT.15](./safe-guides/code_style/fmt/P.FMT.15.md)
        - [P.FMT.16](./safe-guides/code_style/fmt/P.FMT.16.md)
    - [注释](./safe-guides/code_style/comments.md)
        - [P.CMT.01](./safe-guides/code_style/comments/P.CMT.01.md)
        - [P.CMT.02](./safe-guides/code_style/comments/P.CMT.02.md)
        - [P.CMT.03](./safe-guides/code_style/comments/P.CMT.03.md)
        - [P.CMT.04](./safe-guides/code_style/comments/G.CMT.04.md)
        - [P.CMT.05](./safe-guides/code_style/comments/G.CMT.05.md)
        - [G.CMT.01](./safe-guides/code_style/comments/G.CMT.01.md)
        - [G.CMT.02](./safe-guides/code_style/comments/G.CMT.02.md)
        - [G.CMT.03](./safe-guides/code_style/comments/G.CMT.03.md)
- [编码实践](./safe-guides/coding_practice.md)
    - [常量](./safe-guides/coding_practice/consts.md)
        - [G.CNS.01](./safe-guides/coding_practice/consts/G.CNS.01.md)
        - [G.CNS.02](./safe-guides/coding_practice/consts/G.CNS.02.md)
        - [G.CNS.03](./safe-guides/coding_practice/consts/G.CNS.03.md)
        - [G.CNS.04](./safe-guides/coding_practice/consts/G.CNS.04.md)
        - [G.CNS.05](./safe-guides/coding_practice/consts/G.CNS.05.md)
    - [静态变量](./safe-guides/coding_practice/statics.md)
        - [G.STV.01](./safe-guides/coding_practice/statics/G.STV.01.md)
    - [本地变量](./safe-guides/coding_practice/variables.md)
        - [P.VAR.01](./safe-guides/coding_practice/variables/P.VAR.01.md)
        - [P.VAR.02](./safe-guides/coding_practice/variables/P.VAR.02.md)
        - [G.VAR.01](./safe-guides/coding_practice/variables/G.VAR.01.md)
        - [G.VAR.02](./safe-guides/coding_practice/variables/G.VAR.02.md)
        - [G.VAR.03](./safe-guides/coding_practice/variables/G.VAR.03.md)
        - [G.VAR.04](./safe-guides/coding_practice/variables/G.VAR.04.md)
    - [数据类型](./safe-guides/coding_practice/data-type.md)
        - [P.TYP.01](./safe-guides/coding_practice/data-type/P.TYP.01.md)
        - [G.TYP.01](./safe-guides/coding_practice/data-type/G.TYP.01.md)
        - [G.TYP.02](./safe-guides/coding_practice/data-type/G.TYP.02.md)
        - [G.TYP.03](./safe-guides/coding_practice/data-type/G.TYP.03.md)
        - [布尔](./safe-guides/coding_practice/data-type/bool.md)
            - [G.TYP.BOL.01](./safe-guides/coding_practice/data-type/bool/G.TYP.BOL.01.md)
            - [G.TYP.BOL.02](./safe-guides/coding_practice/data-type/bool/G.TYP.BOL.02.md)
            - [G.TYP.BOL.03](./safe-guides/coding_practice/data-type/bool/G.TYP.BOL.03.md)
            - [G.TYP.BOL.04](./safe-guides/coding_practice/data-type/bool/G.TYP.BOL.04.md)
            - [G.TYP.BOL.05](./safe-guides/coding_practice/data-type/bool/G.TYP.BOL.05.md)
            - [G.TYP.BOL.06](./safe-guides/coding_practice/data-type/bool/G.TYP.BOL.06.md)
        - [字符](./safe-guides/coding_practice/data-type/char.md)
            - [G.TYP.CHR.01](./safe-guides/coding_practice/data-type/char/G.TYP.CHR.01.md)
            - [G.TYP.CHR.02](./safe-guides/coding_practice/data-type/char/G.TYP.CHR.02.md)
            - [G.TYP.CHR.03](./safe-guides/coding_practice/data-type/char/G.TYP.CHR.03.md)
        - [整数](./safe-guides/coding_practice/data-type/int.md)
            - [G.TYP.INT.01](./safe-guides/coding_practice/data-type/int/G.TYP.INT.01.md)
            - [G.TYP.INT.02](./safe-guides/coding_practice/data-type/int/G.TYP.INT.02.md)
            - [G.TYP.INT.03](./safe-guides/coding_practice/data-type/int/G.TYP.INT.03.md)
        - [浮点数](./safe-guides/coding_practice/data-type/float.md)
            - [G.TYP.FLT.01](./safe-guides/coding_practice/data-type/float/G.TYP.FLT.01.md)
            - [G.TYP.FLT.02](./safe-guides/coding_practice/data-type/float/G.TYP.FLT.02.md)
            - [G.TYP.FLT.03](./safe-guides/coding_practice/data-type/float/G.TYP.FLT.03.md)
            - [G.TYP.FLT.04](./safe-guides/coding_practice/data-type/float/G.TYP.FLT.04.md)
            - [G.TYP.FLT.05](./safe-guides/coding_practice/data-type/float/G.TYP.FLT.05.md)
        - [切片](./safe-guides/coding_practice/data-type/slice.md)
            - [P.TYP.SLC.01](./safe-guides/coding_practice/data-type/slice/P.TYP.SLC.01.md)
            - [P.TYP.SLC.02](./safe-guides/coding_practice/data-type/slice/P.TYP.SLC.02.md)
        - [元组](./safe-guides/coding_practice/data-type/tuple.md)
            - [G.TYP.TUP.01](./safe-guides/coding_practice/data-type/tuple/G.TYP.TUP.01.md)
        - [固定长度数组](./safe-guides/coding_practice/data-type/array.md)
            - [G.TYP.ARR.01](./safe-guides/coding_practice/data-type/array/G.TYP.ARR.01.md)
            - [G.TYP.ARR.02](./safe-guides/coding_practice/data-type/array/G.TYP.ARR.02.md)
            - [G.TYP.ARR.03](./safe-guides/coding_practice/data-type/array/G.TYP.ARR.03.md)
        - [动态数组](./safe-guides/coding_practice/data-type/vec.md)
            - [P.TYP.VEC.01](./safe-guides/coding_practice/data-type/vec/P.TYP.VEC.01.md)
            - [P.TYP.VEC.02](./safe-guides/coding_practice/data-type/vec/P.TYP.VEC.02.md)
            - [G.TYP.VEC.01](./safe-guides/coding_practice/data-type/vec/G.TYP.VEC.01.md)
        - [结构体](./safe-guides/coding_practice/data-type/struct.md)
            - [P.TYP.SCT.01](./safe-guides/coding_practice/data-type/struct/P.TYP.SCT.01.md)
            - [P.TYP.SCT.02](./safe-guides/coding_practice/data-type/struct/P.TYP.SCT.02.md)
            - [G.TYP.SCT.01](./safe-guides/coding_practice/data-type/struct/G.TYP.SCT.01.md)
            - [G.TYP.SCT.02](./safe-guides/coding_practice/data-type/struct/G.TYP.SCT.02.md)
            - [G.TYP.SCT.03](./safe-guides/coding_practice/data-type/struct/G.TYP.SCT.03.md)
        - [枚举体](./safe-guides/coding_practice/data-type/enum.md)
            - [G.TYP.ENM.01](./safe-guides/coding_practice/data-type/enum/G.TYP.ENM.01.md)
            - [G.TYP.ENM.02](./safe-guides/coding_practice/data-type/enum/G.TYP.ENM.02.md)
            - [G.TYP.ENM.03](./safe-guides/coding_practice/data-type/enum/G.TYP.ENM.03.md)
            - [G.TYP.ENM.04](./safe-guides/coding_practice/data-type/enum/G.TYP.ENM.04.md)
            - [G.TYP.ENM.05](./safe-guides/coding_practice/data-type/enum/G.TYP.ENM.05.md)
            - [G.TYP.ENM.06](./safe-guides/coding_practice/data-type/enum/G.TYP.ENM.06.md)
    - [表达式](./safe-guides/coding_practice/expr.md)
        - [G.EXP.01](./safe-guides/coding_practice/expr/G.EXP.01.md)
        - [G.EXP.02](./safe-guides/coding_practice/expr/G.EXP.02.md)
        - [G.EXP.03](./safe-guides/coding_practice/expr/G.EXP.03.md)
        - [G.EXP.04](./safe-guides/coding_practice/expr/G.EXP.04.md)
        - [G.EXP.05](./safe-guides/coding_practice/expr/G.EXP.05.md)
        - [G.EXP.06](./safe-guides/coding_practice/expr/G.EXP.06.md)
    - [控制流程](./safe-guides/coding_practice/control-flow.md)
        - [P.CTF.01](./safe-guides/coding_practice/control-flow/P.CTF.01.md)
        - [P.CTF.02](./safe-guides/coding_practice/control-flow/P.CTF.02.md)
        - [G.CTF.01](./safe-guides/coding_practice/control-flow/G.CTF.01.md)
        - [G.CTF.02](./safe-guides/coding_practice/control-flow/G.CTF.02.md)
        - [G.CTF.03](./safe-guides/coding_practice/control-flow/G.CTF.03.md)
        - [G.CTF.04](./safe-guides/coding_practice/control-flow/G.CTF.04.md)
    - [字符串](./safe-guides/coding_practice/strings.md)
        - [P.STR.01](./safe-guides/coding_practice/strings/P.STR.01.md)
        - [P.STR.02](./safe-guides/coding_practice/strings/P.STR.02.md)
        - [P.STR.03](./safe-guides/coding_practice/strings/P.STR.03.md)
        - [P.STR.04](./safe-guides/coding_practice/strings/P.STR.04.md)
        - [P.STR.05](./safe-guides/coding_practice/strings/P.STR.05.md)
        - [G.STR.01](./safe-guides/coding_practice/strings/G.STR.01.md)
        - [G.STR.02](./safe-guides/coding_practice/strings/G.STR.02.md)
        - [G.STR.03](./safe-guides/coding_practice/strings/G.STR.03.md)
        - [G.STR.04](./safe-guides/coding_practice/strings/G.STR.04.md)
        - [G.STR.05](./safe-guides/coding_practice/strings/G.STR.05.md)
    - [集合容器](./safe-guides/coding_practice/collections.md)
        - [P.CLT.01](./safe-guides/coding_practice/collections/P.CLT.01.md)
        - [G.CLT.01](./safe-guides/coding_practice/collections/G.CLT.01.md)
    - [函数设计](./safe-guides/coding_practice/fn-design.md)
        - [P.FUD.01](./safe-guides/coding_practice/fn-design/P.FUD.01.md)
        - [P.FUD.02](./safe-guides/coding_practice/fn-design/P.FUD.02.md)
        - [G.FUD.01](./safe-guides/coding_practice/fn-design/G.FUD.01.md)
        - [G.FUD.02](./safe-guides/coding_practice/fn-design/G.FUD.02.md)
        - [G.FUD.03](./safe-guides/coding_practice/fn-design/G.FUD.03.md)
        - [G.FUD.04](./safe-guides/coding_practice/fn-design/G.FUD.04.md)
        - [G.FUD.05](./safe-guides/coding_practice/fn-design/G.FUD.05.md)
        - [G.FUD.06](./safe-guides/coding_practice/fn-design/G.FUD.06.md)
    - [泛型](./safe-guides/coding_practice/generic.md)
        - [P.GEN.01](./safe-guides/coding_practice/generic/P.GEN.01.md)
        - [P.GEN.02](./safe-guides/coding_practice/generic/P.GEN.02.md)
        - [P.GEN.03](./safe-guides/coding_practice/generic/P.GEN.03.md)
        - [P.GEN.04](./safe-guides/coding_practice/generic/P.GEN.04.md)
        - [P.GEN.05](./safe-guides/coding_practice/generic/P.GEN.05.md)
        - [G.GEN.01](./safe-guides/coding_practice/generic/G.GEN.01.md)
        - [G.GEN.02](./safe-guides/coding_practice/generic/G.GEN.02.md)
    - [特质](./safe-guides/coding_practice/traits.md)
        - [P.TRA.01](./safe-guides/coding_practice/traits/P.TRA.01.md)
        - [标准库内置 trait](./safe-guides/coding_practice/traits/std-builtin.md)
            - [P.TRA.BLN.01](./safe-guides/coding_practice/traits/std-builtin/P.TRA.BLN.01.md)
            - [G.TRA.BLN.01](./safe-guides/coding_practice/traits/std-builtin/G.TRA.BLN.01.md)
            - [G.TRA.BLN.02](./safe-guides/coding_practice/traits/std-builtin/G.TRA.BLN.02.md)
            - [G.TRA.BLN.03](./safe-guides/coding_practice/traits/std-builtin/G.TRA.BLN.03.md)
            - [G.TRA.BLN.04](./safe-guides/coding_practice/traits/std-builtin/G.TRA.BLN.04.md)
            - [G.TRA.BLN.05](./safe-guides/coding_practice/traits/std-builtin/G.TRA.BLN.05.md)
            - [G.TRA.BLN.06](./safe-guides/coding_practice/traits/std-builtin/G.TRA.BLN.06.md)
            - [G.TRA.BLN.07](./safe-guides/coding_practice/traits/std-builtin/G.TRA.BLN.07.md)
            - [G.TRA.BLN.08](./safe-guides/coding_practice/traits/std-builtin/G.TRA.BLN.08.md)
            - [G.TRA.BLN.09](./safe-guides/coding_practice/traits/std-builtin/G.TRA.BLN.09.md)
            - [G.TRA.BLN.10](./safe-guides/coding_practice/traits/std-builtin/G.TRA.BLN.10.md)
        - [trait 对象](./safe-guides/coding_practice/traits/trait-object.md)
             - [P.TRA.OBJ.01](./safe-guides/coding_practice/traits/trait-object/P.TRA.OBJ.01.md)
             - [P.TRA.OBJ.02](./safe-guides/coding_practice/traits/trait-object/P.TRA.OBJ.02.md)
    - [错误处理](./safe-guides/coding_practice/error-handle.md)
        - [P.ERR.01](./safe-guides/coding_practice/error-handle/P.ERR.01.md)
        - [P.ERR.02](./safe-guides/coding_practice/error-handle/P.ERR.02.md)
        - [G.ERR.01](./safe-guides/coding_practice/error-handle/G.ERR.01.md)
        - [G.ERR.02](./safe-guides/coding_practice/error-handle/G.ERR.02.md)
    - [内存管理](./safe-guides/coding_practice/memory.md)
        - [生命周期](./safe-guides/coding_practice/memory/lifetime.md)
            - [P.MEM.LFT.01](./safe-guides/coding_practice/memory/lifetime/P.MEM.LFT.01.md)
            - [P.MEM.LFT.02](./safe-guides/coding_practice/memory/lifetime/P.MEM.LFT.02.md)
        - [智能指针](./safe-guides/coding_practice/memory/smart-ptr.md)
            - [P.MEM.SPT.01](./safe-guides/coding_practice/memory/smart-ptr/P.MEM.SPT.01.md)
        - [Box 类型](./safe-guides/coding_practice/memory/box.md)
            - [G.MEM.BOX.01](./safe-guides/coding_practice/memory/box/G.MEM.BOX.01.md)
            - [G.MEM.BOX.02](./safe-guides/coding_practice/memory/box/G.MEM.BOX.02.md)
            - [G.MEM.BOX.03](./safe-guides/coding_practice/memory/box/G.MEM.BOX.03.md)
        - [Drop 析构](./safe-guides/coding_practice/memory/drop.md)
            - [G.MEM.DRP.01](./safe-guides/coding_practice/memory/drop/G.MEM.DRP.01.md)
    - [模块](./safe-guides/coding_practice/module.md)
        - [P.MOD.01](./safe-guides/coding_practice/module/P.MOD.01.md)
        - [P.MOD.02](./safe-guides/coding_practice/module/P.MOD.02.md)
        - [G.MOD.01](./safe-guides/coding_practice/module/G.MOD.01.md)
        - [G.MOD.02](./safe-guides/coding_practice/module/G.MOD.02.md)
        - [G.MOD.03](./safe-guides/coding_practice/module/G.MOD.03.md)
        - [G.MOD.04](./safe-guides/coding_practice/module/G.MOD.04.md)
        - [G.MOD.05](./safe-guides/coding_practice/module/G.MOD.05.md)
    - [包管理](./safe-guides/coding_practice/cargo.md)
        - [P.CAR.01](./safe-guides/coding_practice/cargo/P.CAR.01.md)
        - [P.CAR.02](./safe-guides/coding_practice/cargo/P.CAR.02.md)
        - [P.CAR.03](./safe-guides/coding_practice/cargo/P.CAR.03.md)
        - [P.CAR.04](./safe-guides/coding_practice/cargo/P.CAR.04.md)
        - [G.CAR.01](./safe-guides/coding_practice/cargo/G.CAR.01.md)
        - [G.CAR.02](./safe-guides/coding_practice/cargo/G.CAR.02.md)
        - [G.CAR.03](./safe-guides/coding_practice/cargo/G.CAR.03.md)
        - [G.CAR.04](./safe-guides/coding_practice/cargo/G.CAR.04.md)
    - [宏](./safe-guides/coding_practice/macros.md)
        - [P.MAC.01](./safe-guides/coding_practice/macros/P.MAC.01.md)
        - [P.MAC.02](./safe-guides/coding_practice/macros/P.MAC.02.md)
        - [G.MAC.01](./safe-guides/coding_practice/macros/G.MAC.01.md)
        - [G.MAC.02](./safe-guides/coding_practice/macros/G.MAC.02.md)
        - [声明宏](./safe-guides/coding_practice/macros/decl.md)
            - [P.MAC.DCL.01](./safe-guides/coding_practice/macros/decl/P.MAC.DCL.01.md)
            - [P.MAC.DCL.02](./safe-guides/coding_practice/macros/decl/P.MAC.DCL.02.md)
            - [P.MAC.DCL.03](./safe-guides/coding_practice/macros/decl/P.MAC.DCL.03.md)
            - [P.MAC.DCL.04](./safe-guides/coding_practice/macros/decl/P.MAC.DCL.04.md)
            - [P.MAC.DCL.05](./safe-guides/coding_practice/macros/decl/P.MAC.DCL.05.md)
            - [P.MAC.DCL.06](./safe-guides/coding_practice/macros/decl/P.MAC.DCL.06.md)
            - [P.MAC.DCL.07](./safe-guides/coding_practice/macros/decl/P.MAC.DCL.07.md)
            - [P.MAC.DCL.08](./safe-guides/coding_practice/macros/decl/P.MAC.DCL.08.md)
        - [过程宏](./safe-guides/coding_practice/macros/proc.md)
            - [P.MAC.PRO.01](./safe-guides/coding_practice/macros/proc/P.MAC.PRO.01.md)
            - [P.MAC.PRO.02](./safe-guides/coding_practice/macros/proc/P.MAC.PRO.02.md)
            - [P.MAC.PRO.03](./safe-guides/coding_practice/macros/proc/P.MAC.PRO.03.md)
            - [P.MAC.PRO.04](./safe-guides/coding_practice/macros/proc/P.MAC.PRO.04.md)
            - [P.MAC.PRO.05](./safe-guides/coding_practice/macros/proc/P.MAC.PRO.05.md)
            - [P.MAC.PRO.06](./safe-guides/coding_practice/macros/proc/P.MAC.PRO.06.md)
    - [多线程](./safe-guides/coding_practice/threads.md)
        - [锁同步](./safe-guides/coding_practice/threads/lock.md)
            - [P.MTH.LCK.01](./safe-guides/coding_practice/threads/lock/P.MTH.LCK.01.md)
            - [G.MTH.LCK.01](./safe-guides/coding_practice/threads/lock/G.MTH.LCK.01.md)
            - [G.MTH.LCK.02](./safe-guides/coding_practice/threads/lock/G.MTH.LCK.02.md)
            - [G.MTH.LCK.03](./safe-guides/coding_practice/threads/lock/G.MTH.LCK.03.md)
            - [G.MTH.LCK.04](./safe-guides/coding_practice/threads/lock/G.MTH.LCK.04.md)
        - [无锁](./safe-guides/coding_practice/threads/lock-free.md)
            - [P.MTH.LKF.01](./safe-guides/coding_practice/threads/lock-free/P.MTH.LKF.01.md)
            - [P.MTH.LKF.02](./safe-guides/coding_practice/threads/lock-free/P.MTH.LKF.02.md)
    - [异步编程](./safe-guides/coding_practice/async-await.md)
        - [P.ASY.01](./safe-guides/coding_practice/async-await/P.ASY.01.md)
        - [G.ASY.01](./safe-guides/coding_practice/async-await/G.ASY.01.md)
        - [G.ASY.02](./safe-guides/coding_practice/async-await/G.ASY.02.md)
        - [G.ASY.03](./safe-guides/coding_practice/async-await/G.ASY.03.md)
        - [G.ASY.04](./safe-guides/coding_practice/async-await/G.ASY.04.md)
        - [G.ASY.05](./safe-guides/coding_practice/async-await/G.ASY.05.md)
    - [Unsafe Rust](./safe-guides/coding_practice/unsafe_rust.md)
        - [P.UNS.01](./safe-guides/coding_practice/unsafe_rust/P.UNS.01.md)
        - [P.UNS.02](./safe-guides/coding_practice/unsafe_rust/P.UNS.02.md)
        - [G.UNS.01](./safe-guides/coding_practice/unsafe_rust/G.UNS.01.md)
        - [安全抽象](./safe-guides/coding_practice/unsafe_rust/safe_abstract.md)
            - [P.UNS.SAS.01](./safe-guides/coding_practice/unsafe_rust/safe_abstract/P.UNS.SAS.01.md)
            - [P.UNS.SAS.02](./safe-guides/coding_practice/unsafe_rust/safe_abstract/P.UNS.SAS.02.md)
            - [P.UNS.SAS.03](./safe-guides/coding_practice/unsafe_rust/safe_abstract/P.UNS.SAS.03.md)
            - [P.UNS.SAS.04](./safe-guides/coding_practice/unsafe_rust/safe_abstract/P.UNS.SAS.04.md)
            - [P.UNS.SAS.05](./safe-guides/coding_practice/unsafe_rust/safe_abstract/P.UNS.SAS.05.md)
            - [P.UNS.SAS.06](./safe-guides/coding_practice/unsafe_rust/safe_abstract/P.UNS.SAS.06.md)
            - [P.UNS.SAS.07](./safe-guides/coding_practice/unsafe_rust/safe_abstract/P.UNS.SAS.07.md)
            - [P.UNS.SAS.08](./safe-guides/coding_practice/unsafe_rust/safe_abstract/P.UNS.SAS.08.md)
            - [P.UNS.SAS.09](./safe-guides/coding_practice/unsafe_rust/safe_abstract/P.UNS.SAS.09.md)
            - [G.UNS.SAS.01](./safe-guides/coding_practice/unsafe_rust/safe_abstract/G.UNS.SAS.01.md)
            - [G.UNS.SAS.02](./safe-guides/coding_practice/unsafe_rust/safe_abstract/G.UNS.SAS.02.md)
        - [裸指针操作](./safe-guides/coding_practice/unsafe_rust/raw_ptr.md)
            - [P.UNS.PTR.01](./safe-guides/coding_practice/unsafe_rust/raw_ptr/P.UNS.PTR.01.md)
            - [P.UNS.PTR.02](./safe-guides/coding_practice/unsafe_rust/raw_ptr/P.UNS.PTR.02.md)
            - [P.UNS.PTR.03](./safe-guides/coding_practice/unsafe_rust/raw_ptr/P.UNS.PTR.03.md)
            - [G.UNS.PTR.01](./safe-guides/coding_practice/unsafe_rust/raw_ptr/G.UNS.PTR.01.md)
            - [G.UNS.PTR.02](./safe-guides/coding_practice/unsafe_rust/raw_ptr/G.UNS.PTR.02.md)
            - [G.UNS.PTR.03](./safe-guides/coding_practice/unsafe_rust/raw_ptr/G.UNS.PTR.03.md)
        - [联合体](./safe-guides/coding_practice/unsafe_rust/union.md)
            - [P.UNS.UNI.01](./safe-guides/coding_practice/unsafe_rust/union/P.UNS.UNI.01.md)
            - [P.UNS.UNI.02](./safe-guides/coding_practice/unsafe_rust/union/P.UNS.UNI.02.md)
        - [内存](./safe-guides/coding_practice/unsafe_rust/mem.md)
            - [P.UNS.MEM.01](./safe-guides/coding_practice/unsafe_rust/mem/P.UNS.MEM.01.md)
            - [P.UNS.MEM.02](./safe-guides/coding_practice/unsafe_rust/mem/P.UNS.MEM.02.md)
            - [P.UNS.MEM.03](./safe-guides/coding_practice/unsafe_rust/mem/P.UNS.MEM.03.md)
            - [P.UNS.MEM.04](./safe-guides/coding_practice/unsafe_rust/mem/P.UNS.MEM.04.md)
            - [P.UNS.MEM.05](./safe-guides/coding_practice/unsafe_rust/mem/P.UNS.MEM.05.md)
            - [G.UNS.MEM.01](./safe-guides/coding_practice/unsafe_rust/mem/G.UNS.MEM.01.md)
        - [FFi](./safe-guides/coding_practice/unsafe_rust/ffi.md)
            - [P.UNS.FFI.01](./safe-guides/coding_practice/unsafe_rust/ffi/P.UNS.FFI.01.md)
            - [P.UNS.FFI.02](./safe-guides/coding_practice/unsafe_rust/ffi/P.UNS.FFI.02.md)
            - [P.UNS.FFI.03](./safe-guides/coding_practice/unsafe_rust/ffi/P.UNS.FFI.03.md)
            - [P.UNS.FFI.04](./safe-guides/coding_practice/unsafe_rust/ffi/P.UNS.FFI.04.md)
            - [P.UNS.FFI.05](./safe-guides/coding_practice/unsafe_rust/ffi/P.UNS.FFI.05.md)
            - [P.UNS.FFI.06](./safe-guides/coding_practice/unsafe_rust/ffi/P.UNS.FFI.06.md)
            - [P.UNS.FFI.07](./safe-guides/coding_practice/unsafe_rust/ffi/P.UNS.FFI.07.md)
            - [P.UNS.FFI.08](./safe-guides/coding_practice/unsafe_rust/ffi/P.UNS.FFI.08.md)
            - [P.UNS.FFI.09](./safe-guides/coding_practice/unsafe_rust/ffi/P.UNS.FFI.09.md)
            - [P.UNS.FFI.10](./safe-guides/coding_practice/unsafe_rust/ffi/P.UNS.FFI.10.md)
            - [P.UNS.FFI.11](./safe-guides/coding_practice/unsafe_rust/ffi/P.UNS.FFI.11.md)
            - [P.UNS.FFI.12](./safe-guides/coding_practice/unsafe_rust/ffi/P.UNS.FFI.12.md)
            - [P.UNS.FFI.13](./safe-guides/coding_practice/unsafe_rust/ffi/P.UNS.FFI.13.md)
            - [P.UNS.FFI.14](./safe-guides/coding_practice/unsafe_rust/ffi/P.UNS.FFI.14.md)
            - [P.UNS.FFI.15](./safe-guides/coding_practice/unsafe_rust/ffi/P.UNS.FFI.15.md)
        - [I/O](./safe-guides/coding_practice/unsafe_rust/io.md)
            - [P.UNS.FIO.01](./safe-guides/coding_practice/unsafe_rust/io/P.UNS.FIO.01.md)
        - [Unsafe 代码术语指南](./safe-guides/coding_practice/unsafe_rust/glossary.md)
    - [no-std](./safe-guides/coding_practice/no-std.md)
        - [P.EMB.01](./safe-guides/coding_practice/no-std/P.EMB.01.md)
        - [P.EMB.02](./safe-guides/coding_practice/no-std/P.EMB.02.md)
    - [I/O](./safe-guides/coding_practice/io.md)
        - [P.FIO.01](./safe-guides/coding_practice/io/P.FIO.01.md)
        - [G.FIO.01](./safe-guides/coding_practice/io/G.FIO.01.md)
    - [信息安全](./safe-guides/coding_practice/security.md)
        - [P.SEC.01](./safe-guides/coding_practice/security/P.SEC.01.md)
        - [G.SEC.01](./safe-guides/coding_practice/security/G.SEC.01.md)
    - [其他](./safe-guides/coding_practice/others.md)
        - [G.OTH.01](./safe-guides/coding_practice/others/G.OTH.01.md)
        - [G.OTH.01](./safe-guides/coding_practice/others/G.OTH.02.md)
- [附录](./safe-guides/Appendix/toc.md)
    - [A.开发环境](./safe-guides/Appendix/dev_env.md)
    - [B.测试](./safe-guides/Appendix/test.md)
        - [单元测试](./safe-guides/Appendix/test/unit_test.md)
        - [基准测试](./safe-guides/Appendix/test/benchmark.md)
        - [模糊测试](./safe-guides/Appendix/test/fuzz.md)
    - [C.术语解释](./safe-guides/Appendix/terms.md)
    - [D.模板](./safe-guides/Appendix/templates/intro.md)
        - [rustfmt 模板](./safe-guides/Appendix/templates/rustfmt.toml.md)
        - [clippy 模板](./safe-guides/Appendix/templates/clippy.toml.md)
        - [deny 模板](./safe-guides/Appendix/templates/deny.toml.md)
    - [E.工具链](./safe-guides/Appendix/tools/intro.md)
        - [rustfmt](./safe-guides/Appendix/tools/rustfmt.md)
        - [noisy-clippy](./safe-guides/Appendix/tools/noisy-clippy.md)
        - [cargo-udeps](./safe-guides/Appendix/tools/cargo-udeps.md) 
    - [F.Cheat Sheet](./safe-guides/Appendix/cheat-sheet/README.md)
        - [浮点数](./safe-guides/Appendix/cheat-sheet/Numbers/float.md)
    - [G.优化指南](./safe-guides/Appendix/optimizing/intro.md)
    - [H.编译参数说明](./safe-guides/Appendix/rustc-flag.md)
    - [I.最佳实践](./safe-guides/Appendix/best-practice/intro.md)
        - [初学者常见问题Q&A](./safe-guides/Appendix/best-practice/qa.md)
        - [Rust 编程技巧](./safe-guides/Appendix/best-practice/tips.md)
    - [J.贡献说明](./safe-guides/Appendix/contribution.md)
    - [K.淘汰的规则](./safe-guides/Appendix/old_guidelines.md)

    









