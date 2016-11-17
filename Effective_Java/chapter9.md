# 第九章 异常
1.异常应该只用于异常的情况下，永远不要用于正常的控制流程  
2.如果期望能做适当的恢复，就应该使用受检的异常  
3.用运行时异常来表明编程错误  
4.常用的异常：  

| 异常     | 使用场合     |
| :------------- | :------------- |
| IllegalArgumentException|非null的参数不正确|
| IllegalStateException|对于方法调用而言，对象状态不合适|
| NullPointerException|在禁止使用null的情况下使用了null|
| IndexOutOfBundsException|下标参数值越界|
| ConcurrentModificationException|在禁止并发修改时，对象进行了并发的修改|
| UnsupportedOperationException|对象不支持用户请求的方法|  

5.更高层的实现应该捕获低层的异常，同时抛出可按照高层抽象进行解释的异常  
6.永远不要留下空的catch块，即不要忽略异常
