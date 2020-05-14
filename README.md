# Deno 资源全图谱 · 专注中文版 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<img src="./assets/logo.png" style="height: 88px; width: 88px;">

## 为什么有这个项目？

Deno v1.0 将于 2020 年 05 月 13 日发布 v1.0 正式版本，一个专注于中文技术圈的 Deno 资源列表呼之欲出。

以下资源 🌟 代表品质推荐，⚠️ 代表注意事项。由于资源分类的多样性考虑，部分章节内容可能会有所重复。

### 独特之处

- [x] 长期提供更新，收集越来越多高质量的 Deno 资源，愿我们与 Deno 一起成长。
- [ ] 随着 Deno 主版本进行版本归档更新。
- [x] 配套独家[《Deno 钻研之术》](https://github.com/hylerrix/deno-tutorial)电子书并随着本项目一起成长。
- [ ] 及时跟进已 1k+ Star 的 [@denolib/awesome-deno](https://github.com/denolib/awesome-deno) 仓库。
- [x] 及时跟进已 180+ Star 的 [@olivewind/awesome-deno](https://github.com/olivewind/awesome-deno-cn) 仓库。
- [ ] 增加 CODE_OF_CONDUCT、CONTRIBUTING、MAINTAINERS 等基础协作文件，让本项目更为正式和友好。
- [ ] 开发更好看的 UI 页面来展示这个资源列表 -> 这份 UI 需要抽离出单个项目并引人到本项目中。

### 更新日志

- [x] 2020-04-14 初始化本项目，填充独特的中文版内容。
- [x] 2020-04-14 跟进最新的 [@olivewind/awesome-deno](https://github.com/olivewind/awesome-deno) 仓库内容。
- [x] 2020-05-13 新增《Deno 钻研之术》项目，将本项目作为前者的配套项目。
- [x] 2020-05-14 跟进中文化后大改版的 [@olivewind/awesome-deno-cn](https://github.com/olivewind/awesome-deno-cn) 仓库内容。
- [ ] 2020-05-14 跟进最新的 [@denolib/awesome-deno](https://github.com/denolib/awesome-deno) 仓库内容。
- [ ] 2020-05-xx 跟进最新的 [Deno 官方第三方库列表](https://deno.land/x/) 并进行翻译。
- [ ] 2020-06-xx 跟进最新的 [@denolib/awesome-deno](https://github.com/denolib/awesome-deno) 仓库内容。

Deno 生态正在完善中，期待你的贡献，以下是贡献者列表。

- [@hylerrix](https://github.com/hylerrix)
- ......欢迎加入！

## 前言：从 Node.js 到 Deno.js

- [《Node.js 的设计缺陷》](http://tinyclouds.org/jsconf2018.pdf)，官方 PDF 演讲稿。
- [《Design Mistakes in Node》Node 之父 Ryan Dahl 演讲 PPT 中文版 (2018 JS Conf Berlin)](https://zhuanlan.zhihu.com/p/37637923)，发布于 2018-06-03。
- ......逐步添加中，欢迎 Star & Fork & PR。

## 技术文档

### 官方文档

> 包括中文社区的文档

- [deno.land](https://deno.land)：🌟，Deno 官网。
- [Deno API 类型手册](https://deno.land/typedoc/)：
- [doc.deno.land](https://doc.deno.land)：自动化 Deno 文档生成器。
- [Deno Registry](https://deno.land/x/)：Deno 第三方库汇总。
- ......逐步添加中，欢迎 Star & Fork & PR。

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

### 模块（待翻译）

__NOTICE__: Deno has a few official modules that could be found at [deno_std](https://deno.land/std/).
Consider submitting to [the deno.land/x](https://github.com/denoland/deno_website2/blob/master/src/database.json) repository.

- [abc](https://github.com/zhmushan/abc) - A better Deno framework to create web application.
- [alosaur](https://github.com/alosaur/alosaur) - Alosaur - Deno web framework with many decorators.
- [bytes_formater](https://github.com/manyuanrong/bytes_formater) - Format bytes (Uint8Array、ArrayBufferView...) output, useful when debugging IO functions.
- [cac](https://github.com/cacjs/cac) - Simple yet powerful framework for building command-line apps.
- [camelcase](https://github.com/denolib/camelcase) - Convert a dash/dot/underscore/space separated string to camelCase: foo-bar → fooBar.
- [colors](https://deno.land/std/fmt/colors.ts) - A basic console color library intended for Deno.
- [cli-spinner](https://github.com/ameerthehacker/cli-spinners) - Show spinners in the terminal while running long tasks
- [csv](https://github.com/hashrock/deno-fnparse/blob/master/parsers/csv.ts) - A simple CSV parser.
- [dcc](https://github.com/BoltDoggy/deno#dcc) - Deno Cache Clean, reloading deps when next running.
- [dejs](https://github.com/syumai/dejs) - ejs template engine for deno.
- [denon](https://github.com/eliassjogreen/denon/blob/master/watcher.ts) - A file watcher with an for-await generator
- [deno_case_style](https://github.com/zekth/deno_case_style) - String validator and formater for different case style. eg: camelCase etc.
- [deno-checksum](https://github.com/manyuanrong/deno-checksum) - SHA1/MD5 algorithms.
- [deno-deamon](https://github.com/manyuanrong/deno-deamon) - Make the Deno program run in the background.
- deno-dotenv
    - [pietvanzoen/deno-dotenv](https://github.com/pietvanzoen/deno-dotenv) - Dotenv handling for deno.
    - [cardosomarcos/deno-dotenv](https://github.com/cardosomarcos/deno-dotenv) - Loads environment variables from .env for deno projects.
- [deno-express](https://github.com/NMathar/deno-express) - Node Express ported to Deno.
- [deno-fnparse](https://github.com/hashrock/deno-fnparse) - An extremely simple parser combinator for JavaScript.
- [deno-globrex](https://github.com/hayd/deno-globrex) - Port of globrex to deno, glob to regular expression.
- [deno-mysql](https://github.com/manyuanrong/deno_mysql) - MySQL database driver.
- [deno_mongo](https://github.com/manyuanrong/deno_mongo) - MongoDB database driver.
- [deno-opn](https://github.com/hashrock/deno-opn) - Opens stuff like websites, files, executables. Cross-platform.
- [deno-plugin-prepare](https://github.com/manyuanrong/deno-plugin-prepare) - A library for managing deno native plugin dependencies
- [deno-pretty-assert](https://github.com/bokuweb/deno-pretty-assert) - A colorful assertEqual for deno.
- [deno-prettystring](https://github.com/OnikurYH/deno-prettystring) - Format, trim and remove extra white spaces between characters from string.
- [deno_random_interval](https://github.com/zekth/deno_random_interval) - Helper to generate random interval.
- [deno-redis](https://github.com/keroxp/deno-redis) - An experimental implementation of redis client for deno.
- [deno-slugify](https://github.com/jcardama/deno_slugify) - A string slugifier for deno.
- [deno-smtp](https://github.com/manyuanrong/deno-smtp) - A smtp mail sender for deno.
- [deno_tiny_templates](https://github.com/zekth/deno_tiny_templates) - Template renderer for deno.
- [deno_tokenizer](https://github.com/eliassjogreen/deno_tokenizer) - A simple tokenizer for deno.
- [deno-using](https://github.com/hayd/deno-using) - An python-style with statements for deno.
- [deno-uuid](https://github.com/lucascaro/deno-uuid) - UUID module for deno.
- [deno-ws](https://github.com/keroxp/deno-ws) - An experimental implementation of websocket server for deno.ts.
- [deno-xml-parser](https://github.com/nekobato/deno-xml-parser) - Deno XML parser ported from segmentio/xml-parser.
- [dinatra](https://github.com/syumai/dinatra) - Sinatra like light weight web app framework for deno.
- [djwt](https://github.com/timonson/djwt) - Make JSON Web Tokens (JWT) on deno based on JWT and JWS specifications.
- [dso](https://github.com/manyuanrong/dso) - A simple ORM library based on mysql.
- [evt](https://github.com/garronej/evt) - Type safe replacement for EventEmitter.
- [expect](https://github.com/allain/expect) - Helpers for writing jest like expect tests in deno.
- [flags](https://github.com/denoland/deno_std/tree/master/flags) - Command line arguments parser for Deno based on minimist.
- [gardens](https://github.com/partheseas/gardens) - A useful logging utility for JavaScript everywhere.
- [gentleRpc](https://github.com/timonson/gentleRpc) - A JSON-RPC 2.0 TypeScript library for deno and the browser.
- [http](https://github.com/denoland/deno_std/tree/master/http) - HTTP module including a file server.
- [http-libs](https://github.com/denoserverless/http-libs) - HTTP modules and typings.
- [jwt](https://github.com/denoserverless/jwt) - Port of auth0/jsonwebtoken.
- [lazy](https://github.com/luvies/lazy) - A linq-like lazy-evaluation iteration module.
- [log](https://github.com/denoland/deno_std/tree/master/log) - Logging module for Deno.
- [marked](https://github.com/denolib/marked/) - Markdown-to-HTML converter.
- [ms](https://github.com/denolib/ms) - easily convert various time formats to milliseconds.
- [normalize_diacritics](https://github.com/motss/deno_mod/tree/master/normalize_diacritics) - Remove accents/diacritics in string.
- [oak](https://github.com/oakserver/oak) - A middleware framework for Deno's net server.
- [path](https://github.com/denoland/deno_std/tree/master/fs/path) - Deno Path Manipulation Libraries.
- [pogo](https://github.com/sholladay/pogo) - Server framework for Deno
- [postgres](https://github.com/buildondata/deno-postgres) - Driver for PostgreSQL database.
- [qs](https://github.com/denolib/qs) - A querystring parser with nesting support.
- [sax-ts](https://github.com/Maxim-Mazurok/sax-ts) - SAX-style XML parser ported from [sax-js](https://github.com/isaacs/sax-js)
- [servest](https://github.com/keroxp/servest) - A progressive HTTP server/router.
- [sql-builder](https://github.com/manyuanrong/sql-builder) - An sql query builder.
- [textproto](https://github.com/denoland/deno_std/tree/master/textproto)
- [type-fest](https://github.com/denoserverless/type-fest) - A collection of essential TypeScript types (port of sindresorhus/type-fest).
- [watch](https://github.com/jinjor/deno-watch) - A file watcher.
- [webview](https://github.com/eliassjogreen/deno_webview) - Deno bindings for webview, a tiny library for creating web-based desktop GUIs
- [wu-diff-js](https://github.com/bokuweb/wu-diff-js) - A diff library to compute differences between two slices using wu(the O(NP)) algorithm.

### 工具（待翻译）

- [clone](https://github.com/ekaragodin/clone) - a simple utility for the convenient clone.
- [denoget](https://github.com/syumai/denoget) - denoget installs executable deno script.
- [denoify](https://github.com/garronej/denoify) - For NPM module authors that would like to support Deno but do not want to write and maintain a port.
- [denoinit](https://github.com/syumai/deno-libs/tree/master/denoinit) - denoinit generates useful files for deno project.
- [denomander](https://github.com/siokas/denomander) - Deno command-line interfaces inspired from commander.js.
- [denon](https://github.com/eliassjogreen/denon) - Like Nodemon, but for Deno
- [denopkg](https://github.com/denopkg/denopkg.com) - An easier way to use code from GitHub in your Deno project.
- [denoversion](https://github.com/lucascaro/denoversion) - SemVer+git version management for Deno.
- [denox](https://github.com/BentoumiTech/denox) - Like packages.json scripts, but for Deno with permissions support.
- [deno.mk](https://github.com/MarkTiedemann/deno.mk) - Cross-platform Makefile for installing and running Deno.
- maxmcd's [deno-docker](https://github.com/maxmcd/deno-docker) A docker image.
- hayd's [deno-docker](https://github.com/hayd/deno-docker) Several docker images.
- [deno-vscode](https://github.com/ameerthehacker/deno-vscode) - Leverage the typedef and intellisense built into vscode using this extension
- [deno_ls_plugin](https://www.npmjs.com/package/deno_ls_plugin) - a TypeScript plugin which will allow TypeScript outside of Deno to resolve modules in a similar way to the way they are resolved inside of Deno.
- [dev_server](https://github.com/zhmushan/dev_server) - Let TypeScript files be used directly in the script tag.
- [dpm](https://github.com/BoltDoggy/deno#dpm) - Deno Package Manager, install global command for deno. like denoget.
- dvm
    - [justjavac/dvm](https://github.com/justjavac/dvm) - Deno Version Manager: manage multiple active deno versions.
    - [axetroy/dvm](https://github.com/axetroy/dvm) - Version manger for Deno without runtime dependencies.
- [elm-live-reload](https://github.com/jinjor/deno-playground/tree/master/elm-live-reload) - An elm live reloader written in Deno.
- [nessie](https://github.com/halvardssm/deno-nessie) - Create, migrate and rollback migrations for PostgreSQL, MySQL and SQLite.
- [task-runner](https://github.com/jinjor/deno-task-runner) - Write tasks just like npm scripts.
- [typescript-deno-plugin](https://github.com/justjavac/typescript-deno-plugin) - Deno language service plugin, providing intellisense in TypeScript files within editors.
- [udd](https://github.com/hayd/deno-udd) - Update deno dependencies: updates import statements to their latest published version.
- [vscode-deno](https://github.com/justjavac/vscode-deno) - VS Code extension that provides Deno support using the typescript-deno-plugin.
- [packer-provisioner-deno](https://github.com/dontlaugh/packer-provisioner-deno) - A Packer plugin that makes it easy to build virtual machine images with Deno scripts.
- [pika deno plugin](https://github.com/pikapkg/builders/tree/master/packages/plugin-build-deno/)

### **在线沙箱**

* deno-play.app：（⚠ 证书问题）。
* [deno.town](https://deno.town/)：在线执行 Deno 代码。

## 周边生态

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

### 系列文章（中文）

- [Deno 源码贡献指南（英文版）](https://denolib.gitbook.io/guide)，托管于 Gitbook 上。
- [Deno 进阶开发笔记](https://chenshenhai.com/deno_note)：不定时更新。
- ......逐步添加中，欢迎 Star & Fork & PR。

### 系列文章（英文）

* [V8 Docs for Deno](https://denolib.github.io/v8-docs/)：面向 Deno 的 V8 文档。
* [A Guide to Deno Core (Design & For Contributors)](https://denolib.gitbook.io/guide/) ，（⚠ 内容过期），发布于 2019 年。

### 技术专栏

- [Deno 开发者社区](https://zhuanlan.zhihu.com/denodev)：知乎专栏，[@justjavac](https://github.com/justjavac) 主导。
- [Deno 世界](https://zhuanlan.zhihu.com/denoland)：知乎专栏，[@嘤嘤](https://www.zhihu.com/people/yingyingxue) 主导。
- ......逐步添加中，欢迎 Star & Fork & PR。

### 在线视频

- ......逐步添加中，欢迎 Star & Fork & PR。

## 电子资源

> 专注收集公开免费的 PDF、PNG 以及电子书等资源，放置在本项目的 resources 文件夹下。

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