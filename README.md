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
- [x] 2020-05-14 同步最新的 [@denolib/awesome-deno](https://github.com/denolib/awesome-deno) 仓库内容。
- [ ] 2020-05-xx 跟进中文化后大改版的 [@olivewind/awesome-deno-cn](https://github.com/olivewind/awesome-deno-cn) 仓库内容。
- [ ] 2020-05-xx 全网大量搜索 Deno 中英文资源并入库。
- [ ] 2020-05-xx 跟进最新的 [Deno 官方第三方库列表](https://deno.land/x/) 并进行翻译。
- [ ] 2020-06-xx 跟进最新的 [@denolib/awesome-deno](https://github.com/denolib/awesome-deno) 仓库内容。

### 贡献者

Deno 生态正在完善中，期待你的贡献，以下是贡献者列表。

- [@hylerrix](https://github.com/hylerrix)
- ......欢迎加入！

## 前言：从 Node.js 到 Deno.js

- [《Node.js 的设计缺陷》](http://tinyclouds.org/jsconf2018.pdf)：官方 PDF 演讲稿。
- [《Design Mistakes in Node》Node 之父 Ryan Dahl 演讲 PPT 中文版 (2018 JS Conf Berlin)](https://zhuanlan.zhihu.com/p/37637923)：发布于 2018-06-03。
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

### DenoLand 核心库

> 更多的官方模块可以在 [deno_std](https://deno.land/std/) 上找到。

- [colors](https://deno.land/std/fmt/colors.ts)：用于 Deno 的基本控制台颜色库。
- [denoland/deno_std/.../flags](https://github.com/denoland/deno_std/tree/master/flags)：（⚠️ 已归档），基于极简主义的Deno命令行参数解析器。
- [denoland/deno_std/.../http](https://github.com/denoland/deno_std/tree/master/http)：（⚠️ 已归档），HTTP模块，包括文件服务器。
- [denoland/deno_std/.../log](https://github.com/denoland/deno_std/tree/master/log)：（⚠️ 已归档），Deno的日志记录模块。
- [denoland/deno_std/.../path](https://github.com/denoland/deno_std/tree/master/fs/path)：（⚠️ 已归档）Deno Path操作库。
- [denoland/deno_std/.../textproto](https://github.com/denoland/deno_std/tree/master/textproto)：（⚠️ 已归档）。

### Deno 周边社区库

- [@denolib/ms](https://github.com/denolib/ms)：轻松地将各种时间格式转换为毫秒。
- [@denolib/qs](https://github.com/denolib/qs)：具有嵌套支持的 querystring 解析器。
- [@denolib/camelcase](https://github.com/denolib/camelcase)：将破折号/点号/下划线/空格分隔的字符串转换为驼峰式；示例：foo-bar→fooBar。
- [@denolib/camelcase](https://github.com/denolib/camelcase)：将破折号/点号/下划线/空格分隔的字符串转换为camelCase：foo-bar→fooBar。
- [@denolib/marked](https://github.com/denolib/marked/)：Markdown -> HTML 转换器。
- [@denolib/ms](https://github.com/denolib/ms)：轻松地将各种时间格式转换为毫秒。
- ......逐步添加中，欢迎 Star & Fork & PR。

### 第三方库

> 更多内容可以看 Deno 官网上的[第三方库列表](https://deno.land/x)。可以将你的存储库提交到 [deno.land/x](https://github.com/denoland/deno_website2/blob/master/src/database.json) 中。

如果你有兴趣帮忙按字母排列下放的列表的话，欢迎 PR！

- [@allain/expect](https://github.com/allain/expect)：在 Deno 中编写 Jest 的助手。
- [@alosaur/alosaur](https://github.com/alosaur/alosaur)：具有许多装饰器的 Deno Web框架。
- [@ameerthehacker/cli-spinner](https://github.com/ameerthehacker/cli-spinners)：在执行长任务时在终端中显示微调框。
- [@ameerthehacker/deno-vscode](https://github.com/ameerthehacker/deno-vscode)：利用此扩展利用 VS Code 中内置的 typedef 和 intellisense。
- [@axetroy/dvm](https://github.com/axetroy/dvm)：没有运行时相关性的 Deno 版本管理器。
- [@BentoumiTech/denox](https://github.com/BentoumiTech/denox)：类似于 package.json 脚本，但在 Deno 上具有权限支持。
- [@bokuweb/deno-pretty-assert](https://github.com/bokuweb/deno-pretty-assert)：色彩鲜艳的 deno assert 库。
- [@bokuweb/deno-pretty-assert](https://github.com/bokuweb/deno-pretty-assert)：一个 Deno 下的 assertEqual 库。
- [@bokuweb/wu-diff-js](https://github.com/bokuweb/wu-diff-js)：一个差异库，使用 wu（O（NP））算法计算两个切片之间的差异。
- [@BoltDoggy/dpm](https://github.com/BoltDoggy/deno#dpm)：Deno 软件包管理器，为 Deno 安装全局命令，比如 Denoget。—— DVM。
- [@BoltDoggy/dcc](https://github.com/BoltDoggy/deno)：Deno 清空缓存，在下次运行时重新加载 dep。
- [@buildondata/postgres](https://github.com/buildondata/deno-postgres)：PostgreSQL 数据库驱动程序。
- [@cacjs/cac](https://github.com/cacjs/cac)：用于构建命令行应用程序的简单但功能强大的框架。
- [@cardosomarcos/deno-dotenv](https://github.com/cardosomarcos/deno-dotenv)：从.env加载deno项目的环境变量。
- [@dontlaugh/packer-provisioner-deno](https://github.com/dontlaugh/packer-provisioner-deno)：一个 Packer 插件，可轻松使用 Deno 脚本构建虚拟机映像。
- [@denopkg/denopkg](https://github.com/denopkg/denopkg.com)：在 Deno 项目中使用 GitHub 上的代码的更简单方法。。
- [@denopkg/denopkg.com](https://github.com/denopkg/denopkg.com)：在 Deno 项目中直接使用来自 GitHub 代码的简单方法。
- [@denoserverless/http-libs](https://github.com/denoserverless/http-libs)：HTTP 模块和类型。
- [@denoserverless/jwt](https://github.com/denoserverless/jwt)：auth0/jsonwebtoken 的端口。
- [@denoserverless/type-fest](https://github.com/denoserverless/type-fest)：基本 TypeScript 类型的集合（sindresorhus 端口/type-fest）。
- [@eliassjogreen/denon](https://github.com/eliassjogreen/denon)：像 Nodemon 的 Deno 库。
- [@ekaragodin/clone](https://github.com/ekaragodin/clone)：一个方便克隆的简单实用程序。
- [@eliassjogreen/deno_tokenizer](https://github.com/eliassjogreen/deno_tokenizer)：Deno 的简单标记器。
- [@eliassjogreen/denon../watcher.ts](https://github.com/eliassjogreen/denon/blob/master/watcher.ts)：具有等待生成器的文件监视程序。
- [@eliassjogreen/webview](https://github.com/eliassjogreen/deno_webview)：Webview 的 Deno 绑定，这是一个用于创建基于 Web 的桌面 GUI 的小型库。
- [@garronej/evt](https://github.com/garronej/evt)：EventEmitter 的安全替代品。
- [@garronej/denoify](https://github.com/garronej/denoify)：对于希望支持 Deno 但不想编写和维护端口的 NPM 模块作者。
- [@hashrock/deno-fnparse](https://github.com/hashrock/deno-fnparse)：一个非常简单的 JavaScript 解析器、组合器。
- [@hashrock/deno-opn](https://github.com/hashrock/deno-opn)：一个可以打开网站、(可执行)文件之类资源的跨平台工具。
- [@hashrock/deno-fnparse/.../csv](https://github.com/hashrock/deno-fnparse/blob/master/parsers/csv.ts)：一个简单的 CSV 解析器。
- [@hashrock/deno-fnparse](https://github.com/hashrock/deno-fnparse)：一个非常简单的 JavaScript 解析器组合器。
- [@hashrock/deno-opn](https://github.com/hashrock/deno-opn)：打开网站，文件，可执行文件之类的东西，跨平台。
- [@hayd/deno-udd](https://github.com/hayd/deno-udd)：更新面依赖：将导入语句更新为最新发布的版本。
- [@halvardssm/deno-nessie](https://github.com/halvardssm/deno-nessie)：为 PostgreSQL、MySQL 和 SQLite 创建，迁移和回滚迁移。
- [@hayd/deno-docker](https://github.com/hayd/deno-docker)：数个 Docker 镜像。
- [@hayd/deno-using](https://github.com/hayd/deno-using)：带有 Deno 语句的 Python 样式。
- [@hayd/deno-globrex](https://github.com/hayd/deno-globrex)：globrex 的端口为 deno，globex 的端口为正则表达式。
- [@jinjor/watch](https://github.com/jinjor/deno-watch)：文件观察器（热更新）。
- [@justjavac/vscode-deno](https://github.com/justjavac/vscode-deno)：🌟，VS Code 扩展，使用 typescript-deno-plugin 提供 Deno 支持。
- [@justjavac/dvm](https://github.com/justjavac/dvm)：Deno 版本管理器：管理多个活动的 Deno 版本。
- [@justjavac/typescript-deno-plugin](https://github.com/justjavac/typescript-deno-plugin)：Deno 语言服务插件，在编辑器中的 TypeScript 文件中提供智能感知。
- [@justjavac/vscode-deno](https://github.com/justjavac/vscode-deno)：VS Code 扩展，使用 typescript-deno-plugin 对 Deno 提供支持。
- [@jinjor/elm-live-reload](https://github.com/jinjor/deno-playground/tree/master/elm-live-reload)：一个用 Deno 编写的 Elm Live Reloader。
- [@jcardama/deno-slugify](https://github.com/jcardama/deno_slugify)：Deno 的字符串节流器。
- [@jinjor/deno-playground/.../expressive](https://github.com/jinjor/deno-playground/tree/master/expressive)：一个类似于 Express 的 Deno Web 框架。
- [@jinjor/deno-playground/.../watch](https://github.com/jinjor/deno-playground/tree/master/watch)：一个文件监听程序。
- [@jinjor/deno-playground/.../elm-live-reload](https://github.com/jinjor/deno-playground/tree/master/elm-live-reload)：用 Deno 编写的 Elm Live Reloader。
- [@jinjor/deno-task-runner](https://github.com/jinjor/deno-task-runner)：像 NPM 脚本一样编写任务。
- [@keroxp/deno-redis](https://github.com/keroxp/deno-redis)：一个由 Deno 实现的实验性的 Redis 客户端。
- [@keroxp/deno-ws](https://github.com/keroxp/deno-ws)：一个 Websocket 服务器的实验性实现。
- [@kitsonk/oak](https://github.com/kitsonk/oak)：一个用于 Deno 网络服务器的中间件框架。
- [@keroxp/servest](https://github.com/keroxp/servest)：渐进式HTTP服务器/路由器。
- [@keroxp/deno-ws](https://github.com/keroxp/deno-ws)：Websocket 服务器的实验性实现。
- [@keroxp/deno-redis](https://github.com/keroxp/deno-redis)：Redis Client for Deno 的实验实现。
- [@lucascaro/denoversion](https://github.com/lucascaro/denoversion)：Deno 的 SemVer + Git 版本管理。
- [@lucascaro/deno-uuid](https://github.com/lucascaro/deno-uuid)：Deno 的 UUID 模块。
- [@luvies/lazy](https://github.com/luvies/lazy)：类似于 linq 的惰性求值迭代模块。
- [@muhibbudins/deno-yaml](https://github.com/muhibbudins/deno-yaml)：一个使用 Deno 的简单 Yaml 解析器。
- [@MarkTiedemann/deno.mk](https://github.com/MarkTiedemann/deno.mk)：用于安装和运行 Deno 的跨平台 Makefile。
- [@maxmcd/deno-docker](https://github.com/maxmcd/deno-docker)：一个 Docker 镜像。
- [@Maxim-Mazurok/sax-ts](https://github.com/Maxim-Mazurok/sax-ts)：从 [sax-js](https://github.com/isaacs/sax-js) 移植的SAX风格的XML解析器。
- [@manyuanrong/sql-builder](https://github.com/manyuanrong/sql-builder)：SQL 查询生成器。
- [@manyuanrong/dso](https://github.com/manyuanrong/dso)：一个基于 MySQL 的简单 ORM 库。
- [@manyuanrong/deno-smtp](https://github.com/manyuanrong/deno-smtp)：SMTP 的 SMTP 邮件发件人。
- [@manyuanrong/deno-mysql](https://github.com/manyuanrong/deno_mysql)：MySQL 数据库驱动程序。
- [@manyuanrong/deno_mongo](https://github.com/manyuanrong/deno_mongo)：MongoDB 数据库驱动程序。
- [@manyuanrong/deno-plugin-prepare](https://github.com/manyuanrong/deno-plugin-prepare)：一个用于管理 Dedeno Native 插件依赖关系的库。
- [@manyuanrong/deno-checksum](https://github.com/manyuanrong/deno-checksum)：SHA1/MD5 算法。
- [@manyuanrong/deno-deamon](https://github.com/manyuanrong/deno-deamon)：使Deno程序在后台运行。
- [@manyuanrong/bytes_formater](https://github.com/manyuanrong/bytes_formater)：格式化字节（Uint8Array，ArrayBufferView ...）输出，在调试 IO 功能时很有用。
- [@motss/deno_mod/.../normalize_diacritics](https://github.com/motss/deno_mod/tree/master/normalize_diacritics)：删除字符串中的重音符号/变音符号。
- [@nekobato/deno-xml-parser](https://github.com/nekobato/deno-xml-parser)：一个从 segmentio/xml-parser 移植的 Deno XML 解析器。
- [@npmjs.com/deno_ls_plugin](https://www.npmjs.com/package/deno_ls_plugin)：一个 TypeScript 插件，它将允许 Deno 之外的 TypeScript 以类似于在 Deno 内部进行解析的方式来解析模块。
- [@nekobato/deno-xml-parser](https://github.com/nekobato/deno-xml-parser)：从 segmentio/xml-parser 移植来的 Deno XML 解析器。
- [@NMathar/deno-express](https://github.com/NMathar/deno-express)：Node Express已移植到Deno。
- [@OnikurYH/deno-prettystring](https://github.com/OnikurYH/deno-prettystring)：格式化，修剪和删除字符串中字符之间的多余空白。
- [@oakserver/oak](https://github.com/oakserver/oak)：用于 Deno 网络服务器的中间件框架。
- [@pietvanzoen/deno-dotenv](https://github.com/pietvanzoen/deno-dotenv)：Dotenv 处理 deno。
- [@pikapkg/builders/.../pika deno plugin](https://github.com/pikapkg/builders/tree/master/packages/plugin-build-deno/)。
- [@partheseas/gardens](https://github.com/partheseas/gardens)：一个无处不在的 JavaScript 记录实用程序。
- [@syumai/dejs](https://github.com/syumai/dejs)：一个用于 Deno 的 ejs 模板引擎。
- [@syumai/dinatra](https://github.com/syumai/dinatra)：🌟，一个类似于 Sinatra 的轻量级 Deno Web 应用程序框架。
- [@syumai/dejs](https://github.com/syumai/dejs)：edeno 的 ejs 模板引擎。
- [@sholladay/pogo](https://github.com/sholladay/pogo)：一个 Deno 服务端框架。
- [@syumai/denoget](https://github.com/syumai/denoget)：denoget 安装可执行的 deno 脚本。
- [@syumai/deno-libs/.../denoget](https://github.com/syumai/deno-libs/tree/master/denoget)：安装可执行的 Deno 脚本。
- [@syumai/deno-libs/.../denoinit](https://github.com/syumai/deno-libs/tree/master/denoinit)：为 Deno 项目生成有用的文件。
- [@siokas/denomander](https://github.com/siokas/denomander)：Deno 命令行界面的灵感来自 commander.js。
- [@timonson/djwt](https://github.com/timonson/djwt)：根据 JWT 和 JWS 规范在 Deno 上创建 JSON Web 令牌（JWT）。
- [@timonson/gentleRpc](https://github.com/timonson/gentleRpc)：用于 Deno 和浏览器的 JSON-RPC 2.0 TypeScript 库。
- [@zhmushan/abc](https://github.com/zhmushan/abc)：一个不错的 Deno Web 框架。
- [@zekth/deno_case_style](https://github.com/zekth/deno_case_style)：不同大小写样式的字符串验证器和格式化程序，例如 camelCase 等。
- [@zekth/deno_random_interval](https://github.com/zekth/deno_random_interval)：帮助器生成随机间隔。
- [@zekth/deno_tiny_templates](https://github.com/zekth/deno_tiny_templates)：Deno 的模板渲染器。
- [@zhmushan/dev_server](https://github.com/zhmushan/dev_server)：让 TypeScript 文件直接在 script 标签中使用。
- ......逐步添加中，欢迎 Star & Fork & PR。

### **在线沙箱**

* deno-play.app：（⚠ 证书问题）。
* [deno.town](https://deno.town/)：在线执行 Deno 代码。

## 技术教程

### 单篇文章（中文）

> 专注于收集高质量的博客文章，更多内容可以在谷歌/百度上搜索。目前 Deno 文章不多，尽可能多的诺列不设内容质量限制。

- [Deno 运行时入门教程：Node.js 的替代品](http://www.ruanyifeng.com/blog/2020/01/deno-intro.html)：🌟，发布于 2020-01-26。
- [学得动的 Deno](https://juejin.im/post/5bc8b2166fb9a05d36350ea9)：发布于 2018-10-19。
- [Deno 并不是下一代 Node.js](https://juejin.im/post/5b14a390e51d4506c1300bbc)：🌟，发布于 2018-06-04。
- [让我们一起来学习别人学不动的 Deno](https://segmentfault.com/a/1190000015151287)：发布于 2018-06-03。
- [快速了解 deno 目前的 API](https://zhuanlan.zhihu.com/p/37569396)：发布于 2018-06-03。
- [玩 Deno 遇到问题的解决方案](https://juejin.im/post/5b1245b3f265da6e4c6cf249)：发布于 2018-06-02。
- ......逐步添加中，欢迎 Star & Fork & PR。

### 单篇文章（英文）

- [Forget NodeJS! Build native TypeScript applications with Deno 🦖](https://deepu.tech/deno-runtime-for-typescript/)：发布于 2020-02-18。
- [What’s Deno, and how is it different from Node.js?](https://blog.logrocket.com/what-is-deno/)：发布于 2019-07-09。
- [What is Deno? A ‘better’ Node.js](https://www.infoworld.com/article/3529779/what-is-deno-a-better-nodejs.html)：发布于 2020-02-28。
- [Ryan Dahl’s Node.js regrets lead to Deno](https://www.infoworld.com/article/3283250/ryan-dahls-nodejs-regrets-lead-to-deno.html)：发布于 2018-06-21。
- ......逐步添加中，欢迎 Star & Fork & PR。

### 系列文章（中文）

- [Deno 进阶开发笔记](https://chenshenhai.com/deno_note)：不定时更新。
- [Deno 手册](https://nugine.github.io/deno-manual-cn/)。
- ......逐步添加中，欢迎 Star & Fork & PR。

### 系列文章（英文）

* [V8 Docs for Deno](https://denolib.github.io/v8-docs/)：面向 Deno 的 V8 文档。
* [A Guide to Deno Core (Design & For Contributors)](https://denolib.gitbook.io/guide/)：(⚠ 内容过期），发布于 2019 年。
- [Deno 源码贡献指南（英文版）](https://denolib.gitbook.io/guide):托管于 Gitbook 上。

### 技术专栏

- [Deno 开发者社区](https://zhuanlan.zhihu.com/denodev)：知乎专栏，[@justjavac](https://github.com/justjavac) 主导。
- [Deno 世界](https://zhuanlan.zhihu.com/denoland)：知乎专栏，[@嘤嘤](https://www.zhihu.com/people/yingyingxue) 主导。
- ......逐步添加中，欢迎 Star & Fork & PR。

### 在线视频

- ......逐步添加中，欢迎 Star & Fork & PR。

## 电子资源

> 专注收集公开免费的 PDF、PNG 以及电子书等资源，放置在本项目的 resources 文件夹下。

* [《Node.js 的设计缺陷（英文版）》](./resources/design-mistakes-in-node.pdf)。
* [《Node.js 的设计缺陷（中文版）》](./resources/design-mistakes-in-node-zh.pdf)。
- ......逐步添加中，欢迎 Star & Fork & PR。

## 技术社区

### 社区列表

- [Deno Discord](https://discord.gg/TGMHGv6)：🌟，Discord 上的 Deno 官方聊天室，有中文社区。
- [deno.dev](https://deno.dev)：🌟，开发中，[@justjavac](https://github.com/justjavac) 主导。
- [denocn.org](https://denocn.org)：🌟，Deno 中文社区，[@manyuanrong](https://github.com/manyuanrong) 主导。
- [deno.js.cn](https://deno.js.cn)：开发中，[@???]() 主导。
- ......逐步添加中，欢迎 Star & Fork & PR。

### 讨论热帖

* [@v2ex/Deno 1.0](https://v2ex.com/t/671449)
* [@v2ex/看了 Deno，感觉 TS 前景不可估量啊](https://www.v2ex.com/t/650730)

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