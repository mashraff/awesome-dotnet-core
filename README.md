# Awesome .NET Core [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A collection of awesome [.NET Core](#frameworks-libraries-and-tools) frameworks, libraries, tools, resources and software.

Inspired by [awesome](https://github.com/sindresorhus/awesome), [awesome-dotnet](https://github.com/quozd/awesome-dotnet),  [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs), [frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks).

Contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/thangchung/awesome-dotnet-core/blob/master/contributing.md) pages first. We accept proprietary and commercial software too.

Thanks to all [contributors](https://github.com/thangchung/awesome-dotnet-core/graphs/contributors), you're awesome and wouldn't be possible without you! The goal is to build a categorized community-driven collection of very well-known resources.

## Contents

* [General](#general)
* [Frameworks, Libraries and Tools](#frameworks-libraries-and-tools)  
  * [API](#api)
  * [Application Frameworks](#application-frameworks)
  * [Application Templates](#application-templates)
  * [Authentication and Authorization](#authentication-and-authorization)
  * [Build Automation](#build-automation)
  * [Bundling and Minification](#bundling-and-minification)
  * [Caching](#caching)
  * [Cryptography](#cryptography)
  * [CMS](#cms)
  * [Code Analysis and Metrics](#code-analysis-and-metrics)
  * [Compilers, Transpilers and Languages](#compilers-transpilers-and-languages)
  * [Database Drivers](#database-drivers)
  * [E-Commerce and Payments](#e-commerce-and-payments)
  * [Graphics](#graphics)
  * [Functional Programming](#functional-programming)
  * [IDE](#ide)
  * [Internationalization](#internationalization)
  * [IOC](#ioc)
  * [Logging](#logging)
  * [Mail](#mail)
  * [Mathematics](#mathematics)
  * [Misc](#misc)
  * [ORM](#orm)
  * [Profiling](#profiling)
  * [Queue and Messaging](#queue-and-messaging)
  * [Scheduler and Job](#scheduler-and-job)
  * [SDKs](#sdks)
  * [Security](#security)
  * [Searching](#searching)
  * [Serialization](#serialization)
  * [Testing](#testing)
  * [Tools](#tools)
  * [Web Framework](#web-framework)
  * [Web Socket](#web-socket)
  * [Windows Service](#windows-service)
* [Starter Kits](#starter-kits)
* [Sample Projects](#sample-projects)
* [Articles](#articles)
* [Books](#books)
* [Videos](#videos)
* [Podcasts](#podcasts)
* [Community](#community)

## General

* [ASP.NET Core Documentation](https://docs.asp.net/en/latest/) - The official ASP.NET Core documentation site.
* [.NET Core Documentation](https://docs.microsoft.com/en-us/dotnet/articles/welcome) - Home of the technical documentation for .NET Core, C#, F# and Visual Basic, including basic concepts, getting started instructions, tutorials and samples.
* [.NET Core SDK](https://www.microsoft.com/net/core) - .NET Core SDK is a general purpose development platform maintained by Microsoft and the .NET community on [GitHub](https://github.com/dotnet/core). 
* [.NET Platform Standard](https://github.com/dotnet/corefx/blob/master/Documentation/architecture/net-platform-standard.md) - The differrent between the old version and the new version of .NET.

## Frameworks, Libraries and Tools

### API
* [autorest](https://github.com/Azure/autorest) - Swagger (OpenAPI) Specification code generator featuring C# and Razor templates. Supports C#, Java, Node.js, TypeScript, Python and Ruby. `4.5.x or above`
* [Flurl](https://github.com/tmenier/Flurl) - Fluent URL builder and testable HTTP for .NET [http://tmenier.github.io/Flurl](http://tmenier.github.io/Flurl).
* [LightNode](https://github.com/neuecc/LightNode) - Micro RPC/REST Framework built on OWIN [http://neuecc.github.io/LightNode](http://neuecc.github.io/LightNode).
* [NSwag](https://github.com/NSwag/NSwag) - The Swagger API toolchain for .NET, Web API and TypeScript [http://NSwag.org](http://NSwag.org).
* [refit](https://github.com/paulcbetts/refit) - The automatic type-safe REST library for Xamarin and .NET [http://paulcbetts.github.io/refit/](http://paulcbetts.github.io/refit/).
* [RESTClient .NET](https://bitbucket.org/MelbourneDeveloper/restclient-.net) - Simple REST Client for all .NET platforms.
* [RestEase](https://github.com/canton7/RestEase) - Easy-to-use typesafe REST API client library, which is simple and customisable.
* [Swashbuckle](https://github.com/domaindrivendev/Ahoy) - Seamlessly adds a swagger to WebApi projects.
* [WebAPIContrib for ASP.NET CORE](https://github.com/WebApiContrib/WebAPIContrib.Core) - Community Contributions for ASP.NET Core.
* GraphQL
  * [graphql-dotnetcore](https://github.com/mkmarek/graphql-dotnetcore) - GraphQL for .NET Core based on [https://github.com/graphql/graphql-js](https://github.com/graphql/graphql-js).
  * [graphql-dotnet](https://github.com/graphql-dotnet/graphql-dotnet) - GraphQL for .NET.
  * [parser](https://github.com/graphql-dotnet/parser) - A lexer and parser for GraphQL in .NET.

### Application Frameworks
* [akka.net](https://github.com/akkadotnet/akka.net/tree/netcore) - Toolkit and runtime for building highly concurrent, distributed, and fault tolerant event-driven applications on .NET & Mono. `Stable version only works for 4.5.x, but development version is available for .NET Core 1.0`
* [ASP.NET MVC](https://github.com/aspnet/Mvc) - Model view controller framework for building dynamic web sites with clean separation of concerns, including the merged MVC, Web API, and Web Pages w/ Razor.
* [ExtCore](https://github.com/ExtCore) - Free, open source and cross-platform framework for creating modular and extendable web applications based on ASP.NET Core 1.0.
* [Halibut](https://github.com/OctopusDeploy/Halibut) - A secure communication stack for .NET using JSON-RPC over SSL.
* [grpc](https://github.com/grpc/grpc/tree/master/src/csharp) - Remote Procedure Calls (RPCs) provide a useful abstraction for building distributed applications and services. The libraries in this repository provide a concrete implementation of the gRPC protocol, layered over HTTP/2. These libraries enable communication between clients and servers using any combination of the supported languages.
* [Nancy](https://github.com/NancyFx/Nancy) - Lightweight, low-ceremony, framework for building HTTP based services on .NET and Mono.
* [ServiceStack](https://github.com/ServiceStack/ServiceStack) - Thoughtfully architected, obscenely fast, thoroughly enjoyable web services for all [https://servicestack.net](https://servicestack.net).
* [Steeltoe OSS](https://github.com/SteelToeOSS) - .NET toolkit for common microservice patterns.

### Application Templates
* [ASP.NET MVC Boilerplate](https://github.com/RehanSaeed/ASP.NET-MVC-Boilerplate) - A professional ASP.NET MVC template for building secure, fast, robust and adaptable web applications or sites. It provides the minimum amount of code required on top of the default MVC template provided by Microsoft.
* [kendo-ui-core](https://github.com/telerik/kendo-ui-core) - An HTML5, jQuery-based widget library for building modern web apps. [http://www.telerik.com/kendo-ui](http://www.telerik.com/kendo-ui).
* [JavaScriptServices](https://github.com/aspnet/JavaScriptServices) - Microsoft ASP.NET Core JavaScript Services.
* [ABP ASP.NET Boilerplate](https://github.com/aspnetboilerplate/aspnetboilerplate) - ASP.NET Boilerplate is a starting point for new modern web applications using best practices and popular tools.

### Authentication and Authorization
* [Identity](https://github.com/aspnet/Identity) - ASP.NET Core Identity is the membership system for building ASP.NET Core web applications, including membership, login, and user data.
* [IdentityServer](https://github.com/IdentityServer/IdentityServer4) - IdentityServer for ASP.NET Core 1.0
 * [20|20 IdentityServer4.EntityFrameworkCore](https://github.com/2020IP/TwentyTwenty.IdentityServer4.EntityFrameworkCore) - Entity Framework Core persistence layer for IdentityServer v4.
* [openiddict](https://github.com/openiddict/openiddict-core) - Easy-to-use OpenID Connect server for ASP.NET Core.
* [stormpath-sdk](https://github.com/stormpath/stormpath-sdk-dotnet) - Build [simple, secure web applications](https://github.com/stormpath/stormpath-aspnetcore) with Stormpath and ASP.NET Core.
* [stuntman](https://github.com/ritterim/stuntman) - Library for impersonating users during development leveraging ASP.NET Identity.

### Build Automation
* [cake-build](https://github.com/cake-build/cake) - Cross platform build automation system. [http://cakebuild.net](http://cakebuild.net).
* [Colorful.Console](https://github.com/tomakita/Colorful.Console) - Style your C# console output! [http://colorfulconsole.com](http://colorfulconsole.com).
* [go-dotnet](https://github.com/matiasinsaurralde/go-dotnet) - Go wrapper for the .NET Core Runtime.
* [msbuild](https://github.com/Microsoft/msbuild) - The Microsoft Build Engine is a platform for building applications.
* [vsts-agent](https://github.com/Microsoft/vsts-agent/blob/master/README.md) - Visual Studio Team Services Build and Release Agent.

### Bundling and Minification
* [BundlerMinifier](https://github.com/madskristensen/BundlerMinifier) - Visual Studio extension that let's you configure bundling and minification of JS, CSS and HTML files.
* [JavaScriptViewEngine](https://github.com/pauldotknopf/JavaScriptViewEngine) - ASP.NET MVC ViewEngine for rendering markup in a JavaScript environment. Ideal for React and Angular server-side rendering.
* [Smidge](https://github.com/Shazwazza/Smidge/) - Lightweight runtime CSS/JavaScript file minification, combination, compression & management library for ASP.NET Core.
* [Web Markup Minifier](https://github.com/Taritsyn/WebMarkupMin) - .NET library that contains a set of markup minifiers. The objective of this project is to improve the performance of web applications by reducing the size of HTML, XHTML and XML code.

### Caching
* [CacheManager](https://github.com/MichaCo/CacheManager) - Open source caching abstraction layer for .NET written in C#. It supports various cache providers and implements many advanced features. [http://cachemanager.net](http://cachemanager.net)
* [Foundatio](https://github.com/exceptionless/Foundatio) - Pluggable foundation blocks for building distributed apps.
* [Microsoft Caching](https://github.com/aspnet/Caching) - Libraries for in-memory caching and distributed caching.
* [Stack Exchange Redis](https://github.com/StackExchange/StackExchange.Redis) - High performance general purpose redis client for .NET languages (C# etc).

### Cryptography
* [BCrypt.NET-Core](https://github.com/neoKushan/BCrypt.Net-Core) - .NET Core port of BCrypt.NET used to store passwords securely.
* [BouncyCastle PCL](https://github.com/onovotny/BouncyCastle-PCL) - The Bouncy Castle Crypto package is a C# implementation of cryptographic algorithms and protocols.

### CMS
* [OrchardCMS2](https://github.com/OrchardCMS/Orchard2) - The implementation of Orchard CMS in ASP.NET Core (also known as DNX).
* [Platformus](https://github.com/Platformus) - Free, open source and cross-platform CMS based on ASP.NET Core 1.0 and ExtCore framework.
* [SimpleContent](https://github.com/joeaudette/cloudscribe.SimpleContent) - Simple, yet flexible content and blog engine for ASP.NET Core that can work with or without a database.

### Code Analysis and Metrics
* [App.Metrics](https://github.com/alhardy/AppMetrics) - App Metrics is an open-source and cross-platform .NET library used to record and report metrics within an application and reports it's health. See the [docs](https://alhardy.github.io/app-metrics-docs/) for me details.
* [AspNet.Metrics](https://github.com/alhardy/aspnet-metrics) - Capturing CLR, application-level web request metrics. Middleware and extensions using [Metrics.Net](https://github.com/Recognos/Metrics.NET).
* [Audit.NET](https://github.com/thepirat000/Audit.NET) - Small framework to audit .NET object changes.
* [BenchmarkDotNet](https://github.com/PerfDotNet/BenchmarkDotNet) - Powerful .NET library for benchmarking.
* [NBench](https://github.com/petabridge/NBench/tree/dev) - Performance benchmarking and testing framework for .NET applications. `4.5.x or above`
* [OpenCover](https://github.com/OpenCover/opencover) - Code coverage tool for .NET 2 and above (WINDOWS OS only), support for 32 and 64 processes with both branch and sequence points.

### Compilers, Transpilers and Languages
* [roslyn](https://github.com/dotnet/roslyn) - The .NET Compiler Platform ("Roslyn") provides open-source C# and Visual Basic compilers with rich code analysis APIs.
* [Sprache](https://github.com/sprache/Sprache) - Tiny C# Monadic Parser Framework.

### Database Drivers
* [LiteDB](https://github.com/mbdavid/LiteDB) - .NET NoSQL Document Store in a single data file - [http://www.litedb.org](http://www.litedb.org). `work-around for .NET Core at` [#219](https://github.com/mbdavid/LiteDB/issues/219)
* [MongoDB.Driver](https://github.com/mongodb/mongo-csharp-driver) - .NET Driver for MongoDB. `Stable version only works for 4.5.x, but beta available for .NET Core 1.0`
* [mysql-connector-net](https://github.com/mysql/mysql-connector-net/tree/7.0) - Connector/Net is a fully-managed ADO.NET driver for MySQL. [https://dev.mysql.com/downloads/connector/net](https://dev.mysql.com/downloads/connector/net/)
* [Neo4jClient](https://github.com/Readify/Neo4jClient/tree/DotNetCore) - .NET client binding for Neo4j.
* [npgsql](https://github.com/npgsql/npgsql) - .NET data provider for PostgreSQL. It allows any program developed for .NET framework to access a PostgreSQL database server. It is implemented in 100% C# code. PostgreSQL versions since 9.1 are officially supported, others may work. [http://www.npgsql.org](http://www.npgsql.org)
* [ravendb](https://github.com/ayende/ravendb/tree/v4.0) - Linq enabled document database for .NET.
* [RethinkDb.Driver](https://github.com/bchavez/RethinkDb.Driver) - C#/.NET RethinkDB driver with 100% ReQL API coverage.

### E-Commerce and Payments
* [SimplCommerce](https://github.com/simplcommerce/SimplCommerce) - Super simple ecommerce system built on .NET Core.
* [Stripe](https://github.com/ServiceStack/Stripe) - Typed .NET clients for stripe.com REST APIs.

### Graphics
* [ImageProcessor](https://github.com/JimBobSquarePants/ImageProcessor) - A fluent wrapper around System.Drawing for the processing of image files [http://imageprocessor.org](http://imageprocessor.org). `4.5.x or above`
* [ImageSharp](https://github.com/JimBobSquarePants/ImageSharp) - Cross-platform library for processing of image files written in C# [http://imageprocessor.org](http://imageprocessor.org).

### Functional Programming
* [CSharpFunctionalExtensions](https://github.com/vkhorikov/CSharpFunctionalExtensions) - Functional Extensions for C#.
* [language-ext](https://github.com/louthy/language-ext) - C# functional language extensions and 'Erlang like' concurrency system.
* [ReactiveUI](https://github.com/reactiveui/ReactiveUI) - A MVVM framework that integrates with the Reactive Extensions for .NET to create elegant, testable User Interfaces that run on any mobile or desktop platform.
* [Rx.NET](https://github.com/Reactive-Extensions/Rx.NET) - The [Reactive Extensions](http://reactivex.io) for .NET.
* [Optional](https://github.com/nlkl/Optional) - A robust option type for C#.
* [sodium](https://github.com/SodiumFRP/sodium/tree/master/c%23) - Functional Reactive Programming (FRP) Library. `4.5.x or above`

### IDE
* [rider](https://www.jetbrains.com/rider/) - Cross-platform C# IDE based on the IntelliJ platform and ReSharper.
* [Omnisharp](http://www.omnisharp.net/) - Family of Open Source projects, each with one goal: To enable a great .NET experience in YOUR editor of choice.
* [Visual Studio Code](https://github.com/Microsoft/vscode) - New type of tool that combines the simplicity of a code editor with what developers need for their core edit-build-debug cycle. Code provides comprehensive editing and debugging support, an extensibility model, and lightweight integration with existing tools.
* [Visual Studio Community](https://www.visualstudio.com/en-us/products/visual-studio-community-vs.aspx) - Free editor for individual developers, open source projects, academic research, education, and small professional teams.

### Internationalization
* [Localization](https://github.com/aspnet/Localization) - Localization abstractions and implementations for ASP.NET Core applications.
* [nodatime](https://github.com/nodatime/nodatime) - Better date and time API for .NET [http://nodatime.org](http://nodatime.org).

### IOC
* [Autofac](https://github.com/autofac/Autofac) - Addictive .NET IoC container.
* [DryIoc](https://bitbucket.org/dadhi/dryioc) - Fast, small, full-featured IoC Container for .NET.
* [LightInject](https://github.com/seesharper/LightInject) - Ultra lightweight IoC container [http://www.lightinject.net](http://www.lightinject.net).
* [SimpleInjector](https://github.com/simpleinjector/SimpleInjector) - Easy, flexible, and fast Dependency Injection library that promotes best practice to steer developers towards the pit of success.
* [StructureMap](https://github.com/structuremap/structuremap.dnx) - Dependency Injection/Inversion of Control tool for .NET.

### Logging
* [common-logging](https://github.com/net-commons/common-logging) - Portable logging abstraction for .NET [http://net-commons.github.io/common-logging](http://net-commons.github.io/common-logging).
* [dnxcore-logging-logstash](https://github.com/jvandevelde/dnxcore-logging-logstash) - Logstash logging extension for .NET Core applications with UDP and Redis transports.
* [serilog](https://github.com/serilog/serilog) - Simple .NET logging with fully-structured events.
* [NLog](https://github.com/NLog/NLog) - Advanced .NET, Silverlight and Xamarin Logging.
* [Q42.Logging.ApplicationInsights](https://github.com/Q42/Q42.Logging.ApplicationInsights) - Log appender for the build in ASP.NET Core logging to send all logs to Application Insights.

### Mail
* [MailBody](https://github.com/doxakis/MailBody) - Create transactional email with a fluent interface (.NET).
* [MailKit](https://github.com/jstedfast/MailKit) - Cross-platform .NET library for IMAP, POP3, and SMTP.
* [MailMergeLib](https://github.com/axuno/MailMergeLib) - SMTP mail client library which provides comfortable mail merge capabilities for text, inline images and attachments, as well as good throughput and fault tolerance for sending mail messages.
* [MimeKit](https://github.com/jstedfast/MimeKit) - Cross-platform .NET MIME creation and parser library with support for S/MIME, PGP, DKIM, TNEF and Unix mbox spools.
* [PreMailer.Net](https://github.com/milkshakesoftware/PreMailer.Net/tree/dotnet-core) - C# library that moves your stylesheets to inline style attributes, for maximum compatibility with E-mail clients.
* [SendGrid Client](https://github.com/0xdeafcafe/sendgrid-dotnet) - C# library for the SendGrid v3 mail endpoint.

### Mathematics
* [UnitConversion](https://github.com/Stratajet/UnitConversion) - Expansible Unit Conversion Library for .NET Core and .NET Framework.

### Misc
* [AngleSharp](https://github.com/AngleSharp/AngleSharp) - The ultimate angle brackets parser library. It parses HTML5, MathML, SVG and CSS to construct a DOM based on the official W3C specification. Comparable to beautifulsoup4 of python.
* [AutoMapper](https://github.com/AutoMapper/AutoMapper) - Convention-based object-object mapper in .NET.
* [Castle.Core](https://github.com/castleproject/Core/tree/netcore) - Castle Core, including Castle DynamicProxy, Logging Services and DictionaryAdapter [http://www.castleproject.org](http://www.castleproject.org).
* [CommonMark.NET](https://github.com/Knagis/CommonMark.NET) - The implementation of CommonMark specification in C# for converting Markdown documents to HTML.
* [consuldotnet](https://github.com/PlayFab/consuldotnet/tree/develop) - .NET API for Consul.
* [CoreWF](https://github.com/dmetzgar/corewf/) - Port of Windows Workflow Foundation (WF) to .NET Core.
* [datatables](https://github.com/ALMMa/datatables.aspnet/tree/dev) - Microsoft ASP.NET server-side support and helpers for jQuery DataTables.
* [Docker.DotNet](https://github.com/Microsoft/Docker.DotNet) - .NET (C#) Client Library for Docker API.
* [FluentValidation](https://github.com/JeremySkinner/FluentValidation) - Small validation library for .NET that uses a fluent interface and lambda expressions for building validation rules.
* [Humanizer](https://github.com/Humanizr/Humanizer) - Humanizer meets all your .NET needs for manipulating and displaying strings, enums, dates, times, timespans, numbers and quantities.
* [markdig](https://github.com/lunet-io/markdig) - Fast, powerfull, CommonMark compliant, extensible Markdown processor for .NET.
* [Microphone](https://github.com/rogeralsing/Microphone) - Lightweight framework to run self hosting REST services using Web Api or NancyFx ontop of a Consul or ETCD cluster.
* [NReco.LambdaParser](https://github.com/nreco/lambdaparser) - Parses string expressions (formulas, methods calls, conditions) to LINQ expression tree that can be compiled to lambda and evaluated. 
* [NReco.PivotData](https://www.nuget.org/packages/NReco.PivotData/) - In-memory data cube with OLAP operations and PivotTable data model.
* [reCAPTCHA](https://github.com/PaulMiami/reCAPTCHA) - reCAPTCHA 2.0 for ASP.NET Core.
* [Relinq](https://github.com/re-motion/Relinq) - With re-linq, it's now easier than ever to create full-featured LINQ providers.
* [PdfReport.Core](https://github.com/VahidN/PdfReport.Core) - PdfReport.Core is a code first reporting engine, which is built on top of the iTextSharp.LGPLv2.Core and EPPlus.Core libraries.
* [PreStorm](https://github.com/jshirota/PreStorm) - Parallel REST Client for ArcGIS Server.
* [Polly](https://github.com/App-vNext/Polly) - .NET 3.5 / 4.0 / 4.5 / PCL library that allows developers to express transient exception and fault handling policies such as Retry, Retry Forever, Wait and Retry or Circuit Breaker in a fluent manner.
* [Scrutor](https://github.com/khellang/Scrutor) - Assembly scanning extensions for Microsoft.Extensions.DependencyInjection.
* [sharpcompress](https://github.com/adamhathcock/sharpcompress) - Fully managed C# library to deal with many compression types and formats.
* [SmartFormat.NET](https://github.com/scottrippey/SmartFormat.NET) - An extensible replacement for string.Format.

### ORM
* [Entity Framework Core](https://github.com/aspnet/EntityFramework) - Familiar developer experience to previous versions of EF, including LINQ, POCO, and Code First support.
* [Dapper](https://github.com/StackExchange/dapper-dot-net/tree/netstandard) - Simple object mapper for .NET.
 * [Dapper-FluentMap](https://github.com/henkmollema/Dapper-FluentMap) - Provides a simple API to fluently map POCO properties to database columns when using Dapper.
 * [Dommel](https://github.com/henkmollema/Dommel) - Simple CRUD operations for Dapper.
* [Limebean](https://nick-lucas.github.io/LimeBean/) - Hybrid-ORM, designed to be simple to use and not totally hide SQL, while having all the nice things you expect from an ORM. Inspired by RedBeanPHP.
* [NEventStore](https://github.com/NEventStore/NEventStore/tree/feature/dotnetcore) - Persistence library used to abstract different storage implementations when using event sourcing as storage mechanism. This library is developed with a specific focus on DDD/CQRS applications.
* [NoDb](https://github.com/joeaudette/NoDb) - "no database" file system storage for .NET Core/ASP.NET Core because not every project needs a database.
* [NPoco](https://github.com/schotime/NPoco) - Simple microORM that maps the results of a query onto a POCO object. Project based on Schotime's branch of PetaPoco.
* [NReco.Data](https://github.com/nreco/data) - Lightweight provider-independent DAL for SQL commands generation, CRUD operations and simple POCO mapping.
* [ServiceStack.OrmLite](https://github.com/ServiceStack/ServiceStack.OrmLite) - Light, simple and fast convention-based POCO ORM.
* [SqlFu](https://github.com/sapiens/SqlFu) - Fast and versatile Micro-ORM.
* [yessql](https://github.com/sebastienros/yessql) - .NET document database working on any RDBMS.

### Profiling
* [Glimpse](http://getglimpse.com) - Lightweight, open-source, real-time diagnostics and insights profiler for .NET. 

### Queue and Messaging
* [emitter](https://emitter.io/) - Free open source real-time messaging service that connects all devices. This publish-subscribe messaging API is built for speed and security.
* [EventStore](https://github.com/EventStore/EventStore) - The open-source, functional database with Complex Event Processing in JavaScript. [https://geteventstore.com](https://geteventstore.com)
* [MediatR](https://github.com/jbogard/MediatR) - Simple, unambitious mediator implementation in .NET.
 * [MediatR.Extensions.Microsoft.DependencyInjection](https://github.com/jbogard/MediatR.Extensions.Microsoft.DependencyInjection) - MediatR extensions for Microsoft.Extensions.DependencyInjection.
* [MicroBus](https://github.com/Lavinski/Enexure.MicroBus) - Simple in process mediator for .NET.
* [rabbitmq-dotnet-client](https://github.com/rabbitmq/rabbitmq-dotnet-client) - RabbitMQ .NET client [https://www.rabbitmq.com](https://www.rabbitmq.com).
* [RawRabbit](https://github.com/pardahlman/RawRabbit) - Modern .NET framework for communication over RabbitMq.
* [Restbus](http://restbus.org) - Messaging library for RabbitMq.
* [netmq](https://github.com/zeromq/netmq) - 100% native C# implementation of ZeroMQ for .NET.

### Scheduler and Job
* [Chroniton.NetCore](https://github.com/leosperry/Chroniton) - Lightweight robust library for running tasks(jobs) on schedules. 
* [FluentScheduler](https://github.com/fluentscheduler/FluentScheduler) - Automated job scheduler with fluent interface.
* [HangfireIO](https://github.com/HangfireIO/Hangfire) - Easy way to perform fire-and-forget, delayed and recurring tasks inside ASP.NET apps [http://hangfire.io](http://hangfire.io).
* [quartznet](https://github.com/quartznet/quartznet/tree/quartznet-3) - Quartz Enterprise Scheduler .NET [http://www.quartz-scheduler.net](http://www.quartz-scheduler.net).
* [stateless](https://github.com/dotnet-state-machine/stateless) - Simple library for creating state machines in C# code.

### SDKs
* [AWS SDK](https://github.com/aws/aws-sdk-net) - The Amazon Web Services (AWS) .NET Core SDK components. Each AWS service has its own NuGet package.
* [NetTelegramBotApi](https://github.com/justdmitry/NetTelegramBotApi) - C# client library for building Telegram bot [https://core.telegram.org/bots/api](https://core.telegram.org/bots/api).
* [octokit.net](https://github.com/octokit/octokit.net/tree/target-the-coreclr) - GitHub API client library for .NET.
* [Open-XML-SDK-for-NET-Platform-Standard](https://github.com/xrkolovos/Open-XML-SDK-for-NET-Platform-Standard) - .NET Platform Standard implementation of Open XML SDK 2.5.
* [tweetinvi](https://github.com/linvi/tweetinvi/tree/tweetinvi.netcore) - Intuitive .NET C# library to access the Twitter REST and STREAM API.

### Security
* [HtmlSanitizer](https://github.com/mganss/HtmlSanitizer) - Cleans HTML to avoid XSS attacks.
* [jose-jwt](https://github.com/dvsekhvalnov/jose-jwt) - Library for processing JOSE objects (JWT, JWA, JWS and related).
* [NWebsec](https://github.com/NWebsec/NWebsec) - Security libraries for ASP.NET [https://www.nwebsec.com](https://www.nwebsec.com).
* [Security](https://github.com/aspnet/Security) - Middleware for security and authorization of web apps.

### Searching
* [Elasticsearch.Net & NEST](https://github.com/elastic/elasticsearch-net) - Repository for both NEST and Elasticsearch.NET, the two official elasticsearch .NET clients.
* [ElasticsearchCRUD](https://github.com/damienbod/ElasticsearchCRUD) - Elasticsearch .NET API.
* [SolrExpress](https://github.com/solr-express/solr-express) - Simple and lightweight query .NET library for Solr, in a controlled, buildable and fail fast way.

### Serialization
* [bond](https://github.com/Microsoft/bond) - Cross-platform framework for working with schematized data. It supports cross-language de/serialization and powerful generic mechanisms for efficiently manipulating data. Bond is broadly used at Microsoft in high scale services.
* [Channels](https://github.com/davidfowl/Channels) - Push based .NET Streams.
* [CsvHelper](https://github.com/JoshClose/CsvHelper) - Library to help reading and writing CSV files [http://csvhelper.com](http://csvhelper.com).
* [ExtendedXmlSerializer](https://github.com/wojtpl2/ExtendedXmlSerializer) - Extended Xml Serializer for .NET.
* [Jil](https://github.com/kevin-montrose/Jil) - Fast .NET JSON (De)Serializer, Built On Sigil.
* [msgpack-cli](https://github.com/msgpack/msgpack-cli) - MessagePack implementation for Common Language Infrastructure / [msgpack.org](http://msgpack.org).
* [Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json) - Popular high-performance JSON framework for .NET.
* [protobuf-net](https://github.com/mgravell/protobuf-net/) - Protocol Buffers library for idiomatic .NET.
* [ServiceStack.Text](https://github.com/ServiceStack/ServiceStack.Text) - JSON, JSV and CSV Text Serializers.
* [TinyCsvParser](https://github.com/bytefish/TinyCsvParser) - Easy to use, easy to extend and high-performance library for CSV parsing with .NET.
* [YamlDotNet](https://github.com/aaubry/YamlDotNet) - .NET library for YAML.

### Testing
* [Bogus](https://github.com/bchavez/Bogus) - Simple and sane fake data generator for C#. Based on and ported from the famed faker.js.
* [GenFu](https://github.com/MisterJames/GenFu) - Library you can use to generate realistic test data.
* [FakeItEasy](https://github.com/FakeItEasy/FakeItEasy) - The easy mocking library for .NET.
* [FluentAssertions](https://github.com/dennisdoomen/FluentAssertions) - Set of .NET extension methods that allow you to more naturally specify the expected outcome of a TDD or BDD-style test.
* [moq.netcore](https://github.com/Moq/moq4) - Most popular and friendly mocking framework for .NET.
* [MSpec](https://github.com/machine/machine.specifications) - Popular testing framework for writing BDD-style tests.
* [MyTested.AspNetCore.Mvc](https://github.com/ivaylokenov/MyTested.AspNetCore.Mvc) - Fluent testing
  framework for ASP.NET Core MVC.
* [Netling](https://github.com/hallatore/Netling) - Load tester client for easy web testing.
* [NSubstitute](https://github.com/nsubstitute/NSubstitute) - A friendly substitute for .NET mocking frameworks.
* [nunit](https://github.com/nunit/dotnet-test-nunit) - NUnit test runner for .NET Core.
* [shouldly](https://github.com/shouldly/shouldly) - Should testing for .NET - the way Asserting *Should* be! [http://shouldly.readthedocs.org/en/latest](http://shouldly.readthedocs.org/en/latest)
* [SpecFlow](https://github.com/techtalk/SpecFlow/tree/DotNetCore) - Pragmatic BDD solution for .NET. It uses the Gherkin specification language and integrates to Visual Studio.
* [Stubbery](https://markvincze.github.io/Stubbery/) - A simple library for creating and running Api stubs in .NET.
* [TestStack.BDDfy](https://github.com/TestStack/TestStack.BDDfy) - The simplest BDD framework EVER!
* [xunit](https://github.com/xunit/xunit) - Free, open source, community-focused unit testing tool for the .NET Framework.

### Tools
* [docfx](https://github.com/dotnet/docfx) - Tools for building and publishing API documentation for .NET projects [http://dotnet.github.io/docfx](http://dotnet.github.io/docfx)
* [gitignore.io](https://github.com/joeblau/gitignore.io) - Create useful .gitignore files for your project [https://www.gitignore.io](https://www.gitignore.io).
* [GitInfo](https://github.com/kzu/GitInfo) - Git and SemVer Info from MSBuild, C# and VB.
* [ICanHasDotnetCore](https://github.com/OctopusDeploy/ICanHasDotnetCore) - Scans uploaded packages.config files or GitHub repository and determines whether the nuget packages target .NET Standard [https://icanhasdot.net](https://icanhasdot.net).
* [OctoLinker](https://github.com/OctoLinker/browser-extension) - Navigate through `projects.json` files efficiently with the OctoLinker browser extension for GitHub.
* [Opserver](https://github.com/opserver/Opserver) - Stack Exchange's Monitoring System.
* [ShareX](https://github.com/ShareX/ShareX) - Free and open source program that lets you capture or record any area of your screen and share it with a single press of a key. It also allows uploading images, text or other types of files to over 80 supported destinations you can choose from. [https://getsharex.com](https://getsharex.com)

### Web Framework
* [ReactJS.NET](https://github.com/reactjs/React.NET) - .NET library for JSX compilation and server-side rendering of React components.

### Web Socket
* [SignalR Server](https://github.com/aspnet/signalr) - Real-time web functionality for web apps, including server-side push.
* [WampSharp](https://github.com/Code-Sharp/WampSharp) - C# implementation of [The Web Application Messaging Protocol](http://wamp-proto.org/) - Protocol that provides messaging patterns of Remote Procedure Calls and Publish/Subscribe over WebSockets.

### Windows Service
* [dotnet-win32-service](https://github.com/dasMulli/dotnet-win32-service) - Set up and run as Windows Service directly from .NET Core.
* [Topshelf](https://github.com/Topshelf/Topshelf) - Easy service hosting framework for building Windows services using .NET. `4.5.x or above`

## Starter Kits
* [ASP.NET Core Starter Kit](https://github.com/kriasoft/aspnet-starter-kit) - Opinionated boilerplate for web development based on .NET Core, Kestrel, GraphQL on the backend and Babel, Webpack, React and Redux on the frontend. This boilerplate comes in both C# and F# flavors.
* [ASP.NET Boilerplate](https://github.com/aspnetboilerplate/aspnetboilerplate) - ASP.NET Boilerplate is a starting point for new modern web applications using best practices and most popular tools. It's aimed to be a SOLID model, a general-purpose application framework and a project template. `4.5.x or above`
* [aspnetcore-spa generator](https://github.com/aspnet/JavaScriptServices) - Yeoman generator to build a brand-new ASP.NET Core single page application that uses Angular 2 / React / React With Redux / Knockout / Aurelia on the client.
* [react-aspnet-boilerplate](https://github.com/pauldotknopf/react-aspnet-boilerplate) - Starting point for building isomorphic React applications with ASP.NET Core 1, leveraging existing techniques.
* [saaskit](https://github.com/saaskit/saaskit) - Developer toolkit for building SaaS applications.

## Sample Projects
* [AlbumViewerVNext](https://github.com/RickStrahl/AlbumViewerVNext) - West Wind Album Viewer ASP.NET 5 Sample.
* [allReady](https://github.com/HTBox/allReady) - Open-source solution focused on increasing awareness, efficiency and impact of preparedness campaigns as they are delivered by humanitarian and disaster response organizations in local communities. [http://www.htbox.org/projects/allready](http://www.htbox.org/projects/allready)
* [AspNet5GeoElasticsearch](https://github.com/damienbod/AspNet5GeoElasticsearch) - ASP.NET Core MVC Geo Elasticsearch Swashbuckle Swagger.
* [aspnet-servicediscovery-patterns](https://github.com/cecilphillip/aspnet-servicediscovery-patterns) - Samples of implementing Service Discovery patterns with ASP.NET Core.
* [cloudscribe](https://github.com/joeaudette/cloudscribe) - ASP.NET Core Multi-tenant web application foundation.
* [distributed-playground](https://github.com/jvandevelde/distributed-playground) - Distributed service playground with Vagrant, Consul, Docker & ASP.NET Core.
* [DotNetClub](https://github.com/scheshan/DotNetClub) - Tiny club written in ASP.NET Core.
* [Entropy](https://github.com/aspnet/Entropy) - Chaotic experimental playground for new features and ideas - check here for small and simple samples for individual features.
* [guidance-identity-management-for-multitenant-apps](https://github.com/Azure-Samples/guidance-identity-management-for-multitenant-apps) - How to manage user identities in a multitenant app on Microsoft Azure, using Azure Active Directory for authentication.
* [magazine-website](https://github.com/thangchung/magazine-website) - Magazine website (using .NET Core, ASP.NET Core, EF Core) with DDD, CQRS, microservices, asynchronous programming applied.
* [MegaMine](https://github.com/Nootus/MegaMine) - Open source mining solution that helps miners in extracting Gold, Quartz, Granite etc. This solution is built using ASP.NET Core and AngularJS utilizing multiple light weight components in a Microservices way.
* [minicompiler](Minification, bundling and compiling sample) - Minification, bundling and compiling sample.
* [MusicStore](https://github.com/aspnet/MusicStore) - Sample MusicStore application that uses MVC and Entity Framework.
* [ReactiveTraderCloud](https://github.com/AdaptiveConsulting/ReactiveTraderCloud) - Real-time trading platform demo showcasing reactive programming principles applied across the full application stack.
* [PhotoGallery](https://github.com/chsakell/aspnet5-angular2-typescript) - Cross-platform Single Page Applications with ASP.NET Core, Angular 2 & TypeScript [http://wp.me/p3mRWu-11L](http://wp.me/p3mRWu-11L).
* [Practical ASP.NET Core](https://github.com/dodyg/practical-aspnetcore) - A daily updated micro samples of ASP.NET Core features and facilities. 

## Articles 
* Basic knowledge
  * [A guide to the .NET Core projects on GitHub](https://blog.rendle.io/a-guide-to-the-net-projects-on-github/)
  * [Porting .NET Framework Library to .NET Core](http://www.michael-whelan.net/porting-dotnet-framework-library-to-dotnet-core)
  * The comparison between .NET Core and Nodejs at [here](https://manuel-rauber.com/2016/03/07/node-js-asp-net-core-1-0-a-usage-comparison/), [here](https://gist.github.com/ilyaigpetrov/f6df3e6f825ae1b5c7e2) and [here](https://github.com/thinktecture/nodejs-aspnetcore-webapi)
  * [Understanding ASP.NET Core Initialization](http://developer.telerik.com/featured/understanding-asp-net-core-initialization/)
* Cloud Development
  * [Configuring the AWS SDK in .NET Core](https://aws.amazon.com/blogs/developer/configuring-aws-sdk-with-net-core/)
  * [Using C# and .NET Core in Amazon Web Services (AWS) Lambda](https://aws.amazon.com/blogs/compute/announcing-c-sharp-support-for-aws-lambda/)
* Configuration and deployment
  * [Adding Travis CI builds to a .NET Core app](http://andrewlock.net/adding-travis-ci-to-a-net-core-app/)
  * [ASP.NET Core 1.0 - Configure ApplicationInsights](http://social.technet.microsoft.com/wiki/contents/articles/35918.asp-net-core-1-0-configure-applicationinsights.aspx)
  * [haproxy, nginx, Angular 2, ASP.NET Core, Redis and Docker](http://tattoocoder.azurewebsites.net/legion-of-heroes-haproxy-nginx-angular2-aspnetcore-redis-docker/)
  * [Publishing a .NET project with Appveyor and NuGet](https://few-lines-of-code.blogspot.com/2016/03/publishing-net-project-with-appveyor.html)
  * [The New Configuration Model in ASP.NET Core](http://developer.telerik.com/featured/new-configuration-model-asp-net-core/)
* Entity Framework Core 
  * [.NET Core Data Access](https://blogs.msdn.microsoft.com/dotnet/2016/11/09/net-core-data-access/)
  * [A very good example about EF Core](https://github.com/rowanmiller/Demo-EFCore)
* Miraculous
  * [Vue.js server side rendering with ASP.NET Core](http://mgyongyosi.com/2016/Vuejs-server-side-rendering-with-aspnet-core/)
* Security
  * [.NET Continuous Delivery Microservices](http://stackshare.io/tomstaijen/net-continuous-delivery-microservices)
  * [A walk-through for an ASP.NET Authorization Lab](https://github.com/blowdart/AspNetAuthorizationWorkshop)
  * [Authentication in ASP.NET Core](https://stormpath.com/blog/authentication-asp-net-core)
* Testing
  * [Selenium with .NET Core](http://www.dotnetcatch.com/2016/11/23/selenium-with-net-core/)

## Books
* [ASP.NET Core Application Development: Building an application in four sprints (Developer Reference)](https://www.amazon.com/ASP-NET-Core-Application-Development-application/dp/1509304061)
* [ASP.NET Core 1.0 High Performance](https://www.amazon.com/ASP-NET-Core-1-0-High-Performance/dp/1785881892)
* [Building Microservices with ASP.NET Core: Develop, Test, and Deploy Cross-Platform Services in the Cloud](https://www.amazon.com/Building-Microservices-ASP-NET-Core-Cross-Platform/dp/1491961732)
* [C# 6 and .NET Core 1.0: Modern Cross-Platform Development](https://www.amazon.com/NET-Core-1-0-Cross-Platform-Development/dp/1785285696)
* [Microservices in .NET Core: with C#, the Nancy framework, and OWIN middleware](https://www.amazon.com/Microservices-NET-Core-framework-middleware/dp/1617293377)
* [Professional C# 6 and .NET Core 1.0](https://www.amazon.com/Professional-NET-Core-Christian-Nagel/dp/111909660X)
* [.NET Core in Action](https://manning.com/books/dotnet-core-in-action)

## Videos
* [Channel9](https://channel9.msdn.com)
 * [ASP.NET Monsters](https://channel9.msdn.com/Series/aspnetmonsters)
* [Visual Studio](https://www.youtube.com/user/VisualStudio/channels)
* [.NET World](https://www.youtube.com/channel/UClW5uIyHKPhfSEloQxn7b0Q)

## Podcasts
* [.NET Rocks](https://www.dotnetrocks.com)
* [Static Void Podcast](https://www.staticvoidpodcast.com)
* [The sound of .NET](http://thesoundof.net/?q=.NET+Core)

## Community
* [ASP.NET](https://forums.asp.net)
* [.NET Foundation](http://forums.dotnetfoundation.org)
* [Channel9](https://channel9.msdn.com/Forums)
* Stack Overflow
 *  [.NET Core](https://stackoverflow.com/questions/tagged/.net-core)
 *  [CoreCLR](https://stackoverflow.com/questions/tagged/coreclr)
 *  [ASP.NET Core](https://stackoverflow.com/questions/tagged/asp.net-core)
 *  [ASP.NET Core MVC](https://stackoverflow.com/questions/tagged/asp.net-core-mvc)
 *  [ASP.NET Core 1.0](https://stackoverflow.com/questions/tagged/asp.net-core-1.0)
 *  [Entity Framework Core](https://stackoverflow.com/questions/tagged/entity-framework-core)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [thangchung](http://weblogs.asp.net/thangchung) has waived all copyright and related or neighboring rights to this work.
