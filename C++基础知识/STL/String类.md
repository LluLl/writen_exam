### **string的性质及其基本实现：**

​	

### **string的应用：**

string.size() 会反应字符串的真实长度，非‘\0’

​          .strlen() 反应C中的长度【字符数组长度】，带上\0

**别的类型转string ：**string str=to_string(x);   int x

**string的拼接**：str+'a'；str.append(a); a:字符，字符串

**string的插入：**str.insert(pos,string);

**某个字符的查找：** find（char， start pos）

**反转字符串**：reverse(str.begin(), str.end());

**删除某个字符**：.erase(pos,length);

**字符串截取字符**：x.substr(2，5)；从第二个字符开始，往后五个字符

​							   x.substr(1) 从x[1]开始到最后。

**char型数字转为相应数字：**（int）‘2’ 得到的是asc码， ‘2’-‘0’ 得到数字2

string的相关函数细节：

https://blog.csdn.net/m0_37592397/article/details/79701992