# C++多态  

## 静态多态  

### 模板  
优点：
* 灵活性, 可重用性和可扩展性;  
* 可以大大减少开发时间，模板可以把用同一个算法去适用于不同类型数据，在编译时确定具体的数据类型;  
* 模版模拟多态要比C++类继承实现多态效率要高, 无虚函数, 无继承;  

缺点：
* 易读性比较不好，调试比较困难;
* 模板的数据类型只能在编译时才能被确定;
* 所有用基于模板算法的实现必须包含在整个设计的.h头文件中, 当工程比较大的时候, 编译时间较长;
