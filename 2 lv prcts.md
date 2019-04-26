---
title: 二级题库
tags: 
     - 磨刀
     - patient
     - 二级三级四级五级
	
type: categories
abbrlink: 65336
date: 2019-02-22 23:44:31
---



![movies](\images\erji.jpg)

<!--more-->

#### 0 填空题

1. python安装库常用的工具是（pip）和（conda），其中后者需要安装python集成开发环境Anaconda3之后才可以使用，而前者是python官方推荐和标配的。

2. python程序文件的扩展名主要有（.py) 和（.pyw)两种，其中后者常用于GUI程序。

3. python源代码程序伪编译后的文件扩展名为（.pye )。

4. 使用pip工具在线升级在线科学计算扩展库numpy的完整命令是：pip install -upgrade numpy

5. 使用pip工具把本机已安装的python扩展库及版本信息输出到文本文件requirement.txt中的完整命令是：pip freeze>requirement.txt.

6. 使用pip工具查看当前已安装的python扩展库的完整命令是：pip list

7. 表达式 int('11111',2)的值是：31

8. 表达式 chr(ord('D')+2)的值为：'F'

9. 简单解释python基于值的内存管理模式：python采用的是基于值的内存管理模式，在python中可以为不同变量赋值为相同值，这个值在内存中只有一份，多个变量指向同一个内存地址；python具有自动内存管理功能，会自动跟踪内存中的所有值，对于没有任何变量指向的值，python自动将其删除。

10. 在python关键词中表示空类型的是 ： None

11. 查看变量类型的python内置函数是： type()

12. 查看对象内存地址的python内置函数是： id()

13. python运算符中用来计算并集，差集，交集的分别是： | , -  ,&   

14. 表达式 abs (-3)  的值为 3

15.  python3.x中，语句 print(1,2,3, sep=':')的输出结果是：1：2：3

16. （len（））可以返回列表、元组、字典、集合、字符串以及range对象中元素的个数。

17. 表达式 chr(ord('a')-32)的值为： ‘A’

18. 表达式  abs(3+4a)  的值为 5.0

19. 表达式  type({3})  的值为 set    #集合

20. 表达式  type({3:3})的值为 dict

21. 表达式  isinstance('Hello World', str)的值为  True

22. 表达式  type(3) == int 的值为  True

23. 为什么尽量从列表的尾部进行元素的增添和删除操作？   当列表增加或删除元素时，列表对象自动进行内存扩展或收缩，从而保证元素之间没有缝隙，但这涉及列表元素的移动，效率极低，应尽量从列表尾部进行元素的增加与删除操作，以提高处理速度。

24. python3.x 的 range（）函数返回一个    range对象

25. 编写程序，生成包含1000个0-100的随机数，并统计每个元素的出现个数。 

26. ```
    import random
    ran= [random.randint(0,100) for i in range(1000)]
    
    rans = set(ran)
    for i in rans:
        print(i,': ',ran.count(i))
    ```

    

27. 表达式  [3]  in  [1,2,3,4]  的值为： False        # 3 in 

28. 

29. 

30. 



1. 

1. 









1. 



#### 1 选择题

\1. 关于数据的存储结构，以下选项描述正确的是

A

数据所占的存储空间量

B

数据在计算机中的顺序存储方式

C

数据的逻辑结构在计算机中的表示

D

存储在外存中的数据

正确答案： C 

 

\2. 关于线性链表的描述，以下选项中正确的是

A

存储空间不一定连续，且前件元素一定存储在后件元素的前面

B

存储空间必须连续，且前件元素一定存储在后件元素的前面

C

存储空间必须连续，且各元素的存储顺序是任意的

D

存储空间不一定连续，且各元素的存储顺序是任意的

正确答案： D 

 

\3. 在深度为 7 的满二叉树中，叶子结点的总个数是

A

31

B

64

C

63

D

32

正确答案： B 

 

\4. 关于结构化程序设计所要求的基本结构，以下选项中描述错误的是

A

重复（循环）结构

B

选择（分支）结构

C

goto 跳转

D

顺序结构

正确答案： C 

 

\5. 关于面向对象的继承，以下选项中描述正确的是

A

继承是指一组对象所具有的相似性质

B

继承是指类之间共享属性和操作的机制

C

继承是指各对象之间的共同性质

D

继承是指一个对象具有另一个对象的性质

正确答案： B 

 

\6. 关于软件危机，以下选项中描述错误的是

A

软件成本不断提高

B

软件质量难以控制

C

软件过程不规范

D

软件开发生产率低

正确答案： C 

 

\7. 关于软件测试，以下选项中描述正确的是

A

软件测试的主要目的是确定程序中错误的位置

B

为了提高软件测试的效率，最好由程序编制者自己来完成软件的测试工作

C

软件测试是证明软件没有错误

D

软件测试的主要目的是发现程序中的错误

正确答案： D 

 

\8. 以下选项中用树形结构表示实体之间联系的模型是

A

网状模型

B

层次模型

C

静态模型

D

关系模型

正确答案： B 

 

\9. 设有表示学生选课的三张表，学生S（学号，姓名，性别，年龄，身份证号），课程（课号，课程名），选课SC（学号，课号，成绩），表SC的关键字（键或码）是

A

学号，成绩

B

学号，课号

C

学号，姓名，成绩

D

课号，成绩

正确答案： B 

 

10.

设有如下关系表：

![img](file:///C:/Users/1234/AppData/Local/Temp/msohtmlclip1/01/clip_image001.jpg) 

以下选项中正确地描述了关系表 R、S、T 之间关系的是

A

T＝R∪S   

B

T＝R×S             

C

T＝R–S             

D

T＝R∩S 

正确答案： C 

 

\11. 关于 Python 程序格式框架的描述，以下选项中错误的是

A

Python 语言的缩进可以采用 Tab 键实现

B

Python 单层缩进代码属于之前最邻近的一行非缩进代码，多层缩进代码根据缩进关系决定所属范围

C

判断、循环、函数等语法形式能够通过缩进包含一批 Python 代码，进而表达对应的语义

D

Python 语言不采用严格的“缩进”来表明程序的格式框架

正确答案： D 

 

\12. 以下选项中不符合 Python 语言变量命名规则的是

A

I

B

3_1

C

_AI

D

TempStr

正确答案： B 

 

\13. 以下关于 Python 字符串的描述中，错误的是

A

字符串是字符的序列，可以按照单个字符或者字符片段进行索引

B

字符串包括两种序号体系：正向递增和反向递减

C

Python 字符串提供区间访问方式，采用 [N:M] 格式，表示字符串中从 N 到 M 的索引子字符串（包含 N 和 M）

D

字符串是用一对双引号" "或者单引号' '括起来的零个或者多个字符

正确答案： C 

 

\14. 关于 Python 语言的注释，以下选项中描述错误的是

A

Python 语言的单行注释以#开头

B

Python 语言的单行注释以单引号 ' 开头

C

Python 语言的多行注释以 ' ' '（三个单引号）开头和结尾

D

Python 语言有两种注释方式：单行注释和多行注释

正确答案： B 

 

\15. 关于 import 引用，以下选项中描述错误的是

A

使用 import turtle 引入turtle 库

B

可以使用 from turtle import setup 引入 turtle 库

C

使用 import turtle as t 引入 turtle 库，取别名为 t

D

import 保留字用于导入模块或者模块中的对象

正确答案： B 

 

16.

下面代码的输出结果是

```
x = 12.34print(type(x))
```

A

<class 'int'>

B

<class 'float'>

C

<class 'bool'>

D

<class 'complex'>

正确答案： B 

 

\17. 关于 Python 的复数类型，以下选项中描述错误的是

A

复数的虚数部分通过后缀“J”或者“j”来表示

B

对于复数 z，可以用 z.real 获得它的实数部分

C

对于复数 z，可以用 z.imag 获得它的实数部分

D

复数类型表示数学中的复数

正确答案： C 

 

\18. 关于 Python 字符串，以下选项中描述错误的是

A

可以使用 datatype() 测试字符串的类型

B

输出带有引号的字符串，可以使用转义字符\

C

字符串是一个字符序列，字符串中的编号叫“索引”

D

字符串可以保存在变量中，也可以单独存在

正确答案： A 

 

\19. 关于 Python 的分支结构，以下选项中描述错误的是

A

分支结构使用 if 保留字

B

Python 中 if-else 语句用来形成二分支结构

C

Python 中 if-elif-else 语句描述多分支结构

D

分支结构可以向已经执行过的语句部分跳转

正确答案： D 

 

\20. 关于程序的异常处理，以下选项中描述错误的是

A

程序异常发生经过妥善处理可以继续执行

B

异常语句可以与 else 和 finally 保留字配合使用

C

编程语言中的异常和错误是完全相同的概念

D

Python 通过 try、except 等保留字提供异常处理功能

正确答案： C 

 

\21. 关于函数，以下选项中描述错误的是

A

函数能完成特定的功能，对函数的使用不需要了解函数内部实现原理，只要了解函数的输入输出方式即可。

B

使用函数的主要目的是减低编程难度和代码重用

C

Python 使用 del 保留字定义一个函数

D

函数是一段具有特定功能的、可重用的语句组

正确答案： C 

 

\22. 关于 Python 组合数据类型，以下选项中描述错误的是

A

组合数据类型可以分为 3 类：序列类型、集合类型和映射类型

B

序列类型是二维元素向量，元素之间存在先后关系，通过序号访问

C

Python 的 str、tuple 和 list 类型都属于序列类型

D

Python 组合数据类型能够将多个同类型或不同类型的数据组织起来，通过单一的表示使数据操作更有序、更容易

正确答案： B 

 

\23. 关于 Python 序列类型的通用操作符和函数，以下选项中描述错误的是

A

如果 x 不是 s 的元素，x not in s 返回 True

B

如果 s 是一个序列，s = [1,"kate",True]，s[3] 返回 True

C

如果 s 是一个序列，s = [1,"kate",True]，s[–1] 返回 True

D

如果 x 是 s 的元素，x in s 返回 True

正确答案： B 

 

\24. 关于 Python 对文件的处理，以下选项中描述错误的是

A

Python 通过解释器内置的 open() 函数打开一个文件

B

当文件以文本方式打开时，读写按照字节流方式

C

文件使用结束后要用 close() 方法关闭，释放文件的使用授权

D

Python 能够以文本和二进制两种方式处理文件

正确答案： B 

 

\25. 以下选项中不是 Python 对文件的写操作方法的是

A

writelines

B

write 和 seek

C

writetext

D

write

正确答案： C 

 

\26. 关于数据组织的维度，以下选项中描述错误的是

A

一维数据采用线性方式组织，对应于数学中的数组和集合等概念

B

二维数据采用表格方式组织，对应于数学中的矩阵

C

高维数据有键值对类型的数据构成，采用对象方式组织

D

数据组织存在维度，字典类型用于表示一维和二维数据

正确答案： D 

 

\27. 以下选项中不是 Python 语言的保留字的是

A

except

B

do

C

pass

D

while

正确答案： B 

 

\28. 以下选项中是 Python 中文分词的第三方库的是

A

jieba

B

itchat

C

time

D

turtle

正确答案： A 

 

\29. 以下选项中使 Python 脚本程序转变为可执行程序的第三方库的是

A

pygame

B

PyQt5

C

PyInstaller

D

random

正确答案： C 

 

\30. 以下选项中不是 Python 数据分析的第三方库的是

A

numpy

B

scipy

C

pandas

D

requests

正确答案： D 

 

31.

下面代码的输出结果是

```
x = 0o1010print(x)
```

A

520

B

1024

C

32768

D

10

正确答案： A 

 

32.

下面代码的输出结果是

```
x=10
```

```
y=3print(divmod(x,y))
```

A

(1, 3)

B

3,1

C

1,3

D

(3, 1)

正确答案： D 

 

33.

下面代码的输出结果是

```
for s in "HelloWorld":
```

```
    if s=="W":
```

```
        continue
```

```
    print(s,end="")
```

A

Hello

B

World

C

HelloWorld

D

Helloorld

正确答案： D 

 

34.

给出如下代码：

```
DictColor = {"seashell":"海贝色","gold":"金色","pink":"粉红色","brown":"棕色", "purple":"紫色","tomato":"西红柿色"} 
```

以下选项中能输出“海贝色”的是

A

print(DictColor.keys())

B

print(DictColor["海贝色"])

C

print(DictColor.values())

D

print(DictColor["seashell"])

正确答案： D 

 

35.

下面代码的输出结果是

```
s =["seashell","gold","pink","brown","purple","tomato"]print(s[1:4:2])
```

 

A

['gold', 'pink', 'brown']

B

['gold', 'pink']

C

['gold', 'pink', 'brown', 'purple', 'tomato']

D

['gold', 'brown']

正确答案： D 

 

36.

下面代码的输出结果是

```
d ={"大海":"蓝色", "天空":"灰色", "大地":"黑色"}print(d["大地"], d.get("大地", "黄色"))
```

A

黑的 灰色

B

黑色 黑色

C

黑色 蓝色

D

黑色 黄色

正确答案： B 

 

37.

当用户输入abc时，下面代码的输出结果是

```
try:
```

```
   n = 0
```

```
   n = input("请输入一个整数: ")
```

```
   def pow10(n):
```

```
      return n**10except:
```

```
   print("程序执行错误")
```

A

输出：abc

B

程序没有任何输出

C

输出：0

D

输出：程序执行错误

正确答案： B 

 

38.

下面代码的输出结果是

```
a = [[1,2,3], [4,5,6], [7,8,9]]
```

```
s = 0 for c in a:
```

```
   for j in range(3):
```

```
      s += c[j]print(s)
```

A

0

B

45

C

以上答案都不对

D

24

正确答案： B 

 

39.

文件 book.txt 在当前程序所在目录内，其内容是一段文本：book，下面代码的输出结果是

```
txt = open("book.txt", "r")print(txt)
```

```
txt.close()
```

A

book.txt

B

txt

C

以上答案都不对

D

book

正确答案： C 

 

40.

如果当前时间是 2018年5月1日10点10分9秒，则下面代码的输出结果是

```
import timeprint(time.strftime("%Y=%m-%d@%H>%M>%S", time.gmtime()))
```

A

2018=05-01@10>10>09

B

2018=5-1 10>10>9

C

True@True

D

2018=5-1@10>10>9

正确答案： A 

 

 

**1.** 关于算法的描述，以下选项中错误的是

A

算法具有可行性、确定性、有穷性的基本特征

B

算法的复杂度主要包括时间复杂度和数据复杂度

C

算法的基本要素包括数据对象的运算和操作及算法的控制结构

D

算法是指解题方案的准确而完整的描述

正确答案： B 

 

**2.** 关于数据结构的描述，以下选项中正确的是

A

数据的存储结构是指反映数据元素之间逻辑关系的数据结构

B

数据的逻辑结构有顺序、链接、索引等存储方式

C

数据结构不可以直观地用图形表示

D

数据结构指相互有关联的数据元素的集合

正确答案： D 

 

**3.** 在深度为7的满二叉树中，结点个数总共是

A

64

B

127

C

63

D

32

正确答案： B 

 

**4.** 对长度为n的线性表进行顺序查找，在最坏的情况下所需要的比较次数是

A

n×(n+1)

B

n-1

C

n

D

n+1

正确答案： C 

 

**5.** 关于结构化程序设计方法原则的描述，以下选项中错误的是

A

逐步求精

B

多态继承

C

模块化

D

自顶向下

正确答案： B 

 

**6.** 与信息隐蔽的概念直接相关的概念是

A

模块独立性

B

模块类型划分

C

模块耦合度

D

软件结构定义

正确答案： A 

 

**7.** 关于软件工程的描述，以下选项中描述正确的是

A

软件工程包括3要素：结构化、模块化、面向对象

B

软件工程工具是完成软件工程项目的技术手段

C

软件工程方法支持软件的开发、管理、文档生成

D

软件工程是应用于计算机软件的定义、开发和维护的一整套方案、工具、文档和实践标准和工序

正确答案： D 

 

**8.** 在软件工程详细设计阶段，以下选项中不是详细设计工具的是

A

程序流程图

B

CSS

C

PAL

D

判断表

正确答案： B 

 

**9.** 以下选项中表示关系表中的每一横行的是

A

属性

B

列

C

码

D

元组

正确答案： D 

 

**10.** 将E-R图转换为关系模式时，可以表示实体与联系的是

A

关系

B

键

C

域

D

属性

正确答案： A 

 

**11.** 以下选项中Python用于异常处理结构中用来捕获特定类型的异常的保留字是

A

except

B

do

C

pass

D

while

正确答案： A 

 

**12.** 以下选项中符合Python语言变量命名规则的是

A

*i

B

3_1

C

AI!

D

Templist

正确答案： D 

 

**13.**

关于赋值语句，以下选项中描述错误的是

A

在 Python 语言中，有一种赋值语句，可以同时给多个变量赋值

B

设 x = "alice"；y = "kate"，执行

```
x,y = y,x
```

可以实现变量 x 和 y 值的互换

C

设 a = 10；b = 20，执行

```
a,b = a,a + bprint(a,b)
```

和

```
a = b
```

```
b = a + bprint(a,b)
```

之后，得到同样的输出结果：10 30

D

在 Python 语言中，“=”表示赋值，即将“=”右侧的计算结果赋值给左侧变量，包含“=”的语句称为赋值语句

正确答案： C 

 

**14.**

关于 eval 函数，以下选项中描述错误的是

A

eval 函数的作用是将输入的字符串转为 Python 语句，并执行该语句

B

如果用户希望输入一个数字，并用程序对这个数字进行计算，可以采用 eval(input(<输入提示字符串>)) 组合

C

执行 eval("Hello") 和执行 eval(" 'Hello' ") 得到相同的结果

D

eval 函数的定义为：eval(source, globals=None, locals=None, /)

正确答案： C 

 

**15.** 关于 Python 语言的特点，以下选项中描述错误的是

A

Python 语言是非开源语言

B

Python 语言是跨平台语言

C

Python 语言是多模型语言

D

Python 语言是脚本语言

正确答案： A 

 

**16.** 关于 Python 的数字类型，以下选项中描述错误的是

A

Python 整数类型提供了 4 种进制表示：十进制、二进制、八进制和十六进制

B

Python 语言要求所有浮点数必须带有小数部分

C

Python 语言中，复数类型中实数部分和虚数部分的数值都是浮点类型，复数的虚数部分通过后缀“C”或者“c”来表示

D

Python 语言提供 int、float、complex 等数字类型

正确答案： C 

 

**17.** 关于Python循环结构，以下选项中描述错误的是

A

遍历循环中的遍历结构可以是字符串、文件、组合数据类型和range()函数等

B

break用来跳出最内层for或者while循环，脱离该循环后程序从循环代码后继续执行

C

每个continue语句只有能力跳出当前层次的循环

D

Python通过for、while等保留字提供遍历循环和无限循环结构

正确答案： C 

 

**18.** 关于Python的全局变量和局部变量，以下选项中描述错误的是

A

局部变量指在函数内部使用的变量，当函数退出时，变量依然存在，下次函数调用可以继续使用

B

使用global保留字声明简单数据类型变量后，该变量作为全局变量使用

C

简单数据类型变量无论是否与全局变量重名，仅在函数内部创建和使用，函数退出后变量被释放

D

全局变量指在函数之外定义的变量，一般没有缩进，在程序执行全过程有效

正确答案： A 

 

**19.** 关于Python的lambda函数，以下选项中描述错误的是

A

可以使用lambda函数定义列表的排序原则

B

f = lambda x,y:x+y 执行后，f的类型为数字类型

C

lambda函数将函数名作为函数结果返回

D

lambda用于定义简单的、能够在一行内表示的函数

正确答案： B 

 

**20.**

下面代码实现的功能描述的是

```
def fact(n):
```

```
    if n==0:
```

```
        return 1
```

```
    else:
```

```
        return n*fact(n-1)
```

```
num =eval(input("请输入一个整数："))print(fact(abs(int(num))))
```

A

接受用户输入的整数 n，判断 n 是否是素数并输出结论

B

接受用户输入的整数 n，判断 n 是否是完数并输出结论

C

接受用户输入的整数 n，判断 n 是否是水仙花数

D

接受用户输入的整数 n，输出 n 的阶乘值

正确答案： D 

 

**21.**

执行如下代码：

```
import timeprint(time.time())
```

以下选项中描述错误的是

A

time 库是 Python 的标准库  

B

可使用 time.ctime()，显示为更可读的形式  

C

time.sleep(5) 推迟调用线程的运行，单位为毫秒  

D

输出自1970年1月1日00:00:00 AM 以来的秒数  

正确答案： C 

 

**22.**

执行后可以查看Python的版本的是

A

```
import sysprint(sys.Version)
```

B

```
import systemprint(system.version)
```

C

```
import systemprint(system.Version)
```

D

```
import sysprint(sys.version)
```

正确答案： D 

 

**23.** 关于Python的组合数据类型，以下选项中描述错误的是

A

组合数据类型可以分为3类：序列类型、集合类型和映射类型

B

序列类型是二维元素向量，元素之间存在先后关系，通过序号访问

C

Python的str、tuple和list类型都属于序列类型

D

Python组合数据类型能够将多个同类型或不同类型的数据组织起来，通过单一的表示使数据操作更有序、更容易

正确答案： B 

 

**24.** 以下选项中，不是Python对文件的读操作方法的是

A

readline

B

readall

C

readtext

D

read

正确答案： C 

 

**25.** 关于Python文件处理，以下选项中描述错误的是

A

Python能处理JPG图像文件

B

Python不可以处理PDF文件

C

Python能处理CSV文件

D

Python能处理Excel文件

正确答案： B 

 

**26.** 以下选项中，不是Python对文件的打开模式的是

A

'w'

B

'+'

C

'c'

D

'r'

正确答案： C 

 

**27.** 关于数据组织的维度，以下选项中描述错误的是

A

一维数据采用线性方式组织，对应于数学中的数组和集合等概念

B

二维数据采用表格方式组织，对应于数学中的矩阵

C

高维数据由键值对类型的数据构成，采用对象方式组织

D

数据组织存在维度，字典类型用于表示一维和二维数据

正确答案： D 

 

**28.** Python数据分析方向的第三方库是

A

pdfminer

B

beautifulsoup4

C

time

D

numpy

正确答案： D 

 

**29.** Python机器学习方向的第三方库是

A

PIL

B

PyQt5

C

TensorFlow

D

random

正确答案： C 

 

**30.** Python Web开发方向的第三方库是

A

Django

B

scipy

C

pandas

D

requests

正确答案： A 

 

**31.**

下面代码的输出结果是

```
x=0b1010print(x) 
```

A

16

B

256

C

1024

D

10

正确答案： D 

 

**32.**

下面代码的输出结果是 

```
x=10 
```

```
y=-1+2j print(x+y)
```

A

9

B

2j

C

11

D

(9+2j)

正确答案： D 

 

**33.**

下面代码的输出结果是 

```
x=3.1415926print(round(x,2) ,round(x))
```

A

3 3.14

B

2 2

C

6.28 3

D

3.14 3

正确答案： D 

 

**34.**

下面代码的输出结果是

```
for s in "HelloWorld":
```

```
    if s=="W":
```

```
        break
```

```
    print(s, end="")
```

A

Hello

B

World

C

HelloWorld

D

Helloorld

正确答案： A 

 

**35.** 以下选项中，输出结果是False的是

A

\>>> 5 is not 4

B

\>>> 5 != 4

C

\>>> False != 0

D

\>>> 5 is 5

正确答案： C 

 

**36.**

下面代码的输出结果是

```
a = 1000000
```

```
b = "-"print("{0:{2}^{1},}\n{0:{2}>{1},}\n{0:{2}<{1},}".format(a,30,b))
```

A

1,000,000---------------------

---------------------1,000,000

​     ---------1,000,000----------- 

B

---------------------1,000,000

1,000,000---------------------

​      ----------1,000,000-----------

C

---------------------1,000,000

----------1,000,000-----------

​     1,000,000---------------------

D

----------1,000,000-----------

---------------------1,000,000

​    1,000,000---------------------

正确答案： D 

 

**37.**

下面代码的输出结果是

```
s =["seashell","gold","pink","brown","purple","tomato"]print(s[4:])
```

A

['purple']

B

['seashell', 'gold', 'pink', 'brown']

C

['gold', 'pink', 'brown', 'purple', 'tomato']

D

['purple', 'tomato']

正确答案： D 

 

**38.**

执行如下代码：

```
import turtle as tdef DrawCctCircle(n):
```

```
    t.penup()
```

```
    t.goto(0,-n)
```

```
    t.pendown()
```

```
    t.circle(n)for i in range(20,80,20):
```

```
    DrawCctCircle(i)
```

```
t.done()
```

在 Python Turtle Graphics 中，绘制的图形是

A

同切圆

B

同心圆

C

笛卡尔心形

D

太极

正确答案： B 

 

**39.**

给出如下代码：

```
fname = input("请输入要打开的文件: ")
```

```
fo = open(fname, "r")for line in fo.readlines():
```

```
    print(line)
```

```
fo.close()
```

关于上述代码的描述，以下选项中错误的是

A

通过fo.readlines()方法将文件的全部内容读入一个字典fo

B

通过fo.readlines()方法将文件的全部内容读入一个列表fo

C

上述代码可以优化为：

```
fname = input("请输入要打开的文件: ")
```

```
fo = open(fname, "r")for line in fo.readlines():
```

```
    print(line)
```

```
fo.close()
```

D

用户输入文件路径，以文本文件方式读入文件内容并逐行打印

正确答案： A 

 

**40.**

能实现将一维数据写入CSV文件中的是

A

```
fo = open("price2016bj.csv", "w")
```

```
ls = ['AAA', 'BBB', 'CCC', 'DDD']
```

```
fo.write(",".join(ls)+ "\n")
```

```
fo.close()
```

B

```
fr = open("price2016.csv", "w")
```

```
ls = []for line in fo:
```

```
    line = line.replace("\n","")
```

```
    ls.append(line.split(","))print(ls)
```

```
fo.close()
```

C

```
fo = open("price2016bj.csv", "r")
```

```
ls = ['AAA', 'BBB', 'CCC', 'DDD']
```

```
fo.write(",".join(ls)+ "\n")
```

```
fo.close()
```

D

```
fname = input("请输入要写入的文件: ")
```

```
fo = open(fname, "w+")
```

```
ls = ["AAA", "BBB", "CCC"]
```

```
fo.writelines(ls)for line in fo:
```

```
    print(line)
```

```
fo.close()
```

正确答案： A 

 

**1.** 按照“后进先出”原则组织数据的数据结构是____

A

栈

B

双向链表

C

二叉树

D

队列

正确答案： A 

 

**2.** 以下选项的叙述中，正确的是

A

在循环队列中，只需要队头指针就能反映队列中元素的动态变化情况

B

在循环队列中，只需要队尾指针就能反映队列中元素的动态变化情况

C

循环队列中元素的个数是由队头指针和队尾指针共同决定

D

循环队列有队头和队尾两个指针，因此，循环队列是非线性结构

正确答案： C 

 

**3.** 关于数据的逻辑结构，以下选项中描述正确的是

A

数据所占的存储空间量

B

数据在计算机中的顺序存储方式

C

数据的逻辑结构是反映数据元素之间逻辑关系的数据结构

D

存储在外存中的数据

正确答案： C 

 

**4.** 以下选项中，不属于结构化程序设计方法的是

A

逐步求精

B

模块化

C

可封装

D

自顶向下

正确答案： C 

 

**5.** 以下选项中，不属于软件生命周期中开发阶段任务的是

A

概要设计

B

软件维护

C

详细设计

D

软件测试

正确答案： B 

 

**6.** 为了使模块尽可能独立，以下选项中描述正确的是

A

模块的内聚程度要尽量高，且各模块间的耦合程度要尽量弱

B

模块的内聚程度要尽量低，且各模块间的耦合程度要尽量弱

C

模块的内聚程度要尽量低，且各模块间的耦合程度要尽量强

D

模块的内聚程度要尽量高，且各模块间的耦合程度要尽量强

正确答案： A 

 

**7.** 以下选项中叙述正确的是

A

软件一旦交付就不需要再进行维护

B

软件交付使用后其生命周期就结束

C

软件维护指修复程序中被破坏的指令

D

软件交付使用后还需要进行维护

正确答案： D 

 

**8.** 数据独立性是数据库技术的重要特点之一，关于数据独立性，以下选项中描述正确的是

A

不同数据被存放在不同的文件中

B

不同数据只能被对应的应用程序所使用

C

以上三种说法都不对

D

数据与程序独立存放

正确答案： C 

 

**9.** 以下选项中，数据库系统的核心是

A

数据库管理系统

B

数据库

C

数据库管理员

D

数据模型

正确答案： A 

 

**10.** 一间宿舍可以住多个学生，以下选项中描述了实体宿舍和学生之间联系的是

A

一对多

B

多对一

C

多对多

D

一对一

正确答案： A 

 

**11.** 以下选项中不是Python文件读操作方法的是

A

readline

B

readall

C

readtext

D

read

正确答案： C 

 

**12.** 以下选项中说法不正确的是

A

C语言是静态语言，Python语言是脚本语言

B

编译是将源代码转换成目标代码的过程

C

解释是将源代码逐条转换成目标代码同时逐条运行目标代码的过程

D

静态语言采用解释方式执行，脚本语言采用编译方式执行

正确答案： D 

 

**13.** 以下选项中，不是Python语言特点的是

A

变量声明：Python语言具有使用变量需要先定义后使用的特点

B

平台无关：Python程序可以在任何安装了解释器的操作系统环境中执行

C

黏性扩展：Python语言能够集成C、C++等语言编写的代码

D

强制可读：Python语言通过强制缩进来体现语句间的逻辑关系

正确答案： A 

 

**14.** 拟在屏幕上打印输出“Hello World”，以下选项中正确的是

A

print('Hello World')

B

printf("Hello World")

C

printf('Hello World')

D

print(Hello World)

正确答案： A 

 

**15.** IDLE环境的退出命令是

A

esc()

B

close()

C

回车键

D

exit()

正确答案： D 

 

**16.** 以下选项中，不符合Python语言变量命名规则的是

A

keyword33_

B

33_keyword

C

_33keyword

D

keyword_33

正确答案： B 

 

**17.** 以下选项中，不是Python语言保留字的是

A

while

B

continue

C

goto

D

for

正确答案： C 

 

**18.** 以下选项中，Python语言中代码注释使用的符号是

A

/*… …*/

B

！

C

\#

D

//

正确答案： C 

 

**19.** 关于Python语言的变量，以下选项中说法正确的是

A

随时声明、随时使用、随时释放

B

随时命名、随时赋值、随时使用

C

随时声明、随时赋值、随时变换类型

D

随时命名、随时赋值、随时变换类型

正确答案： B 

 

**20.** Python语言提供的3个基本数字类型是

A

整数类型、浮点数类型、复数类型

B

整数类型、二进制类型、浮点数类型

C

整数类型、二进制类型、复数类型

D

整数类型、二进制类型、浮点数类型

正确答案： A 

 

**21.** 以下选项中，不属于IPO模式一部分的是

A

Program (程序)

B

Process (处理)

C

Output (输出)

D

Input (输入)

正确答案： A 

 

**22.** 以下选项中，属于Python语言中合法的二进制整数是

A

0B1010

B

0B1019

C

0bC3F

D

0b1708

正确答案： A 

 

**23.** 关于Python语言的浮点数类型，以下选项中描述错误的是

A

浮点数类型表示带有小数的类型

B

Python语言要求所有浮点数必须带有小数部分

C

小数部分不可以为0

D

浮点数类型与数学中实数的概念一致

正确答案： C 

 

**24.** 关于Python语言数值操作符，以下选项中描述错误的是

A

x//y表示x与y之整数商，即不大于x与y之商的最大整数

B

x**y表示x的y次幂，其中，y必须是整数

C

x%y表示x与y之商的余数，也称为模运算

D

x/y表示x与y之商

正确答案： B 

 

**25.** 以下选项中，不是Python语言基本控制结构的是

A

程序异常

B

循环结构

C

跳转结构

D

顺序结构

正确答案： C 

 

**26.** 关于分支结构，以下选项中描述不正确的是

A

if 语句中条件部分可以使用任何能够产生True和False的语句和函数

B

二分支结构有一种紧凑形式，使用保留字if和elif实现

C

多分支结构用于设置多个判断条件以及对应的多条执行路径

D

if 语句中语句块执行与否依赖于条件判断

正确答案： B 

 

**27.** 关于Python函数，以下选项中描述错误的是

A

函数是一段可重用的语句组

B

函数通过函数名进行调用

C

每次使用函数需要提供相同的参数作为输入

D

函数是一段具有特定功能的语句组

正确答案： C 

 

**28.** 以下选项中，不是Python中用于开发用户界面的第三方库是

A

PyQt

B

wxPython

C

pygtk

D

turtle

正确答案： D 

 

**29.** 以下选项中，不是Python中用于进行数据分析及可视化处理的第三方库是

A

pandas

B

mayavi2

C

mxnet

D

numpy

正确答案： C 

 

**30.** 以下选项中，不是Python中用于进行Web开发的第三方库是

A

Django

B

scrapy

C

pyramid

D

flask

正确答案： B 

 

**31.**

下面代码的执行结果是

```
>>>1.23e-4+5.67e+8j.real
```

A

1.23

B

5.67e+8

C

1.23e4

D

0.000123

正确答案： D 

 

**32.**

下面代码的执行结果是

```
>>>s = "11+5in">>>eval(s[1:-2])
```

A

6

B

11+5

C

执行错误

D

16

正确答案： A 

 

**33.**

下面代码的执行结果是

```
>>>abs(-3+4j)
```

A

4.0

B

5.0

C

执行错误

D

3.0

正确答案： B 

 

**34.**

下面代码的执行结果是

```
>>>x = 2>>>x *= 3 + 5**2
```

A

15

B

56

C

8192

D

13

正确答案： B 

 

**35.**

下面代码的执行结果是

```
ls=[[1,2,3],[[4,5],6],[7,8]]print(len(ls))
```

A

3

B

4

C

8

D

1

正确答案： A 

 

**36.**

下面代码的执行结果是

```
a = "Python等级考试"
```

```
b = "="
```

```
c = ">"print("{0:{1}{3}{2}}".format(a, b, 25, c))
```

A

Python等级考试===============

B

\>>>>>>>>>>>>>>>Python等级考试

C

Python等级考试===============

D

===============Python等级考试

正确答案： D 

 

**37.**

下面代码的执行结果是：

```
ls = ["2020", "20.20", "Python"]
```

```
ls.append(2020)
```

```
ls.append([2020, "2020"])print(ls)
```

A

['2020', '20.20', 'Python', 2020]

B

['2020', '20.20', 'Python', 2020, [2020, '2020']]

C

['2020', '20.20', 'Python', 2020, ['2020']]

D

['2020', '20.20', 'Python', 2020, 2020, '2020']

正确答案： B 

 

**38.**

设city.csv文件内容如下：

```
巴哈马,巴林,孟加拉国,巴巴多斯
```

```
白俄罗斯,比利时,伯利兹
```

下面代码的执行结果是：

```
f = open("city.csv", "r")
```

```
ls = f.read().split(",")
```

```
f.close()print(ls)
```

A

['巴哈马', '巴林', '孟加拉国', '巴巴多斯\n白俄罗斯', '比利时', '伯利兹']

B

['巴哈马, 巴林, 孟加拉国, 巴巴多斯, 白俄罗斯, 比利时, 伯利兹']

C

['巴哈马', '巴林', '孟加拉国', '巴巴多斯', '\n', '白俄罗斯', '比利时', '伯利兹']

D

['巴哈马', '巴林', '孟加拉国', '巴巴多斯', '白俄罗斯', '比利时', '伯利兹']

正确答案： A 

 

**39.**

下面代码的执行结果是：

```
d = {}for i in range(26):
```

```
    d[chr(i+ord("a"))] = chr((i+13) % 26 + ord("a"))for c in "Python":print(d.get(c, c), end="")
```

A

Cabugl

B

Python

C

Pabugl

D

Plguba

正确答案： D 

 

**40.**

给出如下代码：

```
while True:
```

```
guess = eval(input())if guess == 0x452//2:
```

```
    break
```

作为输入能够结束程序运行的是

A

553

B

0x452

C

"0x452//2"

D

break

正确答案： A 

 

**1.** 以下选项中，不属于需求分析阶段的任务是

A

需求规格说明书评审

B

确定软件系统的性能需求

C

确定软件系统的功能需求

D

制定软件集成测试计划

正确答案： D 

 

**2.** 关于数据流图（DFD）的描述，以下选项中正确的是

A

软件详细设计的工具

B

结构化方法的需求分析工具

C

面向对象需求分析工具

D

软件概要设计的工具

正确答案： B 

 

**3.** 在黑盒测试方法中，设计测试用例的主要根据是

A

程序流程图

B

程序数据结构

C

程序内部逻辑

D

程序外部功能

正确答案： D 

 

**4.** 一个教师讲授多门课程，一门课程由多个教师讲授。描述了实体教师和课程的联系的选项是

A

m : n联系

B

m : 1联系

C

1 : n联系

D

1 : 1联系

正确答案： A 

 

**5.** 数据库设计中，反映用户对数据要求的模式是

A

内模式

B

设计模式

C

外模式

D

概念模式

正确答案： C 

 

**6.** 在数据库设计中，用E-R图来描述信息结构但不涉及信息在计算机中的表示的阶段是

A

概念设计阶段

B

逻辑设计阶段

C

物理设计阶段

D

需求分析阶段

正确答案： A 

 

**7.** 以下选项中描述正确的是

A

只有一个根结点的数据结构不一定是线性结构

B

循环链表是非线性结构

C

双向链表是非线性结构

D

有一个以上根结点的数据结构不一定是非线性结构

正确答案： A 

 

**8.** 一棵二叉树共有25个结点，其中5个是叶子结点，则度为1的结点数是

A

6

B

16

C

10

D

4

正确答案： B 

 

**9.**

下图所示的二叉树进行前序遍历的序列是
 ![IMG_256](file:///C:/Users/1234/AppData/Local/Temp/msohtmlclip1/01/clip_image002.jpg)

 

A

YDEBFZXCA

B

ABDYECFXZ

C

ABCDEFXYZ

D

DYBEAFCZX

正确答案： B 

 

**10.** 以下选项中描述正确的是

A

算法的时间复杂度与空间复杂度一定相关

B

算法的时间复杂度是指执行算法所需要的计算工作量

C

算法的效率只与问题的规模有关，而与数据的存储结构无关

D

数据的逻辑结构与存储结构是一一对应的

正确答案： A 

 

**11.** Python文件的后缀名是

A

pdf

B

do

C

pass

D

py

正确答案： D 

 

**12.**

下面代码的输出结果是

```
print( 0.1 + 0.2 == 0.3)
```

A

False

B

–1

C

0

D

while

正确答案： A 

 

**13.** 以下选项中，不是Python语言保留字的是

A

except

B

do

C

pass

D

while

正确答案： B 

 

**14.**

下面代码的执行结果

```
a = 10.99print(complex(a))
```

A

10.99+j

B

10.99

C

0.99

D

(10.99+0j)

正确答案： D 

 

**15.** 关于 Python 字符编码，以下选项中描述错误的是

A

chr(x) 和 ord(x) 函数用于在单字符和 Unicode 编码值之间进行转换

B

print chr(65) 输出 A

C

print(ord('a')) 输出 97

D

Python 字符编码使用 ASCII 编码

正确答案： D 

 

**16.** 关于Python循环结构，以下选项中描述错误的是

A

遍历循环中的遍历结构可以是字符串、文件、组合数据类型和range()函数等

B

break用来结束当前当次语句，但不跳出当前的循环体

C

continue只结束本次循环

D

Python通过for、while等保留字构建循环结构

正确答案： B 

 

**17.**

给出如下代码

```
import random
```

```
num = random.randint(1,10)while True:
```

```
    if num >= 9:
```

```
        breakelse:
```

```
        num = random.randint(1,10)
```

以下选项中描述错误的是

A

这段代码的功能是程序自动猜数字

B

import random代码是可以省略的

C

while True: 创建了一个永远执行的循环

D

random.randint(1,10) 生成[1,10]之间的整数

正确答案： B 

 

**18.** 关于time库的描述，以下选项中错误的是

A

time库提供获取系统时间并格式化输出功能

B

time.sleep(s)的作用是休眠s秒

C

time.perf_counter()返回一个固定的时间计数值

D

time库是Python中处理时间的标准库

正确答案： C 

 

**19.** 关于jieba库的描述，以下选项中错误的是

A

jieba.cut(s)是精确模式，返回一个可迭代的数据类型

B

jieba.lcut(s)是精确模式，返回列表类型

C

jieba.add_word(s)是向分词词典里增加新词s

D

jieba是Python中一个重要的标准函数库

正确答案： D 

 

**20.** 对于列表ls的操作，以下选项中描述错误的是

A

ls.clear()：删除ls的最后一个元素

B

ls.copy()：生成一个新列表，复制ls的所有元素

C

ls.reverse()：列表ls的所有元素反转

D

ls.append(x)：在ls最后增加一个元素

正确答案： A 

 

**21.**

下面代码的输出结果是

```
listV = list(range(5))print(2 in listV)
```

A

False

B

0

C

-1

D

True

正确答案： D 

 

**22.**

给出如下代码

```
import random as ran
```

```
listV = []
```

```
ran.seed(100)for i in range(10):
```

```
    i = ran.randint(100,999)
```

```
    listV.append(i)
```

以下选项中能输出随机列表元素最大值的是

A

print(listV.max())

B

print(listV.pop(i))

C

print(max(listV))

D

print(listV.reverse(i))

正确答案： C 

 

**23.**

给出如下代码 

```
MonthandFlower={"1月":"梅花","2月":"杏花","3月":"桃花","4月":"牡丹花",\"5月":"石榴花","6月":"莲花","7月":"玉簪花","8月":"桂花",\"9月":"菊花","10月":"芙蓉花","11月":"山茶花","12月":"水仙花"}
```

```
n = input("请输入1—12的月份:")print(n + "月份之代表花：" + MonthandFlower.get(str(n)+"月"))
```

以下选项中描述正确的是

A

代码实现了获取一个整数（1—12）来表示月份，输出该月份对应的代表花名

B

MonthandFlower是列表类型变量

C

MonthandFlower是一个元组

D

MonthandFlower是集合类型变量

正确答案： A 

 

**24.** 关于Python文件打开模式的描述，以下选项中描述错误的是

A

覆盖写模式w

B

追加写模式a

C

创建写模式n

D

只读模式r

正确答案： C 

 

**25.**

执行如下代码：

```
fname = input("请输入要写入的文件: ")
```

```
fo = open(fname, "w+")
```

```
ls = ["清明时节雨纷纷，","路上行人欲断魂，","借问酒家何处有？","牧童遥指杏花村。"]
```

```
fo.writelines(ls)
```

```
fo.seek(0)for line in fo:
```

```
    print(line)
```

```
fo.close()
```

以下选项中描述错误的是

A

fo.writelines(ls)将元素全为字符串的ls列表写入文件

B

fo.seek(0)这行代码如果省略，也能打印输出文件内容

C

代码主要功能为向文件写入一个列表类型，并打印输出结果

D

执行代码时，从键盘输入“清明.txt”，则清明.txt被创建

正确答案： B 

 

**26.** 关于CSV文件的描述，以下选项中错误的是

A

CSV文件的每一行是一维数据，可以使用Python中的列表类型表示

B

CSV文件通过多种编码表示字符

C

整个CSV文件是一个二维数据

D

CSV文件格式是一种通用的文件格式，应用于程序之间转移表格数据

正确答案： B 

 

**27.** 以下选项中，修改turtle画笔颜色的函数是

A

seth()

B

colormode()

C

bk()

D

pencolor()

正确答案： D 

 

**28.** 以下选项中，Python网络爬虫方向的第三方库是

A

numpy

B

openpyxl

C

PyQt5

D

scrapy

正确答案： D 

 

**29.** 以下选项中，Python数据分析方向的第三方库是

A

PIL

B

Django

C

pandas

D

flask

正确答案： C 

 

**30.** 以下选项中，Python机器学习方向的第三方库是

A

TensorFlow

B

scipy

C

PyQt5

D

requests

正确答案： A 

 

**31.**

给出如下代码：

```
TempStr = "Hello World"
```

以下选项中可以输出“World”子串的是

A

print(TempStr[–5: –1])

B

print(TempStr[–5:0])

C

print(TempStr[–4: –1])print(TempStr[–4: –1])

D

print(TempStr[–5:])

正确答案： D 

 

**32.**

下面代码的输出结果是

```
x = 12.34print(type(x))
```

A

<class 'int'>

B

<class 'float'>

C

<class 'bool'>

D

<class 'complex'>

正确答案： B 

 

**33.**

下面代码的输出结果是

```
x=10
```

```
y=3print(x%y,x**y)
```

A

3 1000

B

1 30

C

3 30

D

1 1000

正确答案： D 

 

**34.**

执行如下代码

```
import turtle as tfor i in range(1,5):
```

```
    t.fd(50)
```

```
    t.left(90)
```

在Python Turtle Graphics中，绘制的是

A

五边形

B

三角形

C

五角星

D

正方形

正确答案： D 

 

**35.** 设一年356天，第1天的能力值为基数记为1.0。当好好学习时能力值相比前一天会提高千分之五。以下选项中，不能获得持续努力1年后的能力值的是

A

1.005 ** 365

B

pow((1.0 +0.005),365)

C

1.005 // 365

D

pow(1.0 + 0.005,365)

正确答案： C 

 

**36.**

给出如下代码：

```
s = list("巴老爷有八十八棵芭蕉树，来了八十八个把式要在巴老爷八十八棵芭蕉树下住。\
```

```
老爷拔了八十八棵芭蕉树，不让八十八个把式在八十八棵芭蕉树下住。八十八个把式\
```

```
烧了八十八棵芭蕉树，巴老爷在八十八棵树边哭。")
```

以下选项中能输出字符“八”出现次数的是

A

print(s.index("八"))

B

print(s.index("八"),6)

C

print(s.index("八"),6,len(s))

D

print(s.count("八"))

正确答案： D 

 

**37.**

下面代码的输出结果是

```
vlist = list(range(5))print(vlist)
```

A

0 1 2 3 4

B

0,1,2,3,4,

C

0;1;2;3;4;

D

[0, 1, 2, 3, 4]

正确答案： D 

 

**38.** 以下选项中，不是建立字典的方式是

A

d = {[1,2]:1, [3,4]:3}

B

d = {(1,2):1, (3,4):3}

C

d = {'张三':1, '李四':2}

D

d = {1:[1,2], 3:[3,4]}

正确答案： A 

 

**39.**

如果name = "全国计算机等级考试二级Python"，以下选项中输出错误的是

A

```
>>>print(name[:]) 
```

```
全国计算机等级考试二级Python
```

B

```
>>> print(name[11:])
```

```
Python
```

C

```
>>> print(name[:11])
```

```
全国计算机等级考试二级
```

D

```
>>> print(name[0], name[8], name[–1]) 
```

```
全 试
```

正确答案： D 

 

**40.**

下列程序的运行结果是

```
>>> s = ‘PYTHON’>>> “{0:3}”.format(s)
```

A

‘PYTH’

B

‘PYTHON’

C

‘ PYTHON’

D

‘PYT’

正确答案： B 

 

**1.** 关于二叉树的遍历，以下选项中描述错误的是

A

二叉树的遍历可以分为三种：前序遍历、中序遍历、后序遍历

B

前序遍历是先遍历左子树，然后访问根结点，最后遍历右子树

C

后序遍历二叉树的过程是一个递归的过程

D

二叉树的遍历是指不重复地访问二叉树中的所有结点

正确答案： B 

 

**2.** 关于二叉树的描述，以下选项中错误的是

A

二叉树具有两个特点：非空二叉树只有一个根结点；每一个结点最多有两棵子树，且分别称为该结点的左子树与右子树

B

在任意一棵二叉树中，度为0的结点（叶子结点）比度为2的结点多一个

C

深度为m的二叉树最多有2的m次幂个结点

D

二叉树是一种非线性结构

正确答案： C 

 

**3.** 关于查找技术的描述，以下选项中错误的是

A

如果采用链式存储结构的有序线性表，只能用顺序查找

B

二分查找只适用于顺序存储的有序表

C

顺序查找的效率很高

D

查找是指在一个给定的数据结构中查找某个特定的元素

正确答案： C 

 

**4.** 关于排序技术的描述，以下选项中错误的是

A

选择排序法在最坏的情况下需要比较n(n–1)/2次

B

快速排序法比冒泡排序法的速度快

C

冒泡排序法是通过相邻数据元素的交换逐步将线性表变成有序

D

简单插入排序在最坏的情况下需要比较n的1.5幂 次

正确答案： D 

 

**5.** 关于面向对象的程序设计，以下选项中描述错误的是

A

面向对象方法可重用性好

B

Python 3.x 解释器内部采用完全面向对象的方式实现

C

用面向对象方法开发的软件不容易理解

D

面向对象方法与人类习惯的思维方法一致

正确答案： C 

 

**6.** 在软件生命周期中，能准确地确定软件系统必须做什么和必须具备哪些功能的阶段是

A

需求设计

B

详细设计

C

可行性分析

D

概要设计

正确答案： A 

 

**7.** 以下选项中，用于检测软件产品是否符合需求定义的是

A

集成测试

B

验证测试

C

验收测试

D

确认测试

正确答案： C 

 

**8.** 在PFD图中用箭头表示

A

数据流

B

调用关系

C

组成关系

D

控制流

正确答案： D 

 

**9.** 关于软件调试方法，以下选项中描述错误的是

A

软件调试可以分为静态调试和动态调试

B

软件调试的主要方法有强行排错法、回溯法、原因排除法等

C

软件调试的目的是发现错误

D

软件调试的关键在于推断程序内部的错误位置及原因

正确答案： C 

 

**10.** 关于数据库设计，以下选项中描述错误的是

A

数据库设计可以采用生命周期法

B

数据库设计是数据库应用的核心

C

数据库设计的四个阶段按顺序为概念设计、需求分析、逻辑设计、物理设计

D

数据库设计的基本任务是根据用户对象的信息需求、处理需求和数据库的支持环境设计出数据模式

正确答案： C 

 

**11.** 以下选项中值为False的是

A

'abc' <'abcd'

B

' ' <'a'

C

'Hello' >'hello'

D

'abcd' <'ad'

正确答案： C 

 

**12.** Python语言中用来定义函数的关键字是

A

return

B

def

C

function

D

define

正确答案： B 

 

**13.** 以下选项中，对文件的描述错误的是

A

文件中可以包含任何数据内容

B

文本文件和二进制文件都是文件

C

文本文件不能用二进制文件方式读入

D

文件是一个存储在辅助存储器上的数据序列

正确答案： C 

 

**14.** ls = [3.5, "Python", [10, "LIST"], 3.6]，ls[2][ –1][1]的运行结果是

A

I

B

P

C

Y

D

L

正确答案： A 

 

**15.** 以下用于绘制弧形的函数是

A

turtle.seth()

B

turtle.right()

C

turtle.circle()

D

turtle.fd()

正确答案： C 

 

**16.** 对于turtle绘图中颜色值的表示，以下选项中错误的是

A

(190, 190, 190)

B

BEBEBE

C

\#BEBEBE

D

“grey”

正确答案： B 

 

**17.** 以下选项中不属于组合数据类型的是

A

变体类型

B

字典类型

C

映射类型

D

序列类型

正确答案： A 

 

**18.** 关于random库，以下选项中描述错误的是

A

设定相同种子，每次调用随机函数生成的随机数相同

B

通过from random import *可以引入random随机库

C

通过import random可以引入random随机库

D

生成随机数之前必须要指定随机数种子

正确答案： D 

 

**19.** 关于函数的可变参数，可变参数*args传入函数时存储的类型是

A

list

B

set

C

dict

D

tuple

正确答案： D 

 

**20.** 关于局部变量和全局变量，以下选项中描述错误的是

A

局部变量和全局变量是不同的变量，但可以使用global保留字在函数内部使用全局变量

B

局部变量是函数内部的占位符，与全局变量可能重名但不同

C

函数运算结束后，局部变量不会被释放

D

局部变量为组合数据类型且未创建，等同于全局变量

正确答案： C 

 

**21.**

下面代码的输出结果是

```
ls = ["F","f"]def fun(a):
```

```
    ls.append(a)
```

```
    return
```

```
fun("C")print(ls)
```

A

['F', 'f']

B

['C']

C

出错

D

['F', 'f', 'C']

正确答案： D 

 

**22.** 关于函数作用的描述，以下选项中错误的是

A

复用代码

B

增强代码的可读性

C

降低编程复杂度

D

提高代码执行速度

正确答案： D 

 

**23.** 假设函数中不包括global保留字，对于改变参数值的方法，以下选项中错误的是

A

参数是int类型时，不改变原参数的值

B

参数是组合类型（可变对象）时，改变原参数的值

C

参数的值是否改变与函数中对变量的操作有关，与参数类型无关

D

参数是list类型时，改变原参数的值

正确答案： C 

 

**24.** 关于形参和实参的描述，以下选项中正确的是

A

参数列表中给出要传入函数内部的参数，这类参数称为形式参数，简称形参

B

函数调用时，实参默认采用按照位置顺序的方式传递给函数，Python也提供了按照形参名称输入实参的方式

C

程序在调用时，将形参复制给函数的实参

D

函数定义中参数列表里面的参数是实际参数，简称实参

正确答案： B 

 

**25.** 以下选项中，正确地描述了浮点数0.0和整数0相同性的是

A

它们使用相同的计算机指令处理方法

B

它们具有相同的数据类型

C

它们具有相同的值

D

它们使用相同的硬件执行单元

正确答案： C 

 

**26.** 关于random.uniform(a,b)的作用描述，以下选项中正确的是

A

生成一个[a, b]之间的随机小数

B

生成一个均值为a，方差为b的正态分布

C

生成一个(a, b)之间的随机数

D

生成一个[a, b]之间的随机整数

正确答案： A 

 

**27.** 关于Python语句P = –P，以下选项中描述正确的是

A

P和P的负数相等

B

P和P的绝对值相等

C

给P赋值为它的负数

D

.P的值为0

正确答案： C 

 

**28.** 以下选项中，用于文本处理方向的第三方库是

A

pdfminer

B

TVTK

C

matplotlib

D

mayavi

正确答案： A 

 

**29.** 以下选项中，用于机器学习方向的第三方库是

A

jieba

B

SnowNLP

C

loso

D

TensorFlow

正确答案： D 

 

**30.** 以下选项中，用于Web开发方向的第三方库是

A

Panda3D

B

cocos2d

C

Django

D

Pygame

正确答案： C 

 

**31.**

下面代码的输出结果是

```
x = 0x0101print(x)
```

A

101

B

257

C

65

D

5

正确答案： B 

 

**32.**

下面代码的输出结果是

```
sum = 1.0for num in range(1,4):
```

```
sum+=numprint(sum)
```

A

6

B

7.0

C

1.0

D

7

正确答案： B 

 

**33.**

下面代码的输出结果是

```
a = 4.2e–1
```

```
b = 1.3e2print(a+b)
```

A

130.042

B

5.5e31

C

130.42

D

5.5e3

正确答案： C 

 

**34.**

下面代码的输出结果是

```
name = "Python语言程序设计"print(name[2: –2])
```

A

thon语言程序

B

thon语言程序设

C

ython语言程序

D

ython语言程序设

正确答案： A 

 

**35.**

下面代码的输出结果是

```
weekstr = "星期一星期二星期三星期四星期五星期六星期日"
```

```
weekid = 3print(weekstr[weekid*3: weekid*3+3])
```

A

星期二

B

星期三

C

星期四

D

星期一

正确答案： C 

 

**36.**

下面代码的输出结果是

```
a = [5,1,3,4]print(sorted(a,reverse = True))
```

A

[5, 1, 3, 4]

B

[5, 4, 3, 1]

C

[4, 3, 1, 5]

D

[1, 3, 4, 5]

正确答案： B 

 

**37.**

下面代码的输出结果是

```
for s in "abc":
```

```
   for i in range(3):
```

```
      print (s,end="")
```

```
      if s=="c":
```

```
          break
```

A

aaabccc

B

aaabbbc

C

abbbccc

D

aaabbbccc

正确答案： B 

 

**38.**

下面代码的输出结果是

```
for i in range(10):if i%2==0:
```

```
    continueelse:print(i, end=",")
```

A

2,4,6,8,

B

0,2,4,6,8,

C

0,2,4,6,8,10,

D

1,3,5,7,9,

正确答案： D 

 

**39.**

下面代码的输出结果是

```
ls = list(range(1,4))print(ls)
```

A

{0,1,2,3}

B

[1,2,3]

C

{1,2,3}

D

[0,1,2,3]

正确答案： B 

 

**40.**

下面代码的输出结果是

```
def change(a,b):
```

```
    a = 10
```

```
    b += a
```

```
a = 4
```

```
b = 5
```

```
change(a,b)print(a,b)
```

A

10 5

B

4 15

C

10 15

D

4 5

正确答案： D 

 

**1.** 算法的时间复杂度是指

A

执行算法程序所需要的时间

B

算法程序的长度

C

算法程序中的指令条数

D

算法执行过程中所需要的基本运算次数

正确答案： D 

 

**2.** 下列关于栈的叙述中正确的是

A

在栈中只能插入数据

B

在栈中只能删除数据

C

栈是先进先出的线性表

D

栈是先进后出的线性表

正确答案： D 

 

**3.** 对建立良好的程序设计风格，下面描述正确的是

A

符号名的命名只要符合语法

B

充分考虑程序的执行效率

C

程序的注释可有可无

D

程序应简单、清晰、可读性好

正确答案： D 

 

**4.** 在面向对象方法中，一个对象请求另一对象为其服务的方式是通过发送

A

调用语句

B

命令

C

口令

D

消息

正确答案： D 

 

**5.** 下面不属于软件设计原则的是

A

抽象

B

模块化

C

信息隐蔽

D

自底向上

正确答案： D 

 

**6.** 下面不属于软件工程的3个要素的是

A

工具

B

过程

C

方法

D

环境

正确答案： D 

 

**7.** 在软件开发中，需求分析阶段产生的主要文档是

A

用户手册

B

软件集成测试计划

C

软件详细设计说明书

D

软件需求规格说明书

正确答案： D 

 

**8.** 数据库应用系统中的核心问题是

A

数据库管理员培训

B

数据库维护

C

数据库系统设计

D

数据库设计

正确答案： D 

 

**9.** 在E-R图中，哪个选项是用来表示联系的图形

A

矩形

B

椭圆形

C

三角形

D

菱形

正确答案： D 

 

**10.** 以下选项错误描述的是

A

DDL 是数据定义语言

B

DML 是数据操纵语言

C

DCL 是数据控制语言

D

DBMS 是数据库系统

正确答案： D 

 

**11.** Python 语言中，以下表达式输出结果为11的选项是：

A

print("1+1")

B

print(1+1)

C

print(eval("1+1"))

D

print(eval("1" + "1"))

正确答案： D 

 

**12.** 以下 Python 语言关键字在异常处理结构中用来捕获特定类型异常的选项是：

A

for

B

lambda

C

in

D

expect

正确答案： D 

 

**13.**

函数表达式 all([1,True,True]) 的结果是：

A

无输出

B

False

C

出错

D

True

正确答案： D 

 

**14.**

运行以下程序，

 

```
x = eval(input())
```

```
 
```

```
y = eval(input())
```

```
print(abs(x+y))
```

从键盘输入1+2与4j，则输出结果是：

A

5

B

<class 'complex'>

C

<class 'float'> 

D

5.0              

正确答案： D 

 

**15.** 以下对数值运算操作符描述错误的选项是：

A

Python 提供了9个基本的数值运算操作符

B

Python 数值运算操作符也叫做内置操作符

C

Python 二元数学操作符都有与之对应的增强赋值操作符

D

Python 数值运算操作符需要引用第三方库 math

正确答案： D 

 

**16.** 以下关于列表和字符串的描述，错误的是：

A

列表使用正向递增序号和反向递减序号的索引体系

B

列表是一个可以修改数据项的序列类型

C

字符和列表均支持成员关系操作符（in）和长度计算函数（len()）

D

字符串是单一字符的无序组合

正确答案： D 

 

**17.** str ="Python语言程序设计"，表达式 str.isnumeric() 的结果是：

A

True

B

1

C

0

D

False

正确答案： D 

 

**18.**

以下程序的输出结果是：

```
>>> def f(x, y = 0, z = 0): pass
```

```
>>> f(1, , 3)
```

A

pass

B

None

C

not

D

出错

正确答案： D 

 

**19.**

运行以下程序：

```
try:
```

```
 
```

```
    num = eval(input("请输入一个列表:"))
```

```
 
```

```
    num.reverse()
```

```
 
```

```
    print(num)
```

```
except:
```

```
 
```

```
    print("输入的不是列表")
```

从键盘上输入1,2,3，则输出的结果是：

A

[1,2,3]

B

[3,2,1]

C

运算错误

D

输入的不是列表

正确答案： D 

 

**20.**

以下程序的输出结果是：

```
def fun1(a,b,*args):
```

```
 
```

```
    print(a)
```

```
 
```

```
    print(b)
```

```
 
```

```
    print(args)
```

```
 
```

```
fun1(1,2,3,4,5,6)
```

A

1

2

[3, 4, 5, 6]

B

1,2,3,4,5,6

C

1

2

3, 4, 5, 6

D

1

2

(3, 4, 5, 6)

正确答案： D 

 

**21.**

运行以下程序，当从键盘上输入{1:"清华大学",2:"北京大学"}，运行结果的是：

```
x =eval(input())
```

```
print(type(x))
```

A

<class 'int'>

B

<class 'list'>

C

出错

D

<class 'dict'>

正确答案： D 

 

**22.** 以下选项能改变 turtle 画笔的颜色是：

A

turtle.colormode()

B

turtle.setup()

C

turtle.pd()

D

turtle.pencolor()

正确答案： D 

 

**23.**

以下程序的不可能输出结果是：

```
from random import *
```

```
print(sample({1,2,3,4,5},2))
```

A

[5, 1]

B

[1, 2]

C

[4, 2]

D

[1, 2, 3]

正确答案： D 

 

**24.**

以下程序的输出结果是：

```
import time
```

```
 
```

```
t = time.gmtime()
```

```
print(time.strftime("%Y-%m-%d %H:%M:%S",t))
```

A

系统当前的日期

B

系统当前的时间

C

系统出错

D

系统当前的日期与时间

正确答案： D 

 

**25.**

函数表达式 all([1,True,True]) 的结果是：

A

无输出

B

False

C

出错

D

True

正确答案： D 

 

**26.** 以下关于 Python 函数对变量的作用，错误的是：

A

简单数据类型在函数内部用global保留字声明后，函数退出后该变量保留

B

全局变量指在函数之外定义的变量，在程序执行全过程有效

C

简单数据类型变量仅在函数内部创建和使用，函数退出后变量被释放

D

对于组合数据类型的全局变量，如果在函数内部没有被真实创建的同名变量，则函数内部不可以直接使用并修改全局变量的值

正确答案： D 

 

**27.**

以下程序的输出结果是：

```
ls = ["浣熊","豪猪","艾草松鸡","棉尾兔","叉角羚"]
```

```
 
```

```
x = "豪猪"
```

```
print(ls.index(x,0))
```

A

0

B

-4

C

-3

D

1

正确答案： D 

 

**28.** 以下属于 Python 脚本程序转变为可执行程序的第三方库的是：

A

openpyxl

B

PyPDF2

C

pillow

D

pyinstaller

正确答案： D 

 

**29.** 以下属于 Python 中文分词方向第三方库的是：

A

python-docx

B

python-pptx

C

pefile

D

jieba

正确答案： D 

 

**30.** 以下生成词云的 Python 第三方库的是：

A

csvkit

B

Pydub

C

moviepy

D

wordcloud

正确答案： D 

 

**31.** 假设将单词保存在变量 word 中，使用一个字典类型 counts={}，统计单词出现的次数可采用以下代码：

A

counts[word] = count[word] + 1

B

counts[word] = 1

C

counts[word] = count.get(word,1) + 1

D

counts[word] = count.get(word,0) + 1

正确答案： D 

 

**32.**

以下程序的输出结果是：

```
lcat =["狮子","猎豹","虎猫","花豹","孟加拉虎","美洲豹","雪豹"]
```

```
for s in lcat:
```

```
 
```

```
    if "豹" in s:
```

```
 
```

```
        print(s,end="")
```

```
 
```

```
        continue
```

A

猎豹

花豹

美洲豹

雪豹    

B

猎豹

C

雪豹

D

猎豹花豹美洲豹雪豹

正确答案： D 

 

**33.**

以下程序的输出结果是：

```
s1 ="袋鼠"
```

```
print("{0}生活在主要由母{0}和小{0}组成的较小的群体里。".format(s1))
```

A

TypeError: tuple index out of range

B

{0} 生活在主要由母 {0} 和小 {0} 组成的较小的群体里。

C

IndexError: tuple index out of range

D

袋鼠生活在主要由母袋鼠和小袋鼠组成的较小的群体里。

正确答案： D 

 

**34.**

以下程序的输出结果是：

 

```
s1 ="企鹅"
```

```
 
```

```
s2 ="超级游泳健将"
```

```
print("{0:^4}:{1:!<9}".format(s1,s2))
```

 

A

  企鹅:超级游泳健将!!!

B

企鹅  :超级游泳健将!!!

C

企鹅  :!超级游泳健将!!

D

企鹅 :超级游泳健将!!!

正确答案： D 

 

**35.**

以下程序的输出结果是：

```
for num in range(1,4):
```

```
 
```

```
    sum *= num
```

```
print(sum)
```

A

6

B

7

C

7.0

D

TypeError 出错       

正确答案： D 

 

**36.**

以下程序的输出结果是：

```
ls = ["石山羊","一角鲸","南极雪海燕","竖琴海豹","山蝰"]
```

```
 
```

```
ls.remove("山蝰")
```

```
 
```

```
str = ""
```

```
print("极地动物有",end="")
```

```
for s in ls:
```

```
 
```

```
    str = str + s + ","
```

```
print(str[:-1],end="。")
```

A

极地动物有石山羊,一角鲸,南极雪海燕,竖琴海豹,山蝰

B

极地动物有石山羊,一角鲸,南极雪海燕,竖琴海豹,山蝰。

C

极地动物有石山羊,一角鲸,南极雪海燕,竖琴海豹

D

极地动物有石山羊,一角鲸,南极雪海燕,竖琴海豹。

正确答案： D 

 

**37.**

以下程序的输出结果是：

 

```
for i in "Summer":
```

```
 
```

```
    if i == "m":
```

```
 
```

```
        break
```

```
 
```

```
        print(i)
```

A

m

B

mm

C

mmer

D

无输出

正确答案： D 

 

**38.** 以下关于字典的描述，错误的是：

A

字典中元素以键信息为索引访问

B

字典长度是可变的

C

字典是键值对的集合

D

字典中的键可以对应多个值信息

正确答案： D 

 

**39.** 以下文件操作方法中，打开后能读取 CSV 格式文件的选项是：

A

fo = open("123.csv","w")

B

fo = open("123.csv","x")

C

fo = open("123.csv","a")

D

fo = open("123.csv","r")

正确答案： D 

 

**40.**

以下程序的功能是：

```
s = "What\'s a package, project, or release?We use a number of terms to describe software available on PyPI, like project, release, file, and package. Sometimes those terms are confusing because they\'re used to describe different things in other contexts. Here's how we use them on PyPI:A project on PyPI is the name of a collection of releases and files, and information about them. Projects on PyPI are made and shared by other members of the Python community so that you can use them.A release on PyPI is a specific version of a project. For example, the requests project has many releases, like requests 2.10 and requests 1.2.1. A release consists of one or more files.A file, also known as a package, on PyPI is something that you can download and install. Because of different hardware, operating systems, and file formats, a release may have several files (packages), like an archive containing source code or a binary wheel."
```

```
 
```

```
s = s.lower()
```

```
for ch in '\',?.:()':
```

```
 
```

```
    s = s.replace(ch," ")
```

```
 
```

```
words = s.split()
```

```
 
```

```
counts = {}
```

```
for word in words:
```

```
 
```

```
    counts[word] = counts.get(word,0)+1
```

```
 
```

```
items = list(counts.items())
```

```
 
```

```
items.sort(key=lambda x:x[1],reverse = True)
```

```
 
```

```
fo = open("wordnum.txt","w",encoding ="utf-8")
```

```
for i in range(10):
```

```
 
```

```
    word,count = items[i]
```

```
 
```

```
    fo.writelines( word + ":" + str(count) + "\n")
```

```
 
```

```
fo.close()
```

 

A

统计字符串 s 中所有单词的出现次数，将单词和次数写入 wordnum.txt 文件

B

统计字符串 s 中所有字母的出现次数，将单词和次数写入wordnum.txt 文件

C

统计输出字符串 s 中前10个字母的出现次数，将单词和次数写入 wordnum.txt 文件

D

统计字符串 s 中前10个高频单词的出现次数，将单词和次数写入 wordnum.txt 文件

正确答案： D 

 

**1.** 在面向对象方法中，一个对象请求另一对象为其服务的方式是通过发送___________。

A

命令

B

口令

C

消息

D

调用语句

正确答案： C 

 

**2.** 下面不属于软件需求分析阶段主要工作的是___________。

A

需求评审

B

需求获取

C

需求变更申请

D

需求分析

正确答案： C 

 

**3.** 下面不属于软件测试实施步骤的是___________。

A

确认测试

B

单元测试

C

回归测试

D

集成测试

正确答案： C 

 

**4.** 结构化程序设计中，下面对goto语句使用描述正确的是___________。

A

禁止使用goto语句

B

应避免滥用goto语句

C

goto语句最好用,不容易造成结构体程序混乱。

D

使用goto语句程序效率高

正确答案： B 

 

**5.** 数据库应用系统中的核心问题是___________。

A

数据库管理员培训

B

数据库维护

C

数据库系统设计

D

数据库设计

正确答案： D 

 

**6.** 在E-R图中，用来表示实体联系的图形是___________。

A

三角形

B

菱形

C

椭圆形

D

矩形

正确答案： D 

 

**7.** 在数据库设计中，将E-R图转换为关系数据模型的过程属于

A

物理设计阶段

B

需求分析阶段

C

概念设计阶段

D

逻辑设计阶段

正确答案： D 

 

**8.** 一个栈的初始状态为空。现将元素 1、2、3、4、5、A、B、C、D、E依次入栈，然后再依次出栈，则元素出栈的顺序是

A

12345ABCDE

B

EDCBA54321

C

54321EDCBA

D

ABCDE12345

正确答案： B 

 

**9.** 下列排序方法中，最坏情况下比较次数最少的是

A

堆排序

B

直接插入排序

C

冒泡排序

D

简单选择排序

正确答案： A 

 

**10.** 支持子程序调用的数据结构是

A

队列

B

二叉树

C

树

D

栈

正确答案： D 

 

**11.**

\11. Python 中对变量描述错误的选项是：

A

Python 不需要显式声明变量类型，在第一次变量赋值时由值决定变量的类型

B

变量通过变量名访问

C

变量必须在创建和赋值后使用

D

变量 PI 与变量 Pi 被看作相同的变量

正确答案： D 

 

**12.**

以下 Python 语句运行结果异常的选项是：

A

```
>>> PI , r = 3.14 , 4
```

B

```
>>> a = 1
```

```
>>> b = a = a + 1
```

C

```
>>> x = True
```

```
>>> int(x)
```

D

```
>>> a
```

正确答案： D 

 

**13.**

以下对Python程序设计风格描述错误的选项是： 

A

Python中不允许把多条语句写在同一行

B

Python语句中，增加缩进表示语句块的开始，减少缩进表示语句块的退出

C

Python可以将一条长语句分成多行显示，使用续航符“\”

D

Python中不允许把多条语句写在同一行

正确答案： D 

 

**14.**

下列表达式的运算结果是： 

```
>>> a = 100 
```

```
>>> b = False
```

```
>>> a * b > -1
```

A

False

B

1

C

0

D

True 

正确答案： D 

 

**15.**

运行以下程序，输出结果的是：

```
str1 = "Nanjing University"
```

```
 
```

```
str2 = str1[:7] + " Normal " + str1[-10:]<o:p></o:p>
```

```
print(str2)
```

A

Normal U

B

Nanjing Normal     

C

Normal University

D

Nanjing Normal University

正确答案： D 

 

**16.**

运行以下程序，输出结果的是：

```
print(" love ".join(["Everyday","Yourself","Python",]))
```

A

Everyday love Yourself 

B

Everyday love Python

C

love Yourself love Python

D

Everyday love Yourself love Python     

正确答案： D 

 

**17.** 26. 哪个选项是使用 PyInstaller 库对 Python 源文件打包的基本使用方法？

A

pip -h

B

pip install <拟安装库名>

C

pip download <拟下载库名>

D

pyinstaller 需要在命令行运行 :\>pyinstaller <Python源程序文件名>

正确答案： D 

 

**18.**

以下程序的不可能输出结果是：

```
from random import *
```

```
print(round(random(),2))
```

A

0.47

B

0.54

C

0.27

D

1.87

正确答案： D 

 

**19.**

以下程序的输出结果是：

```
astr = '0\n'
```

```
 
```

```
bstr = 'A\ta\n'
```

```
print("{}{}".format(astr,bstr))
```

A

```
0
```

```
 
```

```
a   a
```

B

```
0
```

```
 
```

```
A   A
```

C

```
A   a
```

D

```
0
```

```
 
```

```
A   a
```

正确答案： D 

 

**20.** 以下关于异常处理的描述，正确的是：

A

try 语句中有 except 子句就不能有 finally 子句

B

Python 中，可以用异常处理捕获程序中的所有错误

C

引发一个不存在索引的列表元素会引发 NameError 错误

D

Python 中允许利用 raise 语句由程序主动引发异常

正确答案： D 

 

**21.**

以下语句执行后a、b、c的值是： 

```
a = "watermelon"
```

```
 
```

```
b = "strawberry"
```

```
 
```

```
c = "cherry"
```

```
if a > b:
```

```
 
```

```
    c = a
```

```
 
```

```
    a = b
```

```
 
```

```
    b = c
```

 

A

watermelon strawberry cherry

B

watermelon cherry strawberry

C

strawberry cherry watermelon

D

strawberry watermelon watermelon

正确答案： D 

 

**22.** 以下关于 Python 的控制结构，错误的是：

A

每个 if 条件后要使用冒号（：）

B

在 Python 中，没有 switch-case 语句

C

Python 中的 pass 是空语句，一般用作占位语句

D

elif 可以单独使用

正确答案： D 

 

**23.**

以下代码段，不会输出A，B，C，的选项是：

A

```
for i in range(3):
```

```
 
```

```
    print(chr(65+i),end=",")
```

B

```
for i in [0,1,2]:
```

```
 
```

```
    print(chr(65+i),end=",")
```

C

```
i = 0
```

```
while i < 3:
```

```
 
```

```
    print(chr(i+65),end= ",")
```

```
 
```

```
    i += 1
```

```
 
```

```
    continue
```

D

```
i = 0
```

```
while i < 3:
```

```
 
```

```
    print(chr(i+65),end= ",")
```

```
 
```

```
    break
```

```
 
```

```
    i += 1
```

正确答案： D 

 

**24.** 设 x = 10；y = 20，下列语句能正确运行结束的是：

A

max = x >y ? x : y

B

if(x>y) print(x)

C

while True: pass

D

min = x if x < y else y

正确答案： D 

 

**25.**

以下程序的输出结果是：

```
Da = {"北美洲":"北极兔","南美洲":"托哥巨嘴鸟","亚洲":"大熊猫","非洲":"单峰驼","南极洲":"帝企鹅"}
```

```
 
```

```
Da["非洲"] = "大猩猩"
```

```
print(Da)
```

A

('北美洲': '北极兔', '南美洲': '托哥巨嘴鸟', '亚洲': '大熊猫', '非洲': '大猩猩', '南极洲': '帝企鹅')    

B

['北美洲': '北极兔', '南美洲': '托哥巨嘴鸟', '亚洲': '大熊猫', '非洲': '大猩猩', '南极洲': '帝企鹅']   

C

{"北美洲":"北极兔","南美洲":"托哥巨嘴鸟","亚洲":"大熊猫","非洲":"单峰驼","南极洲":"帝企鹅"}

D

{'北美洲': '北极兔', '南美洲': '托哥巨嘴鸟', '亚洲': '大熊猫', '非洲': '大猩猩', '南极洲': '帝企鹅'}

正确答案： D 

 

**26.** 以下关于列表操作的描述，错误的是：

A

通过 append 方法可以向列表添加元素

B

通过 extend 方法可以将另一个列表中的元素逐一添加到列表中

C

通过 insert(index,object) 方法在指定位置 index 前插入元素 object

D

通过 add 方法可以向列表添加元素

正确答案： D 

 

**27.** 以下关于字典操作的描述，错误的是：

A

del 用于删除字典或者元素

B

clear 用于清空字典中的数据

C

len 方法可以计算字典中键值对的个数

D

keys 方法可以获取字典的值视图

正确答案： D 

 

**28.**

以下程序的输出结果是： 

```
L1 =['abc', ['123','456']]
```

```
 
```

```
L2 = ['1','2','3']
```

```
print(L1 > L2)
```

A

False

B

TypeError: '>' not supported between instances of 'list' and 'str'

C

1

D

True

正确答案： D 

 

**29.** 以下属于 Python 脚本程序转变为可执行程序的第三方库的是：

A

requests

B

scrapy

C

numpy

D

pyinstaller

正确答案： D 

 

**30.** 以下属于 Python 中文分词方向第三方库的是：

A

pandas

B

beautifulsoup4

C

python-docx

D

jieba

正确答案： D 

 

**31.** 以下生成词云的 Python 第三方库的是：

A

matplotib

B

TVTK

C

mayavi

D

wordcloud

正确答案： D 

 

**32.** Python 中函数不包括

A

标准函数

B

第三库函数

C

内建函数

D

参数函数

正确答案： D 

 

**33.** Python 中，函数定义可以不包括以下：

A

函数名

B

关键字 def

C

一对圆括号

D

可选参数列表

正确答案： D 

 

**34.**

以下程序的输出结果是：

```
def func(num):
```

```
    num *= 2
```

```
x = 20
```

```
func(x)print(x)
```

A

40

B

出错

C

无输出

D

20

正确答案： D 

 

**35.**

以下程序的输出结果是：

```
def func(a,*b):
```

```
    for item in b:
```

```
        a += item
```

```
    return a
```

```
m = 0print(func(m,1,1,2,3,5,7,12,21,33))
```

```
 
```

A

33

B

0

C

7

D

85

正确答案： D 

 

**36.**

下程序的输出结果是：

```
a = ["a","b","c"]
```

```
b = a[::-1]print(b)
```

A

['a', 'b', 'c']

B

'c', 'b', 'a'

C

'a', 'b', 'c'

D

['c', 'b', 'a']

正确答案： D 

 

**37.** Python 文件只读打开模式是

A

w

B

x

C

b

D

r

正确答案： D 

 

**38.** Python 文件读取方法 read(size) 的含义是

A

从头到尾读取文件所有内容

B

从文件中读取一行数据

C

从文件中读取多行数据

D

从文件中读取指定 size 大小的数据,如果 size 为负数或者空，则读取到文件结束。

正确答案： D 

 

**39.** 关于数据组织的维度描述正确的是

A

二维数据由对等关系的有序或无序数据构成

B

高维数据由关联关系数据构成

C

CSV 是一维数据

D

一维数据采用线性方式存储

正确答案： D 

 

**40.** 同时去掉字符串左边和右边空格的函数是：

A

center()

B

count()

C

fomat()

D

strip()

正确答案： D 

 

 

**1.** 数据库设计中反映用户对数据要求的模式是___________。

A

概念模式

B

内模式

C

设计模式

D

外模式

正确答案： D 

 

**2.** 一个工作人员可使用多台计算机，而一台计算机被多个人使用，则实体工作人员与实体计算机之间的联系是___________。

A

多对一

B

多对多

C

一对一

D

一对多

正确答案： B 

 

**3.** 软件生命周期是指___________。

A

软件的运行维护过程

B

软件从需求分析、设计、实现到测试完成的过程

C

软件产品从提出、实现、使用维护到停止使用退役的过程

D

软件的开发过程

正确答案： C 

 

**4.** 软件测试的目的是___________。

A

改正程序中的错误

B

发现并改正程序中的错误

C

评估软件可靠性

D

发现程序中的错误

正确答案： D 

 

**5.** 面向对象方法中，继承是指___________。

A

类之间共享属性和操作的机制

B

各对象之间的共同性质

C

一组对象所具有的相似性质

D

一个对象具有另一个对象的性质

正确答案： A 

 

**6.** 层次型、网状型和关系型数据库划分原则是___________。

A

数据之间的联系方式

B

文件的大小

C

记录长度

D

联系的复杂程度

正确答案： A 

 

**7.** 下列数据结构中，能够按照"先进后出"原则存取数据的是___________。

A

栈

B

二叉树

C

队列

D

循环队列

正确答案： A 

 

**8.** 下列数据结构中，属于非线性结构的是___________。

A

二叉树

B

带链栈

C

队列循环

D

带链队列

正确答案： A 

 

**9.** 下列叙述中正确的是___________。

A

有序线性表既可以采用顺序存储结构，也可以采用链式存储结构

B

队列是"先进后出"的线性表

C

队列是"先进后出"的线性表

D

循环队列是非线性结构

正确答案： A 

 

**10.** 下列选项中不属于结构化程序设计原则的是___________。

A

逐步求精

B

逐步求精

C

模块化

D

可封装

正确答案： D 

 

**11.** 以下选项不属于程序设计语言类别的是：

A

机器语言

B

汇编语言

C

高级语言

D

解释语言

正确答案： D 

 

**12.** s = "the sky is blue"，表达式 print(s[-4:], s[:-4]) 的结果是：

A

the sky is blue

B

blue is sky the

C

sky is blue the

D

blue the sky is

正确答案： D 

 

**13.** 以下关于程序控制结构描述错误的是：

A

分支结构包括单分支结构和二分支结构

B

二分支结构组合形成多分支结构

C

程序由三种基本结构组成

D

Python 里，能用分支结构写出循环的算法

正确答案： D 

 

**14.** 以下关于 python 内置函数的描述，错误的是：

A

hash() 返回一个可计算哈希的类型的数据的哈希值

B

type() 返回一个数据对应的类型

C

sorted() 对一个序列类型数据进行排序

D

id() 返回一个数据的一个编号，跟其在内存中的地址无关

正确答案： D 

 

**15.** 以下关于函数参数传递的描述，错误的是：

A

定义函数的时候，可选参数必须写在非可选参数的后面

B

函数的实参位置可变，需要形参定义和实参调用时都要给出名称

C

调用函数时，可变数量参数被当做元组类型传递到函数中

D

Python 支持可变数量的参数，实参用”*参数名”表示

正确答案： D 

 

**16.**

以下程序的输出结果是：

```
x = [90,87,93] 
```

```
y = ["zhang", "wang","zhao"] print(list(zip(y,x)))
```

A

('zhang', 90), ('wang', 87), ('zhao', 93)

B

[['zhang', 90], ['wang', 87], ['zhao', 93]]

C

['zhang', 90], ['wang', 87], ['zhao', 93]

D

[('zhang', 90), ('wang', 87), ('zhao', 93)]

正确答案： D 

 

**17.** 以下关于组合数据类型的描述，正确的是：

A

集合类型中的元素是有序的

B

序列类似和集合类型中的元素都是可以重复的

C

一个映射类型变量中的关键字可以是不同类型的数据

D

利用组合数据类型可以将多个数据用一个类型来表示和处理

正确答案： D 

 

**18.** 以下不是 Python 语言关键字的选项是：

A

return

B

def

C

in

D

define

正确答案： D 

 

**19.** 以下选项不属于 Python 整数类型的是：

A

二进制

B

十进制

C

八进制

D

十二进制

正确答案： D 

 

**20.** 以下对 Python 程序缩进格式描述错误的选项是：

A

不需要缩进的代码顶行写，前面不能留空白

B

缩进可以用 tab 键实现，也可以用多个空格实现

C

严格的缩进可以约束程序结构，可以多层缩进

D

缩进是用来格式美化 Python 程序的

正确答案： D 

 

**21.**

当键盘输入”3”的时候，以下程序的输出结果是：

```
r = input("请输入半径：")
```

```
 
```

```
ar = 3.1415 * r *r
```

```
print("{:.0f}".format(ar))
```

A

28

B

28.27

C

29

D

Type Error

正确答案： D 

 

**22.** 定义 x=2.6，表达式 int(x) 的结果是：

A

3

B

2.6

C

2.0

D

2

正确答案： D 

 

**23.**

以下程序的输出结果是：

```
s = "python\n编程\t很\t容易\t学"
```

```
print(len(s))
```

A

20

B

12

C

5

D

16

正确答案： D 

 

**24.** 以下关于循环结构的描述，错误的是：

A

遍历循环的循环次数由遍历结构中的元素个数来体现

B

非确定次数的循环的次数是根据条件判断来决定的

C

非确定次数的循环用 while 语句来实现，确定次数的循环用 for 语句来实现

D

遍历循环对循环的次数是不确定的

正确答案： D 

 

**25.**

以下程序的输出结果是： 

```
for i in reversed(range(10, 0, -2)): 
```

```
   print(i,end=" ")
```

A

0 2 4 6 8 10

B

12345678910

C

9 8 7 6 5 4 3 2 1 0

D

2 4 6 8 10

正确答案： D 

 

**26.**

以下程序的输出结果是：

```
for i in "the number changes":
```

```
 
```

```
    if i == 'n':
```

```
 
```

```
        break
```

```
 
```

```
    else:
```

```
 
```

```
        print( i, end= "")
```

A

the umber chages

B

thenumberchanges

C

theumberchages

D

the

正确答案： D 

 

**27.**

以下程序的输出结果是：

```
t = "Python"
```

```
print(t if t>="python" else "None")
```

A

Python

B

python

C

t

D

None

正确答案： D 

 

**28.**

以下程序的输出结果是：

fo = open("text.csv",'w')

x =[ [90,87,93],[87,90,89],[78,98,97]]

b = []

for a in x:

​    for aa in a:

​        b.append(str(aa))

fo. write(",".join(b))

fo.close()

A

[90,87,93,87,90,89,78,98,97]

B

90,87,93 87,90,89 78,98,97

C

[[90,87,93], [87,90,89], [78,98,97]]

D

90,87,93,87,90,89,78,98,97

正确答案： D 

 

**29.**

以下程序的输出结果是：

```
for i in range(3):
```

```
 
```

```
    for s in "abcd":
```

```
 
```

```
        if s=="c":
```

```
 
```

```
             break
```

```
 
```

```
        print (s,end="")
```

A

abcabcabc

B

aaabbbccc

C

aaabbb

D

ababab

正确答案： D 

 

**30.**

以下程序的输出结果是：

```
ab = 4
```

```
def myab(ab, xy):
```

```
 
```

```
    ab= pow(ab,xy)
```

```
 
```

```
    print(ab,end=" ")
```

```
 
```

```
myab(ab,2)
```

```
print( ab)
```

A

4 4

B

16 16

C

4 16

D

16 4

正确答案： D 

 

**31.** 以下关于字典类型的描述，错误的是：

A

字典类型是一种无序的对象集合，通过键来存取

B

字典类型可以在原来的变量上增加或缩短

C

字典类型可以包含列表和其他数据类型，支持嵌套的字典

D

字典类型中的数据可以进行分片和合并操作

正确答案： D 

 

**32.**

以下程序的输出结果是：

```
ls =list("the sky is blue")
```

```
 
```

```
a = ls.index('s',5,10)
```

```
print(a)
```

A

4

B

5

C

10

D

9

正确答案： D 

 

**33.**

以下程序的输出结果是： 

```
L2 = [1,2,3,4] 
```

```
L3 = L2.reverse() print( L3)
```

A

[4, 3, 2, 1]

B

[3, 2, 1]

C

[1,2,3,]

D

None

正确答案： D 

 

**34.** 以下属于Python图像处理第三方库的是：

A

mayavi

B

TVTK

C

pygame

D

PIL

正确答案： D 

 

**35.** 以下关于 Python 文件的描述，错误的是：

A

open 函数的参数处理模式 ’ b ’ 表示以二进制数据处理文件

B

open 函数的参数处理模式 ’ + ’ 表示可以对文件进行读和写操作

C

readline 函数表示读取文件的下一行，返回一个字符串

D

open 函数的参数处理模式 ’ a ’ 表示追加方式打开文件，删除已有内容

正确答案： D 

 

**36.**

以下程序的输出结果是：

```
d = {"zhang":"China", "Jone":"America", "Natan":"Japan"}
```

```
for k in d:
```

```
 
```

```
    print(k, end="")
```

A

ChinaAmericaJapan

B

zhang:China Jone:America Natan:Japan

C

“zhang””Jone””Natan”

D

zhangJoneNatan

正确答案： D 

 

**37.**

以下程序的输出结果是：

```
fr = []
```

```
def myf(frame):
```

```
 
```

```
    fa = ['12','23']
```

```
 
```

```
    fr = fa
```

```
 
```

```
myf(fr)
```

```
print( fr)
```

A

['12', '23']

B

'12', '23'

C

12 23

D

[]

正确答案： D 

 

**38.** 以下属于 Python 机器学习第三方库的是：

A

jieba

B

SnowNLP

C

loso

D

sklearn

正确答案： D 

 

**39.** 以下属于 Python Web 开发框架第三方库的是：

A

Panda3D

B

cocos2d

C

Pygame

D

Flask

正确答案： D 

 

**40.** 以下关于 random 库的描述，正确的是：

A

设定相同种子，每次调用随机函数生成的随机数不相同

B

通过 from random import * 引入 random 随机库的部分函数

C

uniform(0,1) 与 uniform(0.0,1.0) 的输出结果不同，前者输出随机整数，后者输出随机小数

D

randint(a,b) 是生成一个 [a,b] 之间的整数

正确答案： D 

 

 

 

**1.** 下面不属于软件工程的3个要素的是___________。

A

过程

B

方法

C

环境

D

工具

正确答案： C 

 

**2.** 下面不属于软件设计原则的是___________。

A

模块化

B

自底向上

C

信息隐蔽

D

抽象

正确答案： B 

 

**3.** 在关系数据库中，用来表示实体之间联系的是___________。

A

网结构

B

二维表

C

线性表

D

树结构

正确答案： B 

 

**4.** 一般情况下，当对关系R和S进行自然连接时，要求R和S含有一个或者多个共有的___________。

A

属性

B

元组

C

记录

D

行

正确答案： A 

 

**5.** 有表示公司和职员及工作的三张表，职员可在多家公司兼职。其中公司c（公司号，公司名，地址，注册资本，法人代表，员工数），职员s（职员号，姓名，性别，年龄，学历），工作w（公司号，职员号，工资），则表w的键（码）为___________。

A

公司号，职员号，工资

B

职员号

C

职员号，工资

D

公司号，职员号

正确答案： D 

 

**6.** 下列叙述中正确的是___________。

A

栈是一种先进先出的线性表

B

栈与队列都是非线性结构

C

队列是一种后进先出的线性表

D

栈与队列都是线性结构

正确答案： D 

 

**7.** 下列叙述中正确的是___________。

A

线性表的链式存储结构所需要的存储空间一般要少于顺序存储结构

B

线性表的链式存储结构所需要的存储空间一般要多于顺序存储结构

C

线性表的链式存储结构与顺序存储结构所需要的存储方式是相同的

D

线性表的链式存储结构与顺序存储结构所需要的存储空间是相同的

正确答案： B 

 

**8.** 算法的有穷性是指___________。

A

算法只能被有限的用户使用

B

算法程序所处理的数据量是有限的

C

算法程序的运行时间是有限的

D

算法程序的长度是有限的

正确答案： C 

 

**9.** 软件设计中划分模块的一个准则是___________。

A

高内聚高耦合

B

低内聚高耦合

C

高内聚低耦合

D

低内聚低耦合

正确答案： C 

 

**10.** 耦合性和内聚性是对模块独立性度量的两个标准。下面叙述中正确的是

A

降低耦合性提高内聚性有利于提高模块的独立性

B

耦合性是指一个模块内部个元素间彼此结合的紧密程度

C

提高耦合性降低内聚性有利于提高模块的独立性

D

内聚性是模块间相互连接的紧密程度

正确答案： A 

 

**11.** 每个程序都具有的统一的运算模式是：

A

顺序计算模式

B

输入输出模式

C

函数调用模式

D

IPO 模式

正确答案： D 

 

**12.** 以下不是 Python 语言关键字的选项是：

A

None

B

as

C

raise

D

function

正确答案： D 

 

**13.**

以下关于同步赋值语句描述错误的选项是：

A

同步赋值能够使得赋值过程变得更简洁

B

判断多个单一赋值语句是否相关的方法是看其功能上是否相关或相同

C

设 x，y 表示一个点的坐标，则 x=a;y=b 两条语句可以用 x，y = a，b 一条语句来赋值

D

多个无关的单一赋值语句组合成同步赋值语句，会提高程序可读性

正确答案： D 

 

**14.**

以下代码的输出结果是：

```
 print('{:*^10.4}'.format('Flower'))
```

A

Flow

B

Flower

C

Flow

D

***Flow***

正确答案： D 

 

**15.**

表达式

```
print(float(complex(10+5j).imag))
```

的结果是：

A

10

B

5

C

10.0

D

5.0

正确答案： D 

 

**16.**

表达式

```
print("{:.2f}".format(20-2**3+10/3**2*5))
```

的结果是：

A

17.55

B

67.56

C

12.22

D

17.56

正确答案： D 

 

**17.** 如果 p=ord(‘a’)， 表达式 print(p,chr((p+3)%26+ord('a'))) 的结果是：

A

97 d

B

97 c

C

97 x

D

97 w

正确答案： D 

 

**18.**

以下程序的输出结果是：

```
chs = "|'\'-'|"
```

```
for i in range(6):
```

```
 
```

```
    for ch in chs[i]:
```

```
 
```

```
        print(ch,end='')
```

A

|'\'-'

B

|\-|

C

"|'-'|"

D

|''-'|

正确答案： D 

 

**19.** 以下关于随机运算函数库的描述，错误的是：

A

random 库里提供的不同类型的随机数函数是基于 random.random() 函数扩展的

B

伪随机数是计算机按一定算法产生的，可预见的数，所以是“伪”随机数

C

Python 内置的 random 库主要用于产生各种伪随机数序列

D

uniform(a,b) 产生一个 a 到 b 之间的随机整数

正确答案： D 

 

**20.**

以下关于分支和循环结构的描述，错误的是：

A

python 的在分支和循环语句里使用例如 x<=y<=z 的表达式是合法的

B

分支结构的中的代码块是用冒号来标记的

C

while 循环如果设计不小心会出现死循环

D

二分支结构的 <表达式1> if <条件> else <表达式2> 形式，适合用来控制程序分支

正确答案： D 

 

**21.**

以下程序的输出结果是：

```
for i in "CHINA":
```

```
 
```

```
    for k in range(2):
```

```
 
```

```
        print(i, end="")
```

```
 
```

```
        if i == 'N':
```

```
 
```

```
            break
```

A

CCHHIINNAA

B

CCHHIIAA

C

CCHHIAA

D

CCHHIINAA

正确答案： D 

 

**22.**

以下程序的输出结果是：

x= 10

while x:

​    x -= 1

​    if not x%2:

​        print(x,end = '')

else:

​    print(x)

A

86420

B

975311

C

97531

D

864200

正确答案： D 

 

**23.** 用户输入整数的时候不合规导致程序出错，为了不让程序异常中断，需要用到的语句是：

A

if 语句

B

eval 语句

C

循环语句

D

try-except 语句

正确答案： D 

 

**24.** 以下关于 python 内置函数的描述，错误的是：

A

id() 返回一个变量的一个编号，是其在内存中的地址

B

all(ls) 返回 True，如果 ls 的每个元素都是 True

C

type() 返回一个对象的类型

D

sorted() 对一个序列类型数据进行排序，将排序后的结果写回到该变量中

正确答案： D 

 

**25.** 以下关于函数的描述，正确的是：

A

函数的全局变量是列表类型的时候，函数内部不可以直接引用该全局变量

B

如果函数内部定义了跟外部的全局变量同名的组合数据类型的变量，则函数内部引用的变量不确定

C

python 的函数里引用一个组合数据类型变量，就会创建一个该类型对象

D

函数的简单数据类型全局变量在函数内部使用的时候，需要在显式声明为全局变量

正确答案： D 

 

**26.**

以下程序的输出结果是：

s1 ="QQ"

s2 ="Wechat"

print("{:*<10}{:=>10}".format(s1,s2))

A

********QQWechat====

B

QQWechat

C

********QQ Wechat====

D

QQ********====Wechat

正确答案： D 

 

**27.**

关于以下程序输出的两个值的描述正确的是：

```
da = [1,2,3]
```

```
print(id(da))
```

```
def getda(st):
```

```
 
```

```
    fa = da.copy()
```

```
 
```

```
    print(id(fa))
```

```
 
```

```
getda(da)
```

A

两个值相等

B

每次执行的结果不确定

C

首次不相等

D

两个值不相等

正确答案： D 

 

**28.** 以下不是组合数据类型的是：

A

集合类型

B

序列类型

C

映射类型

D

引用类型

正确答案： D 

 

**29.** 以下关于组合类型的描述，错误的是：

A

可以用大括号创建字典，用中括号增加新元素

B

嵌套的字典数据类型可以用来表达高维数据

C

字典的 pop 函数可以返回一个键对应的值，并删除该键值对

D

空字典和空集合都可以用大括号来创建

正确答案： D 

 

**30.**

以下程序的输出结果是：

```
x = ['90','87','90']
```

```
 
```

```
n = 90
```

```
print(x.count(n))
```

A

1

B

2

C

None

D

0

正确答案： D 

 

**31.**

以下程序的输出结果是：

```
dict = {'Name': 'baby', 'Age': 7}
```

```
print(dict.items())
```

A

[('Age', 7), ('Name', 'baby')]

B

('Age', 7), ('Name', 'baby')

C

'Age':7, 'Name': 'baby'

D

dict_items([('Age', 7), ('Name', 'baby')])

正确答案： D 

 

**32.**

以下程序的输出结果是：

```
dat=['1', '2', '3', '0', '0', '0']
```

```
for item in dat:
```

```
 
```

```
    if item == '0':
```

```
 
```

```
        dat.remove(item)
```

```
print(dat)
```

 

 

A

['1', '2', '3']

B

['1', '2', '3', '0', '0']

C

['1', '2', '3', '0', '0', '0']

D

['1', '2', '3', '0']

正确答案： D 

 

**33.**

以下程序的输出结果是：

```
L2 = [[1,2,3,4],[5,6,7,8]]
```

```
 
```

```
L2.sort(reverse = True)
```

```
print( L2)
```

A

[5, 6, 7, 8], [1, 2, 3, 4]

B

[[8,7,6,5], [4,3,2,1]]

C

[8,7,6,5], [4,3,2,1]

D

[[5, 6, 7, 8], [1, 2, 3, 4]]

正确答案： D 

 

**34.** 关于数据维度的描述，错误的是：

A

一维数据采用线性方式组织，对应于数组概念

B

二维数据有关联关系构成，采用表格方式组织

C

高维数据由键值对类型的数据组成，采用对象方式组织

D

一维数据是由对等关系的有序数据构成，无序数据不是一维数据

正确答案： D 

 

**35.**

以下程序的输出结果是：

```
fo = open("text.txt",'w+')
```

```
 
```

```
x,y ='this is a test','hello'
```

```
 
```

```
fo.write('{}+{}\n'.format(x,y))
```

```
print(fo.read())
```

```
 
```

```
fo.close()
```

A

this is a test hello

B

this is a test

C

this is a test,hello.

D

this is a test+hello

正确答案： D 

 

**36.**

文件dat.txt里的内容如下：

QQ&Wechat

Google & Baidu

以下程序的输出结果是：

```
fo = open("tet.txt",'r')
```

```
 
```

```
fo.seek(2)
```

```
print(fo.read(8))
```

```
 
```

```
fo.close()
```

```
 
```

A

Wechat

B

&Wechat G

C

Wechat Go

D

&Wechat

正确答案： D 

 

**37.** 以下属于 Python HTML 和 XML 解析的第三方库的是：

A

Django

B

Networkx

C

Requests

D

Beautiful Soup

正确答案： D 

 

**38.** 以下属于 Python 打包源文件为可执行文件的第三方库的是：

A

PIL

B

Matplotlib

C

Sklearn

D

Pyinstaller

正确答案： D 

 

**39.** 以下属于 Python Web 开发框架第三方库的是：

A

WeRoBot

B

Wheel

C

Pygame

D

Django

正确答案： D 

 

**40.** 以下关于 Python 内置库、标准库和第三方库的描述，正确的是：

A

第三方库需要单独安装才能使用

B

内置库里的函数不需要 import 就可以调用

C

第三方库有三种安装方式，最常用的是 pip 工具

D

标准库跟第三方库发布方法不一样，是跟 python 安装包一起发布的

正确答案： D 

 

 

**1.** 数据库系统的核心是___________。

A

数据库管理系统

B

数据模型

C

软件工具

D

数据库

正确答案： A 

 

**2.** 下列叙述中正确的是___________。

A

线性表链式存储结构的存储空间可以是连续的，也可以是不连续的

B

线性表链式存储结构与顺序存储结构的存储空间都是连续的

C

线性表链式存储结构的存储空间必须是连续的

D

线性表链式存储结构的存储空间一般要少于顺序存储结构

正确答案： A 

 

**3.** 某二叉树共有12个结点，其中叶子结点只有1个。则该二叉树的深度为（根结点在第1层）___________。

A

8

B

12

C

6

D

3

正确答案： B 

 

**4.** 下列叙述正确的是___________。

A

算法的时间复杂度与空间复杂度一定相关

B

数据的逻辑结构与存储结构是一一对应的

C

算法的时间复杂度是指执行算法所需要的计算工作量

D

算法的效率只与问题的规模有关，而与数据的存储结构无关

正确答案： C 

 

**5.** 对长度为n的线性表作快速排序，在最坏情况下，比较次数为___________。

A

n(n-1)/2

B

n(n-1)

C

n-1

D

n

正确答案： A 

 

**6.** 在软件开发中，需求分析阶段产生的主要文档是___________。

A

软件需求规格说明书

B

软件集成测试计划

C

软件详细设计说明书

D

用户手册

正确答案： A 

 

**7.** 下列选项中不属于结构化程序设计原则的是___________。

A

逐步求精

B

逐步求精

C

模块化

D

可封装

正确答案： D 

 

**8.** 设有表示学生选课的三张表，学生S（学号，姓名，性别，年龄，身份证号），课程C（课号，课名），选课SC（学号，课号，成绩），则表SC的关键字（键或码）为

A

学号，课号

B

学号，成绩

C

课号，成绩

D

学号，姓名，成绩

正确答案： A 

 

**9.** 下面叙述错误的是

A

程序调试通常也称为Debug

B

对被调试的程序进行"错误定位"是程序调试的必要步骤

C

软件测试应严格执行测试计划，排除测试的随意性

D

软件测试的目的是发现错误并改正错误

正确答案： D 

 

**10.** 软件按功能可以分为应用软件、系统软件和支撑软件（或工具软件）。下面属于应用软件的是

A

编译程序

B

操作系统

C

教务管理系统

D

汇编程序

正确答案： C 

 

**11.** 以下选项不属于 Python 语言特点的是：

A

支持中文

B

平台无关

C

语法简洁

D

执行高效

正确答案： D 

 

**12.** 如果 Python 程序执行时，产生了 “unexpected indent” 的错误，其原因是：

A

代码中使用了错误的关键字

B

代码中缺少“：”符号

C

代码里的语句嵌套层次太多

D

代码中出现了缩进不匹配的问题

正确答案： D 

 

**13.** 以下关于 Python 程序语法元素的描述，错误的选项是：

A

段落格式有助于提高代码可读性和可维护性

B

虽然 Python 支持中文变量名，但从兼容性角度考虑还是不要用中文名

C

true 并不是 Python 的保留字

D

并不是所有的 if、while、def、class 语句后面都要用 ‘：’ 结尾

正确答案： D 

 

**14.** s = " Python", 能够显示输出 Python 的选项是：

A

print(s[0:-1])

B

print(s[-1:0])

C

print(s[:6])

D

print(s[:])

正确答案： D 

 

**15.** 15. 表达式 'y'<'x' == False 的结果是：

A

True

B

Error

C

None

D

False

正确答案： D 

 

**16.** 以下表达式是十六进制整数的选项是：

A

0b16

B

‘0x61’

C

1010

D

0x3F

正确答案： D 

 

**17.**

字符串 s = "I love Python"，以下程序的输出结果是：

s = "I love Python"

ls = s.split()

ls.reverse()

print(ls)

A

'Python', 'love', 'I'

B

Python love I

C

None

D

['Python', 'love', 'I']

正确答案： D 

 

**18.**

以下程序的输出结果是：

```
s=''
```

```
 
```

```
ls = [1,2,3,4]
```

```
for l in ls:   
```

```
 
```

```
    s += str(l)
```

```
print(s)
```

A

1,2,3,4

B

4321

C

4,3,2,1

D

1234

正确答案： D 

 

**19.** 以下关于程序控制结构描述错误的是：

A

单分支结构是用if保留字判断满足一个条件，就执行相应的处理代码

B

二分支结构是用if-else根据条件的真假，执行两种处理代码

C

多分支结构是用if-elif-else处理多种可能的情况

D

在Python的程序流程图中可以用处理框表示计算的输出结果

正确答案： D 

 

**20.**

ls = [1,2,3,4,5,6], 以下关于循环结构的描述，错误的是：

A

表达式 for i in range(len(ls))  的循环次数跟 for i in ls 的循环次数是一样的

B

表达式 for i in range(len(ls)) 的循环次数跟 for i in range(0,len(ls)) 的循环次数是一样的

C

表达式 for i in range(len(ls)) 的循环次数跟 for i in range(1,len(ls)+1) 的循环次数是一样的

D

表达式 for i in range(len(ls))  跟  for i in ls 的循环中，i 的值是一样的

正确答案： D 

 

**21.**

以下程序的输出结果是：

```
j = ''
```

```
for i in "12345":
```

```
 
```

```
    j += i + ','
```

```
print(j)
```

A

1,2,3,4,5

B

12345

C

‘1,2,3,4,5,’

D

1,2,3,4,5,

正确答案： D 

 

**22.**

以下程序的输出结果是：

```
a = 30
```

```
 
```

```
b = 1
```

```
if a >=10:
```

```
 
```

```
    a = 20
```

```
elif a>=20:
```

```
 
```

```
    a = 30
```

```
elif a>=30:
```

```
 
```

```
    b = a
```

```
else:
```

```
 
```

```
    b = 0
```

```
print('a={}, b={}'.format(a,b))
```

A

a=30, b=1

B

a=30, b=30

C

a=20, b=20

D

a=20, b=1

正确答案： D 

 

**23.**

以下程序的输出结果是：

```
s=''
```

```
try:
```

```
 
```

```
    for i in range(1, 10, 2):
```

```
 
```

```
        s.append(i)
```

```
except:
```

```
 
```

```
    print('error')
```

```
print(s)
```

A

1 3 5 7 9

B

[1, 3, 5, 7, 9]

C

2, 4, 6, 8, 10

D

error

正确答案： D 

 

**24.** 以下关于 python 函数使用的描述，错误的是：

A

函数定义是使用函数的第一步

B

函数被调用后才能执行

C

函数执行结束后，程序执行流程会自动返回到函数被调用的语句之后

D

Python 程序里一定要有一个主函数

正确答案： D 

 

**25.** 以下关于函数参数和返回值的描述，正确的是：

A

采用名称传参的时候，实参的顺序需要和形参的顺序一致

B

可选参数传递指的是没有传入对应参数值的时候，就不使用该参数

C

函数能同时返回多个参数值，需要形成一个列表来返回

D

Python支持按照位置传参也支持名称传参，但不支持地址传参

正确答案： D 

 

**26.**

以下程序的输出结果是：

```
def calu(x = 3, y = 2, z = 10):
```

```
 
```

```
    return(x ** y * z)
```

```
 
```

```
h = 2
```

```
 
```

```
w = 3
```

```
print(calu(h,w))
```

A

90

B

70

C

60

D

80

正确答案： D 

 

**27.**

以下程序的输出结果是：

```
img1 = [12,34,56,78]
```

```
 
```

```
img2 = [1,2,3,4,5]
```

```
def displ():
```

```
 
```

```
    print(img1)
```

```
def modi():
```

```
 
```

```
    img1 = img2
```

```
 
```

```
modi()
```

```
 
```

```
displ()
```

A

[1,2,3,4,5]

B

([12, 34, 56, 78])

C

( [1,2,3,4,5])

D

[12, 34, 56, 78]

正确答案： D 

 

**28.**

以下关于组合数据类型的描述，错误的是：

A

集合类型是一种具体的数据类型

B

序列类似和映射类型都是一类数据类型的总称

C

 python 的集合类型跟数学中的集合概念一致，都是多个数据项的无序组合

D

字典类型的键可以用的数据类型包括字符串，元组，以及列表

正确答案： D 

 

**29.** 以下关于字典类型的描述，正确的是：

A

字典类型可迭代，即字典的值还可以是字典类型的对象

B

表达式 for x in d: 中，假设d是字典，则x是字典中的键值对

C

字典类型的键可以是列表和其他数据类型

D

字典类型的值可以是任意数据类型的对象

正确答案： D 

 

**30.**

以下程序的输出结果是：

```
ls1 = [1,2,3,4,5]
```

```
 
```

```
ls2 = [3,4,5,6,7,8]
```

```
 
```

```
cha1 = []
```

```
for i in ls2:
```

```
 
```

```
    if i not in ls1:
```

```
 
```

```
        cha1.append(i)
```

```
print(cha1)
```

 

A

(6, 7, 8)

B

(1,2,6, 7, 8)

C

[1,2,6,7,8]

D

[6, 7, 8]

正确答案： D 

 

**31.**

以下程序的输出结果是：

```
d = {"zhang":"China", "Jone":"America", "Natan":"Japan"} print(max(d),min(d))
```

A

Japan America

B

zhang:China Jone:America

C

China America

D

zhang Jone

正确答案： D 

 

**32.**

以下程序的输出结果是：

```
frame = [[1,2,3],[4,5,6],[7,8,9]]
```

```
 
```

```
rgb = frame[::-1]
```

```
print(rgb)
```

A

[[1, 2, 3], [4, 5, 6]]

B

[[7, 8, 9]]

C

[[1,2,3],[4,5,6],[7,8,9]]

D

[[7, 8, 9], [4, 5, 6], [1, 2, 3]]

正确答案： D 

 

**33.**

已知以下程序段，要想输出结果为 1,2,3，应该使用的表达式是：

```
x = [1,2,3]
```

```
 
```

```
z = []
```

```
for y in x:
```

```
 
```

```
    z.append(str(y))
```

A

print(z)

B

print(",".join(x))

C

print(x)

D

print(",".join(z))

正确答案： D 

 

**34.**

以下程序输出到文件 text.csv 里的结果是：

```
fo = open("text.csv",'w')
```

```
 
```

```
x = [90,87,93]
```

```
 
```

```
fo. write(",".join(str(x)))
```

```
 
```

```
fo.close()
```

A

[90,87,93]

B

90,87,93

C

,9,0,,, ,8,7,,, ,9,3,

D

[,9,0,,, ,8,7,,, ,9,3,]

正确答案： D 

 

**35.** 以下属于 Python 的 HTML 和 XML 第三方库的是：

A

mayavi

B

TVTK

C

pygame

D

Beautiful Soup

正确答案： D 

 

**36.** 用于安装 Python 第三方库的工具是：

A

jieba

B

yum

C

loso

D

pip

正确答案： D 

 

**37.** 用于将 Python 程序打包成可执行文件的工具是：

A

Panda3D

B

cocos2d

C

pip

D

PyInstaller

正确答案： D 

 

**38.**

以下程序不可能的输出结果是：

```
from random import *
```

```
 
```

```
x = [30,45,50,90]
```

```
print(choice(x))
```

A

30

B

45

C

90

D

55

正确答案： D 

 

**39.** 有一个文件记录了 1000 个人的高考成绩总分，每一行信息长度是 20 个字节，要想只读取最后 10 行的内容，不可能用到的函数是：

A

seek()

B

readline()

C

open()

D

read()

正确答案： D 

 

**40.** 以下关于文件的描述错误的选项是：

A

readlines() 函数读入文件内容后返回一个列表，元素划分依据是文本文件中的换行符

B

read() 一次性读入文本文件的全部内容后，返回一个字符串

C

readline() 函数读入文本文件的一行，返回一个字符串

D

二进制文件和文本文件都是可以用文本编辑器编辑的文件

正确答案： D 

 

 

 

**1.** 以下选项对于import保留字描述错误的是

A

import可以用于导入函数库或者库中的函数

B

可以使用from jieba import lcut 引入 jieba库

C

使用import jieba as jb，引入函数库jieba，取别名jb

D

使用import jieba 引入jieba库

 正确答案： B 

 

**2.** 以下选项中不可用作Python标识符的是

A

3.14

B

姓名

C

__Name__

D

Pi

正确答案： A 

 

**3.** Python可以将一条长语句分成多行显示的续行符号是：

A

\

B

\#

C

;

D

‘

正确答案： A 

 

**4.** 关于Python语言的特点，以下选项描述正确的是

A

Python语言不支持面向对象

B

Python语言是解释型语言

C

Python语言是编译型语言

D

Python语言是非跨平台语言

正确答案： B 

 

**5.**

关于Python整数类型，以下选项描述正确的是：

A

3.14不是整数类型的数值

B

type(100)表达式结果可能是<class 'int'>，也可能是<class 'float'>

C

oct(100)表达式结果获得十六进制数

D

hex(100)表达式结果获得八进制数

正确答案： A 

 

**6.**

运行以下程序，输出结果的是： 

A

3

B

2

C

2.5

D

2.50

正确答案： C 

 

**7.**

\17. 运行以下程序，输出的Python数据类型是：

A

字符串类型

B

浮点数类型

C

整数类型

D

复数类型

正确答案： B 

 

**8.**

下面代码的输出结果是： 

A

3.14159

B

3.141593

C

Pi=3.14

D

3.1416

正确答案： A 

 

**9.** 以下关于异常处理的描述，错误的选项是：

A

Python通过try、except等保留字提供异常处理功能

B

ZeroDivisionError是一个变量未命名错误

C

NameError是一种异常类型

D

异常语句可以与else和finally语句配合使用

正确答案： B 

 

**10.** for或者while与else搭配使用时，关于执行else语句块描述正确的是

A

仅循环非正常结束后执行（以break结束）

B

仅循环正常结束后执行

C

总会执行

D

永不执行

正确答案： B 

 

**11.**

以下代码执行的输出结果是：

A

B

C

D

出错

正确答案： B 

 

**12.** 以下关于TensorFlow库的应用领域的描述，正确的选项是

A

机器学习

B

数据可视化

C

Web开发

D

文本分析

正确答案： A 

 

**13.** 以下不属于Python深度学习第三方库的选项是：

A

Arcade

B

TensorFlow

C

Caffe2

D

MXNet

正确答案： A 

 

**14.** 以下属于Python文本处理第三方库的选项是：

A

matplotib

B

openpyxl

C

wxpython

D

vispy

正确答案： B 

 

**15.** random库的seed(a)函数的作用是

A

生成一个[0.0, 1.0)之间的随机小数

B

生成一个k比特长度的随机整数

C

设置初始化随机数种子a

D

生成一个随机整数

正确答案： C 

 

**16.**

下面代码的输出结果是

A

407

B

408

C

153

D

159

正确答案： A 

 

**17.**

给出下面代码：

代码执行时，从键盘获得Python语言,是,脚本,语言

则代码的输出结果是

A

执行代码出错

B

Python语言,是,脚本,语言

C

Python语言是脚本语言

D

无输出

正确答案： C 

 

**18.** 关于函数的描述，错误的选项是

A

Python使用del保留字定义一个函数

B

函数能完成特定的功能，对函数的使用不需要了解函数内部实现原理，只要了解函数的输入输出方式即可。

C

函数是一段具有特定功能的、可重用的语句组

D

使用函数的主要目的是减低编程难度和代码重用

正确答案： A 

 

**19.**

执行以下代码，运行错误的是：

A

fun(1,2,3)

B

fun(1,,3)

C

fun(1)

D

fun(1,2)

正确答案： B 

 

**20.**

执行以下代码，运行结果

A

['H', 'ppy birthd', 'y to you!']

B

"Happy birthday to you!"

C

运行出错

D

['Happy', 'birthday', 'to', 'you!']

正确答案： A 

 

**21.**

以下代码执行的输出结果是： <o:p></o:p>

 

A

40

B

1024

C

200

D

400

正确答案： A 

 

**22.** 字典 d={'Name': 'Kate', 'No': '1001', 'Age': '20'}，表达式len(d)的值为

A

12

B

9

C

6

D

3

正确答案： D 

 

**23.** 元组变量t=("cat", "dog", "tiger", "human")， t[::-1]的结果是

A

{'human', 'tiger', 'dog', 'cat'}

B

['human', 'tiger', 'dog', 'cat']

C

运行出错

D

('human', 'tiger', 'dog', 'cat')

正确答案： D 

 

**24.** 关于Python的列表，描述错误的选项是

A

Python列表是包含0个或者多个对象引用的有序序列

B

Python列表用中括号[]表示

C

Python列表是一个可以修改数据项的序列类型

D

Python列表的长度不可变的

正确答案： D 

 

**25.**

以下代码执行的输出结果是：

A

出错

B

Hello!Hello! 

C

Hello!Hello! [2]

D

Hello!Hello! []

正确答案： C 

 

**26.**

以下程序的输出结果是：

A

in fun1()

in fun2()

 

B

in fun1()

C

死循环

D

出错

正确答案： D 

 

**27.** 关于Python文件的‘+’打开模式，以下选项正确的描述是

A

追加写模式

B

与r/w/a/x一同使用，在原功能基础上增加同时读写功能

C

只读模式

D

覆盖写模式

正确答案： B 

 

**28.** 以下关于CSV文件的描述，错误的选项是

A

CSV文件可用于不同工具间进行数据交换

B

CSV文件格式是一种通用的，相对简单的文件格式，应用于程序之间转移表格数据。

C

CSV文件通过多种编码表示字符

D

CSV文件的每一行是一维数据，可以使用Python中的列表类型表示

正确答案： C 

 

**29.** 以下关于Python文件对象f的描述，错误的选项是

A

f.closed文件关闭属性，当文件关闭时，值为False

B

f.writable()用于判断文件是否可写

C

f.readable()用于判断文件是否可读

D

f.seekable()判断文件是否支持随机访问

正确答案： A 

 

**30.**

关于以下代码的描述，错误的选项是

A

执行代码后，abc.txt文件未关闭，必须通过close()函数关闭

B

打印输出abc.txt文件内容   

C

item是字符串类型

D

lines是列表类型

正确答案： A 

 

**31.** 下列与队列结构有关联的是

A

先到先服务的作业调度

B

多重循环的执行

C

数组元素的引用

D

函数的递归调用

正确答案： A 

 

**32.** 下列叙述中正确的是

A

以上说法都不对

B

循环队列中的元素个数随队尾指针的变化而动态变化

C

循环队列中的元素个数随队头指针与队尾指针的变化而动态变化

D

循环队列中的元素个数随队头指针的变化而动态变化

正确答案： C 

 

**33.** 下列链表中，其逻辑结构属于非线性结构的是

A

双向链表

B

循环链表

C

二叉链表

D

带链的栈

正确答案： C 

 

**34.** 在结构化设计方法中，生成的结构图中，带有箭头的连线表示

A

模块之间的调用关系

B

程序的组成成分

C

数据的流向

D

控制程序的执行顺序

正确答案： A 

 

**35.** 在数据流图中，带有名字的箭头表示

A

模块之间的调用关系

B

控制程序的执行顺序

C

数据的流向

D

程序的组成成分

正确答案： C 

 

**36.** 模块独立性是软件模块化所提出的要求，衡量模块独立性的度量标准则是模块的

A

抽象和信息隐蔽

B

激活机制和控制方法

C

内聚性和耦合性

D

局部化和封装化

正确答案： C 

 

**37.** 需求分析阶段的任务是确定

A

软件开发费用

B

软件开发方法

C

软件系统功能

D

软件开发工具

正确答案： C 

 

**38.** 在数据管理技术的发展过程中，经历了人工管理阶段、文件系统阶段和数据库系统阶段。其中数据独立性的阶段是

A

数据项管理

B

人工管理

C

数据库系统

D

文件系统

正确答案： C 

 

**39.** 下列说法中，不属于数据模型所描述的内容的是

A

数据约束

B

数据结构

C

数据操作

D

数据查询

正确答案： D 

 

**40.** 下列有关数据库的描述，正确的是

A

数据处理是将信息转化为数据的过程

B

数据的物理独立性是指当数据的逻辑结构改变时，数据的存储结构不变

C

关系中的每一列称为元组，一个元组就是一个字段

D

如果一个关系中的属性或属性组并非该关系的关键字，但它是另一个关系的关键字，则称其为本关系的外关键字

正确答案： D 

 

 

 

**1.** 以下关于程序设计语言的描述，错误的选项是：

A

Python语言是一种脚本编程语言

B

汇编语言是直接操作计算机硬件的编程语言

C

程序设计语言经历了机器语言、汇编语言、脚本语言三个阶段

D

编译和解释的区别是一次性翻译程序还是每次执行时都要翻译程序

正确答案： C 

 

**2.**

表达式 1001 == 0x3e7 的结果是：

A

false

B

False

C

true

D

True

正确答案： B 

 

**3.** 以下选项，不是Python保留字的选项是：

A

del

B

pass

C

not

D

string

正确答案： D 

 

**4.** 表达式 eval('500/10') 的结果是：

A

‘500/10’

B

500/10

C

50

D

50.0

正确答案： D 

 

**5.** 15. 表达式 type(eval('45')) 的结果是：

A

<class 'float'>

B

<class 'str'>

C

None

D

<class 'int'>

正确答案： D 

 

**6.** 表达式 divmod(20,3) 的结果是：

A

6, 2

B

6

C

2

D

(6, 2)

正确答案： D 

 

**7.** 以下关于字符串类型的操作的描述，错误的是：

A

str.replace(x,y)方法把字符串str中所有的x子串都替换成y

B

想把一个字符串str所有的字符都大写，用str.upper()

C

想获取字符串str的长度，用字符串处理函数 str.len()

D

设 x = ’aa’ ，则执行x*3的结果是‘aaaaaa’

正确答案： C 

 

**8.** 设 str = 'python'，想把字符串的第一个字母大写，其他字母还是小写，正确的选项是：

A

print(str[0].upper()+str[1:])

B

print(str[1].upper()+str[-1:1])

C

print(str[0].upper()+str[1:-1])

D

print(str[1].upper()+str[2:])

正确答案： A 

 

**9.** 以下选项，不属于程序流程图基本元素的是：

A

循环框

B

连接点

C

判断框

D

起始框

正确答案： A 

 

**10.** 以下关于循环结构的描述，错误的是：

A

遍历循环使用for <循环变量> in <循环结构>语句，其中循环结构不能是文件

B

使用range()函数可以指定for循环的次数

C

for i in range(5)表示循环5次，i的值是从0到4

D

用字符串做循环结构的时候，循环的次数是字符串的长度

正确答案： A 

 

**11.**

执行以下程序，输入”93python22”，输出结果是：

w = input(‘请输入数字和字母构成的字符串：’)

for x in w:

​    if '0'<= x <= '9':

​        continue

​    else:

​        w.replace(x,'')

print(w)

A

python9322

B

python

C

93python22

D

9322

正确答案： C 

 

**12.**

执行以下程序，输入la，输出结果是：

la = 'python'

try:

​    s = eval(input('请输入整数：'))

​    ls = s*2

​    print(ls)

except:

​    print('请输入整数')

A

la

B

请输入整数

C

pythonpython

D

python

正确答案： C 

 

**13.**

执行以下程序，输入qp，输出结果是：

k = 0

while True:

​    s = input('请输入q退出：')

​    if s == 'q':

​        k += 1

​        continue

​    else:

​        k += 2

​        break

print(k)

A

2

B

请输入q退出：

C

3

D

1

正确答案： A 

 

**14.**

以下程序的输出结果是：

s = 0

def fun(num):

​    try:

​        s += num

​        return s

​    except:

​        return 0

​    return 5

print(fun(2))

A

0

B

2

C

UnboundLocalError

D

5

正确答案： A 

 

**15.** 以下关于函数的描述，错误的是：

A

函数是一种功能抽象

B

使用函数的目的只是为了增加代码复用

C

函数名可以是任何有效的Python标识符

D

使用函数后，代码的维护难度降低了

正确答案： B 

 

**16.**

以下程序的输出结果是：

def test( b = 2, a = 4):

​    global z

​    z += a * b

​    return z

z = 10

print(z, test())

A

18 None

B

10 18

C

UnboundLocalError

D

18 18

正确答案： B 

 

**17.**

以下程序的输出结果是：

def hub(ss, x = 2.0,y = 4.0):

​    ss += x * y

ss = 10

print(ss, hub(ss, 3))

A

22.0 None

B

10 None

C

22 None

D

10.0 22.0

正确答案： B 

 

**18.** 以下表达式，正确定义了一个集合数据对象的是：

A

x = { 200, ’flg’, 20.3}

B

x = ( 200, ’flg’, 20.3)

C

x = [ 200, ’flg’, 20.3 ]

D

x = {‘flg’ : 20.3}

正确答案： A 

 

**19.**

以下程序的输出结果是：

ss = list(set("jzzszyj"))

ss.sort()

print(ss)

A

['z', 'j', 's', 'y']

B

['j', 's', 'y', 'z']

C

['j', 'z', 'z', 's', 'z', 'y', 'j']

D

['j', 'j', 's', 'y', 'z', 'z', 'z']

正确答案： B 

 

**20.**

以下程序的输出结果是：

ss = set("htslbht")

sorted(ss)

for i in ss:

​    print(i,end = '')

A

htslbht

B

hlbst

C

tsblh

D

hhlstt

正确答案： B 

 

**21.**

已知id(ls1) = 4404896968，以下程序的输出结果是：

ls1 = [1,2,3,4,5]

ls2 = ls1

ls3 = ls1.copy()

print(id(ls2),id(ls3))

A

4404896968 4404896904

B

4404896904 4404896968

C

4404896968 4404896968

D

4404896904 4404896904

正确答案： A 

 

**22.**

以下程序的输出结果是：

ls =list({'shandong':200, 'hebei':300, 'beijing':400})

print(ls)

A

['300','200','400']

B

['shandong', 'hebei', 'beijing']

C

[300,200,400]

D

'shandong', 'hebei', 'beijing'

正确答案： B 

 

**23.** 以下关于文件的描述，错误的是：

A

二进制文件和文本文件的操作步骤都是“打开-操作-关闭”

B

open() 打开文件之后，文件的内容并没有在内存中

C

open()只能打开一个已经存在的文件

D

文件读写之后，要调用close()才能确保文件被保存在磁盘中了

正确答案： C 

 

**24.**

以下程序输出到文件text.csv里的结果是：

fo = open("text.csv",'w')

x = [90,87,93]

z = []

for y in x:

​    z.append(str(y))

fo.write(",".join(z))

fo.close()

A

[90,87,93]

B

90,87,93

C

‘[90,87,93]’

D

‘90,87,93’

正确答案： B 

 

**25.**

以下程序的输出结果是：

img1 = [12,34,56,78]

img2 = [1,2,3,4,5]

def displ():

​    print(img1)

def modi():

​    img1 = img2

modi()

displ()

A

( [1,2,3,4,5])

B

[12, 34, 56, 78]

C

([12, 34, 56, 78])

D

[1,2,3,4,5]

正确答案： B 

 

**26.** 以下关于数据维度的描述，错误的是：

A

采用列表表示一维数据，不同数据类型的元素是可以的

B

JSON格式可以表示比二维数据还复杂的高维数据

C

二维数据可以看成是一维数据的组合形式

D

字典不可以表示二维以上的高维数据

正确答案： D 

 

**27.** 以下不属于Python的pip工具命令的选项是：

A

show

B

install

C

download

D

get

正确答案： D 

 

**28.** 用Pyinstall工具把Python源文件打包成一个独立的可执行文件，使用的参数是：

A

-D

B

-L

C

-i

D

-F

正确答案： D 

 

**29.**

以下不是程序输出结果的选项是：

import random as r

ls1 = [12,34,56,78]

r.shuffle(ls1)

print(ls1)

A

[12, 78, 56, 34]

B

[56, 12, 78, 34]

C

[12, 34, 56, 78]

D

[12, 78, 34, 56]

正确答案： C 

 

**30.** 以下关于turtle库的描述，正确的是：

A

在import turtle之后就可以用circle()语句，来画一个圆圈

B

要用from turtle import turtle来导入所有的库函数

C

home() 函数设置当前画笔位置到原点，朝向东

D

seth(x) 是setheading(x)函数的别名，让画笔向前移动x

正确答案： C 

 

**31.** 一些重要的程序语言（如C语言和Pascal语言）允许过程的递归调用。而实现递归调用中的存储分配通常用

A

栈

B

堆

C

链表

D

数组

正确答案： A 

 

**32.** 下列叙述中正确的是

A

一个算法的空间复杂度大，则其时间复杂度必定小

B

一个算法的空间复杂度大，则其时间复杂度也必定大

C

算法的时间复杂度与空间复杂度没有直接关系

D

一个算法的时间复杂度大，则其空间复杂度必定小

正确答案： C 

 

**33.** 为了提高测试的效率，应该

A

随机选取测试数据

B

在完成编码以后制定软件的测试计划

C

取一切可能的输入数据作为测试数据

D

集中对付那些错误群集的程序

正确答案： D 

 

**34.** 软件开发离不开系统环境资源的支持，其中必要的测试数据属于

A

辅助资源

B

硬件资源

C

通信资源

D

支持软件

正确答案： A 

 

**35.** 完全不考虑程序的内部结构和内部特征，而只是根据程序功能导出测试用例的测试方法是

A

错误推测法

B

白箱测试法

C

黑箱测试法

D

安装测试法

正确答案： C 

 

**36.** 在数据管理技术发展过程中，文件系统与数据库系统的主要区别是数据库系统具有

A

特定的数据模型

B

数据无冗余

C

专门的数据管理软件

D

数据可共享

正确答案： A 

 

**37.** 下列有关数据库的描述，正确的是

A

数据库是一个关系

B

数据库是一个DBF文件

C

数据库是一个结构化的数据集合

D

数据库是一组文件

正确答案： C 

 

**38.** 相对于数据库系统，文件系统的主要缺陷有数据关联差、数据不一致性和

A

可重用性差

B

冗余性

C

非持久性

D

安全性差

正确答案： B 

 

**39.** 软件开发的结构化生命周期方法将软件生命周期划分成

A

定义、开发、运行维护

B

设计阶段、编程阶段、测试阶段

C

总体设计、详细设计、编程调试

D

需求分析、功能定义、系统设计

正确答案： A 

 

**40.** 下列不属于结构化分析的常用工具的是

A

判定树

B

数据字典

C

数据流图

D

PAD图

正确答案： C 

 

####  2填空题

1.仅使用 Python 基本语法，即不使用任何模块，编写 Python 程序计算下列数学表达式的结果并输出，小数点后保留3位。

![IMG_256](file:///C:/Users/1234/AppData/Local/Temp/msohtmlclip1/01/clip_image002.jpg)

 

**输入**

该题目没有输入

 

**输出**

输出结果小数点后保留 3 位

 

```
x = pow((3**4 + 5*(6**7))/8, 0.5)
```

```
print("{:.3f}".format(x))
```

2.以中国共产党第十九次全国代表大会报告中一句话作为字符串变量 s，完善 Python 程序，分别用 Python 内置函数及 jieba 库中已有函数计算字符串 s 的中文字符个数及中文词语个数。注意，中文字符包含中文标点符号。（提交的代码应包括题目中给出的部分）

```
import jieba
```

```
s = "中国特色社会主义进入新时代，我国社会主要矛盾已经转化为人民日益增长的美好生活需要和不平衡不充分的发展之间的矛盾。"
```

```
n = ____①____
```

```
m = ____②____print("中文字符数为{}，中文词语数为{}。".format(n, m))，中文
```

```
 
```

 

**输入**

该题目没有输入

 

**输出**

输出字符串 s 的中文字符个数及中文词语个数

```
import jieba
```

```
s = "中国特色社会主义进入新时代，我国社会主要矛盾已经转化为人民日益增长的美好生活需要和不平衡不充分的发展之间的矛盾。"
```

```
n = len(s) 
```

```
m = len(jieba.lcut(s))print("中文字符数为{}，中文词语数为{}。".format(n, m))
```

3.0x4DC0 是一个十六进制数，它对应的 Unicode 编码是中国古老的《易经》六十四卦的第一卦，请输出第 51 卦（震卦）对应的 Unicode 编码的二进制、十进制、八进制和十六进制格式。

```
print("二进制{____①____}、十进制{____②____}、八进制{____③____}、十六进制{____④____}".format(____⑤____))
```

 

**输入**

该题目没有输入 

 

**输出**

符合输出要求即可

 

 

```
print("二进制{0:b}、十进制{0}、八进制{0:o}、十六进制{0:x}".format(0x4DC0+50))
```

# 解析：Python 十进制转二进制、八进制、十六进制

[![IMG_256](file:///C:/Users/1234/AppData/Local/Temp/msohtmlclip1/01/clip_image003.gif) Python3 实例](http://www.runoob.com/python3/python3-examples.html)

以下代码用于实现十进制转二进制、八进制、十六进制：

## 实例(Python 3.0+)

\# -*- coding: UTF-8 -*- # Filename : test.py # author by : www.runoob.com # 获取用户输入十进制数 dec = int(input("输入数字：")) print("十进制数为：", dec) print("转换为二进制为：", bin(dec)) print("转换为八进制为：", oct(dec)) print("转换为十六进制为：", hex(dec))

执行以上代码输出结果为：

```
python3 test.py 输入数字：5十进制数为：5转换为二进制为： 0b101转换为八进制为： 0o5转换为十六进制为： 0x5
```

```
python3 test.py 输入数字：12十进制数为：12转换为二进制为： 0b1100转换为八进制为： 0o14转换为十六进制为： 0xc
```

[![IMG_257](file:///C:/Users/1234/AppData/Local/Temp/msohtmlclip1/01/clip_image003.gif) Python3 实例](http://www.runoob.com/python3/python3-examples.html)

 [Python3 标准库概览](http://www.runoob.com/python3/python3-stdlib.html)

[Python3 正则表达式](http://www.runoob.com/python3/python3-reg-expressions.html) 

## 2 篇笔记

.          

**具体实现**

.          

十进制到二进制：

.          

```
def dec2bin(num):
```

```
    l = []
```

```
    if num < 0:
```

```
        return '-' + dec2bin(abs(num))
```

```
    while True:
```

```
        num, remainder = divmod(num, 2)
```

```
        l.append(str(remainder))
```

```
        if num == 0:
```

```
            return ''.join(l[::-1])
```

.          

十进制到八进制：

.          

```
def dec2oct(num):
```

```
    l = []
```

```
    if num < 0:
```

```
        return '-' + dec2oct(abs(num))
```

```
    while True:
```

```
        num, remainder = divmod(num, 8)
```

```
        l.append(str(remainder))
```

```
        if num == 0:
```

```
            return ''.join(l[::-1])
```

.          

十进制到十六进制：

.          

```
base = [str(x) for x in range(10)] + [ chr(x) 
```

```
for x in range(ord('A'),ord('A')+6)]
```

```
def dec2hex(num):
```

```
    l = []
```

```
    if num < 0:
```

```
        return '-' + dec2hex(abs(num))
```

```
    while True:
```

```
        num,rem = divmod(num, 16)
```

```
        l.append(base[rem])
```

```
        if num == 0:
```

```
            return ''.join(l[::-1])
```

.          

**十进制数转化成二进制数（float）**

.          

```
while True:
```

```
    number=input("请输入一个正数:(输入q退出程序）")
```

```
    if number in ['q','Q']:
```

```
        break
```

```
    elif not float(number)>0:
```

```
        print("请输入一个正数（输入q退出程序）：")
```

```
    else:
```

```
        number=float(number)
```

```
        array1=[]
```

```
        array2=[]
```

```
        integer=int(number)
```

```
        floa=number-integer
```

```
        while integer!=0:
```

```
            array1.append(integer%2)
```

```
            integer=integer//2
```

```
        else:
```

```
            array1.append(0)
```

```
        array1.reverse()
```

```
        while floa>0.00001:
```

```
            array2.append(int(2*floa))
```

```
            floa=floa*2-int(floa*2)
```

```
        else:
```

```
            array2.append(0)
```

```
        array1.append(".")
```

```
        array=array1+array2
```

```
        for x in array:
```

```
            print(x,end="")
```

```
        print("\n")
```

.          

 

4.使用 turtle 库的 turtle.fd() 函数和 turtle.seth() 函数绘制一个边长为 200 的正方形，效果如下图所示。请结合格式框架，补充横线处代码。

![IMG_256](file:///C:/Users/1234/AppData/Local/Temp/msohtmlclip1/01/clip_image004.png)

```
import turtle
```

```
d = 0
```

```
for i in range(____①____):
```

```
    turtle.fd(____②____)
```

```
    d = ____③____
```

```
    turtle.seth(d)
```

 

\---------------------------------------------------------------

自动评阅说明

 

最后使用 print 函数输出 ____①____,____②____,____③____中应填代码即可以自动评阅得分，如果有运算符，请在运算符两侧加上空格，

例如，如果代码为：

```
import turtle
```

```
d = 0for i in range(1):
```

```
    turtle.fd(100)
```

```
    d = i + 100
```

```
    turtle.seth(d)
```

则在提交代码页面输入： print(1, 100, 'i + 100')

习题讲解

参考代码

```
import turtle
```

```
d = 0
```

```
for i in range(4):
```

```
    turtle.fd(200)
```

```
    d = d + 90
```

```
    turtle.seth(d)
```

解析：turtle.seth()固定方向turtle.left()向左转turtle.right()向右转

5.列表 ls 中存储了我国 39 所 985 高校所对应的学校类型，请以这个列表为数据变量，完善 Python 代码，统计输出各类型的数量。

```
ls = ["综合", "理工", "综合", "综合", "综合", "综合", "综合", "综合", "综合", "综合",\
```

```
      "师范", "理工", "综合", "理工", "综合", "综合", "综合", "综合", "综合","理工",\
```

```
      "理工", "理工", "理工", "师范", "综合", "农林", "理工", "综合", "理工", "理工", \
```

```
      "理工", "综合", "理工", "综合", "综合", "理工", "农林", "民族", "军事"]
```

 

**输入格式**

该题目没有输入

 

**输出格式**

要求按以下顺序输出

综合:1
 理工:2
 师范:3
 农林:4
 民族:5
 军事:6

 

其中冒号为英文冒号

习题讲解

参考代码

```
ls = ["综合", "理工", "综合", "综合", "综合", "综合", "综合", "综合", \
```

```
      "综合", "综合", "师范", "理工", "综合", "理工", "综合", "综合", \
```

```
      "综合", "综合", "综合", "理工", "理工", "理工", "理工", "师范", \
```

```
      "综合", "农林", "理工", "综合", "理工", "理工", "理工", "综合", \
```

```
      "理工", "综合", "综合", "理工", "农林", "民族", "军事"]
```

```
d = {}
```

```
for word in ls:
```

```
    d[word] = d.get(word, 0) + 1for k in d:
```

```
    print("{}:{}".format(k, d[k]))
```

# 解析：Python3 字典 get() 方法

[![IMG_256](file:///C:/Users/1234/AppData/Local/Temp/msohtmlclip1/01/clip_image003.gif) Python3 字典](http://www.runoob.com/python3/python3-dictionary.html)

​    

## 描述

Python 字典 get() 函数返回指定键的值，如果值不在字典中返回默认值。

## 语法

get()方法语法：

```
dict.get(key, default=None)
```

## 参数

·        key -- 字典中要查找的键。

·        default -- 如果指定键的值不存在时，返回该默认值值。

## 返回值

返回指定键的值，如果值不在字典中返回默认值 None。

## 实例

以下实例展示了 get()函数的使用方法：

```
#!/usr/bin/python3 
```

```
 
```

```
dict = {'Name': 'Runoob', 'Age': 27}
```

```
print ("Age 值为 : %s" %  dict.get('Age'))print ("Sex 值为 : %s" %  dict.get('Sex', "NA"))
```

以上实例输出结果为：

```
Age 值为 : 27Sex 值为 : NA
```

6.《论语》是儒家学派的经典著作之一，主要记录了孔子及其弟子的言行。网络上有很多《论语》文本版本。这里给出了一个版本，文件名称为“论语-网络版.txt”，其内容采用如下格式组织：

```
【原文】
```

```
 
```

```
1.11子曰：“父在，观其(1)志；父没，观其行(2)；三年(3)无改于父之道(4)，可谓孝矣。”
```

```
 
```

```
【注释】
```

```
 
```

```
（略）
```

```
 
```

```
【译文】
```

```
 
```

```
（略）
```

```
 
```

```
【评析】
```

```
 
```

```
（略）
```

该版本通过【原文】标记《论语》原文内容，采用【注释】、【译文】和【评析】标记对原文的注释、译文和评析。

 

**问题1：**请编写程序，提取《论语》文档中所有原文内容，输出保存到“论语-提取版.txt”文件。输出文件格式要求：去掉文章中原文部分每行行首空格及如“1.11”等的数字标志，行尾无空格、无空行。参考格式如下（原文中括号及内部数字是对应源文件中注释项的标记）：

```
子曰(1)：“学(2)而时习(3)之，不亦说(4)乎？有朋(5)自远方来，不亦乐(6)乎？人不知(7)，而不愠(8)，不亦君子(9)乎？”
```

```
 
```

```
有子(1)曰：“其为人也孝弟(2)，而好犯上者(3)，鲜(4)矣；不好犯上，而好作乱者，未之有也(5)。君子务本(6)，本立而道生(7)。孝弟也者，其为人之本与(8)？”
```

```
 
```

```
子曰：“巧言令色(1)，鲜(2)仁矣。”
```

```
 
```

```
（略）
```

 

**问题2：**请编写程序，在“论语-提取版.txt”基础上，进一步去掉每行文字中所有括号及其内部数字，保存为“论文-原文.txt”文件。参考格式如下： 

```
子曰：“学而时习之，不亦说乎？有朋自远方来，不亦乐乎？人不知，而不愠，不亦君子乎？”
```

```
 
```

```
有子曰：“其为人也孝弟，而好犯上者，鲜矣；不好犯上，而好作乱者，未之有也。君子务本，本立而道生。孝弟也者，其为人之本与？”
```

```
 
```

```
子曰：巧言令色，鲜仁矣。”
```

```
 
```

```
（略）
```

 

本题暂不支持自动评分，print("我已掌握")，即可得分

习题讲解

 

参考代码 1

```
fi = open("论语-网络版.txt", "r", encoding="utf-8")
```

```
fo = open("论语-提取版.txt", "w")
```

```
wflag = False            #写标记
```

```
for line in fi:
```

```
    if "【" in line:     #遇到【时，说明已经到了新的区域，写标记置否
```

```
        wflag = False
```

```
    if "【原文】" in line:  #遇到【原文】时，设置写标记为True
```

```
        wflag = True
```

```
        continue    
```

```
    if wflag == True:    #根据写标记将当前行内容写入新的文件
```

```
        for i in range(0,25):
```

```
            for j in range(0,25):
```

```
                line = line.replace("{}·{}".format(i,j),"**")
```

```
        for i in range(0,10):
```

```
            line = line.replace("*{}".format(i),"")
```

```
        for i in range(0,10):
```

```
            line = line.replace("{}*".format(i),"")
```

```
        line = line.replace("*","")   
```

```
        fo.write(line)
```

```
fi.close()
```

```
fo.close()
```

 

参考代码 2

```
fi = open("论语-提取版.txt", "r")
```

```
fo = open("论语-原文.txt", "w")for line in fi:   #逐行遍历
```

```
    for i in range(1,23):  #对产生1到22数字 
```

```
        line=line.replace("({})".format(i), "")  #构造(i)并替换
```

```
    fo.write(line)
```

```
fi.close()
```

```
fo.close()
```

 

 

 

 

1.编写 Python 程序输出一个具有如下风格效果的文本，用作文本进度条样式，部分代码如下，填写空格处。

```
 10%@==
```

```
 20%@====
```

```
100%@====================
```

 

前三个数字，右对齐；后面字符，左对齐

 

文本中左侧一段输出 *N* 的值，右侧一段根据 *N* 的值输出等号，中间用 @ 分隔，等号个数为 *N* 与 5 的整除商的值，例如，当 *N* 等于 10 时，输出 2 个等号。

```
N = eval(input())   # N取值范围是0—100，整数print(____①____) 
```

习题讲解

参考代码

```
N = 20 # N取值范围为0-100整数
```

```
print("{:>3}%@{}".format(N,"="*(N//5)))
```

2.以论语中一句话作为字符串变量 s，补充程序，分别输出字符串 s 中汉字和标点符号的个数。

```
s = "学而时习之,不亦说乎?有朋自远方来,不亦乐乎?人不知而不愠,不亦君子乎?"
```

```
n = 0  # 汉字个数
```

```
m = 0  # 标点符号个数
```

```
 
```

```
____①____ # 在这里补充代码，可以多行
```

```
print("字符数为{}，标点符号数为{}。".format(n, m))
```

 

习题讲解

参考代码

```
s = "学而时习之,不亦说乎?有朋自远方来,不亦乐乎?人不知而不愠,不亦君子乎?"
```

```
n = 0  # 汉字个数
```

```
m = 0  # 标点符号个数
```

```
m = s.count(',') + s.count('?')
```

```
n = len(s) - mprint("字符数为{}，标点符号数为{}。".format(n, m))
```

3.使用程序计算整数 *N* 到整数 *N*+100 之间所有奇数的数值和，不包含 *N*+100，并将结果输出。整数 *N* 由用户给出，代码片段如下，补全代码。不判断输入异常。

```
N = input("请输入一个整数: ")
```

```
 
```

```
____①____ # 可以是多行代码
```

 

**输入输出示例**

| 输入 | 输出 |
| ---- | ---- |
| 3    | 2600 |

习题讲解

参考代码

```
N = input("请输入一个整数: ")
```

```
s = 0for i in range(eval(N), eval(N)+100):
```

```
    if i%2 == 1:
```

```
        s += iprint(s)
```

4.**B****卷简单应用1**

**上一题 下一题**

·        题目

·        提交代码

·        上传文件

·        答案与讲解

使用 turtle 库的 turtle.fd() 函数和 turtle.left() 函数绘制一个六边形，边长为 200 像素，效果如下图所示，请结合格式框架，补充横线处代码。

```
import turtle as tfor i in range(___①___):
```

```
    t.fd(___②___)
```

```
    t.left(___③___)
```

 

![img](file:///C:/Users/1234/AppData/Local/Temp/msohtmlclip1/01/clip_image005.png)

 

\--------------------------------------------------------------------

自动评阅说明

 

最后使用 print 函数输出 ____①____,____②____,____③____中应填代码即可以自动评阅得分，如果有运算符，请在运算符两侧加上空格，

例如，如果代码为：

```
import turtle as tfor i in range(2):
```

```
    t.fd(i + 100)
```

```
    t.left(200)
```

在提交代码页面输入： print(2, 'i + 100', 200)，运行即可

习题讲解

参考代码

```
import turtle as tfor i in range(6):
```

```
    t.fd(200)
```

```
    t.left(60)
```

5.经常会有要求用户输入整数的计算需求，但用户未必一定输入整数。为了提高用户体验，编写 getInput() 函数处理这样的情况。请补充如下代码，如果用户输入整数，则直接输出整数并退出，如果用户输入的不是整数，则要求用户重新输入，直至用户输入整数为止。

```
def getInput():
```

```
  ____①____ # 可以是多行代码
```

```
  return ____②____  # 只能是单行代码
```

```
print(getInput())
```

习题讲解

参考代码

```
def getInput():
```

```
    try:
```

```
        txt = input()   # "请输入整数: "
```

```
        while eval(txt) != int(txt):
```

```
            txt = input()   # "请输入整数: "
```

```
    except:
```

```
        return getInput()
```

```
    return eval(txt)print(getInput())
```

6.《天龙八部》是著名作家金庸的代表作之一，历时4年创作完成。该作品气势磅礴，人物众多，非常经典。这里给出一个《天龙八部》的网络版本，文件名为“天龙八部-网络版.txt”。

 

**问题1：**请编写程序，对这个《天龙八部》文本中出现的汉字和标点符号进行统计，字符与出现次数之间用冒号:分隔，输出保存到“天龙八部-汉字统计.txt”文件中，该文件要求采用 CSV 格式存储，参考格式如下（注意，不统计空格和回车字符）：

```
天:100, 龙:110, 八:109, 部:10
```

```
 
```

```
（略）
```

 

**问题2：**请编写程序，对《天龙八部》文本中出现的中文词语进行统计，采用 jieba 库分词，词语与出现次数之间用冒号:分隔，输出保存到“天龙八部-词语统计.txt”文件中。参考格式如下（注意，不统计任何标点符号）：

```
天龙:100, 八部:10
```

```
 
```

```
（略）
```

 

本题暂不支持自动评阅，print('ok')，即可得分

习题讲解

参考代码 1

```
fi = open("天龙八部-网络版.txt", "r", encoding='utf-8')
```

```
fo = open("天龙八部-汉字统计.txt", "w", encoding='utf-8')
```

```
txt = fi.read()
```

```
d = {}for c in txt:
```

```
    d[c] = d.get(c, 0) + 1del d[' ']del d['\n']
```

```
ls = []for key in d:
```

```
    ls.append("{}:{}".format(key, d[key]))
```

```
fo.write(",".join(ls))
```

```
fi.close()
```

```
fo.close()
```

 

参考代码 2

```
import jieba
```

```
fi = open("天龙八部-网络版.txt", "r", encoding='utf-8')
```

```
fo = open("天龙八部-词语统计.txt", "w", encoding='utf-8')
```

```
txt = fi.read()
```

```
words = jieba.lcut(txt)
```

```
d = {}for w in words:
```

```
    d[w] = d.get(w, 0) + 1del d[' ']del d['\n']
```

```
ls = []for key in d:
```

```
    ls.append("{}:{}".format(key, d[key]))
```

```
fo.write(",".join(ls))
```

```
fi.close()
```

```
fo.close()
```

 

 

 

 

 

 

1.编写 Python 程序输出一个具有如下风格效果的文本，用作文本进度条样式，部分代码如下，填写空格处。

```
 10%@==
```

```
 20%@====
```

```
100%@====================
```

 

前三个数字，右对齐；后面字符，左对齐

 

文本中左侧一段输出 *N* 的值，右侧一段根据 *N* 的值输出等号，中间用 @ 分隔，等号个数为 *N* 与 5 的整除商的值，例如，当 *N* 等于 10 时，输出 2 个等号。

```
N = eval(input())   # N取值范围是0—100，整数print(____①____) 
```

习题讲解

参考代码

```
N = 20 # N取值范围为0-100整数
```

```
print("{:>3}%@{}".format(N,"="*(N//5)))
```

2.以论语中一句话作为字符串变量 s，补充程序，分别输出字符串 s 中汉字和标点符号的个数。

```
s = "学而时习之,不亦说乎?有朋自远方来,不亦乐乎?人不知而不愠,不亦君子乎?"
```

```
n = 0  # 汉字个数
```

```
m = 0  # 标点符号个数
```

```
 
```

```
____①____ # 在这里补充代码，可以多行
```

```
print("字符数为{}，标点符号数为{}。".format(n, m))
```

 

习题讲解

参考代码

```
s = "学而时习之,不亦说乎?有朋自远方来,不亦乐乎?人不知而不愠,不亦君子乎?"
```

```
n = 0  # 汉字个数
```

```
m = 0  # 标点符号个数
```

```
m = s.count(',') + s.count('?')
```

```
n = len(s) - mprint("字符数为{}，标点符号数为{}。".format(n, m))
```

3.使用程序计算整数 *N* 到整数 *N*+100 之间所有奇数的数值和，不包含 *N*+100，并将结果输出。整数 *N* 由用户给出，代码片段如下，补全代码。不判断输入异常。

```
N = input("请输入一个整数: ")
```

```
 
```

```
____①____ # 可以是多行代码
```

 

**输入输出示例**

| 输入 | 输出 |
| ---- | ---- |
| 3    | 2600 |

习题讲解

参考代码

```
N = input("请输入一个整数: ")
```

```
s = 0for i in range(eval(N), eval(N)+100):
```

```
    if i%2 == 1:
```

```
        s += iprint(s)
```

4.**B****卷简单应用1**

**上一题 下一题**

·        题目

·        提交代码

·        上传文件

·        答案与讲解

使用 turtle 库的 turtle.fd() 函数和 turtle.left() 函数绘制一个六边形，边长为 200 像素，效果如下图所示，请结合格式框架，补充横线处代码。

```
import turtle as tfor i in range(___①___):
```

```
    t.fd(___②___)
```

```
    t.left(___③___)
```

 

![img](file:///C:/Users/1234/AppData/Local/Temp/msohtmlclip1/01/clip_image005.png)

 

\--------------------------------------------------------------------

自动评阅说明

 

最后使用 print 函数输出 ____①____,____②____,____③____中应填代码即可以自动评阅得分，如果有运算符，请在运算符两侧加上空格，

例如，如果代码为：

```
import turtle as tfor i in range(2):
```

```
    t.fd(i + 100)
```

```
    t.left(200)
```

在提交代码页面输入： print(2, 'i + 100', 200)，运行即可

习题讲解

参考代码

```
import turtle as tfor i in range(6):
```

```
    t.fd(200)
```

```
    t.left(60)
```

5.经常会有要求用户输入整数的计算需求，但用户未必一定输入整数。为了提高用户体验，编写 getInput() 函数处理这样的情况。请补充如下代码，如果用户输入整数，则直接输出整数并退出，如果用户输入的不是整数，则要求用户重新输入，直至用户输入整数为止。

```
def getInput():
```

```
  ____①____ # 可以是多行代码
```

```
  return ____②____  # 只能是单行代码
```

```
print(getInput())
```

习题讲解

参考代码

```
def getInput():
```

```
    try:
```

```
        txt = input()   # "请输入整数: "
```

```
        while eval(txt) != int(txt):
```

```
            txt = input()   # "请输入整数: "
```

```
    except:
```

```
        return getInput()
```

```
    return eval(txt)print(getInput())
```

6.《天龙八部》是著名作家金庸的代表作之一，历时4年创作完成。该作品气势磅礴，人物众多，非常经典。这里给出一个《天龙八部》的网络版本，文件名为“天龙八部-网络版.txt”。

 

**问题1：**请编写程序，对这个《天龙八部》文本中出现的汉字和标点符号进行统计，字符与出现次数之间用冒号:分隔，输出保存到“天龙八部-汉字统计.txt”文件中，该文件要求采用 CSV 格式存储，参考格式如下（注意，不统计空格和回车字符）：

```
天:100, 龙:110, 八:109, 部:10
```

```
 
```

```
（略）
```

 

**问题2：**请编写程序，对《天龙八部》文本中出现的中文词语进行统计，采用 jieba 库分词，词语与出现次数之间用冒号:分隔，输出保存到“天龙八部-词语统计.txt”文件中。参考格式如下（注意，不统计任何标点符号）：

```
天龙:100, 八部:10
```

```
 
```

```
（略）
```

 

本题暂不支持自动评阅，print('ok')，即可得分

习题讲解

参考代码 1

```
fi = open("天龙八部-网络版.txt", "r", encoding='utf-8')
```

```
fo = open("天龙八部-汉字统计.txt", "w", encoding='utf-8')
```

```
txt = fi.read()
```

```
d = {}for c in txt:
```

```
    d[c] = d.get(c, 0) + 1del d[' ']del d['\n']
```

```
ls = []for key in d:
```

```
    ls.append("{}:{}".format(key, d[key]))
```

```
fo.write(",".join(ls))
```

```
fi.close()
```

```
fo.close()
```

 

参考代码 2

```
import jieba
```

```
fi = open("天龙八部-网络版.txt", "r", encoding='utf-8')
```

```
fo = open("天龙八部-词语统计.txt", "w", encoding='utf-8')
```

```
txt = fi.read()
```

```
words = jieba.lcut(txt)
```

```
d = {}for w in words:
```

```
    d[w] = d.get(w, 0) + 1del d[' ']del d['\n']
```

```
ls = []for key in d:
```

```
    ls.append("{}:{}".format(key, d[key]))
```

```
fo.write(",".join(ls))
```

```
fi.close()
```

```
fo.close()
```

 

 

 

 

 

1.根据输入正整数 *n*，作为财务数据，输出一个宽度为 20 字符，*n* 右对齐显示，带千位分隔符的效果，使用减号字符“-”填充。如果输入正整数超过 20 位，则按照真实长度输出。提示代码如下：

```
n = input()
```

```
____①____ #可以多行
```

 

**输入输出示例**

|        | 输入      | 输出                   |
| ------ | --------- | ---------------------- |
| 示例 1 | `2190000` | `-----------2,190,000` |

习题讲解

参考代码

```
n = input()  # 请输入整数print("{:->20,}".format(eval(n)))
```

2.PyInstaller 库可以对程序打包，给定一个 Python 源程序文件 a.py，图标文件为 a.ico，将其打包为在 Windows 平台上带有上述图标的单一可执行文件，使用什么样的命令？

 

print 这个命令即可自动评阅

习题讲解

参考代码

```
pyinstaller –i a.ico –F a.py
```

3.以 123 为随机数种子，随机生成 10 个在 1 到 999（含）之间的随机数，以逗号分隔，打印输出，请补充横线处代码。提示代码如下

```
import random
```

```
____①____for i in range(____②____):
```

```
    print(____③____, end=",")
```

习题讲解

参考代码

```
import random
```

```
random.seed(123)for i in range(10):
```

```
    print(random.randint(1,999), end=",")
```

4.使用 turtle 库的 turtle.right() 函数和 turtle.fd() 函数绘制一个菱形四边形，边长为 200 像素，效果如下图所示。请勿修改已经给出的第一行代码，并完善程序。

![img](file:///C:/Users/1234/AppData/Local/Temp/msohtmlclip1/01/clip_image006.png)

提示代码：

```
import turtle as t
```

 

 

本题暂不支持自动评阅，print('ok') 即可得分并查看答案。

 

习题讲解

参考代码

```
import turtle as t
```

```
t.right(-30)for i in range(2):
```

```
    t.fd(200)
```

```
    t.right(60*(i+1))for i in range(2):
```

```
    t.fd(200)
```

```
    t.right(60*(i+1))
```

5.补充完善如下代码，使得程序能够计算 a 中各元素与 b 逐项乘积的累加和。

提示代码如下：

```
a = [[1,2,3], [4,5,6], [7,8,9]]
```

```
b = [3,6,9]
```

```
____①____for c in a:for j in ____②____:
```

```
    s += c[j]*b[j]print(s)
```

习题讲解

参考代码

```
a = [[1,2,3], [4,5,6], [7,8,9]]
```

```
b = [3,6,9]
```

```
s = 0for c in a:
```

```
    for j in range(3):
```

```
        s += c[j]*b[j]print(s)
```

6.《命运》和《寻梦》都是著名科幻作家倪匡的科幻作品。这里给出一个《命运》和《寻梦》的网络版本，文件名为“命运-网络版.txt”和“寻梦-网络版.txt”。

 

**问题1：**请编写程序，对这两个文本中出现的字符进行统计，字符与出现次数之间用冒号:分隔，将两个文件前 100 个最常用字符分别输出保存到“命运-字符统计.txt”和“寻梦-字符统计.txt”文件中，该文件要求采用 CSV 格式存储，参考格式如下（注意，不统计回车字符）：

 

**问题2：**请编写程序，对“命运-字符统计.txt”和“寻梦-字符统计.txt”中出现的相同字符打印输出。“相同字符.txt”文件中，字符间使用逗号分隔。

 

本题暂不支持自动评阅，print('ok') 即可得分并查看答案。

习题讲解

参考代码 1

```
names = ["命运", "寻梦"]for name in names:
```

```
    fi = open(name+"-网络版.txt", "r", encoding="utf-8")
```

```
    fo = open(name+"-字符统计.txt", "w", encoding="utf-8")
```

```
    txt = fi.read()
```

```
    d = {}
```

```
    for c in txt:
```

```
        d[c] = d.get(c, 0) + 1
```

```
    del d['\n']
```

```
    ls = list(d.items())
```

```
    ls.sort(key=lambda x:x[1], reverse=True)
```

```
    for i in range(100):
```

```
        ls[i] = "{}:{}".format(ls[i][0], ls[i][1])
```

```
    fo.write(",".join(ls[:100]))
```

```
    fi.close()
```

```
    fo.close()
```

 

参考代码 2

```
def getList(name):
```

```
    f = open(name+"-字符统计.txt", "r", encoding="utf-8")
```

```
    words = f.read().split(',')
```

```
    for i in range(len(words)):
```

```
        words[i] = words[i].split(':')[0]
```

```
    f.close()
```

```
    return wordsdef main():
```

```
    fo = open("相同字符.txt", "w")
```

```
    ls1 = getList("命运")
```

```
    ls2 = getList("寻梦")
```

```
    ls3 = []
```

```
    for c in ls1:
```

```
        if c in ls2:
```

```
            ls3.append(c)
```

```
    fo.write(",".join(ls3))
```

```
    fo.close()
```

```
main()
```

 

 

 

 

1.编写程序，从键盘上获得用户连续输入且用逗号分隔的若干个数字（不必以逗号结尾），计算所有输入数字的和并输出，给出代码提示如下。

```
n = input()
```

```
nums = ____①____ 
```

```
s = 0for i in nums:
```

```
    ____②____print(s)
```

 

**输入输出示例**

习题讲解

参考代码

```
n = input("")
```

```
nums = n.split(",")
```

```
s = 0for i in nums:
```

```
    s += eval(i)print(s)
```

2.编写程序，获得用户输入的数值 M 和 N，求 M 和 N 的最大公约数。提示代码如下。

```
def GreatCommonDivisor(a,b):
```

```
    if a > b:
```

```
        a,b = b,a
```

```
    r = 1
```

```
    while r != 0:
```

```
        ____①____
```

```
        a = b
```

```
        b = r
```

```
    return a
```

```
m = eval(input())
```

```
n = eval(input())print(____②____)
```

 

**输入输出示例**

|        | 输入   | 输出 |
| ------ | ------ | ---- |
| 示例 1 | `2``3` | `1`  |

习题讲解

参考代码

```
def GreatCommonDivisor(a,b):
```

```
    if a > b:
```

```
        a,b = b,a
```

```
    r = 1
```

```
    while r != 0:
```

```
        r = a % b
```

```
        a = b
```

```
        b = r
```

```
    return a
```

```
m = eval(input())
```

```
n = eval(input())print(GreatCommonDivisor(m,n))
```

3.jieba 是一个中文分词库，一些句子可能存在多种分词结果，请补充横线处代码，产生字符串 s 可能的所有分词结果列表，提示代码如下。

```
____①____
```

```
s = "世界冠军运动员的乒乓球拍卖完了"
```

```
ls = jieba.lcut(____②____)print(ls)
```

习题讲解

参考代码

```
import jieba
```

```
s = "世界冠军运动员的乒乓球拍买完了"
```

```
ls = jieba.lcut(s,True)print(ls)
```

4.使用 turtle 库的 turtle.circle() 函数、turtle.seth() 函数和 turtle.left() 函数绘制一个四瓣花图形，效果如下图所示。请结合程序整体框架，补充横线处代码，从左上角花瓣开始，逆时针作画。

 

​                          ![img](file:///C:/Users/1234/AppData/Local/Temp/msohtmlclip1/01/clip_image008.png)

 

```
import turtle as tfor i in range(____①____):
```

```
    t.seth(____②____)
```

```
    t.circle(200, 90)
```

```
    t.seth(____③____)
```

```
    t.circle(200, 90)
```

 

\---------------------------------------------

自动评阅说明

 

依次以字符串形式输入 ____①____,____②____,____③____ 中应填的代码，即可自动评阅，运算符两侧需要加空格

如果代码为：

```
import turtle as tfor i in range(100):
```

```
    t.seth(i + 100)
```

```
    t.circle(200, 90)
```

```
    t.seth(-10 * (i + 100))
```

```
    t.circle(200, 90)
```

则在提交代码页面输入： print("100", "i + 100", "-10 * (i + 100)")

 

习题讲解

参考代码

```
import turtle as tfor i in range(4):
```

```
    t.seth(90 * (i + 1))
```

```
    #90,180,270，360
```

```
    t.circle(200,90)
```

```
    #-90,0,90,180
```

```
    t.seth(-90 + i * 90)
```

```
    t.circle(200,90)
```

5.编写程序，实现将列表 ls = [23,45,78,87,11,67,89,13,243,56,67,311,431,111,141] 中的素数去除，并输出去除素数后列表 ls 的元素个数。请结合程序整体框架，补充横线处代码。

```
def is_prime(n):
```

```
    ____①____   #此处可为多行函数定义代码
```

```
ls = [23,45,78,87,11,67,89,13,243,56,67,311,431,111,141]for i in ls.copy():
```

```
    if is_prime(i)== True:
```

```
        ____②____   #此处为一行代码print(len(ls))
```

习题讲解

参考代码

```
def is_prime(n):
```

```
    for i in range(2,n):
```

```
        if n % i == 0:
```

```
            return False
```

```
    return True
```

```
 
```

```
ls = [23,45,78,87,11,67,89,13,243,56,67,311,431,111,141]for i in ls:
```

```
    if is_prime(i)== False:
```

```
        ls.remove(i)print(len(ls))
```

6.古代航海人为了方便在航海时辨别方位和观测天象，将散布在天上的星星运用想象力将它们连接起来，有一半是在古时候已命名，另一半是近代开始命名的。两千多年前古希腊的天文学家希巴克斯命名十二星座，依次为白羊座、金牛座、双子座、巨蟹座、狮子座、处女座、天秤座、天蝎座、射手座、魔蝎座、水瓶座和双鱼座。给出二维数据存储CSV文件（SunSign.csv），内容如下：

```
星座,开始月日,结束月日,Unicode
```

```
水瓶座,120,218,9810
```

```
双鱼座,219,320,9811
```

```
白羊座,321,419,9800
```

```
金牛座,420,520,9801
```

```
双子座,521,621,9802
```

```
巨蟹座,622,722,9803
```

```
狮子座,723,822,9804
```

```
处女座,823,922,9805
```

```
天秤座,923,1023,9806
```

```
天蝎座,1024,1122,9807
```

```
射手座,1123,1221,9808
```

```
魔蝎座,1222,119,9809
```

请编写程序，读入CSV文件中数据，循环获得用户输入，直至用户输入 "exit" 退出。根据用户输入的星座名称，输出此星座的出生日期范围及对应字符形式。如果输入的星座名称有误，请输出“输入星座名称有误！”。

习题讲解

参考代码

```
#读入CSV格式数据到列表中
```

```
fo = open("SunSign.csv","r", encoding='utf-8')
```

```
ls = []for line in fo:
```

```
    line = line.replace("\n","")
```

```
    ls.append(line.split(","))
```

```
fo.close()
```

```
while True:
```

```
    InputStr = input() # 请输入星座名称,例如双子座
```

```
    InputStr.strip()
```

```
    flag = False
```

```
    if InputStr == 'exit':
```

```
        break
```

```
    for line in ls:
```

```
        if InputStr == line[0]:
```

```
             print("{}座的生日位于{}-{}之间。".format(chr(eval(line[3])),line[1],line[2]))
```

```
             flag = True
```

```
    if flag == False:
```

```
        print("输入星座名称有误！")
```

```
 
```

 

 

 

 

# 1.基本操作题（1）

## 描述

参照代码模板，完善代码，实现功能：从键盘输入一个汉字，在屏幕上显示输出该汉字的 Unicode 编码值。

本题目支持自动评阅。

 

## 输入

中

 

## 输出

"中"汉字的 Unicode 编码：20013

 

## 输入输出示例

 

|        | 输入 | 输出                         |
| ------ | ---- | ---------------------------- |
| 示例 1 | 中   | "中"汉字的Unicode编码：20013 |

习题讲解

```
#请输入一个汉字
```

```
s = input("")print("\"{}\"汉字的Unicode编码：{}".format(s,ord(s)))
```

# 2.基本操作题（2）

 

## 描述

参照代码模板，完善代码，实现下面的功能：从键盘输入两个数（换行），调用函数 gcd() 输出两个数的最大公约数显示在屏幕上。

本题目支持自动评阅。

 

 输入输出示例

 

|        | 输入    | 输出                   |
| ------ | ------- | ---------------------- |
| 示例 1 | 72   48 | 72与48的最大公约数是24 |

习题讲解

```
#请输入第一个正整数：#请输入第一个正整数：def gcd(x,y):
```

```
    if x < y:
```

```
        x,y = y,x
```

```
    while x % y != 0:
```

```
        r = x % y
```

```
        x = y
```

```
        y = r
```

```
    return y
```

```
a = eval(input(""))
```

```
b = eval(input(""))
```

```
gcdab = gcd(a,b)print("{}与{}的最大公约数是{}".format(a,b,gcd(a,b)))
```

# 3.基本操作题（3）

## 描述

参照代码模板，完善代码，实现功能：从键盘输入一个列表，计算输出列表元素的平均值。示例如下：

 

输入

[2,3,5,7]

 

输出

平均值为： 4.25 

 

本题目支持自动评阅。

 

## 输入输出示例

 

|        | 输入      | 输出            |
| ------ | --------- | --------------- |
| 示例 1 | [2,3,5,7] | 平均值为： 4.25 |

习题讲解

```
def mean(numlist):
```

```
    s = 0.0
```

```
    for num in numlist:
```

```
        s = s + num
```

```
    return s/len(numlist)#请输入一个列表：
```

```
ls = eval(input(""))print("平均值为：",mean(ls))
```

# 4.简单操作题（1）

## 描述

参照代码模板，完善代码，不得修改其它代码。使用 turtle 库的 turtle.right() 函数和 turtle.circle() 函数绘制一个四叶草，效果如下图所示。

直接输出代码模板中正确填写的内容可支持自动评阅。

![img](file:///C:/Users/1234/AppData/Local/Temp/msohtmlclip1/01/clip_image009.jpg)

\---------------------------------------------------------------

自动评阅说明

 

使用字符串形式输出 ____①____,____②____,____③____中应填代码即可以自动评阅得分

例如，如果代码为：

```
# 代码模板               |   # 你的代码
```

```
import turtle           |   import turtle
```

```
d = 0                    |   d = 0
```

```
for i in range(__1__):  |   for i in range(1):
```

```
    turtle.fd(__2__)    |       turtle.fd(100)
```

```
    turtle.__3__         |    turtle.fd(100 + (i * 3))
```

```
turtle.seth(d)          |   turtle.seth(d)
```

则在提交代码页面输入：

```
print('1', '100', 'fd(100 + (i * 3))')
```

提交后即可以查看得分

 

注：如果有运算符，请在运算符两侧加上空格

习题代码

import turtle

d=0

for i in range(4):

​    turtle.right(90)

​    turtle.circle(50,180)

 

# 5.简单操作题（2）

## 描述

使用字典和列表型变量完成某课程的考勤记录统计，某班有 74 名同学，名单由考生目录下文件 Name.txt 给出，某课程第一次考勤数据由考生目录下文件 1.csv 给出。请求出第一次缺勤同学的名单。

参考代码模板，补充代码完成要求。

 

使用 print 方法按输出示例输出结果，支持自动评阅。

 

## 输入输出示例

|        | 输入   | 输出                                |
| ------ | ------ | ----------------------------------- |
| 示例 1 | 无输入 | 第一次缺勤同学有：张三   李四  王五 |

习题讲解

```
# 从1.csv文件中读取考勤数据with open("file/1.csv","r",encoding = "utf-8") as fo:
```

```
    foR =fo.readlines()
```

```
ls = []for line in foR:
```

```
    line = line.replace("\n","")
```

```
    ls.append(line.split(","))
```

```
# 从name.txt文件中读取所有同学的名单with open("Name.txt","r",encoding = "utf-8") as foName:
```

```
    foNameR = foName.readlines()
```

```
lsAll = []for line in foNameR:
```

```
    line = line.replace("\n","")
```

```
    lsAll.append(line)
```

```
#求出第一次缺勤同学的名单for l in ls:
```

```
    if l[0] in lsAll:
```

```
        lsAll.remove(l[0])
```

```
print("第一次缺勤同学有：",end ="")for l in lsAll:
```

```
    print(l,end=" ")
```

# 6.综合应用题

## 描述

苏格拉底是古希腊著名的思想家、哲学家、教育家、公民陪审员。苏格拉底的部分名言被翻译为中文，其部分内容由 sgld.txt 给出。请参考代码模板，补充代码完成中文分词和统计“人”出现的次数。

 

本题目支持自动评阅。

##  

## 输入输出示例

 

|        | 输入   | 输出   |
| ------ | ------ | ------ |
| 示例 1 | 无输入 | 人:1次 |

习题讲解

```
import jiebawith open("sgld.txt","r",encoding ="utf-8")as f:
```

```
    lssgld = f.readlines()
```

```
 
```

```
fo = open("sgldout.txt","w",encoding ="utf-8")for ls in lssgld:
```

```
    ls =ls.strip()
```

```
    wordlist = list(jieba.cut(ls))
```

```
    fo.writelines("\n".join(wordlist))
```

```
fo.close()
```

 

 

 

 

 

 

 

 

# 1.基本操作题 (1)

 

从键盘输入 3 个数作为三角形的边长，在屏幕上显示输出由这 3 个边长构成三角形的面积（保留 2 位小数）。

请参照代码模板，完善代码。

 

## **输入输出示例**

 

|        | **输入** | **输出** |
| ------ | -------- | -------- |
| 示例 1 | 3,3,3    | 3.90     |

习题讲解

```
a,b,c = eval(input())
```

```
p = (a+b+c)/2
```

```
area = pow(p * (p-a)*(p-b)*(p-c),0.5)print("{:.2f}".format(area))
```

# 2.基本操作题（2）

 

将一个列表中所有的单词首字母转换成大写。

请参照代码模板，完善代码。

 

**输入输出示例** 

|        | **输入**                  | **输出**                      |
| ------ | ------------------------- | ----------------------------- |
| 示例 1 | ["python","is","opening"] | ['Python', 'Is',   'Opening'] |

习题讲解

```
ls = eval(input())
```

```
for i in range(len(ls)):
```

```
    ls[i] = ls[i].capitalize()print(ls)
```

# 3.基本操作题（3）

 

从键盘输入一个列表，计算输出列表元素的均方差。

请参照代码模板，完善代码。本题支持自动评阅。 

 

 

## **输入输出示例**

 

|        | **输入**         | **输出**       |
| ------ | ---------------- | -------------- |
| 示例 1 | [99,98,97,96,95] | 均方差为：1.58 |

习题讲解

```
def mean(numlist):
```

```
    s = 0.0
```

```
    for num in numlist:
```

```
        s = s + num
```

```
    return s/len(numlist)
```

```
def dev(numlist,mean):
```

```
    sdev = 0.0
```

```
    for num in numlist:
```

```
        sdev = sdev + (num - mean)**2
```

```
    return (sdev /(len(numlist)-1) )** 0.5#请输入一个列表：
```

```
ls = eval(input(""))print("均方差为：{:.2f}".format(dev(ls,mean(ls))))
```

# **4.****简单操作题(1）**

 

使用 turtle 库的 turtle.right() 函数和 turtle.circle() 函数绘制一个星星图形，如下图所示。

请参照代码模板，完善代码。

 

 ![img](file:///C:/Users/1234/AppData/Local/Temp/msohtmlclip1/01/clip_image010.png)

\---------------------------------------------------------------

自动评阅说明

 

使用字符串形式输出 ____①____,____②____,____③____中应填代码即可以自动评阅得分

例如，如果代码为：

```
# 代码模板               |   # 你的代码
```

```
import turtle           |   import turtle
```

```
d = 0                   |   d = 0for i in range(__1__):  |   for i in range(1):
```

```
    turtle.fd(__2__)    |       turtle.fd(100)
```

```
    d = __3__           |       d = (i + 100) * 100
```

```
turtle.seth(d)          |   turtle.seth(d)
```

则在提交代码页面输入：

```
print('1', '100', '(i + 100) * 100')
```

提交后即可以查看得分

 

注：如果有运算符，请在运算符两侧加上空格

**习题讲解**

```
import turtlefor i in range(4):
```

```
    turtle.circle(-90,90)
```

```
    turtle.right(180)print(-90,180)
```

# 5.简单操作题（2）

 

用字典和列表型变量完成某课程的考勤记录统计，某班有 74 名同学，名单由考生目录下文件 txt 给出，某课程 10 次考勤数据由考生目录下文件 1.csv，2.csv … 给出。请输出全勤同学的名字。

请参照代码模板，完善代码。

##  

## **输入输出示例**

|        | **输入** | **输出**                             |
| ------ | -------- | ------------------------------------ |
| 示例 1 |          | 全勤同学有：陈恒杰,张冲,蔡冯顺,..... |

习题讲解

```
# 从csv文件中读取考勤数据
```

```
ls = []for i in range(1,11):
```

```
    fo =  open(str(i) +".csv","r",encoding = "utf-8")
```

```
    for line in fo:
```

```
        line = line.replace("\n","")
```

```
        ls.append(line.split(",")[0])        
```

```
    fo.close()
```

```
counts = {}for name in ls:
```

```
    counts[name] = counts.get(name,0) + 1
```

```
items = list(counts.items())print("全勤同学有：",end ="")for i in range(1,74,1):
```

```
    word,count = items[i]
```

```
    if count == 10 :
```

```
        #print("{0:<10}:{1:<5}次".format(word,count))
```

```
        print(word,end =",")
```

# 6.综合应用题

 

苏格拉底是古希腊著名的思想家、哲学家、教育家、公民陪审员。苏格拉底的名言部分被翻译为中文，部分内容分词结果由考生目录下文件 sgldout.txt 给出。对文件 sgldout.txt 进行分析，输出词频排名前五的词 (不包括中文标点符号) 和次数到 sgldstatistics.txt。

参照输出格式如下：
 了：234
 了：234
 了：234
 了：234
 了：234

请参照代码模板，完善代码，通过单机测试运行程序。

 

\-----------------------------------

自动评阅说明

不需要打开（open）写入（writeline）文件，使用 print 输出内容即可自动评阅。

习题讲解

```
import jieba
```

```
fo = open("sgldout.txt","r",encoding ="utf-8")
```

```
words = fo.readlines()
```

```
fo.close()
```

```
 
```

```
sym = "；。，“”： "
```

```
DictWords = {}
```

```
for ls in words:
```

```
    if ls[:-1] not in sym:
```

```
        DictWords[ls[:-1]] = DictWords.get(ls[:-1], 0) + 1
```

```
        L = list(DictWords.items())
```

```
        L.sort(key = lambda s:s[1],reverse=True)
```

```
# 输出到文件
```

```
fo = open("sgldstatistics.txt", "w", encoding="utf-8")      for i in range(5):
```

```
    fo.writeline(L[i][0] + ":" + str(L[i][1]) + "\n")
```

```
fo.close()
```

```
# print 输出for i in range(5):
```

```
    print(L[i][0] + ":" + str(L[i][1]))
```

 

 

 

 

 

 

# 1.基本操作题 (1)

 

从键盘输入 3 个数作为三角形的边长，在屏幕上显示输出由这 3 个边长构成三角形的面积（保留 2 位小数）。

请参照代码模板，完善代码。

 

## **输入输出示例**

 

|        | **输入** | **输出** |
| ------ | -------- | -------- |
| 示例 1 | 3,3,3    | 3.90     |

习题讲解

```
a,b,c = eval(input())
```

```
p = (a+b+c)/2
```

```
area = pow(p * (p-a)*(p-b)*(p-c),0.5)print("{:.2f}".format(area))
```

# 2.基本操作题（2）

 

将一个列表中所有的单词首字母转换成大写。

请参照代码模板，完善代码。

 

**输入输出示例** 

|        | **输入**                  | **输出**                      |
| ------ | ------------------------- | ----------------------------- |
| 示例 1 | ["python","is","opening"] | ['Python', 'Is',   'Opening'] |

习题讲解

```
ls = eval(input())
```

```
for i in range(len(ls)):
```

```
    ls[i] = ls[i].capitalize()print(ls)
```

# 3.基本操作题（3）

 

从键盘输入一个列表，计算输出列表元素的均方差。

请参照代码模板，完善代码。本题支持自动评阅。 

 

 

## **输入输出示例**

 

|        | **输入**         | **输出**       |
| ------ | ---------------- | -------------- |
| 示例 1 | [99,98,97,96,95] | 均方差为：1.58 |

习题讲解

```
def mean(numlist):
```

```
    s = 0.0
```

```
    for num in numlist:
```

```
        s = s + num
```

```
    return s/len(numlist)
```

```
def dev(numlist,mean):
```

```
    sdev = 0.0
```

```
    for num in numlist:
```

```
        sdev = sdev + (num - mean)**2
```

```
    return (sdev /(len(numlist)-1) )** 0.5#请输入一个列表：
```

```
ls = eval(input(""))print("均方差为：{:.2f}".format(dev(ls,mean(ls))))
```

# **4.****简单操作题(1）**

 

使用 turtle 库的 turtle.right() 函数和 turtle.circle() 函数绘制一个星星图形，如下图所示。

请参照代码模板，完善代码。

 

 ![img](file:///C:/Users/1234/AppData/Local/Temp/msohtmlclip1/01/clip_image010.png)

\---------------------------------------------------------------

自动评阅说明

 

使用字符串形式输出 ____①____,____②____,____③____中应填代码即可以自动评阅得分

例如，如果代码为：

```
# 代码模板               |   # 你的代码
```

```
import turtle           |   import turtle
```

```
d = 0                   |   d = 0for i in range(__1__):  |   for i in range(1):
```

```
    turtle.fd(__2__)    |       turtle.fd(100)
```

```
    d = __3__           |       d = (i + 100) * 100
```

```
turtle.seth(d)          |   turtle.seth(d)
```

则在提交代码页面输入：

```
print('1', '100', '(i + 100) * 100')
```

提交后即可以查看得分

 

注：如果有运算符，请在运算符两侧加上空格

**习题讲解**

```
import turtlefor i in range(4):
```

```
    turtle.circle(-90,90)
```

```
    turtle.right(180)print(-90,180)
```

# 5.简单操作题（2）

 

用字典和列表型变量完成某课程的考勤记录统计，某班有 74 名同学，名单由考生目录下文件 txt 给出，某课程 10 次考勤数据由考生目录下文件 1.csv，2.csv … 给出。请输出全勤同学的名字。

请参照代码模板，完善代码。

##  

## **输入输出示例**

|        | **输入** | **输出**                             |
| ------ | -------- | ------------------------------------ |
| 示例 1 |          | 全勤同学有：陈恒杰,张冲,蔡冯顺,..... |

习题讲解

```
# 从csv文件中读取考勤数据
```

```
ls = []for i in range(1,11):
```

```
    fo =  open(str(i) +".csv","r",encoding = "utf-8")
```

```
    for line in fo:
```

```
        line = line.replace("\n","")
```

```
        ls.append(line.split(",")[0])        
```

```
    fo.close()
```

```
counts = {}for name in ls:
```

```
    counts[name] = counts.get(name,0) + 1
```

```
items = list(counts.items())print("全勤同学有：",end ="")for i in range(1,74,1):
```

```
    word,count = items[i]
```

```
    if count == 10 :
```

```
        #print("{0:<10}:{1:<5}次".format(word,count))
```

```
        print(word,end =",")
```

# 6.综合应用题

 

苏格拉底是古希腊著名的思想家、哲学家、教育家、公民陪审员。苏格拉底的名言部分被翻译为中文，部分内容分词结果由考生目录下文件 sgldout.txt 给出。对文件 sgldout.txt 进行分析，输出词频排名前五的词 (不包括中文标点符号) 和次数到 sgldstatistics.txt。

参照输出格式如下：
 了：234
 了：234
 了：234
 了：234
 了：234

请参照代码模板，完善代码，通过单机测试运行程序。

 

\-----------------------------------

自动评阅说明

不需要打开（open）写入（writeline）文件，使用 print 输出内容即可自动评阅。

习题讲解

```
import jieba
```

```
fo = open("sgldout.txt","r",encoding ="utf-8")
```

```
words = fo.readlines()
```

```
fo.close()
```

```
 
```

```
sym = "；。，“”： "
```

```
DictWords = {}
```

```
for ls in words:
```

```
    if ls[:-1] not in sym:
```

```
        DictWords[ls[:-1]] = DictWords.get(ls[:-1], 0) + 1
```

```
        L = list(DictWords.items())
```

```
        L.sort(key = lambda s:s[1],reverse=True)
```

```
# 输出到文件
```

```
fo = open("sgldstatistics.txt", "w", encoding="utf-8")      for i in range(5):
```

```
    fo.writeline(L[i][0] + ":" + str(L[i][1]) + "\n")
```

```
fo.close()
```

```
# print 输出for i in range(5):
```

```
    print(L[i][0] + ":" + str(L[i][1]))
```

 

 

 

# **1.****101**

 

参照代码模板完善代码，实现下述功能。从键盘输入一个整数和一个字符，以逗号隔开，在屏幕上显示输出一条信息。

示例如下：

**输入**

10,@

**输出**

@@@@@@@@@@ 10 @@@@@@@@@@

 

## **输入输出示例**

|        | 输入 | 输出                     |
| ------ | ---- | ------------------------ |
| 示例 1 | 10,@ | @@@@@@@@@@ 10 @@@@@@@@@@ |

习题讲解

答案:

```
a,x = input().split(',') # 请输入1个整数和1个符号，逗号隔开print(x*eval(a),a,x*eval(a))
```

要点：

\1. 输入两个值组成的字符串，要用split（）分割开

2.同时赋值给两个变量

3.利用eval得到数值做运算，给字符做乘法，得到需要的格式

# 2.**102**

 

参照代码模板完善代码，实现下述功能。从键盘输入一个由 1 和 0 组成的二进制字符串 s，转换为八进制数输出显示在屏幕上，示例如下：

**输入：**

1100

**输出：**

转换成八进制数是：14

 

## **输入输出示例**

|        | 输入 | 输出 |
| ------ | ---- | ---- |
| 示例 1 | 1100 | 14   |

习题讲解

答案：

```
s = input() # 请输入一个由1和0组成的二进制数字串
```

```
d = 0while s:
```

```
    d = d*2 + (ord(s[0]) -ord('0'))
```

```
    s = s[1:]print("转换成八进制数是：{:o}".format(d))
```

```
 
```

要点：

1.print和format的格式用法，字符串的内置处理函数，切片

2.理解数据类型及其转换

# 3.**103**

 

参照代码模板完善代码，实现下述功能。文件 data.txt 文件中有多行数据，打开文件，读取数据，并将其转化为列表。统计读取的数据，计算每一行的总和、平均值，在屏幕上输出结果。

文件内容示例如下：

Chinese: 80,Math:85,English:92, Physical: 81,Art:85,Chemical:88

屏幕输出结果示例如下：

总和是：511.0，平均值是：85.17

 

## **输入输出示例**

|        | **输入**               | **输出**                       |
| ------ | ---------------------- | ------------------------------ |
| 示例 1 | 从文件 data.txt 中读取 | 总和是：511.0，平均值是：85.17 |

习题讲解

答案：

```
fi = open("data.txt", 'r')
```

```
for l in fi:
```

```
    l = l.split(',')
```

```
    s = 0.0
```

```
    n = len(l)
```

```
    for cours in l:
```

```
        items  = cours.split(':')
```

```
        s += eval(items[1])
```

```
    print("总和是：{}，平均值是：{:.2f}".format(s,s/n))
```

```
fi.close()
```

# 4.**201**

 

参照代码模板完善代码，实现下述功能，不得修改其它代码。使用 turtle 库的 turtle.circle() 函数和 turtle.seth() 函数绘制同心圆套圈，最小的圆圈半径为 10 像素，不同圆圈之间的半径差是 40 像素，效果如下图所示。 

 

 ![img](file:///C:/Users/1234/AppData/Local/Temp/msohtmlclip1/01/clip_image011.jpg)

\---------------------------------------------------------------

自动评阅说明

 

使用字符串形式输出 ____①____,____②____,____③____中应填代码即可以自动评阅得分

例如，如果代码为：

```
# 代码模板               |   # 你的代码import turtle           |   import turtle
```

```
d = 0                   |   d = 0for i in range(__1__):  |   for i in range(1):
```

```
    turtle.fd(__2__)    |       turtle.fd(100)
```

```
    turtle.__3__        |    turtle.fd(100 + (i * 3))
```

```
turtle.seth(d)          |   turtle.seth(d)
```

则在提交代码页面输入：

```
print('1', '100', 'fd(100 + (i * 3))')
```

提交后即可以查看得分

 

注：如果有运算符，请在运算符两侧加上空格

习题讲解

答案：

```
# 请在______处填写一行代码# 请不要修改其他代码
```

```
 
```

```
import turtle
```

```
r = 10
```

```
dr = 40
```

```
head = 90for i  in range (4):
```

```
    turtle.pendown()
```

```
    turtle.circle(r)
```

```
    r +=  dr
```

```
    turtle.penup()
```

```
    turtle.seth(-head)
```

```
    turtle.fd(dr)
```

```
    turtle.seth(0)
```

```
turtle.done()
```

要点：

\1. 同心圆主要问题是要挪动画笔，用到 pendown 和 penup

\2. 用循环来处理重画的个数

# 5.**202**

 

参照代码模板完善代码，实现下述功能。从键盘输入一个中文字符串变量 s，内部包含中文标点符号。

 

**问题****1****：**（8分）用 jieba 分词，计算字符串 s 中的中文词汇个数，不包括中文标点符号。显示输出分词后的结果，用”/ ”分隔，以及中文词汇个数。示例如下：

输入：

工业互联网”实施的方式是通过通信、控制和计算技术的交叉应用，建造一个信息物理系统，促进物理系统和数字系统的融合。

输出：

工业/ 互联网/实施/ 的/ 方式/是/ 通过/ 通信/控制/ 和/ 计算技术/的/ 交叉/ 应用/建造/ 一个/ 信息/物理/ 系统/ 促进/物理/ 系统/ 和/数字/ 系统/ 的/融合/

中文词语数是：27

 

**问题****2****：**（7分）在问题1的基础上，统计分词后的词汇出现的次数，用字典结构保存。显示输出每个词汇出现的次数，以及出现次数最多的词汇。如果有多个词汇出现次数一样多，都要显示出来。示例如下：

继续输出：

控制: 1

物理: 2

通信: 1

交叉: 1

互联网: 1

和: 2

是: 1

计算技术: 1

一个: 1

的: 3

数字: 1

促进: 1

信息: 1

方式: 1

建造: 1

应用: 1

系统: 3

通过: 1

实施: 1

融合: 1

工业: 1

出现最多的词是（的 系统）：3 次

 

## **输入输出示例**

|        | 输入                                                         | 输出                                                         |
| ------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 问题 1 | `“工业互联网”实施的方式是通过通信、控制和计算技术的交叉应用，建造一个信息物理系统，促进物理系统和数字系统的融合。` | 中文词语数是：27                                             |
| 问题2  |                                                              | 控制: 1   物理: 2   通信: 1   交叉: 1   互联网: 1   和: 2   是: 1   计算技术: 1   一个: 1   的: 3   数字: 1   促进: 1   信息: 1   方式: 1   建造: 1   应用: 1   系统: 3   通过: 1   实施: 1   融合: 1   工业: 1   出现最多的词是（的 系统）：3 次 |

习题讲解

答案：

```
#请在.....处填写多行表达式或语句#可以修改其他代码
```

```
 
```

```
import jieba
```

```
# s = '“工业互联网”实施的方式是通过通信、控制和计算技术的交叉应用，建造一个信息物理系统，促进物理系统和数字系统的融合。'
```

```
s = input("请输入一个中文字符串，包含逗号和句号：")
```

```
s = s.replace('，','').replace('。','').replace('、','').replace('“','').replace('”','')
```

```
k=jieba.lcut(s)
```

```
d1 = {}
```

```
maxc = 0
```

```
wo = ''for i in k:
```

```
   print(i, end= "/ ")
```

```
   d1[i] = d1.get(i,0) + 1print("\n中文词语数是：{}".format(len(k)))
```

```
for key in d1:
```

```
    if maxc < d1[key]:
```

```
        wo = key
```

```
        maxc = d1[key]
```

```
    elif maxc == d1[key]:
```

```
        wo += ' ' + key
```

```
    print("{}: {}".format(key,d1[key]))
```

```
print("出现最多的词是（{}）：{} 次".format(wo, maxc))
```

要点：

\1. 用 jieba 分词处理词汇统计

\2. 要处理掉输入的各种标点符号，用到replace（）

\3. 用字典保存各个词出现次数

\4. 要遍历字典的键值对，找到最大的值，及其对应的键

# 6.**301**

 

一个人脸识别研究小组对若干名学生做了人脸识别的测试，将测试结果与被测试者的现场照片组合成文件名，写到了一个文件 dir_100.txt 中，每行是一个文件名的信息，示例如下：

['1709020621', '0']_116.jpg

['1709020621']_115.jpg

['1770603107', '1770603105', '0', '0']_1273.jpg

文件名各部分含义如下：

[‘识别出学号1’，‘ 识别出学号2’,…,‘0表示检测到人脸但未识别出人’]_照片的顺序编号.jpg

测试过程中，一个学生可能被抓拍到多张照片中，所以会在多个文件名中被识别，学号出现在多个文件名中；一张照片中，可能有多个人脸，但有些分辨率不够而识别不出来，文件名位置用‘0’代替学号。

使用字典和列表型变量进行数据分析，最终获取实际参加测试的学生人数和人均被测次数。

（1）读入 dir_300.txt 文件的内容，处理每一行文件名信息。将文件名中的学号内容以列表形式保存，丢掉‘0’的字串；照片的顺序编号作为字典的关键字，学号列表作为字典的值。转换后，显示字典中的每行信息，示例如下：

116:1709020621

115:1709020621

117:1709020621

1273: 1770603107,1770603105

 

（2）将该字典中的学号提取出来，构造另一个字典，以学号作为字典的关键字，累计学号出现的次数，将累计值作为字典的值。格式示例如下：

1709020621:3

1770603107:1

1770603105:1

（3）累计字典中关键字的个数，即为实际参加测试的学生人数；累加每个关键字对应的值，即为所有学号测试次数；与实际测试人数之比，即为人均被测次数。将实际参加测试人数和人均被测次数显示输出在屏幕上，示例如下：

实际参加测试的人数是：1024

人均被测次数是：2.7

 

## **输入输出示例**

|        | 输入                 | 输出                                             |
| ------ | -------------------- | ------------------------------------------------ |
| 问题 1 | 从文件dir_50.txt读入 | 实际参加测试的人数是：1024   人均被测次数是：2.7 |

 

自动评阅提示：输出最终结果即可，中间结果不需要输出

习题讲解

答案：

```
#P301-1.py#请在.....处填写多行表达式或语句#可以修改其他代码
```

```
 
```

```
picd = {}
```

```
numd = {}
```

```
fi = open("dir_50.txt",'r')for l in fi:
```

```
    l=l.replace('\n','').split('_')##    print(l[1])
```

```
    if l[0] != '' :
```

```
        lkey,lvalue = l[1][:-4],eval(l[0])
```

```
        lval = []
```

```
        for v in lvalue:
```

```
            if v != '0':
```

```
                lval.append(v)
```

```
        if lval:
```

```
            lv= ','.join(lval)
```

```
            print("{}:{}".format( lkey,lv))
```

```
            picd[lkey] = lv
```

```
 
```

```
fi.close()
```

```
idd = {}for key in picd:
```

```
    ids = picd[key].split(',')
```

```
    for num in ids:
```

```
        idd[num] = idd.get(num,0) +1
```

```
            #print(num,idd[num])
```

```
s = 0for key in idd:
```

```
    s += int(idd[key])
```

```
    # print("{}:{}".format(key, idd[key]))
```

```
count = len(idd)print("实际参加测试的人数是：",count)print("人均被测次数是：{:.1f}".format(s/count))
```

要点：

\1. 这是一个实际问题，解决问题的方法有实际的推广意义。问题的关键是要完成数据提取，然后才是分析统计

\2. 文件的读写，打开关闭是基础

\3. 读入文件要进行字符串的处理，按行，分割成列表

\3. 数据提取：先取得文件里的有效内容，转换成列表，利用列表的切片，提取出照片编号和学号，放到字典picd里

\4. 第二步数据分析，需要先从字典里把学号提取出来，为了便于统计每个学号被测的次数，再建一个字典idd

\5.  idd字典的键是学号，所以字典的len就是参加测试的人数

\6. 为了计算平均测试次数，需要累计每个学号被测的次数，最后除以参加测试人数就得到结果

 

 

 

 

 

# 1.101

 

## **描述**

参照代码模板完善代码，实现下述功能。输入一个字符串，其中的字符由（英文）逗号隔开，编程将所有字符连成一个字符串，输出显示在屏幕上。

 

## **输入输出示例**

 

|        | **输入**  | **输出** |
| ------ | --------- | -------- |
| 示例 1 | 1,2,3,4,5 | 12345    |

习题讲解

答案：

ls= input("请输入一个字符串，由逗号隔开每个字符:").split(',')（1）

print(''.join(ls))（2）

要点：

\1. 题目要求输入的字符用逗号隔开，所以，需要用到split(',')来从字符串里提取所输入的字符

\2. 经过split（）函数的字符串，返回的是列表

\3. 字符串有个操作函数是 str.join（ls）,可以把列表里的各个元素，用str的内容连接起来。本题利用了空字符串‘’，来调用这个函数，因此，达到了所想要的效果：将带有逗号的字符串变换成了没有逗号的字符串。

\4. 有一个不可忽视的地方是join（）函数的括号里的参数是列表，如果忘了这一点，会犯错

\5. 这个功能利用好了，可以拓展，解决其他的问题。

# 2.**102**

 

## **描述**

参照代码模板完善代码，实现下述功能。

 

有一个列表 studs 如下：

```
studs= [{'sid':'103','Chinese': 90,'Math':95,'English':92},{'sid':'101','Chinese': 80,'Math':85,'English':82},{'sid':'102','Chinese': 70,'Math':75,'English':72}]
```

将列表 studs 的数据内容提取出来，放到一个字典 scores 里，在屏幕上按学号从小到大的顺序显示输出 scores 的内容。内容示例如下：

101:[85, 82, 80]

102:[75, 72, 70]

103:[95, 92, 90]

 

 

## **输入输出示例**

 

|        | 输入 | 输出                                                   |
| ------ | ---- | ------------------------------------------------------ |
| 示例 1 | 无   | 101:[85, 82, 80]   102:[75, 72, 70]   103:[95, 92, 90] |

习题讲解

答案：

```
studs= [{'sid':'103','Chinese': 90,'Math':95,'English':92},{'sid':'101','Chinese': 80,'Math':85,'English':82},{'sid':'102','Chinese': 70,'Math':75,'English':72}]
```

```
 
```

```
scores = {}
```

```
for stud in studs:
```

```
    sv = stud.items() （1）
```

```
    v = []
```

```
    for it in sv:
```

```
        if it[0] =='sid':
```

```
            k = it[1]
```

```
        else:
```

```
            v.append(it[1])
```

```
    scores[k]  = v（2）
```

```
# print(scores)
```

```
 
```

```
so = list(scores.items())（3）
```

```
so.sort(key = lambda x:x[0],reverse = False)
```

```
for l in so:
```

```
    print('{}:{}'.format(l[0],l[1]))
```

 

要点：

\1. 字典作为元素，定义在列表里，用列表的遍历就可以从中提取出来

\2. 提取出来的元素直接就是字典，因此可以用 items（）直接获取，形成键值对对象集合 sv；

\3. 对键值对对象集合sv遍历，就可以以元组it的方式访问其中的每一对键值对，sv = stud.items()，是第一个空的答案；

\4. 题目要求提取学生的学号，所以需要比较键it[0]是否是'sid'，是则将学号it[1]提取出来作为新的字典scores的键k；不是则将成绩提取出来作为新字典scores的值v；

\5. 由于课程是多门，因此新字典scores的值v需要以列表的方式，保存各门课程的成绩，所以在不是的情况下，新字典scores的值v是利用append（it[1]）的方式，追加到列表的后面；

\6. 对v做append操作，必须要事先定义v是一个空列表；因此需要在对每一条旧字典stud的键值对信息做处理的for it in sv:语句之前，用v = []初始化v为一个空列表；

\7. 经过对一条字典stud的处理，就形成一对k和v，所以接下来是给新字典scores添加一条键值对，scores[k]  = v，是第二个空的答案

\8. 经过对全部的studs列表里的各条字典处理完之后，新的scores字典就全部生成。

\9. 题目要求按学号从小到大的顺序输出学号和成绩，所以需要对字典的键值对内容items（）提取到列表so里，此处是第三个空的答案：so = list(scores.items())

\10. 用Lambda函数进行排序。这个不在考试范围里，所以代码模板直接给出语句；

\11. 对排好序的列表输出每组列表，这个直接给出语句，不再赘述。

# 3.**103**

 

## **描述**

参照代码模板完善代码，实现下述功能。

从键盘输入一个用于填充的图符，一个字符串，一个要显示的字符串的总长度；编程将输入的字符串，居中输出显示在屏幕上，用填充图符补齐到输入的总长度。如果总长度处输入的不是正整数，则提示请输入一个正整数，并重新提示输入，直至输入正整数。

 

输入：

请输入填充符号:@

请输入要显示的字符串：qq

请输入字符串总长度：r

请输入一个正整数

请输入字符串总长度：3.4

请输入一个正整数

请输入字符串总长度：4

输出：

@qq@

 

## **输入输出示例**

|        | 输入       | 输出 |
| ------ | ---------- | ---- |
| 示例 1 | @   qq   4 | @qq@ |

习题讲解

答案：

```
#请在____处填写一行代码#请在… 处填写多行代码#不要修改已给出代码
```

```
 
```

```
a = input()  # 请输入填充符号
```

```
 
```

```
c = input()  # 请输入要显示的字符串
```

```
 
```

```
flag = 1   (1)
```

```
while flag:
```

```
   try:
```

```
       b = eval(input()) # 请输入字符串总长度
```

```
   except:
```

```
       flag = 1
```

```
       print("请输入一个正整数")
```

```
   else:
```

```
       if type(b)== int （2）and b>0:
```

```
            flag = 0
```

```
       else:
```

```
            flag = 1
```

```
            print("请输入一个正整数")
```

```
print('{0:{1}^{2}}'（3）.format(c,a,b))
```

# 4.**201**

 

## **描述**

参照代码模板完善代码，实现下述功能，**不得修改其它代码。**使用 turtle 库的 turtle.fd() 函数和 turtle.seth() 函数绘制螺旋状的正方形，正方形边长从 1 像素开始，第一条边从 0 度方向开始，效果如下图所示。

 ![img](file:///C:/Users/1234/AppData/Local/Temp/msohtmlclip1/01/clip_image013.jpg)

\---------------------------------------------------------------

自动评阅说明

 

使用字符串形式输出 ____①____,____②____,____③____中应填代码即可以自动评阅得分

例如，如果代码为：

```
# 代码模板               |   # 你的代码import turtle           |   import turtle
```

```
d = 0                   |   d = 0for i in range(__1__):  |   for i in range(1):
```

```
    turtle.fd(__2__)    |       turtle.fd(100)
```

```
    d = __3__           |       d = (i + 100) * 100
```

```
turtle.seth(d)          |   turtle.seth(d)
```

则在提交代码页面输入：

```
print('1', '100', '(i + 100) * 100')
```

提交后即可以查看得分

 

注：如果有运算符，请在运算符两侧加上空格

习题讲解

答案：

```
import turtle
```

```
 
```

```
d = 0
```

```
k = 1
```

```
for j in range(10):
```

```
   for i in range(4):
```

```
       turtle.fd(k（1）)
```

```
       d += 91
```

```
       turtle.seth(d（2）)
```

```
       k += 2_(3)
```

```
 
```

```
turtle.done()
```

 

要点：

\1. 降低了难度，让填写的都是最简单的

# 5.**202**

## **描述**

参照代码模板完善代码，实现下述功能，**可以修改其它代码。**附件文件 question.txt 中有一道 Python 选择题，第 1 行的第 1 个数据为题号，后续的 4 行是 4 个选项。示例内容如下：

\3. 以下关于字典类型的描述，错误的是：
 A. 字典类型中的数据可以进行分片和合并操作 
 B. 字典类型是一种无序的对象集合，通过键来存取
 C. 字典类型可以在原来的变量上增加或缩短
 D. 字典类型可以包含列表和其他数据类型，支持嵌套的字典

##  

读取其中的内容，提取题干和四个选项的内容，利用 jieba 分词并统计出现频率最高的 3 个词，其中要删除以下的常用字和符号“的 ，:：可以是和中以下B”，作为该题目的主题标签，显示输出在屏幕上。

 

## **输入输出示例**

|        | 输入                               | 输出                                       |
| ------ | ---------------------------------- | ------------------------------------------ |
| 示例 1 | 从文件 question.txt 中读取所有内容 | 第3题的主题是：   类型:5   集合:2   组合:2 |

习题讲解

答案：

```
import jieba
```

```
fi = open("question.txt",'r')
```

```
con = ''
```

```
num = 0for l in fi:
```

```
    l=l.replace('\n','').strip().split('.')
```

```
    # print(l)
```

```
    try:
```

```
        ft = eval(l[0])
```

```
    except:
```

```
        pass
```

```
    else:
```

```
        num = ft
```

```
    con += l[1]print('第{}题的主题是：'.format(num))
```

```
conls = jieba.lcut(con)dict = {}for word in conls:
```

```
    dict[word] = dict.get(word, 0) + 1
```

```
dictls = list(dict.items())
```

```
dictls.sort(key = lambda x:x[1], reverse = True)
```

```
k = 0for it in dictls:
```

```
    if it[0] in '的 ，:：可以是和中以下B':
```

```
        continue
```

```
    else:
```

```
        if k == 3:
```

```
            break
```

```
        else:
```

```
            print('{}:{}'.format(it[0],it[1]))
```

```
            k += 1
```

```
fi.close()
```

 

**要点：**

**1.** **导入****jieba****库，使用****lcut****分词，返回列表****conls**

**2.** **打开文件，读文件，关闭文件**

**3.** **按行从文件里读，每一行是一个字符串，用****strip****和****split****处理成列表，因为要识别题号，还要提取题目和选项的内容，所以要按照****'.'****分隔来提取，分别返回题号和选项号作为列表****l****的第****0****个字段，后面的内容是列表****l****的第一个字段；**

**4.** **为了识别题号，要利用****eval****，并逆向利用****try-except****结构捕捉第一个字段是整数的字段，把题号提取出来放到****num****里面，把其他的内容都用字符串加法，拼成一个大字符串****con**

**5.** **给出第一句显示：****print('****第****{}****题的主题是：****'.format(num))**

**6.** **接下来处理****con****，提取整个题干的主题词：**

**7.** **用****jieba****分词，然后用字典****dict****来保存没个词出现的次数。一种惯用法是****for word in conls:     dict[word] = dict.get(word, 0) + 1 8.****统计出来的词以及词频，需要排序找到最大三个词频，此时需要把字典的键值对****items****（）提取出来形成列表****dictls****，并利用列表排序和****lambda****函数。得到排好序的****dictls**

**9.****显示的时候，遍历字典的每个键，要避开那些没有意义的词，题目里给出了剔除列表，拿过来判断一下，如果是没用的词，就直接跳过，循环下一个，用****continue****；**

**10.** **如果是有意义的词，题目要求显示三个最高词频的词，因为中间有跳过的词，不能直接只循环排序靠前的****3****个词。要对显示了的词做计数，计够三个，就中断循环，所以要用****break****；**

**11.** **这里用了嵌套的分支结构，在第一个分支里是有意义的词，在第二个分支里是计数不到三个，才做显示输出的语句，显示完了，要把计数器****k****加一。**

**12.****程序最后记着关闭文件。**

# 6.**301**

 

## **描述**

老王的血压有些高，医生让家属给老王测血压。老王的女儿记录了一段时间的血压测量值，在文件 xueyajilu.txt 中，内容示例如下：

2018/7/2 6:00,140,82,136,90,69
 2018/7/2 15:28,154,88,155,85,63
 2018/7/3 6:30,131,82,139,74,61
 2018/7/3  16:49,145,84,139,85,73
 2018/7/4  5:03,152,87,131,85,63

文件内各部分含义如下：

测量时间,左臂高压,左臂低压,右臂高压,右臂低压,心率

 

参照代码模板完善代码，实现下述功能，可以修改给定代码。

（1）使用字典和列表类型进行数据分析，获取老王的

·        左臂和右臂的血压平均值

·        左臂和右臂的高压最高值、低压最高值

·        左臂和右臂的高/低压差平均值

·        心率的平均值

给出左臂和右臂血压情况的对比表，输出到屏幕上，请注意每行三列对齐。示例如下：

![img](file:///C:/Users/1234/AppData/Local/Temp/msohtmlclip1/01/clip_image015.png)

 

**（****2****）**上述显示的五个项目，如果左臂有大于 50% 的项目高于右臂，则输出“结论：左臂血压偏高”；如果等于 50% 的项目高于右臂，则输出“结论：左臂血压与右臂血压相当”；如果小于 50% 的项目高于右臂，则输出“结论：右臂血压偏高”。示例如下：

结论：左臂血压偏高, 心率的平均值为66

(注意：此处为格式示例，实际数据与此不同）

 

## **输入输出示例**

 

|        | 输入                        | 输出                                                         |
| ------ | --------------------------- | ------------------------------------------------------------ |
| 示例 1 | 读取文件 xueyajilu.txt 内容 | ![img](file:///C:/Users/1234/AppData/Local/Temp/msohtmlclip1/01/clip_image016.png)   结论：左臂血压偏高, 心率的平均值为66 |

习题讲解

答案：

```
fi = open("xueyajilu.txt",'r')
```

```
jl = [[],[],[],[],[]]   # 1:zb_h, zb_l,yb_h,yb_l
```

```
zyc = []
```

```
yyc = []
```

```
xl  = []for l in fi:
```

```
    lls=l.replace('\n','').strip().split(',')
```

```
    for i in range(1,5):
```

```
        jl[i].append(eval(lls[i]))
```

```
    zyc.append(eval(lls[1])-eval(lls[2]))
```

```
    yyc.append(eval(lls[3])-eval(lls[4]))
```

```
    xl.append(eval(lls[5]))
```

```
fi.close()
```

```
 
```

```
cnt = len(xl)
```

```
res = []
```

```
res.append(list(("高压最大值",max(jl[1]),max(jl[3]))))
```

```
res.append(list(("低压最大值",max(jl[2]),max(jl[4]))))
```

```
res.append(list(("压差平均值",sum(zyc)//cnt,sum(yyc)//cnt)))
```

```
res.append(list(("高压平均值",sum(jl[1])//cnt,sum(jl[3])//cnt)))
```

```
res.append(list(("低压平均值",sum(jl[2])//cnt,sum(jl[4])//cnt)))
```

```
res.append(list(("心率平均值",sum(xl)//cnt,0)))
```

```
 
```

```
zbg = 0
```

```
ybg = 0print('{:<10}{:<10}{:<10}'.format("对比项", "左臂", "右臂"))for r in range(len(res)-1):
```

```
    print('{:<10}{:<10}{:<10}'.format(res[r][0],res[r][1],res[r][2]))
```

```
    if res[r][1]> res[r][2]:
```

```
        zbg += 1
```

```
    else:
```

```
        ybg += 1
```

```
if zbg > ybg:
```

```
    print('结论：左臂血压偏高',end ='')elif zbg == ybg:
```

```
    print('结论：左臂血压与右臂血压相当',end ='')else:
```

```
    print('结论：右臂血压偏高',end ='')print(', 心率的平均值为{}'.format(res[5][1]))
```

```
 
```

```
输出结果：
```

```
 
```

```
对比项     左臂      右臂 
```

```
高压最大值  163      155 
```

```
低压最大值  93       90 
```

```
压差平均值  61       57 
```

```
高压平均值  146      140 
```

```
低压平均值  85       82 
```

```
结论：左臂血压偏高, 心率的平均值为66
```

```
要点：

1. 这道题的关键问题是解决对行数据按照列的方式来处理

2.参考答案给出的是一般思路，把文件里读出来的数据分别按列的方式，拷贝到一维列表中去，对一维列表进行各种max，min，sum，len操作

4.数据处理的逻辑并不复杂，这里不赘述。

5.其次要解决的问题，是当列数有些多的时候，程序看起来很冗余，需要做一些优化合并；

6.答案里给出的方案是前四个计算公式类似的，放到一个二维列表里，加个循环结构，就可以把四条语句缩成一条。

7.第三个问题，显示输出要求像表格一样输出，又要比较高效率，就引入了一个二维列表，把要输出的行头和内容，变成列表，再加到二维列表中去

8.最后的显示就变得很容易，一个循环就搞定了。

9.最后的问题，是要对输出的二维表格数据作统计、比对、下结论。比较好的方法是输出的时候，顺便做计数；

10. 显示输出结论的时候，遇到一个小问题，要在做比对后的不同的结论后面，追加一条相同的心率的平均值，还不能换行；解决的方法就是用end=''，然后在最后加一句print心率的结果。

11. 当然可以在每条结论的后面，都重复的写一句心率的结果，虽然最后的结果是一样的，但代码有冗余。

如果把咱们写程序，比喻成女娲造人，冗余的程序就像胖子，而高效简洁的程序就像美女，咱们还是要追求造出美女，而不是胖子
```

 

 

 

# **综合应用题**

参照代码模板完善代码，实现下述功能。

文件ngchina.html保持了网页源代码，请将该页面中图片的URL提取出来,并输出所有图像的URL。

习题讲解

```
#P301
```

```
#读取HTML文件内容def getHTMLlines(htmlpath):
```

```
    f = open(htmlpath,"r",encoding = 'utf-8')
```

```
    ls = f.readlines()
```

```
    f.close()
```

```
    return ls
```

```
#用于解析文件并提取图像的URLdef extractImageUrls(htmllist):
```

```
    urls = []
```

```
    for line in htmllist:
```

```
        if 'img' in line:
```

```
            url = line.split('src=')[-1].split('"')[1]
```

```
            if 'http' in url:
```

```
                urls.append(url)
```

```
    return urls
```

```
#将获取的链接输出到屏幕上def showResults(urls):
```

```
    count = 1
```

```
    for url in urls:
```

```
        print("第{:2}个URL:{}".format(count,url))
```

```
        count += 1
```

```
# 主程序：1 读取文件；2 解析并提取其中的图片链接；3 输出提取结果到屏幕def main():
```

```
    inputfile = "ngchina.html"
```

```
    htmllines = getHTMLlines(inputfile)
```

```
    imageUrls = extractImageUrls(htmllines)
```

```
    showResults(imageUrls)
```

```
    
```

```
main()
```

 

# **基本操作题（****1****）**

从键盘输入一个整数，在屏幕上显示输出该整数Python语言十六进制、八进制、二进制表示形式。本题支持OJ。

 

 

## **输入输出示例**

 

|        | 输入 | 输出                 |
| ------ | ---- | -------------------- |
| 示例 1 | 100  | 0x64,0o144,0b1100100 |

习题讲解

```
#在_____上填写一行代码#请输入一个十进制数
```

```
Tempstr = eval(input())print("0x{0:x},0o{0:o},0b{0:b}".format(Tempstr))
```

# **基本操作题（****3****）**

参照代码模板完善代码，实现下述功能统。

输入字符串，使用中文分词库输出精确模式的中文分词结果。   

## **输入输出示例**

 

|        | 输入                                                         | 输出                                                         |
| ------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 示例 1 | 计算机程序只能解决计算问题，不能解决诸如“”人类生命的意义”这样的非计算问题。 | **['****计算机程序****', '****只能****', '****解决****', '****计算****', '****问题****', '****，****', '****不能****', '****解决****', '****诸如****', '“', '”', '****人类****', '****生命****', '****的****', '****意义****', '”', '****这样****', '****的****', '****非****', '****计算****', '****问题****', '****。****']** |

习题讲解

```
import jieba
```

```
Tempstr = input()
```

```
ls = jieba.lcut(Tempstr)print(ls)
```

# **基本操作题（****3****）**

##  

参照代码模板完善代码，实现下述功能。

 某自然数除它本身之外的所有因子之和等于该数，则该数被称为完数。请输出1000以内的完数。本题支持OJ。

 

 

## **输入输出示例**

 

|        | 输入 | 输出                                                         |
| ------ | ---- | ------------------------------------------------------------ |
| 示例 1 | 无   | `说明：每行显示一个完数（本行不需要在代码中输出）``*``*``* ` |

习题讲解

```
for i in range(2,1001):
```

```
    s = i
```

```
    for j in range(1,i):
```

```
        if i%j == 0:
```

```
            s -= j
```

```
    if s == 0:
```

```
        print(i)
```

# **简单应用题（****1****）**

 

参照编程代码模板完善代码，实现下述功能。

使用turtle库绘制类似斯洛克形状图案，效果如下图所示。 ![IMG_256](file:///C:/Users/1234/AppData/Local/Temp/msohtmlclip1/01/clip_image019.png)

本题暂不支持自动评阅，本地绘制图形正确后，print('ok') 即可得分。

习题讲解

```
#在_____上填写一行代码import turtledef drawCircle():
```

```
    turtle.pendown()
```

```
    turtle.circle(20)
```

```
    turtle.penup()
```

```
    turtle.fd(40)def drawRowCircle(n):
```

```
    for j  in range(n,1,-1):
```

```
        for i in range(j):
```

```
            drawCircle()        
```

```
        turtle.fd(-j*40-20)
```

```
        turtle.right(90)
```

```
        turtle.fd(40)
```

```
        turtle.left(90)
```

```
        turtle.fd(40)
```

```
    drawCircle()
```

```
drawRowCircle(5)
```

```
turtle.hideturtle()
```

```
turtle.done()
```

# 简单应用题（2）

参照代码模板完善代码，实现下述功能。
 从键盘输入一些字符，逐个把它们写到指定的文件，直到输入一个@为止。

 **示例****1****：**
 请输入文件名：
 out.txt
 请输入字符串：
 Python
 is
 open.@
 执行代码后，out.txt文件中内容为
 Python is open.

 **示例****2****：**
 请输入文件名：
 out.txt
 请输入字符串：
 python@123
 执行代码后，out.txt文件中内容为
 Python

 

本题暂不支持自动评阅，请检查你输出的文件内容是否符合要求，print ('ok') 即可得分

习题讲解

```
filename = input("请输入文件名：\n")
```

```
fp = open(filename,"w")
```

```
ch = input("请输入字符串：\n")while ch != '@':
```

```
    if '@' in ch:
```

```
        t = ch.find("@")
```

```
        fp.write(ch[0:t])
```

```
        break
```

```
    else:
```

```
        fp.write(ch + " ")
```

```
    ch = input("")
```

```
fp.close()
```

 

 

 

 

# **101**

## **描述**

## 参照代码模板完善代码，实现下述功能。

## 从键盘输入一个整数和一个字符，以逗号隔开，在屏幕上显示输出一条信息。

示例1：

输入：

请输入1个整数和1个符号，逗号隔开:10,@

输出：

@@@@@@@@@@10@@@@@@@@@@

 

示例2：

请输入1个整数和1个符号，逗号隔开:8,#

\########8########

 

## **输入输出示例**

|        | 输入 | 输出                   |
| ------ | ---- | ---------------------- |
| 示例 1 | 10,@ | @@@@@@@@@@10@@@@@@@@@@ |

习题讲解

答案：

\#在_____处填写一行代码

ls= input().split(',')（1）

print(ls[0].center(eval(ls[0])*2+len(ls[0]),ls[1]))（2）

 讲解：

\1. 理解input的结果是返回一个字符串

\2. split是字符串的方法，能够以逗号把字符串分割成列表，但列表的元素都是字符串

3.用ls[0]和ls[1]分别取得输入的数字和后面的符号

4.题目要求用一行表达式来解决这个问题，所以增加了难度

\5. 此时要想起来用字符串的操作方法center，问题就迎刃而解了，这个方法str.center(x,y) 会用字符串str构造一个新的字符串，新的字符串长度是x, 两边填充y。此处的x是数字，y是字符

\6. 要记得ls[0]里的10是一个字符串，所以要记得用eval把它变成数字，乘2，加上10自己的长度，就得到了所需的x；y就是ls[1]里的字符

\7. 这道题关键是深入理解，并灵活运用center

[下一节：单选题](https://python123.io/student/series/5/catalogs/5/modules/56/problem_set/choices#to-pagetop)

# **102**

## **描述**

## 参照代码模板完善代码，实现下述功能。

## 输入一个正整数n，自动生成n个1-100范围内的随机浮点数，计算输出每个随机数，并显示平均值。 

 

**输入格式**

## 输入一个正整数n

 

## **输出格式**

## 输出n个1-100范围内的随机浮点数，并显示平均值

 

 

## **输入输出示例**

|        | 输入 | 输出                                                         |
| ------ | ---- | ------------------------------------------------------------ |
| 示例 1 | 4    | 27.337682138808397   25.469857251321084   86.76520259704735   3.6817383527287464   the average is:   35.81362008497639 |

习题讲解

答案：

```
import random
```

```
random.seed()
```

```
n=eval(input())
```

```
sum=0
```

```
for i in range(n):
```

```
random.uniform(1,100)
```

```
sum+=f1
```

```
print(f1)
```

```
print(‘the average is:’,sum/n)
```

```
讲解：
```

\1. 要使用random随机库，所以要import random

\2. 题目限制了程序框架，所以主要考核uniform（），题目并不难

\3. 要能读懂程序，最后就知道求平均数，是用sum/n

# **103**

## **描述**

## 参照代码模板完善代码，实现下述功能。

## 输入一个字符串，检查并统计字符串中包含的英文单引号的对数。如果没有找到单引号，就在屏幕上显示“没有单引号”；每统计到2个单引号，就算一对，如果找到2对单引号，就显示“找到了2对单引号”；如果找到3个单引号，就显示“有1对配对单引号，存在没有配对的单引号”。示例如下：

输入：

dfd'dfa'fd'

输出：

有1对配对单引号，存在没有配对的单引号

## **输入格式**

## 输入一个字符串

 

## **输出格式**

## 检查并统计字符串中包含的英文单引号的对数。如果没有找到单引号，就在屏幕上显示“没有单引号”；每统计到2个单引号，就算一对，如果找到2对单引号，就显示“找到了2对单引号”；如果找到3个单引号，就显示“有1对配对单引号，存在没有配对的单引号”。

 

## **输入输出示例**

 

|        | 输入        | 输出                                  |
| ------ | ----------- | ------------------------------------- |
| 示例 1 | dfd'dfa'fd' | 有1对配对单引号，存在没有配对的单引号 |

习题讲解

答案：

```
st = input()
```

```
pair = 0
```

```
count = 0for s in st:
```

```
    if s == "'":
```

```
        pair += 1
```

```
        if pair % 2 == 0:
```

```
            count += 1if pair == 0:
```

```
    pro = "没有单引号"elif pair % 2 == 0:
```

```
    pro = "有{}对单引号".format(count)else:
```

```
    pro = "有{}对配对单引号，存在没有配对的单引号".format(count)print(pro)
```

 讲解：

1.     多分支结构，分支语句的嵌套

2.     利用对2求模运算，来判断单引号是否配对

3.     利用pro变量来记录不同情况下的输出内容，最后只用一个print来输出显示

4.     利用字符串的format操作，把合成要输出的变量和提示字符串

# **201**

 

## **描述**

参照代码模板完善代码，实现下述功能，不得修改其它代码。

使用turtle库的turtle.fd()函数和turtle.seth()函数绘制嵌套六角形，六角形边长从1像素开始，第一条边从0度方向开始，边长按照3个像素递增，效果如下图所示。

 

## **输出格式**

![IMG_256](file:///C:/Users/1234/AppData/Local/Temp/msohtmlclip1/01/clip_image020.jpg) 

 本题暂不支持自动评阅，检查绘制图形无误后，print('ok') 即可得分。

习题讲解

答案：

\#在_____处填写一行代码

\#不允许修改其他代码

 **import** turtle
 edge = 6
 d = 0
 k = 1
 **for** j **in** **range(**10**)**:
    **for** i **in** **range(**edge**)**:
        turtle.fd**(**k（1）**)**        d += 360/edge 或 60（2）
        turtle.seth**(**d**)**        k += 3（3）
 turtle.done**()**

 

**讲解：**

**1.** **二重循环，第一道循环控制画的圈数，内循环控制六边形的边数**

**2.****六边形，所以每次画笔旋转的角度是****360/edge****，或者直接写****60****也可以**

**3.**  **k****用来控制不断增加的边长，根据题目给的增量是****3**

# **202**

## **描述**

参照代码模板完善代码，实现下述功能。实现下面的功能：有一个文件data.txt内容如下：

 {'sid':'501','7月': 9000,'8月':9500,'9月':9200}
 {'sid':'502','7月': 8000,'8月':8500,'9月':8200}
 {'sid':'503','7月': 7000,'8月':7500,'9月':7200}

将文件的数据内容提取出来，计算每个人的平均工资，将其转化为字典salary，按照key的递增序在屏幕上显示输出score的内容，内容示例如下：

501:[9500, 9000, 9200, 9233]

502:[8500, 8000, 8200, 8233]

503:[7500, 7000, 7200, 7233]
  **输入格式**

有一个文件data.txt内容如下：

 {'sid':'501','7月': 9000,'8月':9500,'9月':9200}
 {'sid':'502','7月': 8000,'8月':8500,'9月':8200}
 {'sid':'503','7月': 7000,'8月':7500,'9月':7200}

## **输出格式**

按照key的递增序在屏幕上显示输出score的内容，内容示例如下：

501:[9500, 9000, 9200, 9233]

502:[8500, 8000, 8200, 8233]

503:[7500, 7000, 7200, 7233]

 

## **输入输出示例**

|        | 输入             | 输出                                                         |
| ------ | ---------------- | ------------------------------------------------------------ |
| 示例 1 | `读文件data.txt` | 501:[9500, 9000, 9200, 9233]   502:[8500, 8000, 8200, 8233]   503:[7500, 7000, 7200, 7233] |

 

附件

**序号**

**名称** **程序内使用说明**

1

data.txt

习题讲解

```
salarys = {}
```

```
fi = open("data.txt",'r',encoding='utf-8')
```

```
for l in fi:
```

```
    # print(l)
```

```
    stud = eval(l)
```

```
    sv = stud.items()
```

```
 
```

```
    v = []
```

```
    k = ''
```

```
    for it in sv:
```

```
        if it[0] =='sid':
```

```
            k = it[1]
```

```
        else:
```

```
            v.append(it[1])
```

```
    else:
```

```
        v.append(sum(v)//len(v))
```

```
    salarys[k] = v
```

```
fi.close()
```

```
 
```

```
# print(scores)
```

```
so = list(salarys.items())
```

```
so.sort(key = lambda x:x[0],reverse = False)for l in so:
```

```
    print('{}:{}'.format(l[0],l[1]))
```

讲解：

\1. 有读文件，写入字典，取出到列表，排序，显示输出
 \2. 先从文件中按行读取数据，通过eval（）变换成字典，然后通过items（）获取每个字典的键值对构成的列表

\3. 每个字典项的键值对有四个元组，对四个元组做遍历循环，构造所需要的新字典salarys

\4. 新字典的键是it[0]为‘sid’对应的it[1]；而值则是其他it[0]对应的it[1]，要将这些it[1]通过append（）拼成一个新的列表v，

\5. 一组字典项处理完成之后，要用对v的求和函数和求长度函数返回的值，计算平均分，并且也append到v列表里

\6. 最后把k和v加到salarys里，生成新的字典

\7. 对新的字典提取items构成列表，对列表按照键sid的升序排序，并输出显示。

# **301**

## **描述**

参照代码模板完善代码，实现下述功能，**可以修改其它代码。**

附件文件question.txt中有若干道Python选择题目，第1行的第1个数据为题号，后续的4行是4个选项，接下来是第二道题。示例内容如下：

\1. 以下关于字典类型的描述，错误的是：
 A. 字典类型中的数据可以进行分片和合并操作 
 B. 字典类型是一种无序的对象集合，通过键来存取
 C. 字典类型可以在原来的变量上增加或缩短
 D. 字典类型可以包含列表和其他数据类型，支持嵌套的字典

\24. 以下属于Python图像处理第三方库的是：
 A. PIL       B. mayavi      C. TVTK       D. pygame 

读取其中的内容，提取题干和四个选项的内容，利用jieba分词并统计出现频率最高的3个词，其中要删除以下的常用字和符号

```
 的，:：可以是和中或一个以下“”了其时产生DBC
```

(第一个字符是空格)

作为该题目的主题标签，显示输出在屏幕上。

示例如下：

 

## **输出格式**

统计每道题出现频率最高的3个词，显示输出在屏幕上。示例如下：

第1题的主题是：

字典:6

类型:5

对象:1

第24题的主题是：

库:1

Python:1

属于:1

##  

 

## **输入输出示例**

|        | 输入 | 输出                                                         |
| ------ | ---- | ------------------------------------------------------------ |
| 示例 1 | 无   | 第1题的主题是：   字典:6   类型:5   对象:1   第24题的主题是：   库:1   Python:1   属于:1 |

 

附件

**序号**

**名称** **程序内使用说明**

1

question.txt

习题讲解

**答案：**

**import** jieba
 **def** **qtopic(con)**:
     conls = jieba.lcut**(con)**     dict = **{}**     **for** word **in** conls:
         dict**[**word**]** = dict.get**(**word,0**)** + 1
     dictls = **list(**dict.items**())**     dictls.sort**(****\*key***=**lambda** **x**: x**[**1**]**, **\*reverse***=**True)**     k = 0
     **for** it **in** dictls:
         **if** it**[**0**]** **in** **'** **的，****:****：可以是和中或一个以下****“”****了其时产生****DBC'**:
             **continue         else**:
             **if** k == 3:
                 **break             else**:
                 **print('{}:{}'**.format**(**it**[**0**]**, it**[**1**]))**                 k += 1
 fi = **open("question.txt"**, **'r')** con = **''** num1 = 0
 flag = 0
 **for** l **in** fi:
     l = l.replace**('\n'**, **'')**.strip**()**.split**('.')**     *# print(l)*     **try**:
         ft = **eval(**l**[**0**])**     **except**:
         **pass     else**:
         flag += 1
         num2 = num1
         num1 = ft
         **if** flag > 1:
             **print('****第****{}****题的主题是：****'**.format**(**num2**))**             qtopic**(**con**)**             con = **''**     con += l**[**1**] print('****第****{}****题的主题是：****'**.format**(**num1**))** qtopic**(**con**)** fi.close**()**

 

**讲解：**

**1.** **要用****jieba****分词，****import jieba**

**2.** **打开****data.txt****看到，不止一道题目和选项，所以要考虑用函数来实现分析一道题目的功能，然后在主程序里调用函数，实现分析多道题目的功能**

**3.****打开****-****读文件****-****关闭文件的操作，就不解释了，属于基本功**

**4.** **用****for****循环按行处理文件，然后用****replace****替换掉回车，****strip****去掉首尾空格，用****split****把每行切分成两部分，用****‘.’****来分割**

**5.** **题目要求输出****“****第****1****题的主题是：****”****这样的提示语，所以，需要提取出每道题的题号，是数字，而每个选项是字母****ABCD****，这就需要考虑区分不同的行首情况；**

**6.****为了提高效率，利用****try-except****语句来区分行首是数字还是字母。**

**7.****每行的列表的****l[0]****就是首字符，所以把** **ft =** **eval(l[0])****放在****try****下面，就可以区分出来数字和字母了**

**8.** **巧妙利用****try****后面的****except****和****else****结构是这道题的关键。****except****情况下，不用额外做动作，只是直接****pass****就可以，直接执行****try****结构后续的** **con += l[1]****，用字符串加法，加到****con****里面去；**

**9.****没有异常的情况，可以用****else****结构来处理，这块代码就是把题号提取出来显示提示在屏幕上，然后分析选项内容；**

**10.** **此时遇到新问题，抓到第一个题号的时候，还没有取到后面的选项内容，是不能做选项分析的；得等抓到第二个题号，或者是整个文件结束了之后，才能把搜集到的选项字符串，送给选项分析函数去处理；所以这里有需要一个技巧。**

**11.** **引入一个标志计数器****flag****，当抓到一个题号时，****flag****就加****1****。当****flag****大于****1****的时候，表明第一道题的选项已经读完了，可以显示****“****第****1****题的主题是：****”****这个提示，并且把读到的选项字符串拿去分析了；同时还要为读下一道题的选项把存放选项字符串的变量****con****重新初始化为****‘’****；**

**12.** **对于每道题，无论行首是字母还是数字，都要把文件内容拿去分析，所以在****try****结构之后，都有一句** **con += l[1]****，用来把读到的每行里的文字串，加到****con****变量上去**

**13.****此时还要处理一个情况，就是每次读到下一道题的题号****num1****的时候，需要显示上一道题的提示信息和分析结果，所以需要在把新读到的题号****ft****赋值给****num1****之前，要用一个变量****num2****来保存上一个****num1****的值；然后显示的是前一个****num2****，即语句：****print('****第****{}****题的主题是：****'.format(num2))**

**14.** **在****for****循环之外，还要处理最后一道题，因为最后一道题后面没有带题号的内容，而是文件结束了，所以在文件****for****循环之外，****con****里面还记录着最后一道题的内容，需要再单独显示输出****“****第？题的主题是：****”****这个提示，此时****num1****里面就是刚刚读到的最后一个题号，并且调用一次选项分析函数****qtopic(con)****，做分析并显示结果**

**15.****接下来看分析函数****qtopic****，参数就是从文件里搜集到的一道题目的题目和选项的所有文字组成的字符串；，**

**16.** **首先要用****jieba****切分长字符串，然后用字典，统计每个词出现的次数** 

**for word in conls:         dict[word] = dict.get(word, 0) + 1**

**17.** **因为要找出现次数最多的词，所以要把字典的项提取出来形成列表****dictls= list(dict.items())****；按照出现次数排序，** **dictls.sort(****\*key*****=lambda x: x[1],** **reverse****=True)****；**

**18.** **接下来，要输出有意义的词汇，需要把出现次数多但在给出的黑名单里的词及其次数跳过，所以需要一个循环按顺序遍历排好序的列表**

**19.** **题目要求只显示****3****个出现次数最多的词汇，并且要跳过黑名单里的词，所以这里不能贸然的循环三次，输出前三个出现最多的词汇，而是要先判断是否在黑名单里；**

**20.** **注意，列表里的元素是一对元组，****it[0]****是词汇，****it[1]****是出现的次数，所以要用****it[0]****检查是否在黑名单里，如果在就用****continue****跳过，看下一个；如果不在黑名单，就是能够显示出来的词汇**

**20.** **对能够显示的词汇做计数，加一个计数器****k****，如果等于****3****了，就用****break****跳出循环，否则的话就显示，并且让****k****加****1**

**21.** **到此程序就写完了。**

 

 

 