# LLVM系统入门
# 目录
- [概述](#概述)  
- [编译LLVM工程](#编译LLVM工程)  
---------------------
作者：Erice_s
来源：CSDN
原文：https://blog.csdn.net/Erice_s/article/details/80190859
版权声明：本文为博主原创文章，转载请附上博文链接！
## 概述
LLVM项目有多个组件。项目的核心本身称为LLVM。它包含处理中间代码(intermediate representation)，并将其转换为目标文件所需的所有工具、库和头文件。它包含汇编器、反汇编器、位代码分析器和位代码优化器。它还包含基本的回归测试。

另一块是`clang end`。该组件使用LLVM将C、c++、Objective C和Objective c++代码编译成`LLVM bitcode`，然后再编译成目标文件。

## 编译LLVM工程
下载
