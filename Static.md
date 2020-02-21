# Static

**1.类中的static**

类中修饰的static成员变量或者成员函数属于类，而不属于对象

**1.1类中的static成员变量**

一个类共享static成员变量；

static成员变量先于类对象存在，所以static成员变量一定要在类外定义；

**1.2类中的static成员函数**

类中的static成员函数属于类而不属于对象，因此没有this指针，因而不能访问类中的非static成员变量。

**2.static的内存位置**

static变量保存在内存中的静态存储区

