<p align="center"><img src="./document/images/logo.png" height="100" alt="logo"/></p>
<h1 align="center"> xinguan &nbsp; 🚀 &nbsp; 新冠-物资管理系统  </h1>
<h3 align="center">2020新冠疫情期间, 寂寞消遣之作~</h3>
<h3 align="center"><a href="https://www.zykhome.club" target="_blank">https://www.zykhome.club</a></h3>


---

<p align="center">
    <a href="https://www.oracle.com/technetwork/java/javase/downloads/index.html"><img src="https://img.shields.io/badge/JDK-8+-green.svg" alt="jdk 8+"></a>
    <a href="#"><img src="https://img.shields.io/badge/license-Apache%202.0-blue.svg?longCache=true&style=flat-square"></a>
    <a href="#"><img src="https://img.shields.io/badge/springboot-2.2.1-yellow.svg?style=flat-square"></a>
    <a href="#"><img src="https://img.shields.io/badge/shiro-1.4.2-orange.svg?longCache=true&style=flat-square"></a>
    <a href="https://github.com/zykzhangyukang/Xinguan"><img src="https://img.shields.io/github/stars/zykzhangyukang/Xinguan?style=social" alt="GitHub stars"></a>
    <a href="https://github.com/zykzhangyukang/Xinguan"><img src="https://img.shields.io/github/forks/zykzhangyukang/Xinguan?style=social" alt="GitHub forks"></a>
    <a href="https://github.com/zykzhangyukang/Xinguan"><img src="https://img.shields.io/github/repo-size/zykzhangyukang/Xinguan" alt="size"></a>
</p>


---

>该项目是一个以新冠疫情为主题开发的一个物资管理系统,主要分为系统模块和业务模块,业务模块是处理疫情期间,物资的发放,物资入库,以及查看物资的库存等.
系统模块是一个后台通用的RBAC权限模块,可以精确的控制到后台API级别的权限控制,项目不定期更新中.武汉加油~~
开发模式:前后端分离,前端负责数据渲染,后端返回数据。


### [在线预览](https://www.zykhome.club/#/login "在线预览") & [后端项目](https://github.com/zykzhangyukang/Xinguan "后端项目") & [前端项目](https://github.com/zykzhangyukang/xinguan-vue "前端项目")

#### 模块划分

- xinguan-business: 业务模块,所有与业务相关的代码放在此工程中。
- xinguan-system: 系统模块,权限控制相关的代码放在此工程中。
- xinguan-common: 公共模块,存放工具类、领域模型（DTO）、数据模型对象(DO)一些通用的类。
- xinguan-generator: 代码生成器，生成Controller,Service,ServiceImpl,以及前端代码。
- xinguan-vue: 前端项目, npm install 安装依赖后, npm run serve  启动该项目。
- xinguan-web: 处理前端请求的Controller,放在此工程中。

#### 技术栈

SpringBoot, Shiro ,Swagger-UI,mybatis,JWT,Mysql,通用mapper,Vue.js+element-ui,FastDFS,Nginx,Node.js(v12.9.1版本)

#### 演示页面


- 后台系统首页

![2](https://www.zykhome.club/group1/M00/00/13/rBofMmAT9W2AfurCAAbpCxg4Ryw771.PNG)


- 附件管理

![3](https://www.zykhome.club/group1/M00/00/13/rBofMmAT9Z-AAZx3AAmL5u2dO1U985.PNG)

- 物资库存管理

![5](https://www.zykhome.club/group1/M00/00/13/rBofMmAT9TSAELlUAAM8r-W_KnQ759.PNG)

- 物资入库管理

![6](https://coderman-blog.oss-cn-beijing.aliyuncs.com/6_1588596788146.PNG)







