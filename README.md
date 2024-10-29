[合集 \- .NET 开源项目(22\)](https://github.com)[1\.推荐一款界面优雅、功能强大的 .NET \+ Vue 权限管理系统08\-05](https://github.com/1312mn/p/18342737)[2\..NET 开源权限认证项目 MiniAuth上线08\-06](https://github.com/1312mn/p/18344646)[3\..NET 与 LayUI 实现高效敏捷开发框架08\-08](https://github.com/1312mn/p/18347553)[4\..NET 8 \+ Blazor 多租户、模块化、DDD框架、开箱即用08\-09](https://github.com/1312mn/p/18350326)[5\.推荐一个优秀的 .NET MAUI 组件库08\-13](https://github.com/1312mn/p/18352047)[6\..NET 7 \+ Vue 权限管理系统 小白快速上手08\-15](https://github.com/1312mn/p/18358437)[7\..NET 权限工作流框架 TOP 榜07\-30](https://github.com/1312mn/p/18331216)[8\..NET 8 高并发微服务电商系统实战08\-29](https://github.com/1312mn/p/18383133)[9\..NET 8\.0 前后分离快速开发框架09\-02](https://github.com/1312mn/p/18387692)[10\..NET 开源工业级移动端仓库管理系统09\-18](https://github.com/1312mn/p/18408636)[11\..NET 8 \+ Vue/UniApp 高性能前后端分离框架09\-24](https://github.com/1312mn/p/18418452)[12\..NET 7\+Angular 4 轻量级新零售进销存系统09\-20](https://github.com/1312mn/p/18417365)[13\..NET 代码混淆工具\-JIEJIE.NET10\-09](https://github.com/1312mn/p/18435527)[14\..NET 实现的交互式 OA 系统10\-10](https://github.com/1312mn/p/18435039)[15\..NET 8 实现无实体库表 API 部署服务10\-12](https://github.com/1312mn/p/18454788)[16\..NET \+Vue 开源在线考试系统10\-15](https://github.com/1312mn/p/18462482):[蓝猫机场](https://fenfang.org)[17\.C\# 并发控制框架：单线程环境下实现每秒百万级调度10\-16](https://github.com/1312mn/p/18460025)[18\..NET 7\+Vue 3 开源仓库管理系统 ModernWMS10\-17](https://github.com/1312mn/p/18468668)[19\..NET 开源餐饮系统支持桌面与Web版10\-18](https://github.com/1312mn/p/18471102)[20\..NET 开源扁平化、美观的 C/S 控件库10\-25](https://github.com/1312mn/p/18501489)[21\..NET \+ 微信小程序开源多功能电商系统10\-28](https://github.com/1312mn/p/18476131)22\..NET 8\.0 开源在线考试系统（支持移动端）10\-29收起**阅读目录**

* [前言](#_label0)
* [系统介绍](#_label1)
* [系统功能](#_label2)
* [支持环境](#_label3)
* [系统源码](#_label4)
* [项目部署](#_label5)
* [项目效果](#_label6)
* [项目总结](#_label7)
* [项目地址](#_label8)
* [最后](#_label9)

## 前言


推荐一款基于.NET 8\.0 免费开源跨平台在线考试系统，系统不仅支持桌面端，还特别优化了移动端的用户体验。


通过本系统可以轻松搭建自己的在线考试平台，实现随时随地的测试与评估。


本文将详细介绍系统的功能特点、技术架构以及如何部署和使用。


## 系统介绍


支持跨平台、国产化部署。


支持国产人大金仓、达梦、OceanBase数据库 及 MySql、SqlServer、PostgreSql、SQLite 等常见数据库，极大地提高了项目的可移植性和适用范围。


系统不仅支持主流的操作系统，还特别针对国产化环境进行了优化，确保在多种国产操作系统上稳定运行。


## 系统功能


**1、管理端首页**


基本信息：展示当前账号的信息及欢迎语。


预览信息：查看管理员的基本资料。


修改信息：更新个人信息。


修改密码：更改登录密码。


退出登录：安全退出系统。


**2、发布考试**


支持多种考试模式（正式考试、模拟测试）。


提供灵活的试题生成方式（随机出题、手动选题、开考随机）。


支持自动与手动阅卷。


考试合格者可直接获得证书。


**3、试卷管理**


试卷分类：多级分类管理，支持批量操作。


发布考试：包括保存草稿、正式发布等功能。


复制：一键复制已有的试卷。


预览：查看试卷内容。


修改：编辑试卷信息。


启停用：控制试卷的状态。


删除：移除不再需要的试卷。


**4、阅卷**


阅卷：对主观题进行评分。


预览：查看阅卷情况。


考试管理：涵盖考生、成绩、阅卷进度、数据分析等方面。


**5、考试管理**


题型管理：提供单选、多选、判断、填空、简答题型，并支持扩展。


题库管理：批量导入/导出试题，支持预览。


证书管理：创建证书模板，支持拖拽定位及预览。


题目组：组织题目便于练习和组合成卷。


**6、问卷调查**


支持内部与外部问卷，后者可通过二维码填写。


发布：创建新的问卷。


复制：快速复制现有问卷。


预览：查看问卷设计。


修改：编辑问卷内容。


启停用：控制问卷的有效性。


删除：移除问卷。


问卷统计：生成统计图表。


**7、其他功能**


企业管理：包括组织架构调整、人员权限设定等。


系统管理：如管理员配置、用户设置、数据库维护、安全规则制定等。


日志管理：记录管理员操作、用户活动、系统错误，以及相关设置。


统计图表：展示用户登录频率、安全拦截次数等关键指标。


## 支持环境


### 支持的操作系统


1、Windows


![](https://img2024.cnblogs.com/blog/576536/202410/576536-20241028144902033-978368177.png)


2、Linux


![](https://img2024.cnblogs.com/blog/576536/202410/576536-20241028145005351-313503638.png)


### 支持的数据库


![](https://img2024.cnblogs.com/blog/576536/202410/576536-20241028145025448-175152523.png)


## 系统源码


系统代码组织框架结构，如下所示：




```
├── src (源代码)
│   ├── Datory (数据库基础类)
│   ├── XBLMS (接口基础类)
│   ├── XBLMS.Core (核心代码)
│   ├── XBLMS.Web (UI)
│   │   ├── wwwroot (对外访问目录)
│   │   ├── Controllers (WebApi)
│   │   ├── log (运行日志)
│   │   ├── Pages (页面)
│   │   ├── appsettings.json (配置文件)
│   │   ├── web.config (配置文件，非IIS部署可以删除)
│   │   ├── xblms.json (配置文件)
├── appsettings.json (配置文件)
├── build.sln (解决方案，用于发布)
├── gulpfile.js (配置文件，用于发布)
├── xblms.sln (解决方案，用于开发)
```


## 项目部署


发布跨平台版本，为了构建和发布适用于不同操作系统的XBLMS，请遵循以下步骤：


**Windows (x64\)**


1、执行以下命令来安装依赖项、构建前端资源、编译.NET解决方案并发布.NET Core应用程序：




```
npm install
npm run build-win-x64
dotnet build ./build-win-x64/build.sln -c Release
dotnet publish ./build-win-x64/src/XBLMS.Web/XBLMS.Web.csproj -r win-x64 -c Release -o ./publish/xblms-win-x64
```


2、然后进入发布目录获取部署文件




```
cd ./publish/xblms-win-x64
```


**Linux (x64\)**


1、执行以下命令来安装依赖项、构建前端资源、编译.NET解决方案并发布.NET Core应用程序：




```
npm install
npm run build-linux-x64
dotnet build ./build-linux-x64/build.sln -c Release
dotnet publish ./build-linux-x64/src/XBLMS.Web/XBLMS.Web.csproj -r linux-x64 -c Release -o ./publish/xblms-linux-x64
```


2、然后进入发布目录获取部署文件




```
cd ./publish/xblms-linux-x64
```


**注意事项**


* 确保所有依赖项都已正确安装。
* 在执行构建命令之前，请检查`.csproj`文件中的路径是否正确。
* 如果需要针对不同的Linux发行版进行交叉编译，可能还需要额外的步骤来设置正确的交叉编译工具链。
* 确认`.NET SDK`版本与项目要求相符。
* 对于Linux环境，建议在一个与目标系统相同架构的机器上进行构建，以避免潜在的二进制兼容性问题。
* 发布和部署手册：https://gitee.com/xblms/xblms/tree/master/部署手册


## 项目效果


演示环境为单机构版本，多机构版本麻烦自己在本地运行代码体验。


主要区别在于按公司和部门进行权限划分，各自管理和组织考试。


**管理端**


![](https://img2024.cnblogs.com/blog/576536/202410/576536-20241028145345288-1164716137.png)


![](https://img2024.cnblogs.com/blog/576536/202410/576536-20241028145456439-2140443414.png)


 


![](https://img2024.cnblogs.com/blog/576536/202410/576536-20241028145409272-1427884765.png)


**用户端**


![](https://img2024.cnblogs.com/blog/576536/202410/576536-20241028145535374-1175404132.png)


![](https://img2024.cnblogs.com/blog/576536/202410/576536-20241028145554256-1689205330.png)


![](https://img2024.cnblogs.com/blog/576536/202410/576536-20241028145619535-206127873.png)


**移动端**


![](https://img2024.cnblogs.com/blog/576536/202410/576536-20241028145640374-1539098094.png)


![](https://img2024.cnblogs.com/blog/576536/202410/576536-20241028145656939-1029901296.jpg)


**注意事项**


* 由于演示环境限制，同一个账号不能同时在多个设备上登录。
* 如果突然被强制离线，可能是其他用户登录了同一账号，请重新登录尝试。


## 项目总结


本文展示了部分功能和内容，如有需求访问项目地址获取详细信息。希望本文能在考试系统开发方面为各位提供有益的帮助。期待大家在评论区留言交流，分享您的宝贵经验和建议。


## 项目地址


**Gitee：**https://gitee.com/xblms/xblmes


## 最后


如果你觉得这篇文章对你有帮助，不妨点个赞支持一下！你的支持是我继续分享知识的动力。如果有任何疑问或需要进一步的帮助，欢迎随时留言。


也可以加入微信公众号**\[DotNet技术匠]** 社区，与其他热爱技术的同行一起交流心得，共同成长！**优秀是一种习惯，欢迎大家留言学习！**


![](https://img2024.cnblogs.com/blog/576536/202408/576536-20240814113403514-910171896.png)


