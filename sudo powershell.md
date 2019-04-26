##### 31.使用运行窗口打开带管理员权限的PowerShell

```
按下组合键Windows + R以打开运行窗口。输入powershell然后按下回车键。

Windows PowerShell会以当前用户的权限去执行。

如果你想要从普通模式转至管理员模式，输入以下PowerShell命令然后按下回车键。

```

```sql
Start-Process powershell -Verb runAs 
```

