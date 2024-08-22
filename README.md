English｜[简体中文](README.zh-Hans.md) | [Türkçe](README.tr.md)

# Awesome ABP!

A categorized list of [ABP](https://github.com/abpframework/abp) related resources.

## Table of Contents

- [Official Links](#official-links)
- [Other Lists](#other-lists)
- [Tutorials](#tutorials--articles)
- [Events](#events)
- [UI Themes](#ui-themes)
- [Application Modules](#application-modules)
- [Tools](#tools)
- [NuGet / NPM Packages](#nuget--npm-packages)
- [Video Trainings](#video-trainings)

## Official Links

### The official website

* **[abp.io](https://abp.io/)** (home page for ABP Platform - including pro startup templates, features, modules, tooling and support -)
* **[abp.io/docs](https://abp.io/docs/latest/)** (main documentation)
* **[abp.io/community](https://abp.io/community/)** (posts and events related to ABP and .NET)
* **[abp.io/blog](https://abp.io/blog/)** (official blog for the latest news and releases)

### Other official links

* [**twitter**.com/abpframework](https://twitter.com/abpframework)
* [**discord**.gg/abp](https://discord.gg/abp)
* [**stackoverflow**.com/questions/tagged/abp](https://stackoverflow.com/questions/tagged/abp)
* [**github**.com/abpframework](https://github.com/abpframework)

## Other Lists

* [Awesome ABP](https://github.com/EasyAbp/awesome-abp) (by EasyAbp Community): A list of ABP related resources, just like this repository.

## Tutorials / Articles

### Official Tutorials

* [Getting Started](https://abp.io/docs/latest/get-started/layered-web-application): Create an application with ABP and make it ready for development.
* [Quick Start](https://abp.io/docs/latest/tutorials/todo): Get started with ABP and create a simple TODO application.
* [Web Application Development](https://abp.io/docs/latest/tutorials/book-store/part-01): 10-parts tutorial to create a full featured web application.

### Community Posts

See [abp.io/community/articles](https://abp.io/community/articles) for the latest articles posted by the core ABP team and the ABP community.

## Events

You can check the following list for the online events, demos, and Q&A sessions organized by the ABP team:

* [ABP Community Talks](https://www.youtube.com/playlist?list=PLsNclT2aHJcOsPustEkzG6DywiO8eh0lB)
* [ABP .NET Conference 2023](https://www.youtube.com/playlist?list=PLsNclT2aHJcPTA3D4fIF10fsbhbckEbBC)
* [ABP Dotnet Conference 2024](https://www.youtube.com/playlist?list=PLsNclT2aHJcNbSrRbO4K36Pm0Pa8MDC-A)

> Don't forget to subscribe to [our YouTube channel](https://www.youtube.com/c/Volosoft) to inform what's new in ABP!

## UI Themes

### Official Themes

* [Basic Theme](https://abp.io/docs/latest/framework/ui/mvc-razor-pages/basic-theme): A minimalist theme that doesn't add any styling on top of the plain Bootstrap. You can take the Basic Theme as the base theme and build your own theme or styling on top of it.
* [Lepton Theme](https://abp.io/docs/latest/ui-themes/lepton): A professional UI theme with multiple color and style options.
* [LeptonX Theme](https://x.leptontheme.com/): A modern, responsive and flexible UI theme. This is the recommended theme for new applications. It has two versions:
  * [LeptonX Lite](https://abp.io/docs/latest/ui-themes/lepton-x-lite/asp-net-core): Free version with less features and options.
  * [LeptonX](https://abp.io/docs/latest/ui-themes/lepton-x/mvc): Full version with all the features and options.

## Application Modules

An application module provides a fully implemented application/business functionality, typically with its own entities, services, APIs and UI components.

### Open Source / Free Modules

#### Official Open Source / Free Modules

These application modules are created and maintained by the core ABP team.

* [Account](https://abp.io/docs/latest/Modules/Account): Provides UI for the account management and allows user to login/register to the application.
* [Audit Logging](https://abp.io/docs/latest/Modules/Audit-Logging): Persists audit logs to a database.
* [Background Jobs](https://abp.io/docs/latest/Modules/Background-Jobs): Persist background jobs when using the default background job manager.
* [Blogging](https://abp.io/modules/Volo.Blogging): Create and manage your own blogs (Not developed anymore, use the [CMS Kit](https://abp.io/docs/latest/Modules/Cms-Kit/Index) [blogging feature](https://abp.io/docs/latest/Modules/Cms-Kit/Blogging) instead).
* [CMS Kit](https://abp.io/docs/latest/Modules/Cms-Kit/Index): A set of reusable *Content Management System* features.
* [Docs](https://abp.io/docs/latest/Modules/Docs): Used to create technical documentation website. ABP's [own documentation](https://abp.io/docs) already using this module.
* [Feature Management](https://abp.io/docs/latest/Modules/Feature-Management): Used to persist and manage the [features](https://abp.io/docs/latest/framework/infrastructure/features).
* [Identity](https://abp.io/docs/latest/Modules/Identity): Manages organization units, roles, users and their permissions, based on the Microsoft Identity library.
* [IdentityServer](https://abp.io/docs/latest/Modules/IdentityServer): Integrates to IdentityServer4.
* [OpenIddict](https://abp.io/docs/latest/Modules/OpenIddict): Integrates to OpenIddict.
* [Permission Management](https://abp.io/docs/latest/Modules/Permission-Management): Used to persist permissions.
* [Setting Management](https://abp.io/docs/latest/Modules/Setting-Management): Used to persist and manage the [settings](https://abp.io/docs/latest/framework/infrastructure/settings).
* [Tenant Management](https://abp.io/docs/latest/Modules/Tenant-Management): Manages tenants for a [multi-tenant](https://abp.io/docs/latest/framework/architecture/multi-tenancy) application.

### Commercial Modules

#### Official Commercial Modules

* [Account](https://abp.io/modules/Volo.Account.Pro): Login, register, forgot password, email activation, social logins and other account related functionalities.
* [Audit Logging](https://abp.io/modules/Volo.AuditLogging.Ui): Reporting the user audit logs and entity histories in details.
* [Chat](https://abp.io/modules/Volo.Chat): Real time messaging between users.
* [CMS Kit](https://abp.io/modules/Volo.CmsKit.Pro): Building blocks to create your own Content Management System.
* [File Management](https://abp.io/modules/Volo.FileManagement): Upload, download and organize files in a hierarchical folder structure.
* [Forms](https://abp.io/modules/Volo.Forms): Create forms and surveys to your users.
* [GDPR](https://abp.io/modules/Volo.Gdpr): Allows users to download and delete their personal data collected by the application.
* [Identity](https://abp.io/modules/Volo.Identity.Pro): User, role, organization unit and permission management.
* [Identity Server UI](https://abp.io/modules/Volo.Identityserver.Ui): Managing the identity server objects like clients, API resources, identity resources, secrets, application URLs, claims and more.
* [Language Management](https://abp.io/modules/Volo.LanguageManagement): Add or remove languages and localize the application UI on the fly.
* [Payment](https://abp.io/modules/Volo.Payment): Provides integration for various payment gateways.
* [SaaS](https://abp.io/modules/Volo.Saas): Manage tenants, editions and features to create your multi-tenant / SaaS application.
* [Text Template Management](https://abp.io/modules/Volo.TextTemplateManagement): Edit text/email templates on the user interface.
* [Twilio SMS](https://abp.io/modules/Volo.Abp.Sms.Twilio): Sends SMS over Twilio Cloud service.

## Tools

* [ABP CLI](https://abp.io/docs/latest/CLI): Official CLI for the ABP Platform.
* [ABP Suite](https://abp.io/suite): A tool to automatically generate fully layered CRUD-style pages, install and download source of the application modules. This tool can only be used by active license owners.
* [ABP Studio](https://abp.io/studio): ABP Studio is a cross-platform desktop application that aims to provide a comfortable development environment for you by automating things, providing insights about your solution, making develop, run and deploy your solutions much easier.
* [AbpDevTools](https://github.com/enisn/AbpDevTools): Unofficial a CLI application that includes a set of tools to make development with ABP easier.

## NuGet / NPM Packages

* [All the official NuGet and NPM packages](https://abp.io/packages)

## Video Trainings

Check **[abp.io/community](https://abp.io/community/)** website for the latest video posts for ABP and .NET. Here, we list some of the posts published there and other platforms.

### English

* [.NET Microservices with ABP - Full Series](https://abp.io/community/videos/.net-microservice-with-abp-full-series-m6opqjb1)

### Non-English

#### Türkçe (Turkish)

* [ABP & Blazor ile kapsamlı bir eğitim seti](https://www.udemy.com/course/web-tabanli-on-muhasebe-1-5/) (Udemy, toplam 100 saat)
* [ABP Framework Eğitim Serisi](https://www.youtube.com/watch?v=JvwPpSTEAvg&list=PLBEMB-Eql15s3kaMvQ6pIobVk492a7s9j&index=1)  (YouTube, ücretsiz)
