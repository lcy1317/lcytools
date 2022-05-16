# Personal Tools

写这个个人仓库的目的是为自己的代码提供一些可以直接调用的常用的东西。

当前一个需求是以邮件/QQ消息（需要结合服务器部署的QQrobot来做，比较烦）的形式来实现远端跑代码时候的自动化提醒，就不需要我自己一个个的去check。

## 使用

查看当前有哪些写好的文件：

```python
import lcytools.help
lcytools.help.fileList()
```

# code

## help

提供一个查询接口，发送一下当前有哪些东西

## emailMe

给自己发送文件，调用方式：

```python
import lcytools.emailMe as eM
eM.lcy_email(["11158340882@qq.com"],key = "这是一个防止SMTP密码丢掉的自己密码hh")
```

