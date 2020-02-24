#                         helloworld
[![Build Status](https://travis-ci.com/loodao/helloworld.svg?branch=master)](https://travis-ci.com/loodao/helloworld)

（上面的build|passing图标说明： 当passing是绿色，证明你代码提交上来是已经通过一系列的自动集成构建测试；当你提交代码之后passing颜色是红色，就是你的代码没有通过审查，你的邮件会收到不通过的原因并指出问题所在的代码行）

####  增加文档目录

​	documents : 放置与开发有关的资料，图片，说明文档等;

~~~
1. doxygen注释语法
2. 代码提交指引
3. 何为代码持续集成自动化部署？
~~~

#### 代码目录

​	提交每一个功能模块都建立一个目录，请看项目中的course_2_2就是一个功能模块；

一个功能模块相对独立，原则一个.c文件和一个.h文件

#### 服务器端的代码风格自动审查

​	    在服务器端部署了googl C/C++ 代码规则审查，并在其基础上修改符合我们公司实际开发的定义规则。

 现在我正测试用那个方式更便于大家推送的（居于目前部署在github的连线速度，我正测试在码云gitee上实现，本周大家就可以两个架构都可以推送）