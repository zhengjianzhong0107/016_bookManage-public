---
### 👉作者QQ ：1556708905 微信：zheng0123Long (支持修改、部署调试、定制毕设)

### 👉接网站建设、小程序、H5、APP、各种系统等

### 👉选题+开题报告+任务书+程序定制+安装调试+ppt 都可以做
---

**毕业设计所有选题地址 [https://github.com/zhengjianzhong0107/allProject](https://github.com/zhengjianzhong0107/allProject)**

**博客地址：[https://blog.csdn.net/2303_76227485/article/details/128651214](https://blog.csdn.net/2303_76227485/article/details/128651214)**

**视频演示：[https://space.bilibili.com/384537280](https://space.bilibili.com/384537280)**

## springboot+vue的图书管理系统项目(源代码+数据库)

## 一、系统介绍

本项目前后端分离

- 前台功能：图书查询、图书借阅、图书归还、登录注册、修改密码
- 后台功能-管理员登录：图书管理、借阅信息管理、图书类型管理、用户管理

## 二、所用技术

- 后端使用Java+SpringBoot+MyBatis+MySQL
  
  前端使用Vue+Axios+Element UI

## 三、环境介绍

基础环境 :IDEA/eclipse, JDK 1.8, Mysql5.7及以上,Node.js,Maven

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图

![contents](./picture/picture1.png)

![contents](./picture/picture2.png)

![contents](./picture/picture3.png)

![contents](./picture/picture4.png)

![contents](./picture/picture5.png)

![contents](./picture/picture6.png)

![contents](./picture/picture7.png)

![contents](./picture/picture8.png)

![contents](./picture/picture9.png)

### 数据库结构

![Diagram 1](./picture/picture10.jpg)

## 五、浏览地址

项目演示地址：http://localhost:8092/BookManager/

管理员账号`admin`，密码`admin`

读者账号`wangpeng`，密码`123456`

## 六、安装教程

1. 数据库导入，新建数据库BookManager，将BookManager2-master文件夹下的`book_manager.sql`文件运行。
2. 使用IDEA/Eclipse导入项目，请选择maven;导入成功后请执行maven clean;maven install命令，然后运行；
3. 打开项目，打开`src/main/resources/application.properties`，修改数据库和Redis的配置文件。
4. 启动项目后端项目 
5. vscode打开BookManagerVue-permission-control项目。
6. 打开终端，执行npm install 依赖下载完成后执行 npm run dev,执行成功后会显示访问地址

对应的后端文件夹如下：BookManager

对应的前端文件夹如下：BookManagerVue-permission-control
