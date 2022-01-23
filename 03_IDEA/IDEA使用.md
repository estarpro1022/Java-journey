### 编译型和解释型

Java处于两者之间

#### Java文件的编译过程

![image-20220123122343031](https://gitee.com/starriverflow/cloud-pictures/raw/master/img/image-20220123122343031.png)

执行过程：

* Java编译器将`*.java`文件编译为`*.class`文件——预编译

* `*.class`文件在JVM虚拟机的**类装载器**中操作
* **字节码校验器**检验代码是否正确
* **解释器**将`*.class`文件解释给操作系统



`javac Hello.java` 相当于将文件编译为`*.class`

`java Hello`相当于解释器解释文件给操作系统



### IDE

全称：**集成开发环境**（integrated development environment）

IDEA下载官网：https://www.jetbrains.com/

#### **学生可以免费申请Ultimate版本的jetbrains全家桶**

#### 划算！！！



选择下载目录

![image-20220123140754917](https://gitee.com/starriverflow/cloud-pictures/raw/master/img/image-20220123140754917.png)

#### 注意事项

* 第一次加载，选择`do not import settings`

* QQ会和IDEA抢热键，记得打开系统设置<u>删除QQ冲突的热键</u>

#### 快捷键

* ctrl + alt + L

  格式化代码，即自动对齐

* ctrl + alt + enter
  在当前行上方生成空白行

* shift + enter
  在当前行的下方生成空白行

* ctrl + /
  行注释

* ctrl + shift + /
  代码块注释，即/* ... */
  取消注释，不需要全选，只需光标移至块注释区，再ctrl + shift + /

* ctrl + shift + enter
  自动补全，如在行尾加上分好；

#### 第一个Java程序

* 先建项目
* 选择保存路径
* 在**src目录**下新建（虽然不知道为什么）

<img src="https://gitee.com/starriverflow/cloud-pictures/raw/master/img/image-20220123152609740.png" alt="image-20220123152609740" style="zoom: 50%;" />

```java
》public class Hello {
    // psvm
》  public static void main(String[] args) {
        // sout
        System.out.println("Hello, World!!!");
    }
}
```

##### tips:

* **先点击第二个绿色三角形，再运行即可**

* 直接输入psvm再enter，即可出现`public static void main(String[] args)`
  * 甚至只需要打一个p
* sout 即可出现 `System.out.println("");`
* IDEA<u>自动保存文件</u>，因此可以直接退出

