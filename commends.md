##### 21.pass 语句

```
# pass 在程序中什么事情都不需要做，类似于一个占位符。
# 用于有待补充的代码模块
输入：
name = input('请输入用户名：')
if name== 'dcy':
    print('您是管理员，请进')
elif name == 'gn':
    #身份未分配
    pass
    
输出：

请输入用户名：dcy
您是管理员，请进
请输入用户名：gn

```

##### 22.del 语句

```
输入1：
name = 'dcy'
del name
print(name)
输出：
NameError                   Traceback (most recent call last)
<ipython-input-6-5037ff6fe2c1> in <module>()
      1 name = 'dcy'
      2 del name
----> 3 print(name)

NameError: name 'name' is not defined

输入2：
name = 'dcy'
keys = name
del name
print(keys)
输出：
dcy

```

##### 