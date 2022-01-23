没出现class是因为没保存代码

## 写一个HelloWorld

1. 创建java文件
   * 文件后缀名.java （记得开显示隐藏项目）
   * hello.java

2. 编写代码（notepad++）

```java
public class Hello{
	public static void main(String[] args){
		System.out.print("Hello, World!!!");
	}
}
// public class 是一个类，Hello是类的名字
/
```

3. 编译代码

   ```java
   // cmd 中打开
   地址栏前输入cmd 直接输，覆盖原来
   // 
   javac Hello.java
   // 出现class文件
   java Hello
   ```

### 可能遇到的情况

* 单词**大小写**不能出现问题，Java对大小写很敏感
* 尽量使用**英文**
* **文件名**和**类名**保持一致，并且首字母大写
* 输入法不能使用**中文**