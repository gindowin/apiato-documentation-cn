---
title: "Apiato 中文文档"
---

> **使用 PHP 7.4 和 Laravel 7 快速构建你的 API 应用**

![apiato.jpg]({{ site.baseurl }}/images/image-rounded.png)

[![apiato](https://img.shields.io/badge/Status-Awesome-brightgreen.svg)](https://github.com/apiato/apiato)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/apiato/apiato/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/apiato/apiato/?branch=master)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/ce8fed7f8fcd492ebbe5ef0fb36c0a9a)](https://www.codacy.com/app/mahmoudz/apiato?utm_source=github.com&utm_medium=referral&utm_content=apiato/apiato&utm_campaign=badger)
[![Build Status](https://scrutinizer-ci.com/g/apiato/apiato/badges/build.png?b=master)](https://scrutinizer-ci.com/g/apiato/apiato/build-status/master)
[![Build Status](https://travis-ci.org/apiato/apiato.svg?branch=master)](https://travis-ci.org/apiato/apiato)
[![Latest Stable Version](https://poser.pugx.org/apiato/apiato/v/stable)](https://packagist.org/packages/apiato/apiato)
[![Backers on Open Collective](https://opencollective.com/apiato/backers/badge.svg)](#backers)
[![Sponsors on Open Collective](https://opencollective.com/apiato/sponsors/badge.svg)](#sponsors)
[![License](https://poser.pugx.org/apiato/apiato/license)](https://packagist.org/packages/apiato/apiato)


## Apiato 介绍

**Apiato** 是一款基于 PHP 和 Laravel 技术，用于快速构建易扩展、易测试并以 API 为核心的应用框架。

它旨在帮您更快地构建可伸缩的 API 应用，通过提供特性功能和工具，加速以 API 为核心的应用程序开发。

Apiato 用最好的框架、工具和编程约定，以极具创意的方式，为现代化 PHP 应用程序提供丰富的功能。

**为什么?** 因为从头开始建立一套有效的 API 是非常耗时的，时间就是金钱。Apiato 免费提供了一套实现健壮 API 的解决方案，因此您只需专注开发业务逻辑，从而实现更快地交付。

### 功能特性

Apiato 具有以下惊艳的特性

![]({{ site.baseurl }}/images/features.png)

## 软件架构

**Apiato** 采用先进的软件构架模式 **[Porto](https://github.com/Mahmoudz/Porto)**。

**Porto SAP** 是一种现代软件架构模式，旨在帮助开发人员以一种极易维护的方式进行编码。这对大型项目非常有用，因为它们往往更复杂性。

但使用 Porto 架构**不是必须**的。即便是使用 [MVC]({{ site.baseurl }}{% link _docs/getting-started/architecture.md %}) 软件架构，你仍然会在 Apiato 中受益。



### 快速预览本文档

这份文档有 4 个部分：

- **起步**: 主要介绍安装步骤；
- **常规内容**: 一些基础内容，帮助你起步；
- **功能特性**: 如何使用 Apiato 的各项功能；
- **组件**: 说明使用每个组件“类”的使用方法等。在每个组件页面中，您将看到：
  * **定义**: 什么是组件，它充担什么角色。
  * **原则**: 介绍组件的一般原则（适用于任何编程语言）。
  * **规则**: Apiato 中应用组件的规则。
  * **目录结构**: 组件的位置及目录结构。
  * **实例**: 编写和使用组件的样板案例。
  * **其它**: 其它与组件相关的东西，如配置等。


### 约定

> 本文件中的关键词“必须”、“不得”、“必需”、“应”、“不得”、“应”、“不应”、“不应”、“推荐”、“可”和“可选”等，请参照 [[RFC2119](http://tools.ietf.org/html/rfc2119)]。

<a name="Sponsors"></a>
## 赞助商

<a href="https://opencollective.com/apiato/sponsor/0/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/0/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/1/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/1/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/2/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/2/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/3/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/3/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/4/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/4/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/5/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/5/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/6/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/6/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/7/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/7/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/8/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/8/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/9/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/9/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/10/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/10/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/11/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/11/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/12/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/12/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/13/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/13/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/14/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/14/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/15/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/15/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/16/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/16/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/17/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/17/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/18/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/18/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/19/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/19/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/20/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/20/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/21/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/21/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/22/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/22/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/23/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/23/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/24/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/24/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/25/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/25/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/26/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/26/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/27/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/27/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/28/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/28/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/29/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/29/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/30/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/30/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/31/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/31/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/32/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/32/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/33/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/33/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/34/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/34/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/35/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/35/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/36/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/36/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/37/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/37/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/38/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/38/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/39/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/39/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/40/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/40/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/41/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/41/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/42/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/42/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/43/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/43/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/44/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/44/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/45/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/45/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/46/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/46/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/47/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/47/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/48/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/48/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/sponsor/49/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/sponsor/49/avatar.svg?requireActive=false"></a>

通过 [企业或组织](https://opencollective.com/apiato/contribute/) 赞助 Apiato 项目。
<br>
你的品牌会被展示在 [github repository](https://github.com/apiato/apiato/) 和 [documentation](http://apiato.io/) 主页。
<br>
需要了解更多请联系 <a href = "mailto: support@apiato.io">support@apiato.io</a>。

<a name="Backers"></a>
## 支持者

<a href="https://opencollective.com/apiato/backer/0/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/0/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/1/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/1/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/2/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/2/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/3/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/3/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/4/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/4/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/5/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/5/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/6/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/6/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/7/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/7/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/8/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/8/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/9/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/9/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/10/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/10/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/11/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/11/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/12/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/12/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/13/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/13/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/14/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/14/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/15/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/15/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/16/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/16/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/17/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/17/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/18/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/18/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/19/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/19/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/20/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/20/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/21/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/21/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/22/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/22/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/23/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/23/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/24/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/24/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/25/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/25/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/26/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/26/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/27/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/27/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/28/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/28/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/29/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/29/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/30/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/30/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/31/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/31/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/32/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/32/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/33/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/33/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/34/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/34/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/35/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/35/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/36/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/36/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/37/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/37/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/38/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/38/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/39/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/39/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/40/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/40/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/41/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/41/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/42/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/42/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/43/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/43/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/44/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/44/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/45/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/45/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/46/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/46/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/47/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/47/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/48/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/48/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/apiato/backer/49/website?requireActive=false" target="_blank"><img src="https://opencollective.com/apiato/backer/49/avatar.svg?requireActive=false"></a>

<a name="Donations"></a>
### 财务赞助

帮助我们维护此项目。

<b>选项 1:</b> 使用 [Paypal](https://paypal.me/mzmmzz) 捐助。
<br>
<b>选项 2:</b> 成为一个 [Github Sponsors](https://github.com/sponsors/Mahmoudz)。
<br>
<b>选项 3:</b> 成为一个 [Open Collective](https://opencollective.com/apiato/contribute)。
<br>
<b>选项 4:</b> 成为一个 [Patreon](https://www.patreon.com/zalt)。

<a name="Chat"></a>
### 联系我们

点击下面的图标，加入到我们的 [Slack](https://slackin-mezlsumyvc.now.sh/) 聊天室。

<a href="https://slackin-mezlsumyvc.now.sh/">
   <img src="https://s19.postimg.cc/h7pvzy9ar/Slack-i_OS-icon.png" alt="Apiato SLACK"/>
</a>

<a name="起步"></a>
## 起步

安装并享用 ：） [安装指南]({{ site.baseurl }}{% link _docs/getting-started/installation.md %})

<!--**LTS (Long-Term Support)** release is available. And offers support for 12 months, after the release date.-->
<!--The current LTS version is **7.2** (Release date 2017-11-11).-->
<!--It offers bug fixes (for 12 months) and security updates (for 12 months). And does not get any new features.-->

<a name="Testimonials"></a>
## 用户评价

> 阅读部分 **[用户评价]({{ site.baseurl }}{% link _docs/miscellaneous/testimonials.md %})**
