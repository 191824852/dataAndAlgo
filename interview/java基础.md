一、面向对象

1. 面向对象的三大特性
   - 封装
   - 继承
   - 多态
2. 类与方法修饰符
   - public
   - protected
   - private
   - public private protected作用域
   - static
   - final关键字的作用是什么
   - abstract
3. 如果父类引用了子类对象，调用这个对象的方法是子类中的还是父类中的
4. 如果父类有一个同名同参数的方法，是private级别。子类可以声明这个方法吗
5. 抽象方法的默认级别是什么
6. 如果父类方法是public级别，子类可以声明成private级别吗
7. Object类有哪些方法
   - wait、notify、notifyAll
   - hashCode
   - equals
   - toStirng

二、字符串

1. String,StringBuilder,StringBuffer区别

2. 如何判断两个字符串是否相等

   Strng a = "abc";

   String b = "abc";

   String c = "ab"+"c";

   String d = new String("abc");

   System.out.println(a == b);

   System.out.println(a == c);

   System.out.println(a == d);

   System.out.println(a.eqaulls(b);

3. 创建了几个字符串对象

   Strng a = "abc";

   String b = "ab"+"c";

   String c = new String("abc");

三、常用集合

1. java集合框架结构

   ![img](https://www.runoob.com/wp-content/uploads/2014/01/2243690-9cd9c896e0d512ed.gif)

2. ArrayList , LinkedList，Vector区别

3. Set,Map区别

4. HashMap

   - HashMap的数据结构
   - HashMap如何解决Hash冲突的，在java8中为什么要使用红黑树
   - HashMap高并发场景下会产生什么问题
   - HashMap的环是怎么产生的，它的原理是什么，java8中还会出现吗，说说为什么, 生产环境会出现什么问题
   - HashMap除了会产生环还有什么其他问题，并说明原理
   - HashTable和HashMap在哪些地方有所不同
   - 解决hash冲突的方式有哪些，描述一下

5. HashMap,HashTable区别

6. Collections,Collection区别

四、反射

1. Java反射的作用，为什么不用JavaBean抽象
2. 反射如何获取父类属性
3. 反射如何获取泛型



