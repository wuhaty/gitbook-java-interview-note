# 关键字static
|修饰的对象|作用|
|--|--|
|类中的成员变量|这个变量是静态变量，属于类，不属于某个实例（不需要创建对象可以使用）；在内存中只有一个复制，在类加载时，这个变量就会被分配空间|
|类中的方法|这个方法是静态方法，属于类，不需要创建对象可以使用|
|代码块|加载类时会执行static代码块，且只被执行一次；通常用来初始化静态变量|
|内部类|可以不依赖外部类被实例化|

## 常问问题
- 静态方法只能调用静态方法、只能使用静态变量