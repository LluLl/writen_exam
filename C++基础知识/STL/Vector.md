## **vector：**【类】

### ***STL实现：***





### ***应用一：***

二维可变数组 **初始化**

1.用new 构建一个指向对象的指针（nums）:**数据存在堆里面**

vector<vector<int>>  *nums = new vector<vector<int>>(n ,vector<int>(m));

2.直接调用构造函数调用： **数据存在栈里面**

vector<vector<int>> nums(n ,vector<int>(m));  //n,m **vector长度**,插入时为一个**vector<int>**

二维数组**行**：***nums.size()***; 单个行的**列**：***nums[i].size()***

***拓展：***

静态：静态存储区，他们在程序编译完成后就已经分配好了，生命周期持续至程序结束。（常量、常变量（const 变量）、静态变量、全局变量等）。

栈：程序退出其作用域后自动调用类的析构函数（函数的返回地址、参数和局部变量）

堆：由malloc new等分配的空间，生命周期是从分配的那一刻直到free结束。



### ***应用二：***

容器相关**函数应用**【增删改查及其他操作】

向vector中插入元素[不是向元素赋值] ：A**.push_back(val)**  A.pop_back()

**查找**某个元素是否属于vector：

```
vector<int>::iterator got = myrecipe.find ("coffee");//迭代器
```

if(got != solution.end()) {存在}

**排序** sort(vec.begin(),vec.end());

迭代器：