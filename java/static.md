##static

不需要实例化就能使用，static存在的类，只要这个类被加载，Java虚拟机就能根据类名在运行时数据区的方法区内定找到他们。

###变量

变量在内存中只有一个拷贝，JVM只为静态分配一次内存，在加载类的过程中完成静态变量的内存分配，可用类名直接访问。

###方法、代码块

静态方法可以直接通过类名调用，任何的实例也都可以调用。

用static修饰的代码块表示静态代码块，当Java虚拟机（JVM）加载类时，就会执行该代码块。不需要实例化，就能被调用。