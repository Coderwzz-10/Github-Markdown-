>Markdown是一种重要的写文档的语法，在这里简单总结了Github上面Markdown的一些常用的基础语法。

1、**标题**  
Markdown总共有六级标题，分别是  
\# 一级标题  
\## 二级标题  
\### 三级标题  
\#### 四级标题  
\##### 五级标题  
\###### 六级标题  

**效果：**  
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

2、**换行**

在文字后面加\<br\>;也可以在上一行后加两个空格再按回车。

第一行<br>第二行<br>第三行

3、**缩进**  
3.1  缩进一个空格  
一般在要缩进的元素前面加上\&ensp;或\&nbsp;  
3.2  缩进两个空格  
加上\&emsp;  

示例：  
  no indentation  
\&ensp;one blank  
\&emsp;two blanks

no indentation  
&ensp;one blank  
&emsp;two blanks




4、**文本块**

（1）常用文本块语法：使用反引号`，在输入文本的开头和结尾各连续三个。

\`\`\`<br>
一万年太久，只争朝夕<br>
\`\`\`

```
一万年太久，只争朝夕
```

（2）渲染代码块：在开头反引号后加上编程语言名称

例如：\`\`\`c++<br>
#include<iostream><br>
using namespace std;<br>
int main(){<br>
int a;<br>
a=1;<br>
cout<<a<<endl;<br>
}<br>
\`\`\`

```c++
#include<iostream>
using namespace std;
int main(){
int a;
a=1;
cout<<a<<endl;
}
```

5、**文字高亮**  
针对行内文字，在文字前后加上一对反引号\`。  
`热度` `点击` `点赞`

6、字体
加粗用\*\*文字\*\*  或\_\_文字\_\_  
**文字**

斜体用\*文字\*  或\_文字\_  
*文字*

删除线用\~\~文字\~\~  
~~文字~~

7、**图片**  
\![失败时替换文本](Url title)  
![mj](https://github.com/Coderwzz-10/Github-Markdown-/blob/master/Link/mj.png)

8、**链接**  
8.1 外部Url：

\[名称](Url)  
\[bilibili](https://www.bilibili.com/)  
[bilibili](https://www.bilibili.com/)

8.2 仓库内的Url：  
\[我的链接](/Link/me.md)  
[我的链接](/Link/me.md)

9、**列表**  
9.1 无序列表  
输入\* listitem即创建无序的列表,\'\*\'也能用\'\-\'或\'\+\'代替  
* Red
* Blue
* Yellow

9.2 有序列表  
输入1. listitem即创建有序的列表  
1. Red
2. Blue
3. Yellow

9.3  复选框  
未完成的为\- [ ] incompleted task   
完成的为\- [x] completed task  
- [ ] incompleted task  
- [x] completed task

10、**表格**  
第一行输入表头，第二行为对齐方式，'-:'为右对齐，':-:'为居中对齐;':-'为左对齐；无对齐时就为'-'。  
10.1 无对齐方式  
输入：  
\| First Header  \| Second Header \|  
\|-|-|  
\| messi  \| Barca  \|  
\| cristiano  \| Juven  \|  
预览：  
| First Header  | Second Header |
|-|-|
| messi  | Barca  |
| cristiano  | Juven  |

10.2 对齐方式  
输入：  
\| Left-Aligned  \| Center Aligned  \| Right Aligned |  
\|:-\|:-:\|-:\|  
\|messi          \|is               \|Argentine      \|  
\|cristiano      \|is               \|Portuguese     \|  
预览：  
| Left-Aligned | Center Aligned | Right Aligned |
|:-|:-:|-:|
|messi         |is              |Argentine      |
|cristiano     |is              |Portuguese     |










 


