---
### 👉作者QQ ：1556708905 微信：zheng0123Long (支持修改、部署调试、定制毕设)

### 👉接网站建设、小程序、H5、APP、各种系统等

### 👉选题+开题报告+任务书+程序定制+安装调试+ppt 都可以做
---

**博客地址：
[https://blog.csdn.net/2303_76227485/article/details/137398745](https://blog.csdn.net/2303_76227485/article/details/137398745)**

**视频演示：
[https://www.bilibili.com/video/BV1up421y7F2/](https://www.bilibili.com/video/BV1up421y7F2/)**

**毕业设计所有选题地址：
[https://github.com/zhengjianzhong0107/allProject](https://github.com/zhengjianzhong0107/allProject)**

## 基于Java+Springboot+Vue的自习室座位预约小程序管理系统(源代码+数据库)132

## 一、系统介绍

本项目前后端分离带小程序，分为管理员、用户两种角色

### 1、用户：

- 注册、登录、自习室介绍、推荐图书、校园资讯、座位查询、座位预约、预约查看、个人信息

### 2、管理员：

- 用户管理、场地管理、座位管理、预约记录管理、封面管理、文章管理、文章类型管理

## 二、所用技术

后端技术栈：

- Springboot
- Mybatis
- Mysql
- Maven
- redis

前端技术栈：

- Vue 
- Vue-router 
- axios 
- element-ui
- uniapp

## 三、环境介绍

基础环境:IDEA/eclipse, JDK1.8, Mysql5.7及以上, Maven3.6, node14, navicat, vscode

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图

### 1、用户

![contents](./picture/picture0.png)
![contents](./picture/picture1.png)
![contents](./picture/picture2.png)
![contents](./picture/picture3.png)
![contents](./picture/picture4.png)
![contents](./picture/picture5.png)
![contents](./picture/picture6.png)
![contents](./picture/picture7.png)
![contents](./picture/picture8.png)
![contents](./picture/picture9.png)
![contents](./picture/picture10.png)
![contents](./picture/picture11.png)
![contents](./picture/picture12.png)
![contents](./picture/picture13.png)

### 2、管理员：

![contents](./picture/picture14.png)
![contents](./picture/picture15.png)
![contents](./picture/picture16.png)
![contents](./picture/picture17.png)
![contents](./picture/picture18.png)
![contents](./picture/picture19.png)
![contents](./picture/picture20.png)
![contents](./picture/picture21.png)
![contents](./picture/picture22.png)
![contents](./picture/picture23.png)

## 五、浏览地址

后台访问地址：http://localhost:9528/

- 管理员账号/密码：admin/123456

- 用户账号/密码：李强/123456

## 六、部署教程

1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并执行项目的sql

2. 使用IDEA/Eclipse导入roomAppointmentJava项目，导入时，若为maven项目请选择maven; 等待依赖下载完成

3. 修改resources目录下面application.yml里面的数据库配置

4. com/company/project/Application.java启动后端

5. vscode或idea打开roomAppointmentVue项目

6. 在编译器中打开terminal，执行npm install 依赖下载完成后执行 npm run dev,执行成功后会显示后台管理访问地址

7. hbuilder打开roomAppointmentUniapp项目, 修改manifest.json里面的微信小程序配置AppId(从注册的微信小程序账号里面复制)

8. hbuilder点击运行-运行到小程序模拟器-微信开发者工具，然后会打开微信开发者工具，小程序页面就展示出来了(如果没有微信小程序开发工具也可以运行到浏览器打开)

