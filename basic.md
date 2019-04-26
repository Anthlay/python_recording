##### 1. Python 环境配置

###### 略

##### 2.Python 运算符、内置函数

###### 内容：

1.编写程序，输入任意大自然数，输出各数字之和。

2.编写程序，输入两个集合 setA 和 setB，分别输出它们的交集，并集和差集 setA-setB。

3.编写程序，输入一个自然数，输出它的二进制，八进制，十六进制表达形式。

###### 代码：

```python
1.
num = input('请输入一个自然数: ')
print(sum(map(int,num)))

输出：
请输入一个自然数: 456 15


```

```
2.

```

##### 3.类，对象命名规则



```python
class Myclass:				#类名首字母 大写
  __username = ''            #私有属性前有两个下划线
  def __init__ (self , username):
    self.__username = username #相当于this关键字
  def getUserName (self):      #方法名首字母小写，其后每个单词首字母大写
    return self.__username
if __name__ == "__main__":
  myclass = MyClass('sdmin')
  print (myclass.getUserName())
  
输出：sdmin
```

##### 4.函数的命名规则

​       

```
import random
def equalseNum (num): #方法名首字母小写，其后每个单词首字母大写
    if (num == 6):
        print(1)
    else:
        print(0)

num = random.randrange(1,9)
print('num = '+ str(num))
print(equalseNum(num))

输出：
num = 7
0
None
```

##### 5.复数

```
aComplex = -6.8888-5.66666j
print(aComplex.real)  #实部
print(aComplex.imag) #虚部
print(aComplex.conjugate())#共轭

输出：
-6.8888
-5.66666
(-6.8888+5.66666j)
```

##### 6.十进制代码

```
from decimal import Decimal
dec = Decimal('1.1')
print(dec)
print(dec+Decimal('2.2'))

输出：
1.1
3.3
```

##### 7.购物清单

```
pro_name_1 = '特仑苏'
pro_price_1 = 48
pro_total_1 = pro_price_1 * 1
pro_name_2 = '蒙牛    '
pro_price_2 = 50
pro_total_2 = pro_price_2 * 1
pro_name_3 = '伊利    '
pro_price_3 = 52
pro_total_3 = pro_price_3 * 1
pro_name_4 = '康师傅'
pro_price_4 = 54
pro_total_4 = pro_price_4 * 1
print("-------------------购物清单-------------------")
print("商品名称   数量   单价  总计")
print(pro_name_1+"   "+"1"+"   "+str(pro_price_1)+"   "+str(pro_total_1))
print(pro_name_2+"   "+"1"+"   "+str(pro_price_2)+"   "+str(pro_total_2))
print(pro_name_3+"   "+"1"+"   "+str(pro_price_3)+"   "+str(pro_total_3))
print(pro_name_4+"   "+"1"+"   "+str(pro_price_4)+"   "+str(pro_total_4))

输出：
-------------------购物清单-------------------
商品名称   数量   单价  总计
特仑苏   1   48   48
蒙牛     1   50   50
伊利     1   52   52
康师傅   1   54   54
```

##### 8.输入输出

```
Python 3.0后 input() 代替了 raw_input()
```



##### 9.逻辑运算符和逻辑表达式

```
输入：

print(2<3 and 4<5)

print(2>3 or 4<5)

print(not 2<3)

输出：

True
True
False
```



##### 10.计算圆的周长和面积

```
输入：
r = input('半径：')
#r = 3
c = 2*3.14*int(r)
s = 3.14*(int(r)**2)
print("周长："+str(c))
print("面积："+str(s))
输出：
半径：3
周长：18.84
面积：28.26
```

##### 11.运算符 的优先级

逻辑运算符 > 关系运算符 > 算术运算符



##### 12.乘法表

```
输入：
for i in range(1,10):
    for j in range(1,i+1):
        #print(str(j)+'*'+str(i)+'='+str(i*j))
        print("   ".join(["%d*%d=%d" %(j , i , i*j)]))
        

输出：
	乘法表
```

##### 13.并行迭代

```
输入1：range函数对两个列表进行迭代

names = ['dcy','mxl' ,'ltt  ' ,'dyd','hsr']
ages = [23,22,25,26,27]
for i in range (len(names)):
    print(names[i],' 的年龄是 ',ages[i])
    
输出：
dcy  的年龄是  23
mxl  的年龄是  22
ltt  的年龄是  25
dyd  的年龄是  26
hsr  的年龄是  27


输入2：使用内建函数zip吧两个序列压缩，然后返回一个元祖的列表
names = ['dcy','mxl' ,'ltt  ' ,'dyd','hsr']
ages = [23,22,25,26,27]
for name,age in zip(names,ages):
    print(name,' 的年龄是 ',age)
    
输出：
dcy  的年龄是  23
mxl  的年龄是  22
ltt  的年龄是  25
dyd  的年龄是  26

```

##### 14.编号迭代

```
输入：
shijus = ['星桥鹊驾','经年才见,','想离情','别恨难穷']
for index ,shiju in enumerate(shijus) :
    if  '星桥鹊驾' in shiju:
        shijus[index] = '金风玉露一相逢，便胜却人间无数'
        print (index,shiju)
        for shi in shijus:
            print (shi)
            
输出：
0 星桥鹊驾
金风玉露一相逢，便胜却人间无数
经年才见,
想离情
别恨难穷
```



##### 15.关键字搜索功能

```
输入：
zifu = input("请输入您要查询的鲜花的名称: ")
shujus = ['长春花', '珍珠花','向日葵','风铃草','金盏菊','含羞草','夹竹桃','野蔷薇']
for index,shuju in enumerate(shujus):
    if  zifu in shuju:
        print (shuju)
        
输出：、
请输入您要查询的鲜花的名称: 花
长春花
珍珠花
```

##### 16 break语句

```
输入：
i = 1
while i<=5:
    print (i)
    if i == 4:
        print ('打印到此停止的数是: ', i)
        break
    i+=1
    
输出：
1
2
3
4
打印到此停止的数是:  4
```

##### 17.for循环中的break语句

```
输入：
items = ['my name is dcy','I miss you',(4,5),2 ]
keys = ['my name is dcy',(4,5),'I miss you' ,'I\'m tired']
for key in keys:
    for item in items:
        if item == key:
            print(key,'was found')
            break
    else:
            print(key,'not found')

输出：
my name is dcy was found
(4, 5) was found
I miss you was found
I'm tired not found
```

##### 18.while True 循环中的 break语句

```
输入：
while True:
    word = input('请输入用户名：')
    if not word:
        break
        print (*'您输入的用户名是：'+ word)
      
输出：
请输入用户名：dd
请输入用户名：ff
请输入用户名：yy
请输入用户名：ersdgs
请输入用户名：dfgsdgsdg 
请输入用户名：\
请输入用户名：

```

##### 19.continue语句

```
输入：
i=1
while i<=5:
    
    name = input('输入您的用户名：')
    age = input('输入您的年龄：')
    if name == 'dcy':
        continue
    print ("helle ","您输入的名字是",name,'您输入的年龄是：',age)
    
输出：
输入您的用户名：dcy
输入您的年龄：23
输入您的用户名：sss
输入您的年龄：323
helle  您输入的名字是 sss 您输入的年龄是： 323
输入您的用户名：
```

##### 20.歌单循环方式

```
输入：
gequ = ['追光者','烟火','尘埃','明天过后','开门见山','默']
countstr = input('您想循环的次数：')
count = int(countstr)

tiaoguo = input('输入您想跳过的歌曲：')
i=1
while i<=count:
    i+=1
    print('---循环开始---')
    for danqu in gequ:
        if danqu == tiaoguo:
            continue
输出：
您想循环的次数：7
输入您想跳过的歌曲：烟火
---循环开始---
第 1 次循环  追光者
第 1 次循环  尘埃
第 1 次循环  明天过后
第 1 次循环  开门见山
第 1 次循环  默
---循环开始---
第 2 次循环  追光者
第 2 次循环  尘埃
第 2 次循环  明天过后
第 2 次循环  开门见山
第 2 次循环  默
---循环开始---
第 3 次循环  追光者
第 3 次循环  尘埃
第 3 次循环  明天过后
第 3 次循环  开门见山
第 3 次循环  默
---循环开始---
第 4 次循环  追光者
第 4 次循环  尘埃
第 4 次循环  明天过后
第 4 次循环  开门见山
第 4 次循环  默
---循环开始---
第 5 次循环  追光者
第 5 次循环  尘埃
第 5 次循环  明天过后
第 5 次循环  开门见山
第 5 次循环  默
---循环开始---
第 6 次循环  追光者
第 6 次循环  尘埃
第 6 次循环  明天过后
第 6 次循环  开门见山
第 6 次循环  默
---循环开始---
第 7 次循环  追光者
第 7 次循环  尘埃
第 7 次循环  明天过后
第 7 次循环  开门见山
第 7 次循环  默

```

##### 