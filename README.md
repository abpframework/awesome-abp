# Awesome ABP!

A categorized list of [ABP Framework](https://github.com/abpframework/abp) related resources.

## Table of Contents

- [Official Links](#official-links)
- [Other Lists](#other-lists)
- [Tutorials](#tutorials--articles)
- [UI Themes](#ui-themes)
- [Application Modules](#application-modules)
- [Tools](#tools)
- [NuGet / NPM Packages](#nuget--npm-packages)
- [Video Trainings](#video-trainings)

## Official Links

### The official website

* **[abp.io](https://abp.io/)** (home page)
* **[docs.abp.io](https://docs.abp.io/)** (main documentation)
* **[community.abp.io](https://community.abp.io/)** (posts and events related to ABP and .NET)
* **[blog.abp.io](https://blog.abp.io/)** (official blog for the latest news and releases)
* **[commercial.abp.io](https://commercial.abp.io/)** (commercial startup templates, UI themes, application modules, tooling and support)

### Other official links

* [**twitter**.com/abpframework](https://twitter.com/abpframework)
* [**discord**.gg/abp](https://discord.gg/abp)
* [**stackoverflow**.com/questions/tagged/abp](https://stackoverflow.com/questions/tagged/abp)
* [**github**.com/abpframework](https://github.com/abpframework)

## Other Lists

* [Awesome ABP](https://github.com/EasyAbp/awesome-abp) (by EasyAbp Community): A list of ABP related resources, just like this repository.

## Tutorials / Articles

### Official Tutorials

* [Getting Started](https://docs.abp.io/en/abp/latest/Getting-Started): Create an application with the ABP Framework and make it ready for development.
* [Quick Start](https://docs.abp.io/en/abp/latest/Tutorials/Todo/Overall): Get started with the ABP Framework and create a simple TODO application.
* [Web Application Development](https://docs.abp.io/en/abp/latest/Tutorials/Part-1): 10-parts tutorial to create a full featured web application.

### Community Posts

See [community.abp.io/posts](https://community.abp.io/posts) for the latest articles posted by the core ABP Framework team and the ABP community.

### Other Tutorials

TODO...

## UI Themes

### Official Themes

* [Basic Theme](https://docs.abp.io/en/abp/latest/UI/AspNetCore/Basic-Theme): A minimalist theme that doesn't add any styling on top of the plain Bootstrap. You can take the Basic Theme as the base theme and build your own theme or styling on top of it.
* [Lepton Theme](https://docs.abp.io/en/commercial/latest/themes/lepton): A professional UI theme with multiple color and style options.
* [LeptonX Theme](https://x.leptontheme.com/): A modern, responsive and flexible UI theme. This is the recommended theme for new applications. It has two versions:
  * [LeptonX Lite](https://docs.abp.io/en/abp/latest/Themes/LeptonXLite/AspNetCore): Free version with less features and options.
  * [LeptonX](https://docs.abp.io/en/commercial/latest/themes/lepton-x/commercial/mvc): Full version with all the features and options.

### Community Themes

TODO...

## Application Modules

An application module provides a fully implemented application/business functionality, typically with its own entities, services, APIs and UI components.

### Open Source / Free Modules

#### Official Open Source / Free Modules

These application modules are created and maintained by the core ABP team.

* [Account](https://docs.abp.io/en/abp/latest/Modules/Account): Provides UI for the account management and allows user to login/register to the application.
* [Audit Logging](https://docs.abp.io/en/abp/latest/Modules/Audit-Logging): Persists audit logs to a database.
* [Background Jobs](https://docs.abp.io/en/abp/latest/Modules/Background-Jobs): Persist background jobs when using the default background job manager.
* [Blogging](https://commercial.abp.io/modules/Volo.Blogging): Create and manage your own blogs (Not developed anymore, use the [CMS Kit](https://docs.abp.io/en/abp/latest/Modules/Cms-Kit/Index) [blogging feature](https://docs.abp.io/en/abp/latest/Modules/Cms-Kit/Blogging) instead).
* [CMS Kit](https://docs.abp.io/en/abp/latest/Modules/Cms-Kit/Index): A set of reusable *Content Management System* features.
* [Docs](https://docs.abp.io/en/abp/latest/Modules/Docs): Used to create technical documentation website. ABP's [own documentation](https://docs.abp.io/) already using this module.
* [Feature Management](https://docs.abp.io/en/abp/latest/Modules/Feature-Management): Used to persist and manage the [features](https://docs.abp.io/en/abp/latest/Features).
* [Identity](https://docs.abp.io/en/abp/latest/Modules/Identity): Manages organization units, roles, users and their permissions, based on the Microsoft Identity library.
* [IdentityServer](https://docs.abp.io/en/abp/latest/Modules/IdentityServer): Integrates to IdentityServer4.
* [Permission Management](https://docs.abp.io/en/abp/latest/Modules/Permission-Management): Used to persist permissions.
* [Setting Management](https://docs.abp.io/en/abp/latest/Modules/Setting-Management): Used to persist and manage the [settings](https://docs.abp.io/en/abp/latest/Settings).
* [Tenant Management](https://docs.abp.io/en/abp/latest/Modules/Tenant-Management): Manages tenants for a [multi-tenant](https://docs.abp.io/en/abp/latest/Multi-Tenancy) application.

#### Community Modules

TODO...

### Commercial Modules

#### Official Commercial Modules

* [Account](https://commercial.abp.io/modules/Volo.Account.Pro): Login, register, forgot password, email activation, social logins and other account related functionalities.
* [Audit Logging](https://commercial.abp.io/modules/Volo.AuditLogging.Ui): Reporting the user audit logs and entity histories in details.
* [Chat](https://commercial.abp.io/modules/Volo.Chat): Real time messaging between users.
* [CMS Kit](https://commercial.abp.io/modules/Volo.CmsKit.Pro): Building blocks to create your own Content Management System.
* [File Management](https://commercial.abp.io/modules/Volo.FileManagement): Upload, download and organize files in a hierarchical folder structure.
* [Forms](https://commercial.abp.io/modules/Volo.Forms): Create forms and surveys to your users.
* [GDPR](https://commercial.abp.io/modules/Volo.Gdpr): Allows users to download and delete their personal data collected by the application.
* [Identity](https://commercial.abp.io/modules/Volo.Identity.Pro): User, role, organization unit and permission management.
* [Identity Server UI](https://commercial.abp.io/modules/Volo.Identityserver.Ui): Managing the identity server objects like clients, API resources, identity resources, secrets, application URLs, claims and more.
* [Language Management](https://commercial.abp.io/modules/Volo.LanguageManagement): Add or remove languages and localize the application UI on the fly.
* [Payment](https://commercial.abp.io/modules/Volo.Payment): Provides integration for various payment gateways.
* [SaaS](https://commercial.abp.io/modules/Volo.Saas): Manage tenants, editions and features to create your multi-tenant / SaaS application.
* [Text Template Management](https://commercial.abp.io/modules/Volo.TextTemplateManagement): Edit text/email templates on the user interface.
* [Twilio SMS](https://commercial.abp.io/modules/Volo.Abp.Sms.Twilio): Sends SMS over Twilio Cloud service.

## Tools

* [ABP CLI](https://docs.abp.io/en/abp/latest/CLI): Official CLI for the ABP Framework.
* [ABP Suite](https://commercial.abp.io/tools/suite): A tool to automatically generate fully layered CRUD-style pages, install and download source of the application modules. This tool is a part of the [ABP Commercial](https://commercial.abp.io/) product.

## NuGet / NPM Packages

* [All the official NuGet and NMP packages](https://abp.io/packages)

## Video Trainings

Check **[community.abp.io](https://community.abp.io/)** website for the latest video posts for ABP and .NET. Here, we list some of the posts published there and other platforms.

### English

* [.NET Microservices with ABP - Full Series](https://community.abp.io/posts/.net-microservice-with-abp-full-series-m6opqjb1)

### Non-English

#### Türkçe (Turkish)

* [ABP & Blazor ile kapsamlı bir eğitim seti](https://www.udemy.com/course/web-tabanli-on-muhasebe-1-5/) (Udemy, toplam 100 saat)
* [ABP Framework Eğitim Serisi](https://www.youtube.com/watch?v=JvwPpSTEAvg&list=PLBEMB-Eql15s3kaMvQ6pIobVk492a7s9j&index=1)  (YouTube, ücretsiz)
