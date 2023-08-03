[English](https://github.com/abpframework/awesome-abp/blob/main/README.md) | 简体中文 | [Türkçe](README.tr.md)

# Awesome ABP!

[ABP Framework](https://github.com/abpframework/abp) 相关资源的分类清单.

## 目录
- [Awesome ABP!](#awesome-abp)
  - [目录](#目录)
  - [一、官方链接](#一官方链接)
    - [1、官方站点](#1官方站点)
    - [2、其他官方链接](#2其他官方链接)
  - [二、其他清单](#二其他清单)
  - [三、教程/博文](#三教程博文)
    - [1、官方教程](#1官方教程)
    - [2、社区博文](#2社区博文)
    - [3、其他教程](#3其他教程)
  - [四、UI主题](#四ui主题)
    - [1、官方主题](#1官方主题)
    - [2、社区开源主题](#2社区开源主题)
  - [五、应用模块](#五应用模块)
    - [1、开源/免费模块](#1开源免费模块)
      - [1.1、官方开源/免费模块](#11官方开源免费模块)
      - [1.2、社区开源模块](#12社区开源模块)
    - [2、商业化模块](#2商业化模块)
      - [2.1、官方商业化模块](#21官方商业化模块)
  - [六、工具](#六工具)
  - [七、NuGet / NPM 软件包](#七nuget--npm-软件包)
  - [八、视频教程](#八视频教程)
    - [1、英文版](#1英文版)
    - [2、其他语言](#2其他语言)
      - [2.1、Türkçe (土耳其语)](#21türkçe-土耳其语)


## 一、官方链接

### 1、官方站点

* **[abp.io](https://abp.io/)** (主页)
* **[docs.abp.io](https://docs.abp.io/zh-Hans/abp/latest/)** (开发文档)
* **[community.abp.io](https://community.abp.io/)** (ABP社区)
* **[blog.abp.io](https://blog.abp.io/)** (官方博客)
* **[commercial.abp.io](https://commercial.abp.io/)** (ABP商业版支持)

### 2、其他官方链接

* [**twitter**.com/abpframework](https://twitter.com/abpframework)
* [**discord**.gg/abp](https://discord.gg/abp)
* [**stackoverflow**.com/questions/tagged/abp](https://stackoverflow.com/questions/tagged/abp)
* [**github**.com/abpframework](https://github.com/abpframework)

## 二、其他清单

* [Awesome ABP](https://github.com/EasyAbp/awesome-abp) (EasyAbp社区)

## 三、教程/博文

### 1、官方教程

* [Getting Started](https://docs.abp.io/zh-Hans/abp/latest/Getting-Started?UI=MVC&DB=EF&Tiered=No): 使用ABP框架创建一个脚手架应用以快速开始开发.
* [Quick Start](https://docs.abp.io/en/abp/latest/Tutorials/Todo/Overall): 开始使用ABP框架并创建一个简单的TODO应用程序.
* [Web Application Development](https://docs.abp.io/zh-Hans/abp/latest/Tutorials/Part-1?UI=MVC&DB=EF): 10步教你快速创建一个全功能的web应用程序.

### 2、社区博文

​	关注 [community.abp.io/posts](https://community.abp.io/posts)了解更多关于ABP框架核心团队和社区发布的最新文章.

### 3、其他教程

​	TODO...

## 四、UI主题

### 1、官方主题

* [Basic Theme](https://docs.abp.io/en/abp/latest/UI/AspNetCore/Basic-Theme): 基于Bootstrap框架构建的一个简约主题，并且未新增任何新的样式。你可以把它作为基础主题，并且在此基础上构建自己的主题或样式.
* [Lepton Theme](https://docs.abp.io/en/commercial/latest/themes/lepton): 一个专业的UI主题，有多种颜色和风格选项.
* [LeptonX Theme](https://x.leptontheme.com/): 一个现代的、响应式的、灵活的UI主题，新的应用程序推荐使用这个主题。它有两个版本：
  * [LeptonX Lite](https://docs.abp.io/en/abp/latest/Themes/LeptonXLite/AspNetCore): 免费版缺少一些高级功能和配置选项
  * [LeptonX](https://docs.abp.io/en/commercial/latest/themes/lepton-x/mvc): 具有所有功能和配置选项的完整版本

### 2、社区开源主题

​	TODO...

## 五、应用模块

​	一个应用模块提供一个完整的、独立实现的应用且包含业务功能，它们通常有自己的实体、服务、API和UI组件.

### 1、开源/免费模块

#### 1.1、官方开源/免费模块

​	以下这些应用模块都是由ABP核心团队创建和维护的.

* [Account](https://docs.abp.io/zh-Hans/abp/latest/Modules/Account): 为账户管理提供用户界面，允许用户登录/注册应用程序.
* [Audit Logging](https://docs.abp.io/zh-Hans/abp/latest/Modules/Audit-Logging): 将审计日志持久化到数据库中.
* [Background Jobs](https://docs.abp.io/zh-Hans/abp/latest/Modules/Background-Jobs): 一个在后台持久运行的任务管理模块.
* [Blogging](https://commercial.abp.io/modules/Volo.Blogging): 创建和管理你自己的博客站点 (不再维护，请使用 [CMS Kit](https://docs.abp.io/en/abp/latest/Modules/Cms-Kit/Index)或者[blogging feature](https://docs.abp.io/en/abp/latest/Modules/Cms-Kit/Blogging) 作为替代品).
* [CMS Kit](https://docs.abp.io/zh-Hans/abp/latest/Modules/Cms-Kit/Index): 一套可复用的内容管理系统套件模块.
* [Docs](https://docs.abp.io/zh-Hans/abp/latest/Modules/Docs): 用于创建一个管理技术文档的站点. ABP框架[官方文档](https://docs.abp.io/) 已经在使用这个模块.
* [Feature Management](https://docs.abp.io/zh-Hans/abp/latest/Modules/Feature-Management): 系统功能管理模块[查看详情](https://docs.abp.io/en/abp/latest/Features).
* [Identity](https://docs.abp.io/zh-Hans/abp/latest/Modules/Identity): 基于微软官方身份认证库，用以管理组织、角色、用户和他们的权限.
* [IdentityServer](https://docs.abp.io/zh-Hans/abp/latest/Modules/IdentityServer): 集成IdentityServer4.
* [Permission Management](https://docs.abp.io/zh-Hans/abp/latest/Modules/Permission-Management): 用于权限管理以及持久化.
* [Setting Management](https://docs.abp.io/zh-Hans/abp/latest/Modules/Setting-Management): 用于管理和持久化系统设置信息 [查看详情](https://docs.abp.io/zh-Hans/abp/latest/Settings).
* [Tenant Management](https://docs.abp.io/zh-Hans/abp/latest/Modules/Tenant-Management): 租户系统[多租户](https://docs.abp.io/en/abp/latest/Multi-Tenancy)管理模块.

#### 1.2、社区开源模块

​	TODO...

### 2、商业化模块

#### 2.1、官方商业化模块

* [Account](https://commercial.abp.io/modules/Volo.Account.Pro): 整合登录、注册、忘记密码、电子邮件激活、社交登录和其他账户相关功能.
* [Audit Logging](https://commercial.abp.io/modules/Volo.AuditLogging.Ui): 用户审计日志以及实体变更历史报表.
* [Chat](https://commercial.abp.io/modules/Volo.Chat): 在线即时通讯系统.
* [CMS Kit](https://commercial.abp.io/modules/Volo.CmsKit.Pro): 构建定制化的内容管理系统.
* [File Management](https://commercial.abp.io/modules/Volo.FileManagement): 文件管理系统（文件上传、下载、分层管理）.
* [Forms](https://commercial.abp.io/modules/Volo.Forms): 问卷调查系统.
* [GDPR](https://commercial.abp.io/modules/Volo.Gdpr): 允许用户下载和删除应用程序收集的个人数据.
* [Identity](https://commercial.abp.io/modules/Volo.Identity.Pro): 用户、角色、组织和权限管理.
* [Identity Server UI](https://commercial.abp.io/modules/Volo.Identityserver.Ui): 用户身份认证管理服务，如客户端、API资源、身份资源、秘密、应用程序URL、claims等.
* [Language Management](https://commercial.abp.io/modules/Volo.LanguageManagement): 系统UI本地化资源管理.
* [Payment](https://commercial.abp.io/modules/Volo.Payment): 集成各种支付网关.
* [SaaS](https://commercial.abp.io/modules/Volo.Saas): 管理租户、版本和功能，创建你的多租户或者SaaS应用程序.
* [Text Template Management](https://commercial.abp.io/modules/Volo.TextTemplateManagement): 提供一个用于管理文本或邮件模版的管理系统.
* [Twilio SMS](https://commercial.abp.io/modules/Volo.Abp.Sms.Twilio): 通过Twilio云服务发送短信.

## 六、工具

* [ABP CLI](https://docs.abp.io/zh-Hans/abp/latest/CLI): ABP框架的官方CLI.
* [ABP Suite](https://commercial.abp.io/tools/suite): 自动生成基于分层结构的CRUD页面工具，并且安装和下载应用模块的源代码. 这个工具属于 [ABP商业版](https://commercial.abp.io/) 的一部分.
* * [AbpDevTools](https://github.com/enisn/AbpDevTools): 非官方的 CLI 应用程序，包含一组使 ABP 开发变得更容易的工具。
* 
## 七、NuGet / NPM 软件包

* [所有官方NuGet和NMP软件包](https://abp.io/packages)

## 八、视频教程

​	请查看 **[community.abp.io](https://community.abp.io/)** 网站，了解我们在这里或者其他平台发表的ABP框架和.NET相关的最新视频帖子，以下罗列了部分视频资源：

### 1、英文版

* [基于ABP框架构建.NET微服务 - 全系列](https://community.abp.io/posts/.net-microservice-with-abp-full-series-m6opqjb1)

### 2、其他语言

#### 2.1、Türkçe (土耳其语)

* [ABP & Blazor ile kapsamlı bir eğitim seti](https://www.udemy.com/course/web-tabanli-on-muhasebe-1-5/) (Udemy, toplam 100 saat)
* [ABP Framework Eğitim Serisi](https://www.youtube.com/watch?v=JvwPpSTEAvg&list=PLBEMB-Eql15s3kaMvQ6pIobVk492a7s9j&index=1)  (YouTube, ücretsiz)
