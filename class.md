##### 28.调用模块函数添加用户

添加用户.py

```
class Person:
    def addPer (person):
        #提示用户输入名称
        userName = input("please input your name:")
        #打印输出名称
        print(userName)
        #判断用户输入的名称是否为空
        if userName != "":
            print("person add success")
        else:
            print("person add failure")
```

添加用户_main.py

```
#引入模块
import 添加用户
person = 添加用户.Person() #调用模块中的类
person.addPer()           #执行类中的添加方法、

```

输出：

```
please input your name:dcy
dcy
person add success


```







##### 32.模拟购物

模块属性：

```
# _name_
#用于判断当前模块是不是程序的入口，在编写程序时，通常给每个模块添加条件语句，用于单独测试该模块的功能
# _doc_
#Python中的模块是一个对象，而每个对象都要一个_doc_属性
if _name_ == '_main_':
    print("myThirdModule 作为主程序")
else:
    print("myThirdModule 被另一个模块调用")
    


```

```
输入：
class Goods:
    '购买商品的活动' #描述
    def buyGoods (self):
        #判断是否执行购买商品的活动
        if __name__ == '__main__':
        #提示是否购买物品
            self.goods = input('您是否购买商品？ y/n:')
            if (self.goods=='y'):
                #提示输入商品的名称和数量
                goodsName=input('请输入商品的名称：')
                num = int(input('请输入商品的数量:'))
                #输出
                print('您购买的商品是：'+ goodsName + '数量是：' + str(num))
                #输出总价
                print('您购买的商品单价为5元，总价格：'+str(5*num))
            if(self.goods=='n'):
                print('您没有购买商品')
        else:
            print('您放弃了参与该活动')
print(Goods,__doc__)
print(Goods.buyGoods.__doc__)
good = Goods()
good.buyGoods()

输出：
您是否购买商品？ y/n:y
请输入商品的名称：dld
请输入商品的数量:666
您购买的商品是：dld数量是：666
您购买的商品单价为5元，总价格：3330

您是否购买商品？ y/n:n
您没有购买商品



```



##### 33.使用模块内置函数生成验证码

```

```

##### 列表



##### 元组



##### 使用字典实现用户账号管理



##### 序列



##### 邮箱注册系统



##### 打印客户凭条



##### 列车路线查询系统



##### 获取邮箱用户名



##### 上传图片格式判断



##### 模拟水果成熟过程





##### 创建独特的服装连锁店



##### 下载页面访问量统计



##### 创建本地记事本



##### 格式化本地记事本



##### 备份与恢复本地记事本



##### 日记内容过滤器



##### 记事本的分类



##### 记事本文件列表



##### 异常



##### 制作一个可永久保存的硬盘



##### 服务器与客户端通信



##### 异步通信



##### 实现一个简单的web服务器