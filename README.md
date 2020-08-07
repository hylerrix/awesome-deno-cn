# Deno 资源全图谱 · 专注中文版 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<img src="./assets/logo.png" style="height: 88px; width: 88px;">

<!--
https://github.com/denorg
https://github.com/denodep/dep
https://nest.land/
为什么有这个项目？
  提供解决方案推荐：Web 开发 Oak + MongoDB + GraphQL 推荐方案

https://juejin.im/tag/deno
https://github.com/youngjuning/deno-oak-mongo-demo

针对官网每个子项目，看看有没有对应的本土项目
-->

- [Deno 资源全图谱 · 专注中文版 ![Awesome](https://github.com/sindresorhus/awesome)](#deno-资源全图谱--专注中文版-img-srchttpscdnrawgitcomsindresorhusawesomed7305f38d29fed78fa85652e3a63e154dd8e8829mediabadgesvg-altawesome)
  - [为什么有这个项目？](#为什么有这个项目)
    - [独特之处](#独特之处)
    - [更新日志](#更新日志)
    - [贡献者](#贡献者)
  - [前言：从 Node.js 到 Deno.js](#前言从-nodejs-到-denojs)
  - [技术文档](#技术文档)
    - [官方文档](#官方文档)
    - [中文社区文档](#中文社区文档)
  - [基础设施](#基础设施)
    - [DenoLand 核心库](#denoland-核心库)
    - [Deno 周边社区库](#deno-周边社区库)
    - [第三方库](#第三方库)
    - [底层生态](#底层生态)
    - [在线沙箱](#在线沙箱)
    - [Demo](#demo)
  - [技术教程](#技术教程)
    - [演讲稿（中文）](#演讲稿中文)
    - [演讲稿（英文）](#演讲稿英文)
    - [单篇文章（中文）](#单篇文章中文)
    - [单篇文章（英文）](#单篇文章英文)
    - [翻译文章（中文）](#翻译文章中文)
    - [系列文章（中文）](#系列文章中文)
    - [系列文章（英文）](#系列文章英文)
    - [技术专栏（中文）](#技术专栏中文)
    - [技术专栏（英文）](#技术专栏英文)
    - [在线视频（中文）](#在线视频中文)
    - [在线视频（英文）](#在线视频英文)
  - [电子资源](#电子资源)
  - [技术社区](#技术社区)
    - [社区列表（全网）](#社区列表全网)
    - [讨论热帖（中文）](#讨论热帖中文)
    - [讨论热帖（英文）](#讨论热帖英文)
    - [Github 开源组织](#github-开源组织)
  - [谁在用 Deno？](#谁在用-deno)
  - [其它订阅](#其它订阅)
    - [新闻媒体（英文）](#新闻媒体英文)
    - [社交媒体（英文）](#社交媒体英文)
  - [开源协议](#开源协议)

## 为什么有这个项目？

Deno v1.0 于 2020 年 05 月 13 日正式发布 v1.0 版本，一个专注于中文技术圈的 Deno 资源列表呼之欲出。

以下资源 🌟 代表品质推荐，⚠️ 代表注意事项。由于资源分类的多样性考虑，部分章节内容可能会有所重复。

### 独特之处

- [x] 长期提供更新，收集越来越多高质量的 Deno 资源，愿我们与 Deno 一起成长。
- [x] 随着 Deno 主版本进行版本归档更新。
- [x] 配套独家[《Deno 钻研之术》](https://github.com/hylerrix/deno-tutorial)电子书并随着本项目一起成长。
- [x] 及时跟进 [@denolib/awesome-deno](https://github.com/denolib/awesome-deno) 仓库。
- [x] 及时跟进 [@olivewind/awesome-deno-cn](https://github.com/olivewind/awesome-deno-cn) 仓库。
- [ ] 开发更好看的 UI 页面来展示这个资源列表 -> 这份 UI 需要抽离出单个项目并引人到本项目中。

### 更新日志

- [x] 2020-04-14 初始化本项目，填充独特的中文版内容。
- [x] 2020-04-14 跟进最新的（180+ Star） [@olivewind/awesome-deno-cn](https://github.com/olivewind/awesome-deno) 仓库内容。
- [x] 2020-05-13 新增《Deno 钻研之术》项目，将本项目作为前者的配套项目。
- [x] 2020-05-14 同步最新的 [@denolib/awesome-deno](https://github.com/denolib/awesome-deno) 仓库内容。
- [x] 2020-05-17 跟进中文化后大改版的（200+ Star） [@olivewind/awesome-deno-cn](https://github.com/olivewind/awesome-deno-cn) 仓库内容。
- [x] 2020-05-22 全网大量搜索 Deno 中英文资源并入库，发布 v1.0 版本并收录在[《Deno 钻研之术》](https://github.com/denolib/awesome-deno)第二篇中。
- [ ] 2020-06-xx 月度更新：全网大量搜索 Deno 中英文资源并入库。
- [ ] 2020-06-xx 月度更新：跟进最新的 [@denolib/awesome-deno](https://github.com/denolib/awesome-deno) 和 [@olivewind/awesome-deno-cn](https://github.com/olivewind/awesome-deno-cn) 仓库内容。

### 贡献者

Deno 生态正在完善中，期待你的贡献，以下是贡献者列表。

- [@hylerrix](https://github.com/hylerrix)
- ...欢迎加入！

## 前言：从 Node.js 到 Deno.js

- [《Node.js 的设计缺陷》](http://tinyclouds.org/jsconf2018.pdf)：官方 PDF 演讲稿。
- [《Design Mistakes in Node》Node 之父 Ryan Dahl 演讲 PPT 中文版 (2018 JS Conf Berlin)](https://zhuanlan.zhihu.com/p/37637923)：发布于 2018-06-03。
- ...逐步添加中，欢迎 Star & Fork & PR。

## 技术文档

### 官方文档

> 包括中文社区的文档。

- [deno.land](https://deno.land)：🌟，Deno 官网。
- [Deno API 类型手册](https://deno.land/typedoc/)：
- [doc.deno.land](https://doc.deno.land)：自动化 Deno 文档生成器。
- [Deno Registry](https://deno.land/x/)：Deno 第三方库汇总。
- ...逐步添加中，欢迎 Star & Fork & PR。

### 中文社区文档
- [denolang.cn](https://denolang.cn)：🌟，Deno中文网
- [denolang.cn/manual](https://denolang.cn/manual)：🌟，Deno中文手册
- [@denodev/typedoc](https://github.com/denodev/typedoc)：🌟，Deno API 简体中文版。
- ...逐步添加中，欢迎 Star & Fork & PR。

## 基础设施

### DenoLand 核心库

> 更多的官方模块可以在 [deno_std](https://deno.land/std/) 上找到，目前版本 0.56.0。

- [deno/std/archive](https://deno.land/std/archive)。
- [deno/std/async](https://deno.land/std/async)。
- [deno/std/bytes](https://deno.land/std/bytes)。
- [deno/std/datetime](https://deno.land/std/datetime)。
- [deno/std/encoding](https://deno.land/std/encoding)。
- [deno/std/examples](https://deno.land/std/examples)。
- [deno/std/flags](https://deno.land/std/flags)。
- [deno/std/fmt](https://deno.land/std/fmt)。
- [deno/std/fs](https://deno.land/std/fs)。
- [deno/std/hash](https://deno.land/std/hash)。
- [deno/std/http](https://deno.land/std/http)。
- [deno/std/io](https://deno.land/std/io)。
- [deno/std/log](https://deno.land/std/log)。
- [deno/std/mime](https://deno.land/std/mime)。
- [deno/std/node](https://deno.land/std/node)。
- [deno/std/path](https://deno.land/std/path)。
- [deno/std/permissions](https://deno.land/std/permissions)。
- [deno/std/signal](https://deno.land/std/signal)。
- [deno/std/testing](https://deno.land/std/testing)。
- [deno/std/textproto](https://deno.land/std/textproto)。
- [deno/std/uuid](https://deno.land/std/uuid)。
- [deno/std/ws](https://deno.land/std/ws)。

### Deno 周边社区库

> 重点将第三方库中，Github 组织带有 Deno 关键字的库专注整理这里。

- [@denolib/ms](https://github.com/denolib/ms)：轻松地将各种时间格式转换为毫秒。
- [@denolib/qs](https://github.com/denolib/qs)：具有嵌套支持的 querystring 解析器。
- [@denolib/camelcase](https://github.com/denolib/camelcase)：将破折号/点号/下划线/空格分隔的字符串转换为驼峰式；示例：foo-bar→fooBar。
- [@denolib/camelcase](https://github.com/denolib/camelcase)：将破折号/点号/下划线/空格分隔的字符串转换为camelCase：foo-bar→fooBar。
- [@denolib/marked](https://github.com/denolib/marked/)：Markdown -> HTML 转换器。
- [@denolib/ms](https://github.com/denolib/ms)：轻松地将各种时间格式转换为毫秒。
- [@denopkg/denopkg](https://github.com/denopkg/denopkg.com)：在 Deno 项目中使用 GitHub 上的代码的更简单方法。。
- [@denopkg/denopkg.com](https://github.com/denopkg/denopkg.com)：在 Deno 项目中直接使用来自 GitHub 代码的简单方法。
- [@denoserverless/http-libs](https://github.com/denoserverless/http-libs)：HTTP 模块和类型。
- [@denoserverless/jwt](https://github.com/denoserverless/jwt)：auth0/jsonwebtoken 的端口。
- [@denoserverless/type-fest](https://github.com/denoserverless/type-fest)：基本 TypeScript 类型的集合（sindresorhus 端口/type-fest）
- ...逐步添加中，欢迎 Star & Fork & PR。

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
- [@johannlai/doa](https://github.com/JohannLai/doa)：🌟一个移植自 koa 的 Deno web 框架 doa。
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
- [@sholladay/pogo](https://github.com/sholladay/pogo)：一个 Deno 服务端框架。
- [@syumai/denoget](https://github.com/syumai/denoget)：denoget 安装可执行的 deno 脚本。
- [@syumai/deno-libs/.../denoget](https://github.com/syumai/deno-libs/tree/master/denoget)：安装可执行的 Deno 脚本。
- [@syumai/deno-libs/.../denoinit](https://github.com/syumai/deno-libs/tree/master/denoinit)：为 Deno 项目生成有用的文件。
- [@siokas/denomander](https://github.com/siokas/denomander)：Deno 命令行界面的灵感来自 commander.js。
- [@timonson/djwt](https://github.com/timonson/djwt)：根据 JWT 和 JWS 规范在 Deno 上创建 JSON Web 令牌（JWT）。
- [@timonson/gentleRpc](https://github.com/timonson/gentleRpc)：用于 Deno 和浏览器的 JSON-RPC 2.0 TypeScript 库。
- [@youngjuning/duck](https://github.com/youngjuning/duck): 一个简单的扫描controller并自动注册路由的中间件。
- [@zhmushan/abc](https://github.com/zhmushan/abc)：一个不错的 Deno Web 框架。
- [@zekth/deno_case_style](https://github.com/zekth/deno_case_style)：不同大小写样式的字符串验证器和格式化程序，例如 camelCase 等。
- [@zekth/deno_random_interval](https://github.com/zekth/deno_random_interval)：帮助器生成随机间隔。
- [@zekth/deno_tiny_templates](https://github.com/zekth/deno_tiny_templates)：Deno 的模板渲染器。
- [@zhmushan/dev_server](https://github.com/zhmushan/dev_server)：让 TypeScript 文件直接在 script 标签中使用。
- ...逐步添加中，欢迎 Star & Fork & PR。

### 底层生态

> Deno 本身依赖的技术的清单库

- [@dzharii/awesome-typeScript](https://github.com/dzharii/awesome-typescript)。
- [@semlinker/awesome-typeScript](https://github.com/semlinker/awesome-typescript)。
- [@rust-unofficial/awesome-rust](https://github.com/rust-unofficial/awesome-rust)。
- [@sindresorhus/awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs)。
- [@avelino/awesome-go](https://github.com/avelino/awesome-go)。
- [@jobbole/awesome-go-cn](https://github.com/jobbole/awesome-go-cn)：中文版。
- ...逐步添加中，欢迎 Star & Fork & PR。

### 在线沙箱

- deno-play.app：（⚠ 证书问题）。
- [deno.town](https://deno.town/)：在线执行 Deno 代码。
- [REPL](https://repl.it/languages/deno): 在线REPL

### Demo

> 如果遇到好的 Demo，均会收录在[《Deno 钻研之术》仓库](https://github.com/hylerrix/deno-tutorial)中，以下罗列社区来源。

- ...逐步添加中，欢迎 Star & Fork & PR。

## 技术教程

### 演讲稿（中文）

- ...逐步添加中，欢迎 Star & Fork & PR。

### 演讲稿（英文）

- [Ryan Dahl - 我为 Node.js 感到遗憾的 10 件事 | JSConf EU 2018](https://www.youtube.com/watch?v=M3BM9TB-8yA)
  - [演讲稿](https://tinyclouds.org/jsconf2018.pdf)
- [Ryan Dahl - Deno, 新的服务器端运行时 | JSDC 2018#A01](https://www.youtube.com/watch?v=FlTG0UXRAkE)
  - [演讲稿](https://tinyclouds.org/deno_jsdc.pptx)
- [Ryan Dahl - Deno, 一种新的 JavaScript 方法 | JS Fest 2019 Spring](https://www.youtube.com/watch?v=z6JRlx5NC9E)
  - [演讲稿](https://www.slideshare.net/JSFestUA/js-fest-2019-ryan-dahl-deno-a-new-way-to-javascript)
- [Rafał Pocztarski — 从 Node.js 到 Deno -使用 V8 和 Rust 构建的 JavaScript / TypeScript 运行时[EN]](https://www.youtube.com/watch?v=Aib1OZLy0_c)
  - [演讲稿](https://gitpitch.com/rsp/ntd/ntd?utm_campaign=Deno%20Newsletter#/)
- [Ryan Dahl: JavaScript 和 TypeScript 的安全运行时 | js.la April 2019](https://www.youtube.com/watch?v=RAmqgbv247s)
  - [演讲稿](https://docs.google.com/presentation/d/1CSQVTeH5tFzE4AZVXIpx9Xwew5YS-gxJZ03eRFtNeIc/edit)
- [Ryan Dahl: Deno, 一种新的 JavaScript 方法 | HolyJS 2019 Piter](https://www.youtube.com/watch?v=HjdJzNoT_qg)
  - [演讲稿](https://docs.google.com/presentation/d/1BjvZx5S8noVfFINptH4jfKfqh9jB9nXlFC0I3oIDtg4/edit)
- [Rafał Pocztarski - 什么是 Deno？ 2020年代用于现代 JavaScript 和 TypeScript 后端的新运行时 | Deno Warsaw](https://www.youtube.com/watch?v=aI5A9zvYSjk)
  - [演讲稿](https://gitpitch.com/rsp/wid/wid)
- [Michał Sabiniarz - 如何为 Deno 做贡献 | Deno Warsaw](https://www.youtube.com/watch?v=LAtjnKLbPpw)
  - [演讲稿](https://docs.google.com/presentation/d/1rETgslJS1ks4EihzLpUI3sS_zI46YxAOuQ5B1Z_k1mY/edit?usp=sharing)
- [Bartek Iwańczuk - Deno 内部是如何构建现代运行时 | Deno Warsaw](https://www.youtube.com/watch?v=qt7fbmypAFk)
  - [演讲稿](https://docs.google.com/presentation/d/1LYNGpyjx9PemL-P__7hVC8mSqkX-jL8VQLMhCRehy00/edit?usp=sharing)
- [Ryan Dahl & Kitson Kelly:  Deno 是一种新的 JavaScript 方法 | TSConf 2019](https://www.youtube.com/watch?v=1gIiZfSbEAE)
- ...逐步添加中，欢迎 Star & Fork & PR。

### 单篇文章（中文）

> 专注于收集高质量的博客文章，更多内容可以在谷歌/百度上搜索。目前 Deno 文章不多，尽可能多的诺列不设内容质量限制。

- [听说要干掉 node.js？用Deno实现价值上亿的AI核心算法试一下](https://juejin.im/post/5ebcfe79e51d454def2279bc)：发布于 2020-05-14。
- [了不起的 Deno 入门教程](https://mp.weixin.qq.com/s/2eqRTsf_z7Bcs6dziXe73Q)，发布于 2020-05-14。
- [Deno 运行时入门教程：Node.js 的替代品](http://www.ruanyifeng.com/blog/2020/01/deno-intro.html)：🌟，发布于 2020-01-26。
- [学得动的 Deno](https://juejin.im/post/5bc8b2166fb9a05d36350ea9)：发布于 2018-10-19。
- [Deno 并不是下一代 Node.js](https://juejin.im/post/5b14a390e51d4506c1300bbc)：🌟，发布于 2018-06-04。
- [让我们一起来学习别人学不动的 Deno](https://segmentfault.com/a/1190000015151287)：发布于 2018-06-03。
- [快速了解 deno 目前的 API](https://zhuanlan.zhihu.com/p/37569396)：发布于 2018-06-03。
- [玩 Deno 遇到问题的解决方案](https://juejin.im/post/5b1245b3f265da6e4c6cf249)：发布于 2018-06-02。
- [我不看好 Deno](https://zhuanlan.zhihu.com/p/139386360)。
- ...逐步添加中，欢迎 Star & Fork & PR。

### 单篇文章（英文）

- [First thoughts about Deno](https://www.codegram.com/blog/first-thoughts-about-deno/)：发布于 2020-05-20。
- [Is Deno the new Node?](https://dev.to/smithg09/is-deno-the-new-node-7o4)：发布于 2020-05-20。
- [Deno vs. Node.js — Here are the most Important Differences](https://medium.com/javascript-in-plain-english/deno-vs-node-js-here-are-the-most-important-differences-62b547443be1)：发布于 2020-05-18。
- [From Node to Deno](https://dev.to/aralroca/from-node-to-deno-5gpn)：发布于 2020-05-17。
- [Why I Believe Deno is a Step in the Wrong Direction for JavaScript Runtime Environments](https://www.freecodecamp.org/news/why-deno-is-a-wrong-step-in-the-future/)：发布于 2020-05-14。
- [The Deno Handbook: A TypeScript Runtime Tutorial with Code Examples](https://www.freecodecamp.org/news/the-deno-handbook/)：发布于 2020-05-12。
- [Learn Deno: Chat app](https://aralroca.com/blog/learn-deno-chat-app)：发布于 2020-05-10。
- [Deno 1.0: What you need to know](https://blog.logrocket.com/deno-1-0-what-you-need-to-know/)：发布于 2020-05-06。
- [Forget NodeJS! Build native TypeScript applications with Deno 🦖](https://deepu.tech/deno-runtime-for-typescript/)：发布于 2020-02-18。
- [What’s Deno, and how is it different from Node.js?](https://blog.logrocket.com/what-is-deno/)：发布于 2019-07-09。
- [What is Deno? A ‘better’ Node.js](https://www.infoworld.com/article/3529779/what-is-deno-a-better-nodejs.html)：发布于 2020-02-28。
- [Ryan Dahl’s Node.js regrets lead to Deno](https://www.infoworld.com/article/3283250/ryan-dahls-nodejs-regrets-lead-to-deno.html)：发布于 2018-06-21。
- ...逐步添加中，欢迎 Star & Fork & PR。

### 翻译文章（中文）

> 这里专门抽来出来中文文章中，是翻译自其它语言（如英语）的文章。

- [Deno 1.0 即将发布，你需要知道的都在这里了](https://mp.weixin.qq.com/s/YZ39X_-nij-8Hl8vwsFBJA)：原文发布于 2020-05-06 日。
- ...逐步添加中，欢迎 Star & Fork & PR。

### 系列文章（中文）

> 目前包括可能会写成电子书的资源。

- [Deno 进阶开发笔记](https://chenshenhai.com/deno_note)：不定时更新。
- [Deno 手册](https://nugine.github.io/deno-manual-cn/)。
- ...逐步添加中，欢迎 Star & Fork & PR。

### 系列文章（英文）

- [V8 Docs for Deno](https://denolib.github.io/v8-docs/)：面向 Deno 的 V8 文档。
- [A Guide to Deno Core (Design & For Contributors)](https://denolib.gitbook.io/guide/)：(⚠ 内容过期），发布于 2019 年。
- [Deno 源码贡献指南（英文版）](https://denolib.gitbook.io/guide):托管于 Gitbook 上。
- ...逐步添加中，欢迎 Star & Fork & PR。

### 技术专栏（中文）

- [Deno 开发者社区](https://zhuanlan.zhihu.com/denodev)：知乎专栏，[@justjavac](https://github.com/justjavac) 主导。
- [Deno 世界](https://zhuanlan.zhihu.com/denoland)：知乎专栏，[@嘤嘤](https://www.zhihu.com/people/yingyingxue) 主导。
- ...逐步添加中，欢迎 Star & Fork & PR。

### 技术专栏（英文）

- ...逐步添加中，欢迎 Star & Fork & PR。

### 在线视频（中文）

- [Bilibilii | 【中英双语】Node 之父 - Deno，一个新的 JS 运行时](https://www.bilibili.com/video/BV124411Y74C)。
- [Deno 1.0 新特性了解一下](https://www.bilibili.com/video/BV14C4y1H76e)。
- ...逐步添加中，欢迎 Star & Fork & PR。

### 在线视频（英文）

- [Deno in 100 Seconds](https://www.youtube.com/watch?v=F0G9lZ7gecE)。
- ...逐步添加中，欢迎 Star & Fork & PR。

## 电子资源

> 专注收集公开免费的 PDF、PNG 以及电子书等资源，放置在本项目的 resources 文件夹下。

- [《Node.js 的设计缺陷（英文版）》](./resources/design-mistakes-in-node.pdf)。
- [《Node.js 的设计缺陷（中文版）》](./resources/design-mistakes-in-node-zh.pdf)。
- ...逐步添加中，欢迎 Star & Fork & PR。

## 技术社区

### 社区列表（全网）

- [Deno Discord](https://discord.gg/TGMHGv6)：🌟，Discord 上的 Deno 官方聊天室，有中文社区。
- [deno.dev](https://deno.dev)：🌟，开发中，[@justjavac](https://github.com/justjavac) 主导。
- [deno.js.cn](https://deno.js.cn)：🌟，Deno 中文社区，[@justjavac](https://github.com/justjavac) 主导。
- [denocn.org](https://denocn.org)：🌟，Deno 中文社区，[@manyuanrong](https://github.com/manyuanrong) 主导。
- [yydeno](https://github.com/yydeno)：YY 大前端团队 Deno 仓库。
- ...逐步添加中，欢迎 Star & Fork & PR。

### 讨论热帖（中文）

- [Deno 会在短期内取代 Node 吗？](https://www.v2ex.com/t/674250)：发布于 2020-05-22。
- [@v2ex/Deno 1.0](https://v2ex.com/t/671449)：发布于 2020-05-13。
- [@v2ex/看了 Deno，感觉 TS 前景不可估量啊](https://www.v2ex.com/t/650730)：发布于 2020-03-08。
- ...逐步添加中，欢迎 Star & Fork & PR。

### 讨论热帖（英文）

- [Reddit 社区 | Deno](https://www.reddit.com/search/?q=deno)。
- ...逐步添加中，欢迎 Star & Fork & PR。

### Github 开源组织

> 重点收集专注于使用 & 回馈 Deno 生态圈的 Github 组织。暂不考虑可能有内容会与“技术社区”栏目重叠的问题。

- [Deno Land](https://github.com/denoland)：Deno 官方 Github 组织。
- [Deno Dev](https://github.com/denodev)：Deno 第三方组织之一，[@justjavac](https://github.com/justjavac) 主导。
- [Deno Lib](https://github.com/denolib)：Deno 第三方组织。
- ...逐步添加中，欢迎 Star & Fork & PR。

## 谁在用 Deno？

> 重点收集已经部署在生产环境的应用，欢迎推荐你的案例，逐步完善中。

- ...逐步添加中，欢迎 Star & Fork & PR。

## 其它订阅

### 新闻媒体（英文）

- [Deno 新闻推送](https://deno.news)
- ...逐步添加中，欢迎 Star & Fork & PR。

### 社交媒体（英文）

- [twitter@deno_land](https://twitter.com/deno_land)：Deno Land 官方推特。
- ...逐步添加中，欢迎 Star & Fork & PR。

## 开源协议

本项目文档内容均采用 [CC-BY-SA-4.0](./LICENSE) 协议进行共享。
