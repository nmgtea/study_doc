##final
声明一个东西无法改变

###数据

- 编译期常数，永远不改变
- 运行期初始化一个值，不希望在改变

###方法

- 防止任何继承类修改
- 提高执行效率，一般的方法调用，采用常规代码插入方法（将自变量压入堆栈；跳至方法代码并执行它；跳回来；清除堆栈自变量；最后对返回值进行处理），final方法调用的时候，会在调用方法的地方，插入final方法副本；这样避免了调用方法时的系统开销，但是，若方法体积太大，程序会很臃肿，反而影响性能。

###类

- 不允许其他类，继承此类