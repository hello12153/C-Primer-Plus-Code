# C-Primer-Plus-Code
# 2.C语言概述
## 2.1程序示例

```
#include<stdio.h>   /*头文件*/
int main(void)  /*main函数*/
{
    int num;    /*定义名为num的变量*/
    num = 1;    /*为num变量赋值*/
    
    printf("1 + 1 = %d\n",num++);   /*使用printf()函数*/
    return 0;
}
```
#include<stdio.h>:在程序的顶部的信息集合被称为**头文件**。而这段代码叫**预处理指令**,它会在编译器在编译前对源代码做一些准备工作。 

stdio.h：这是C编译器软件包中的标准输入/输出头文件，该文件包含了供编译器使用的输入和输出函数（如：scanf()函数、printf()函数）    

注释：写注释能让他人或自己更容易明白你所写的程序。注释可以放在任意地方，如：/**/、//

{...}：C程序中函数都使用花括号标记函数体的开始和结束。花括号也可以把函数中的多条语句合并为一个单元或块

分号：C程序的语句都以分号‘;’结束

声明：向内存申请存储空间，限定该空间存储的数据类型，并给予标识符

赋值：向某标识符指向的内存空间存储数据

调用函数：函数调用有三种情况：第一种函数不需要传递参数，第二种调用函数需要传递指定的参数，第三种调用函数需要接收函数返回的数据
