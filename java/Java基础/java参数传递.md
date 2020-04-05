## java传递：值传递

基本类型：int, char...

变量里面直接存储值

引用类型：string,class

变量里面存的是地址

![img](https://pic4.zhimg.com/80/287c0efbb179638cf4cf27cbfdf3e746_1440w.jpg)



**值传递**：调用函数时，实参向形参传递时进行变量值的**复制传递**

```
public class PassByValueExample {
    public static void main(String[] args) {
        Dog dog = new Dog("A");
        System.out.println(dog.getObjectAddress()); // Dog@4554617c
        func(dog);
        System.out.println(dog.getObjectAddress()); // Dog@4554617c
        System.out.println(dog.getName());          // A
    }

    private static void func(Dog dog) {
        System.out.println(dog.getObjectAddress()); // Dog@4554617c
        dog = new Dog("B");
        System.out.println(dog.getObjectAddress()); // Dog@74a14482
        System.out.println(dog.getName());          // B
    }
}
```

![img](https://pic1.zhimg.com/80/v2-43a9da74c477ac45106eafc29becb422_1440w.jpg)

https://www.zhihu.com/question/31203609【参考】

