## 卸载JDK

1.删除Java的安装目录

2.删除JAVA_HOME

3.删除path下关于Java的目录

4.java -version



## IDEA快捷键

alt+enter

代码自动对齐：ctrl+alt+L

复制当前行：ctrl+d

删除当前行：ctrl+y

方法注释：/**+回车







## JavaSE

### 基础

#### JDK JRE JVM

JDK: Java Development Kit

JRE: Java Runtime Environment

JVM: Java Virtual Machine

从大到小



#### Java是强类型语言

- 所有变量都必须先定义后才能使用



#### 数据类型

**demo-Demo01**

1. 基本类型

   - 数值类型

     -整数类型

     1. byte 占一个字节 范围：-128-127
     2. short 占两个字节 范围：-32768-32767
     3. int 占4个字节 
     4. long 占8个字节

     -浮点类型

     1. float 占4个字节
     2. double 占8个字节

     -字符类型

     1. char 占两个字节

   - boolean类型
     
     1. 占1位 值只有true和false

2. 引用类型

   - 类
   - 接口
   - 数组



位（bit）：是计算机内部数据储存的最小单位，11001100是一个八位二进制

字节（byte）：是计算机这种数据处理的基本单位，习惯上用大写B来表示

1B = 8bit

字符：是指计算机中使用的字母、数字、字和符号



#### 类型转换

**demo-Demo02、demo-Demo03**

低---------------------------------------------------高

btye,short,char->int->long->float->double

强制转换 (类型)变量名 高->低
自动转换 (类型)变量名 低->高

注意内存溢出和精度问题



#### 变量

**demo-Demo04**

Java变量是程序中最基本的存储单元，其要素包括变量名，变量类型和作用域

作用域：

- 类变量
- 实例变量
- 局部变量



#### 常量

**demo-Demo05**



#### 运算符

**operator-Demo01、Demo02、Demo03**



#### JavaDoc生成文档

cmd：javadoc -encoding UTF-8 -charset UTF-8 Doc.java



### 流程控制



#### Scanner

**scanner-Demo01、Demo02、Demo03**

![image-20210119225149946](C:\Users\A\AppData\Roaming\Typora\typora-user-images\image-20210119225149946.png)



