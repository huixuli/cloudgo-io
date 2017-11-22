# CloudGo-io
标签（）： go语言学习

---

## 概述
设计一个 web 小应用，展示静态文件服务、js 请求支持、模板输出、表单处理、Filter 中间件设计等方面的能力。（不需要数据库支持）
## 任务基本要求
编程web应用程序cloudgo-io。请在项目 README.MD 给出完成任务的证据！
基本要求：

* 支持静态文件服务

* 支持简单 js 访问

* 提交表单，并输出一个表格

* 对 /unknown 给出开发中的提示，返回码 5xx
## 代码编写
此次实验中我所编写的服务器与客户端代码都是参考了老师在课程上所介绍的博客[golang web 服务器 request 与 response 处理](http://blog.csdn.net/pmlpml/article/details/78539261)。加以理解与修改完成我此次的代码编写。本次实验代码使用的是"github.com/codegangsta/negroni"中提供的框架。

## 测试

**运行main.go函数**

![](/图片/1.png)

**静态文件服务**

![](/图片/2.png)

**js访问**

![](/图片/6.png)

**提交表单，并输出表格**

![](/图片/3.png)
![](/图片/4.png)
![](/图片/5.png)

**对/unkonw给出提示**

![](/图片/7.png)




