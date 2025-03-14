# 赛题要求文档

**项目名称：**

内核代码映射用户态

**项目链接：**

GitHub链接

**导师信息：**

姓名：李弋

邮箱：liy@fudan.edu.cn

**难度：**

中

**分类：**

？

**题目要求：**

将目标函数代码段及其依赖数据（栈/全局变量）映射到进程用户地址空间，确保映射后的函数在用户态可直接调用（提供示例测试程序）。

选择内核代码映射到用户态，这样用户态程序可以直接调用这些代码，减少用户态-内核态切换开销，同时可以复用内核代码并利用其健壮性。

**特征：**

- 被映射内核代码可动态调节
- 不会影响内核的正确运行

**预期目标：**

> 第一题：实现代码映射内核模块
>
> - 实现一个内核模块可以将某些内核代码映射到用户态并验证正确性

> 第二题：探索可映射条件
>
> - 并不是所有内核代码都可以被映射，所以要寻找能够被映射的内核代码需要符合的条件

> 第三题：实现内存管理的代码映射（可选）
>
> - 将内核态的内存管理模块代码映射到用户态
> - 对内存分配效率进行检测

**License：**

GPL-3.0 License

**参考资料：**

暂无

**备注：**

暂无
