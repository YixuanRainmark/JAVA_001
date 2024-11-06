# JAVA_001
## 变量与数据类型
### 变量与常量
#### 什么是常量，什么是变量
你只需要记住两点：

常量：**就是一种不会根据环境而改变的数据**，例如：圆周率。
变量：**是一种能够根据不同环境产生不同值的数据**，例如：手机电量。
##### 怎么定义变量
在 `Java`中，我们通过三个元素描述变量：**变量类型、变量名以及变量值**。
![alt text](https://data.educoder.net/api/attachments/MUxna09DTmo3eGhRWEk4aUNOLzNsdz09 )
在JAVA中变量类型大致可以分为两种一种是`数值类型`，一种是`非数值类型`，数值类型又分为两种:`整形`和`非整形`
我们定义变量，需要四个步骤。
* 确定变量类型。
* 取变量名。
* 给变量赋初值。
* 分号结尾。
例如：我们要定义一个名字是张三的变量，并且输出:
```java
    public static void main(String[] args){
 String name = "张三";
 System.out.println(name);
}
```
输出的结果： `张三`
### 变量的使用
#### 变量的命名规则和规范
JAVA中变量的命名和前面第一章所学的标识符命名规则是一样的，不过还是有一些不同，总结下来规则与规范一共有六点：

* 由字母，下划线，美元符号（$），数字组成，但第一个字符不能是数字。
* 如果变量名是复合型的那么我们采用驼峰式，或者蛇形式的方式。 驼峰式：teaCup（表示茶杯的意思），`stuAge`（学生年龄） 蛇形式：`tea_cup`，`stu_age`
* 如果是单个单词就全小写就行了。
* 千万不要用中文拼音来表达：例如学生年龄：xueShengNianling。
* 在一个方法中变量名不能重复。
* 变量一定要给自己一个确定的类型。
![alt text](https://data.educoder.net/api/attachments/OE4yb3ZCRitWU0NjNW1NVFFxL2VYQT09)
#### 变量的赋值
我们定义了一个变量 `name` ，用来保存一个字符串 “张三丰” , 在程序中只要找到了 `name` 这个变量，就能找到存储在里面的 ”张三丰”！当然，我们也可以把 `name`的值更换成新的字符串 "张三"。
最后的输出结果为：
`变量name的值为张三丰`  
`最新赋值后变量name的值为张三`
### JAVA数据类型
#### JAVA中的数据类型
`Java`基本类型共有八种，基本类型可以分为三类，字符类型`char`，布尔类型`boolean`以及数值类型`byte、short、int、long、float、double`。数值类型又可以分为整数类型`byte、short、int、long`和浮点数类型`float、double`。
JAVA中的数值类型不存在无符号的，它们的取值范围是固定的，不会随着机器硬件环境或者操作系统的改变而改变。实际上，`JAVA`中还存在另外一种基本类型`void`，它也有对应的包装类 `java.lang.Void`，不过我们无法直接对它们进行操作。8 种类型表示范围如下：

1、**byte**：8位，最大存储数据量是255，存放的数据范围是-128~127之间。
2、**short**：16位，最大数据存储量是65536，数据范围是-32768 ~ 32767之间。
3、**int**：32位，最大数据存储容量是2的32次方减1，数据范围是负的2的31次方到正的2的31次方减1。
4、**long**：64位，最大数据存储容量是2的64次方减1，数据范围为负的2的63次方到正的2的63次方减1。
5、**float**：32位，数据范围在3.4e-45 ~ 1.4e38，直接赋值时必须在数字后加上f或F。
6、**double**：64位，数据范围在4.9e-324 ~ 1.8e308，赋值时可以加d或D也可以不加。
7、**boolean**：只有`true`和`false`两个取值。
8、**char**：16位，存储Unicode码，用单引号赋值。
![alt text](https://data.educoder.net/api/attachments/cEkraFdNV0E0dTd0bEdtelphSFdmQT09)
![alt text](https://data.educoder.net/api/attachments/M2lFKzNKbENvSUZ5K0hQajdCTUFNdz09)
#### 怎么定义对应数据类型的变量
![alt text](https://data.educoder.net/api/attachments/ZWRoV1ovNmgxQTZ2czVFS3lIeEYwUT09)
