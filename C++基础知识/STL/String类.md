**string的性质及其基本实现：**



**string的应用：**

别的类型转string ：string str=to_string(x);

反转字符串：reverse(str.begin(), str.end());

字符串截取字符：x.substr(2，5)；从第二个字符开始，往后五个字符

​							   x.substr(1) 从x[1]开始到最后

char型数字转为相应数字：（int）‘2’ 得到的是asc码， ‘2’-‘0’ 得到数字2