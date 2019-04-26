##### 1.filter函数

可以对序列做过滤处理，把序列的每一项传递到过滤函数

```
输入：

#定义验证用户名的函数validate（），长度在4-12之间
def validate (usernames):
    if (len(usernames) > 4) and (len(usernames)<12):
        return usernames
#调用函数filter（），过滤元祖参数
#必须要加list，书上写错了
print (list(filter(validate, ('admin','duchangyuan','dcy','balefire'))))

输出：
['admin', 'duchangyuan', 'balefire']
```

##### 2.reduce函数

```

```

##### 3.

```

```

##### 23.计算相对年龄

```
输入：
#定义函数
def countAge(yson,setAge,yfather):
#求年龄差
    differAge = (int)(setAge-yson)
#计算父亲实际年龄
    realFatherAge = (int)(yfather + differAge)
    return realFatherAge

print( "年龄差："+ str(countAge(5,7,26)))

输出：
年龄差：28
```

##### 24.验证登录密码

```
当需要用到可变长度参数时，在函数的参数前使用标识符*，可实现要求

Python还提供了另一个标识符**，在形参前面添加双星号，可以引用一个字典作为参数，根据实际参数的复制表达式生成字典
```

```
输入：
def login(username,password):
    if(username == 'admin' ) and ( password == 'admin'):
        print("登录成功！")
    else:
        print("登录失败！")
        
user = input("请输入用户名：")
pword = input("请输入密码：")
login(user,pword)

输出：
请输入用户名：admin
请输入密码：admin
登录成功！
```

##### 25.字典元素作为形参

```
输入：
def login(**userpwds):
    keys = userpwds.keys()
    username = ' '
    password = ' '
    for key in keys:
        if 'username' ==key:
            username = userpwds[key]
        if 'password' ==key:
            password =  userpwds[key]
    if(username == 'admin') and (password == 'admin'):
                print("登录成功！")
    else:
                print("登录失败！")
login(username='admin',password='admin')

输出：
登录成功！
```

##### 26.验证用户注册规范

```
输入：
创建函数并设置默认值
def  registerUser(userName = "py",idcard = "python",tel = "123"):
    #提示输入用户名称
    userName = input("请输入用户名称：")
    #判断用户输入名称的长度
    if (len(userName)>3 and len(userName)<10):
        idcard = input("请输入账号：")
        #判断账号是否为数字
        if (idcard.isdigit()):
            tel = input("请输入电话号码：")
            #判断电话号码的长度及格式
            if (tel.isdigit() and len(tel)>=7 and len(tel)<=11):
                print("恭喜你，注册成功！")
            else:
                print("电话格式或长度不正确！")
                
        else:
            print("账号格式不正确，请输入数字！")
            
    else:
        print("用户名的长度必须在3-10之间！")
        
print (registerUser('python','3232','45256888'))#或：print (registerUser())

输出：
请输入用户名称：python
请输入账号：2323
请输入电话号码：342424234
恭喜你，注册成功！
None

```

##### 27.判断是否闰年

tuple()函数可将列表元素装到元组中

```
输入：
def judgeYear(year):
    #声明变量用于返回值
    message = ' '
    if ((year%4 == 0) and (year%100!=0) or (year%400 == 0)):
        message = "今年是闰年"
    else:
        message = "今年是平年"
    return message
print( judgeYear(2018))

输出：
今年是平年

```

##### 28.调用模块函数添加用户