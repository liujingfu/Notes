## 目录
+ [一个简单的应用程序](#一个简单的应用程序)
+ 数据类型
+ 逻辑运算
+ 类
+ 关键字
+ 特殊类
+ 特殊接口
+ 特殊包
+ 反射
+ [泛型](#泛型)


##  一个简单的应用程序

    
      public class Test{
         public static void main(string[] args){
      System.out.println("hello word");
    }
  }

    1. java大小写敏感
       java大小写敏感，类名，方法名，变量名都是敏感的，main和Main,test和Test，Str和str都是不同的。
    2. 访问修饰符
       java访问修饰符总共有4钟，public,default,protected,private.他们代表了不同的访问控制权限。是用来描述包之间的关系，
    （也就是说他们的上层结构是包），private代表只能在本类中访问，default代表只有在同一包下的类才具有访问权限，project代表在同一包中
     或子类中才能访问。public代表的是公共访问权限，在工程下任务地方都可以访问，所以也叫接口访问权限。
    3. 程序入口
       java程序的入口是main方法，main方法内是顺序执行的。
    4. 返回值类型
       方法的返回值类型可以没有也可以是基本数据类型或者引用数据类型。
##  数据类型
    1. 基本数据类型
       java有八种基本数据类型，byte(一个字节),short（2个字节）,int（四个字节）,long（四个字节）,float（四个字节）,double（八个个字节）,char（看字符集）,boolean（一个字节）.
    2. 引用数据类型 
    3. 字符集
    4. 常量池
    5. 类型转换

    6. 可用于switch的数据类型
##  逻辑运算
    1. 常见数学函数
    2. 自增自减
    3. 位运算
    4. 三目运算
##  类
    1. 封装
    2. 继承
    3. 多态
    4. 加载顺序
    5. 内部类
    6. 匿名类
##  关键字
    1. this
    2. supper
    3. final
    4. static
##  特殊类
    1. 字符串类
    2. 时间类
    3. thread类
## 特殊接口
    1. Runnable
    2. 
## 特殊包
   1. JUC包
## 反射
## 泛型
