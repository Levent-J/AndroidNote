# 第六章 枚举和注解
1.Java的枚举本质上是int值  
2.枚举的基本想法：通过共有的静态final域为每个枚举常亮导出实例的类  
3.枚举类型是真正的final  
4.可以增加或者重新排列枚举类型中的常亮而无需重新编译他的客户端代码  
5.为了将数据与枚举常亮关联起来，得声明实例域，并编写一个带有数据并且将数据保存在域中的构造器  
6.Java的printf()方法和C语言的差别在于，换行时用%n而非\n  
7.如果一个枚举具有普遍适用性，他应该成为一个顶层类；如果只是被用在一个特定的顶层类中，他就应该成为该顶层类的一个成员类  
8.枚举的使用场景：需要一组固定常量的时候  
9.特定于常量的方法要优先于启用自有值的枚举  
10.所有枚举都有一个ordinal方法，它返回每个枚举常量在类型中的数字位置  
11.永远不要根据枚举的序数导出与他相关联的值，而是要将他保存在一个实例域中  
12.注解优先于命名模式  
13.应该在想要覆盖超类声明的每个方法声明中使用Override注解  
