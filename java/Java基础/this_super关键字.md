## This关键字

1、引用成员变量【与形参做区分】

```tsx
Public Class Student { 
 String name; //定义一个成员变量name
 private void SetName(String name) { //定义一个参数(局部变量)name
  this.name=name; //将局部变量的值传递给成员变量
 }
}
```

//保证了同名时指的是哪一个，要是不同名，不用也行

2、调用类的构造方法，同一个类的另一个构造方法【】

```cpp
public class Student { //定义一个类，类的名字为student。 
public Student() { //定义一个方法，名字与类相同故为构造方法
  this(“Hello!”);
 }
public Student(String name) { //定义一个带形式参数的构造方法
 }
}
```

3、返回对象的值

this关键字除了可以引用变量或者成员方法之外，还可以作为类的**返回值**，



## **Super关键字**【当前调用对象的父类】

