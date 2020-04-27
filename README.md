# Deno 资源全图谱 · 专注中文版 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

![](./assets/logo.png)

## 为什么有这个项目？

Deno v1.0 将于 2020 年 05 月 13 日发布 v1.0 正式版本，一个专注于中文技术圈的 Deno 资源列表呼之欲出。

本项目将长期提供更新，愿我们与 Deno 一起成长。同时，本列表也会及时跟进已 1k+ Star 的 [@denolib/awesome-deno](https://github.com/denolib/awesome-deno) 和 180+ Star 的 [@olivewind/awesome-deno](https://github.com/olivewind/awesome-deno) 仓库并进行更多的中文化更新。

以下资源 🌟 代表品质推荐（逐步添加中）。由于资源分类的多样性考虑，部分章节内容可能会有所重复。

<!--

## 独家《Deno 钻研之术》

感谢你的关注，献上我的[《Deno 钻研之术》](https://github.com/hylerrix/deep-into-deno)作为本仓库的独特内容之一。

-->

## 关于共建

本项目未来待做事项大致如下，欢迎讨论：

- [ ] 及时进行内容更新，收集越来越多高质量的 Deno 资源：
  - [x] 初始化本项目，填充独特的中文版内容。
  - [x] 2020-04-14 跟进最新的 [@olivewind/awesome-deno](https://github.com/olivewind/awesome-deno) 仓库内容。
  - [ ] 2020-04-27 跟进最新的 [@denolib/awesome-deno](https://github.com/denolib/awesome-deno) 仓库内容。
  - [ ] 2020-04-27 跟进最新的 [Deno 官方第三方库列表](https://deno.land/x/) 并进行翻译。
- [ ] 增加 CODE_OF_CONDUCT、CONTRIBUTING、MAINTAINERS 等基础协作文件，让本项目更为正式和友好。
- [ ] 介绍独家《Deno 钻研之术》电子书并随着本仓库一起成长（预计五月份开始正式上线）。
- [ ] 开发更好看的 UI 页面来展示这个资源列表 -> 这份 UI 需要抽离出单个项目并引人到本仓库中。

Deno 生态正在完善中，期待你的贡献，以下是贡献者列表。

- [@hylerrix](https://github.com/hylerrix)
- ......欢迎加入！

## 插曲：从 Node.js 到 Deno.js

- [《Node.js 的设计缺陷》](http://tinyclouds.org/jsconf2018.pdf)，官方 PDF 演讲稿。
- [《Design Mistakes in Node》Node 之父 Ryan Dahl 演讲 PPT 中文版 (2018 JS Conf Berlin)](https://zhuanlan.zhihu.com/p/37637923)，发布于 2018-06-03。
- ......逐步添加中，欢迎 Star & Fork & PR。

## 技术文档

### 官方文档

> 包括中文社区的文档

- [deno.land](https://deno.land)：🌟，Deno 官网。
- [Deno API TypeDoc](https://deno.land/typedoc/)
- [doc.deno.land](https://doc.deno.land)：Deno 文档。
- [Deno Registry](https://deno.land/x/)：Deno 第三方

### 中文社区文档

- [@denodev/typedoc](https://github.com/denodev/typedoc)：🌟，Deno API 简体中文版。
- ......逐步添加中，欢迎 Star & Fork & PR。

## 基础设施

### 核心库

> 更多官方核心库请参考最新的[官方文档](https://deno.land)。

- [@denolib/ms](https://github.com/denolib/ms)：轻松地将各种时间格式转换为毫秒。
- [@denolib/qs](https://github.com/denolib/qs)：具有嵌套支持的 querystring 解析器。
- [@denolib/camelcase](https://github.com/denolib/camelcase)：将破折号/点号/下划线/空格分隔的字符串转换为驼峰式；示例：foo-bar→fooBar。
- ......逐步添加中，欢迎 Star & Fork & PR。

### 第三方库

> 更多内容可以看 Deno 官网上的[第三方库列表](https://deno.land/x)

- [@bokuweb/deno-pretty-assert](https://github.com/bokuweb/deno-pretty-assert)：一个 Deno 下的 assertEqual 库。
- [@hashrock/deno-fnparse](https://github.com/hashrock/deno-fnparse)：一个非常简单的 JavaScript 解析器、组合器。
- [@hashrock/deno-opn](https://github.com/hashrock/deno-opn)：一个可以打开网站、(可执行)文件之类资源的跨平台工具。
- [@hashrock/deno-fnparse/.../csv](https://github.com/hashrock/deno-fnparse/blob/master/parsers/csv.ts)：一个简单的 CSV 解析器。
- [@jinjor/deno-playground/.../expressive](https://github.com/jinjor/deno-playground/tree/master/expressive)：一个类似于 Express 的 Deno Web 框架。
- [@jinjor/deno-playground/.../watch](https://github.com/jinjor/deno-playground/tree/master/watch)：一个文件监听程序。
- [@keroxp/deno-redis](https://github.com/keroxp/deno-redis)：一个由 Deno 实现的实验性的 Redis 客户端。
- [@keroxp/deno-ws](https://github.com/keroxp/deno-ws)：一个 Websocket 服务器的实验性实现。
- [@kitsonk/oak](https://github.com/kitsonk/oak)：一个用于 Deno 网络服务器的中间件框架。
- [@muhibbudins/deno-yaml](https://github.com/muhibbudins/deno-yaml)：一个使用 Deno 的简单 Yaml 解析器。
- [@nekobato/deno-xml-parser](https://github.com/nekobato/deno-xml-parser)：一个从 segmentio/xml-parser 移植的 Deno XML 解析器。
- [@syumai/dejs](https://github.com/syumai/dejs)：一个用于 Deno 的 ejs 模板引擎。
- [@syumai/dinatra](https://github.com/syumai/dinatra)：🌟，一个类似于 Sinatra 的轻量级 Deno Web 应用程序框架。
- [@sholladay/pogo](https://github.com/sholladay/pogo)：一个 Deno 服务端框架。
- [@zhmushan/abc](https://github.com/zhmushan/abc)：一个不错的 Deno Web 框架。
- ......逐步添加中，欢迎 Star & Fork & PR。

## 周边工具

> shell、node、python、go 等

- [@justjavac/vscode-deno](https://github.com/justjavac/vscode-deno)：🌟，VS Code 扩展，使用 typescript-deno-plugin 提供 Deno 支持
- [@syumai/deno-libs/.../denoget](https://github.com/syumai/deno-libs/tree/master/denoget)：安装可执行的 Deno 脚本。
- [@syumai/deno-libs/.../denoinit](https://github.com/syumai/deno-libs/tree/master/denoinit)：为 Deno 项目生成有用的文件。
- [@denopkg/denopkg.com](https://github.com/denopkg/denopkg.com)：在 Deno 项目中直接使用来自 GitHub 代码的简单方法。
- [@jinjor/elm-live-reload](https://github.com/jinjor/deno-playground/tree/master/elm-live-reload)：一个用 Deno 编写的 Elm Live Reloader。
- ......逐步添加中，欢迎 Star & Fork & PR。

## 技术教程

### 单篇文章（中文）

> 专注于收集高质量的博客文章，更多内容可以在谷歌/百度上搜索。目前 Deno 文章不多，尽可能多的诺列不设内容质量限制。

- [Deno 运行时入门教程：Node.js 的替代品](http://www.ruanyifeng.com/blog/2020/01/deno-intro.html)，🌟，发布于 2020-01-26。
- [学得动的 Deno](https://juejin.im/post/5bc8b2166fb9a05d36350ea9)，发布于 2018-10-19。
- [Deno 并不是下一代 Node.js](https://juejin.im/post/5b14a390e51d4506c1300bbc)，🌟，发布于 2018-06-04。
- [让我们一起来学习别人学不动的 Deno](https://segmentfault.com/a/1190000015151287)，发布于 2018-06-03。
- [快速了解 deno 目前的 API](https://zhuanlan.zhihu.com/p/37569396)，发布于 2018-06-03。
- [玩 Deno 遇到问题的解决方案](https://juejin.im/post/5b1245b3f265da6e4c6cf249)，发布于 2018-06-02。
- ......逐步添加中，欢迎 Star & Fork & PR。

### 单篇文章（英文）

- [Forget NodeJS! Build native TypeScript applications with Deno 🦖](https://deepu.tech/deno-runtime-for-typescript/)，发布于 2020-02-18。
- [What’s Deno, and how is it different from Node.js?](https://blog.logrocket.com/what-is-deno/)，发布于 2019-07-09。
- [What is Deno? A ‘better’ Node.js](https://www.infoworld.com/article/3529779/what-is-deno-a-better-nodejs.html)，发布于 2020-02-28。
- [Ryan Dahl’s Node.js regrets lead to Deno](https://www.infoworld.com/article/3283250/ryan-dahls-nodejs-regrets-lead-to-deno.html)，发布于 2018-06-21。
- ......逐步添加中，欢迎 Star & Fork & PR。

### 系列文章

- [Deno 源码贡献指南（英文版）](https://denolib.gitbook.io/guide)，托管于 Gitbook 上。
- [Deno 进阶开发笔记](https://chenshenhai.com/deno_note)。
- ......逐步添加中，欢迎 Star & Fork & PR。

### 技术专栏

- [Deno 开发者社区](https://zhuanlan.zhihu.com/denodev)：知乎专栏，[@justjavac](https://github.com/justjavac) 主导。
- [Deno 世界](https://zhuanlan.zhihu.com/denoland)：知乎专栏，[@嘤嘤](https://www.zhihu.com/people/yingyingxue) 主导。
- ......逐步添加中，欢迎 Star & Fork & PR。

### 在线视频

- ......逐步添加中，欢迎 Star & Fork & PR。

## 电子资源

> 专注收集公开免费的 PDF、PNG 以及电子书等资源，放置在仓库的 resources 文件夹下。

* [《Node.js 的设计缺陷（英文版）》](./resources/design-mistakes-in-node.pdf)
* [《Node.js 的设计缺陷（中文版）》](./resources/design-mistakes-in-node-zh.pdf)
- ......逐步添加中，欢迎 Star & Fork & PR。

## 技术社区

### 社区列表

- [Deno Discord](https://discord.gg/TGMHGv6)：🌟，Discord 上的 Deno 官方聊天室，有中文社区。
- [deno.dev](https://deno.dev)：🌟，开发中，[@justjavac](https://github.com/justjavac) 主导。
- [denocn.org](https://denocn.org)：🌟，Deno 中文社区，[@manyuanrong](https://github.com/manyuanrong) 主导。
- [deno.js.cn](https://deno.js.cn)：开发中，[@???]() 主导。
- ......逐步添加中，欢迎 Star & Fork & PR。

### Github 开源组织

> 重点收集专注于使用 & 回馈 Deno 生态圈的 Github 组织。暂不考虑可能有内容会与“技术社区”栏目重叠的问题。

* [Deno Land](https://github.com/denoland)：Deno 官方 Github 组织。
* [Deno Dev](https://github.com/denodev)：Deno 第三方组织之一，[@justjavac](https://github.com/justjavac) 主导。
* [Deno Lib](https://github.com/denolib)：Deno 第三方组织。
- ......逐步添加中，欢迎 Star & Fork & PR。

## 谁在用 Deno？

> 重点收集已经部署在生产环境的应用，欢迎推荐你的案例，逐步完善中。

- ......逐步添加中，欢迎 Star & Fork & PR。

## 其它订阅

- [twitter@deno_land](https://twitter.com/deno_land)：Deno Land 官方推特。
- ......逐步添加中，欢迎 Star & Fork & PR。

## 开源协议

本项目文档内容均采用 [CC-BY-SA-4.0] 协议进行共享。