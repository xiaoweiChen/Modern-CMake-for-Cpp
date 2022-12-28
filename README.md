# Modern CMake for C++  

*Discover a better approach to building, testing, and packaging your software*

*(构建、测试和打包软件)*

<a href="https://www.packtpub.com/product/modern-cmake-for-c/9781801070058"><img src="https://static.packt-cdn.com/products/9781801070058/cover/smaller" height="256px" align="right"></a>

* 作者：Rafał Świdziński
* 译者：陈晓伟
* 首次发布时间：2022年2月28日([来源](https://www.amazon.com/Modern-CMake-Discover-approach-packaging/dp/1801070059))

> 翻译是译者用自己的思想，换一种语言，对原作者想法的重新阐释。鉴于我的学识所限，误解和错译在所难免。如果你能买到本书的原版，且有能力阅读英文，请直接去读原文。因为与之相较，我的译文可能根本不值得一读。
>
> <p align="right"> — 云风，程序员修炼之道第2版译者</p>

PDF可在本库的[Release页面](https://github.com/xiaoweiChen/Modern-CMake-for-Cpp/releases)获取。

## 本书概述

创建一流的软件非常困难，开发人员很难确定哪些建议是最新的，哪些方法已经可以用更简单、更好的实践所取代。与此同时，大多数在线资源提供的解释有限，也缺乏相应的上下文。

本书提供了一种更简单、更全面的体验，介绍了如何构建C++解决方案。Modern CMake for C++是一个端到端的任务自动化指南，包括构建、测试和打包。不仅可以了解如何在项目中使用CMake语言，还可以了解如何使它们可维护，优雅和干净。本书还关注源目录、构建目标和包的结构。随着了解的深入，将学习如何编译和链接可执行文件和库，这些过程如何工作，以及如何优化CMake中的构建得最佳结果。还将了解如何在项目中使用外部依赖项——第三方库、测试框架、程序分析工具和文档生成器。最后，导出内部和外部目标，以及安装和打包。

读完这本书，就能够自信地使用CMake了。

#### 关键特性

- 理解并自动化CMake编译和链接

- 管理内部和外部依赖关系
- 添加质量检查和测试作为构建步骤

#### 将会学到

- 了解构建C++代码的最佳实践
- 通过使用来获得CMake语言的实践知识
- 在测试、静态和动态分析的帮助下，使用前沿工具来保证代码质量
- 了解如何使用CMake管理、发现、下载和链接依赖关系
- 构建可长期重用和维护的解决方案
- 了解如何优化构建构件和构建过程本身



## 适读人群

这本书是为具有C/ C++编程知识的工程师和软件开发人员所著，从而可以学习CMake，以了解自动化构建小型和大型软件的解决方案。若刚刚开始使用CMake，并长期使用GNU Make，或者只是想复习一下最新的最佳实践，那么本书非常适合您。

## 作者简介

**Rafał Świdziński**在Google公司担任工程师，具有超过10年专业经验的全栈开发人员，了解大量的编程语言和技术，一直在自己的公司和包括Cisco Meraki、Amazon和Ericsson在内的公司开发软件。他来自波兰的罗兹(Łódź)，现在生活在英国伦敦，在那里经营一个YouTube频道“Smok”，讨论与软件开发相关的话题。他很喜欢处理技术问题，包括该领域的挑战。在工作中，他了解各种技术概念，并揭开了软件工程师角色背后的艺术和科学的神秘面纱。他的主要关注代码质量和编程技巧。

> 感谢我的家人:我的父母Bożena和Bogdan，我的姐妹Ewelina和Justyna，以及我的妻子Katarzyna，感谢他们一直以来的支持和建议。
>
> <p align="right"> — Rafał Świdziński</p>

## 审评者介绍

**Sergio Guidi Tabosa Pessoa** 是一名软件工程师，在软件开发和维护方面有超过30年的经验，从复杂的企业软件项目到现代移动应用。早期主要与Microsoft打交道，但很快就喜欢上了UNIX和Linux操作系统的强大功能。尽管他多年来使用过许多语言，但C和C++仍因其强大的功能和速度而成为他最喜欢的语言。

他拥有计算机科学学士学位和IT管理工商管理硕士学位，总是渴望学习新技术，破解代码，从错误中学习。目前和妻子，两只约克郡犬和两只鹦鹉生活在巴西。

> 首先，我要感谢参与这个项目的所有人，包括精心制作了如此伟大作品的作者，以及给我这个机会的Packt  Publishing。我也要感谢我美丽的妻子Lucia，以及Touché和Lion，感谢他们的耐心和给我所需的时间来帮助

**Eric Noulard**拥有法国ENSEEIHT的工程学学位和法国UVSQ的计算机科学博士学位。20年来，他一直在用各种语言编写和编译源代码。自2006年以来一直是CMake的用户，多年来一直是该项目的积极贡献者。职业生涯中，Eric曾为私人公司和政府机构工作。现在受雇于Antidot，这是一家软件供应商，负责开发和营销高端信息检索技术和解决方案。

**Mohammed Alqumairi**是Cisco Meraki的软件工程师，使用各种语言和框架开发关键和性能后端服务方面有经验，尤其关注现代C++、CMake和Poco库。Mohammed以优异的成绩毕业于伦敦城市大学，获得计算机科学学士学位。

## 本书相关

* github地址：https://github.com/xiaoweiChen/Modern-CMake-for-Cpp
* 译文的LaTeX 环境配置：https://www.cnblogs.com/1625--H/p/11524968.html 
  * 禁用拼写检查：https://blog.csdn.net/weixin_39278265/article/details/87931348

* vscode中配置latex：https://blog.csdn.net/Ruins_LEE/article/details/123555016
* 原书示例：https://github.com/PacktPublishing/Modern-CMake-for-Cpp

