## 引言

### 计算机语言发展史

第一代语言：0101

第二代语言：汇编语言

第三代语言：高级语言

* 高级语言：分为面向过程和面向对象

### Java帝国的诞生

#### C&C++的诞生

1972：C诞生

* 操作系统，编译器

* 指针和内存管理

1982：C++诞生

* 面向对象
* 图形领域，游戏

#### Java的诞生——1995年

> Bill Gates说：这是迄今为止设计的最好的语言

##### Java特性和优势

* 简单性
* 面向对象
* 可移植性
* 高性能
* 多线程

##### Java三大版本

* JavaSE：标准版（桌面程序，控制台开发）
* ~~JavaME~~：嵌入式开发（手机，小家电）
* JavaEE：E企业级开发（web端，服务器开发）

==JavaSE==优先学习

##### JDK，JRE，JVM

* JDK: Java Development Kit（Java开发工具）

* JRE: Java Runtime Environment （Java运行时环境）

* JVM: Java Virtual Machine  （Java虚拟机）

![image-20220123002717484](https://gitee.com/starriverflow/cloud-pictures/raw/master/img/image-20220123002717484.png)

##### Java开发环境搭建

###### 下载JDK8

oracle 官网下载

<img src="https://gitee.com/starriverflow/cloud-pictures/raw/master/img/image-20220123005030659.png" alt="image-20220123005030659" style="zoom: 67%;" />

> 记住安装目录

* 配置环境变量

  * 系统路径添加变量名：JAVA_HOME

  * 配置path变量
    * %JAVA_HOME%\bin
    * %JAVA_HOME%\jre\bin
  * 测试JDK是否安装成功
    * cmd 输入 java -version





###### 卸载JDK

* 环境变量找到 **JAVA_HOME**, 双击，打开Java目录，删除。

* 再去掉 **JAVA_HOME**,

* 在path去掉路径

* cmd中输入java -version ，显示不是内部命令



###### 下载notepad++