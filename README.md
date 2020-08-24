# Deno 资源全图谱 · 专注简中版 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-7-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

<img src="http://qiniu.ningo.cloud/deno/awesome-deno-cn-logo.png" style="height: 88px; width: 88px;">

> 仓库目录可以使用 Github Chrome 插件来浏览。

## 为什么有这个项目？

Deno v1.0 于 2020 年 05 月 13 日正式发布 v1.0 版本，一个专注于简中技术圈的 Deno 资源列表呼之欲出。

以下资源 🌟 代表品质推荐，⚠️ 代表注意事项。由于资源分类的多样性考虑，部分章节内容可能会有所重复。

### 独特之处

- [x] 长期提供更新，收集越来越多高质量的 Deno 资源，愿我们与 Deno 一起成长。
- [x] 随着 Deno 主版本进行版本归档更新。
- [x] 配套独家[《Deno 钻研之术》](https://github.com/hylerrix/deno-tutorial)电子书并随着本项目一起成长。
- [x] 及时跟进 [@denolib/awesome-deno](https://github.com/denolib/awesome-deno) 仓库。
- [ ] 开发更好看的 UI 页面来展示这个资源列表 -> 这份 UI 需要抽离出单个项目并引人到本项目中。

## 技术文档 🌟

- [deno.land](https://deno.land)：Deno 官网。
  - 简中：[denolang.cn](https://denolang.cn)。
- [deno.land/manual](https://deno.land/manual)：Deno 手册。
  - 简中：[nugine.github.io/deno-manual-cn](https://nugine.github.io/deno-manual-cn)。
  - 简中：[manual.deno.js.cn/](https://manual.deno.js.cn/)。
  - 简中：[denolang.cn/manual](https://denolang.cn/manual)。
- [doc.deno.land](https://doc.deno.land)：Deno API 文档。
  - 简中：[deno.dev/typedoc](https://deno.dev/typedoc)
- [deno.land/x](https://deno.land/x)：DenoX 第三方库。
- ...逐步添加中，欢迎 Star & Fork & PR。

## 基础设施

### Deno 源

> 虽然 Deno 可以直接导入 URL 代表着一定程度的去中心化，但是有中心化仓库也真香。

- [deno.land/x](https://deno.land/x)：官方提供的第三方库注册表。
- [nest.land](https://nest.land/)，基于区块链去中心化仓库。

### DenoLand 核心库

- [deno.land/std@0.63.0](https://deno.land/std@0.63.0)。

### Deno 周边社区库

> 重点将第三方库中，Github 组织带有 Deno 关键字的库专注整理这里。

- [@denolib/ms](https://github.com/denolib/ms)：轻松地将各种时间格式转换为毫秒。
- [@denolib/qs](https://github.com/denolib/qs)：具有嵌套支持的 querystring 解析器。
- [@denolib/camelcase](https://github.com/denolib/camelcase)：将破折号/点号/下划线/空格分隔的字符串转换为驼峰式；示例：foo-bar→fooBar。
- [@denolib/marked](https://github.com/denolib/marked/)：Markdown -> HTML 转换器。
- [@denofn/http-libs](https://github.com/denofn/http-libs)：HTTP 模块和类型。
- [@denofn/jwt](https://github.com/denofn/jwt)：auth0/jsonwebtoken 的端口。
- [@denofn/type-fest](https://github.com/denofn/type-fest)：基本 TypeScript 类型的集合（sindresorhus 端口/type-fest）。
- ...逐步添加中，欢迎 Star & Fork & PR。

### 第三方模块

> 更多内容可以看 Deno 官网上的[第三方库列表](https://deno.land/x)。可以将你的存储库提交到 [deno.land/x](https://github.com/denoland/deno_website2/blob/master/src/database.json) 中。

欢迎按字典顺序 PR！

- [abc](https://github.com/zhmushan/abc)：一个不错的 Deno Web 框架。
- [alosaur](https://github.com/alosaur/alosaur)：具有许多装饰器的 Deno Web 框架。
- [aqua](https://github.com/l2ig/aqua)：用于 Deno 的小又快的 Web 框架。
- [attain](https://github.com/aaronwlee/Attain)：用于 Deno 的中间件 Web 框架，它使用受 Express 和 Oak 启发的 http 标准库，快速稳定地使用适当的内存。
- [autopilot](https://github.com/divy-work/autopilot-deno)：使用 Deno 进行跨平台的 Web 自动化。
- [bytes_formater](https://github.com/manyuanrong/bytes_formater)：格式化字节（Uint8Array，ArrayBufferView ...）输出，在调试 IO 功能时很有用。
- [cac](https://github.com/cacjs/cac)：用于构建命令行应用程序的简单但功能强大的框架。
- [camelcase](https://github.com/denolib/camelcase)：将破折号/点号/下划线/空格分隔的字符串转换为camelCase：foo-bar→fooBar。
- [cli-spinner](https://github.com/ameerthehacker/cli-spinners)：在执行长任务时在终端中显示微调框。
- [coffee](https://github.com/irandeno/coffee)：Deno 配置——一种类型安全、易于使用的 Deno 配置管理器。
- [colors](https://deno.land/std/fmt/colors.ts)：用于 Deno 的基本控制台颜色库。
- [computed_types](https://github.com/neuledge/computed-types)：类似 Joi 的 Typescript 和 Deno 验证器。
- [context-finder](https://github.com/ebebbington/deno-context-finder)：从配置文件中提取上下文块。
- [csv](https://github.com/hashrock/deno-fnparse/blob/master/parsers/csv.ts)：一个简单的 CSV 解析器。
- [dejs](https://github.com/syumai/dejs)：一个用于 Deno 的 ejs 模板引擎。
- [deno-checksum](https://github.com/manyuanrong/deno-checksum)：SHA1/MD5 算法。
- [deno-context](https://github.com/code-hex/deno-context)：将期限，取消和其他要求范围的值传播给多个 Promise，行为就像 Go 的上下文。
- [deno-deamon](https://github.com/manyuanrong/deno-deamon)：使 Deno 程序在后台运行。
- [deno-dotenv](https://github.com/cardosomarcos/deno-dotenv)：从 .env 加载 deno 项目的环境变量。
- [deno-dotenv](https://github.com/pietvanzoen/deno-dotenv)：Dotenv 处理 deno。
  - [pietvanzoen/deno-dotenv](https://github.com/pietvanzoen/deno-dotenv)：Deno 下的 Dotenv。
  - [cardosomarcos/deno-dotenv](https://github.com/cardosomarcos/deno-dotenv)：从 .env 中 为Deno 项目加载环境变量。
- [deno-express](https://github.com/NMathar/deno-express)：Node Express 已移植到 Deno。
- [deno-fnparse](https://github.com/hashrock/deno-fnparse)：一个非常简单的 JavaScript 解析器、组合器。
- [deno-globrex](https://github.com/hayd/deno-globrex)：globrex 的端口为 deno，globex 的端口为正则表达式。
- [deno-mysql](https://github.com/manyuanrong/deno_mysql)：MySQL 数据库驱动程序。
- [deno-opn](https://github.com/hashrock/deno-opn)：一个可以打开网站、(可执行)文件之类资源的跨平台工具。
- [deno-plugin-prepare](https://github.com/manyuanrong/deno-plugin-prepare)：一个用于管理 Dedeno Native 插件依赖关系的库。
- [deno-pretty-assert](https://github.com/bokuweb/deno-pretty-assert)：一个 Deno 下的 assertEqual 库。
- [deno-prettystring](https://github.com/OnikurYH/deno-prettystring)：格式化，修剪和删除字符串中字符之间的多余空白。
- [deno-redis](https://github.com/keroxp/deno-redis)：Redis Client for Deno 的实验性实现。
- [deno-slugify](https://github.com/jcardama/deno_slugify)：Deno 的字符串节流器。
- [deno-smtp](https://github.com/manyuanrong/deno-smtp)：SMTP 的 SMTP 邮件发件人。
- [deno-using](https://github.com/hayd/deno-using)：带有 Deno 语句的 Python 样式。
- [deno-uuid](https://github.com/lucascaro/deno-uuid)：Deno 的 UUID 模块。
- [deno-websocket](https://github.com/ryo-ma/deno-websocket) - 🦕 一个简单的WebSocket库，例如 node.js 库的 ws。
- [deno-ws](https://github.com/keroxp/deno-ws)：一个 Websocket 服务器的实验性实现。
- [deno-xml-parser](https://github.com/nekobato/deno-xml-parser)：一个从 segmentio/xml-parser 移植的 Deno XML 解析器。
- [deno-yaml](https://github.com/muhibbudins/deno-yaml)：一个使用 Deno 的简单 Yaml 解析器。
- [deno_case_style](https://github.com/zekth/deno_case_style)：不同大小写样式的字符串验证器和格式化程序，例如 camelCase 等。
- [deno_cron](https://github.com/rbrahul/deno_cron)：cron job 调度程序，使您可以编写具有大量灵活性的可读 cron 语法
- [deno_ls_plugin](https://www.npmjs.com/package/deno_ls_plugin)：一个 TypeScript 插件，它将允许 Deno 之外的 TypeScript 以类似于在 Deno 内部进行解析的方式来解析模块。
- [deno_mongo](https://github.com/manyuanrong/deno_mongo)：MongoDB 数据库驱动程序。
- [deno_notify](https://github.com/PandawanFr/deno_notify)：在所有平台上发送桌面通知。
- [deno_random_interval](https://github.com/zekth/deno_random_interval)：帮助器生成随机间隔。
- [deno_tiny_templates](https://github.com/zekth/deno_tiny_templates)：Deno 的模板渲染器。
- [deno_tokenizer](https://github.com/eliassjogreen/deno_tokenizer)：Deno 的简单标记器。
- [denodb](https://github.com/eveningkid/denodb)：适用于 Deno 的 MySQL、SQLite、MariaDB、PostgreSQL 和 MongoDB ORM。
- [denon../watcher.ts](https://github.com/eliassjogreen/denon/blob/master/watcher.ts)：具有等待生成器的文件监视程序。
- [denon](https://github.com/eliassjogreen/denon)：像 Nodemon 的 Deno 库。
- [denotrain](https://github.com/Caesar2011/denotrain)：带有中间件支持的多合一 Web 框架，如 Express 或 Fastify for Node.js。
- [dinatra](https://github.com/syumai/dinatra)：🌟，一个类似于 Sinatra 的轻量级 Deno Web 应用程序框架。
- [dinoenv](https://deno.land/x/dinoenv):小型库，用于使用 deno 管理环境变量。
- [djwt](https://github.com/timonson/djwt)：根据 JWT 和 JWS 规范在 Deno 上创建 JSON Web 令牌（JWT）。
- [doa](https://github.com/JohannLai/doa)：一个移植自 koa 的 Deno web 框架 doa。
- [drash](https://github.com/drashland/deno-drash)：零依赖性的 Deno HTTP 服务器的 REST 微框架。
- [dso](https://github.com/manyuanrong/dso)：一个基于 MySQL 的简单 ORM 库。
- [duck](https://github.com/youngjuning/duck)：一个简单的扫描 controller 并自动注册路由的中间件。
- [ensure](https://github.com/eankeen/ensure)：确保您运行的是 Deno，Typescript 或 V8 的最低版本。
- [evt](https://github.com/garronej/evt)：EventEmitter 的安全替代品。
- [expect](https://github.com/allain/expect)：在 Deno 中编写 Jest 的助手。
- [flags](https://github.com/denoland/deno_std/tree/master/flags)：基于极简主义的 Deno 命令行参数解析器。
- [fossil](https://github.com/matteocrippa/fossil)：值类型验证套件。
- [gardens](https://github.com/partheseas/gardens)：一个无处不在的 JavaScript 记录实用程序。
- [gentleRpc](https://github.com/timonson/gentleRpc)：用于 Deno 和浏览器的 JSON-RPC 2.0 TypeScript 库。
- [http](https://github.com/denoland/deno_std/tree/master/http)：HTTP 模块，包括文件服务器。
- [invert-kv](https://github.com/denorg/invert-kv)：在 Deno 中反转键/值对。
- [lazy](https://github.com/luvies/lazy)：类似于 linq 的惰性求值迭代模块。
- [log](https://github.com/denoland/deno_std/tree/master/log)：Deno 的日志记录模块。
- [marked](https://github.com/denolib/marked/)：Markdown 到 HTML 转换器。
- [maze_generator](https://github.com/thewizardbear/maze_generator)：用于生成、求解、分析和显示迷宫的 Javascript 模块。
- [merlin](https://github.com/crewdevio/merlin)：Deno 的测试和基准框架 🧙‍♂️
- [microraptor](https://github.com/matteocrippa/microraptor)：轻量级框架，可通过验证轻松进行网络路由。
- [ms](https://github.com/denolib/ms)：轻松地将各种时间格式转换为毫秒。
- [normalize_diacritics](https://github.com/motss/deno_mod/tree/master/normalize_diacritics)：删除字符串中的重音符号/变音符号。
- [oak](https://github.com/oakserver/oak)：用于 Deno 网络服务器的中间件框架。
- [online](https://github.com/denorg/online)：检查您当前是否将 Deno 运行在线上。
- [opine](https://github.com/asos-craigmorten/opine)：从ExpressJS移植的快速，简约的网络框架。
- [path](https://github.com/denoland/deno_std/tree/master/fs/path)：Deno Path 操作库。
- [pogo](https://github.com/sholladay/pogo)：一个 Deno 服务端框架。
- [postgres](https://github.com/buildondata/deno-postgres)：PostgreSQL 数据库驱动程序。
- [qrcode](https://github.com/denorg/qrcode)：Deno 的 QR 码图像生成器。
- [qs](https://github.com/denolib/qs)：具有嵌套支持的查询字符串解析器。
- [recursive-readdir](https://github.com/denorg/recursive-readdir)：递归读取 Deno 中的目录。
- [rhum](https://github.com/drashland/rhum)：用于 Deno 的轻量级测试框架。
- [router](https://github.com/zhmushan/router)：高性能基本路由器可在任何地方工作。
- [rubico](https://github.com/richytong/rubico) - 🏞 异步函数组成；它刚刚能运行。
- [sax-ts](https://github.com/Maxim-Mazurok/sax-ts)：从 [sax-js](https://github.com/isaacs/sax-js) 移植的 SAX 风格的 XML 解析器。
- [servest](https://github.com/keroxp/servest)：渐进式HTTP服务器/路由器。
- [sockets](https://github.com/drashland/sockets) - 用于 Deno 的 WebSocket 库。
- [sql-builder](https://github.com/manyuanrong/sql-builder)：SQL 查询生成器。
- [status](https://github.com/denosaurs/status)：Deno 的 HTTP 代码和状态实用程序。
- [superdeno](https://github.com/asos-craigmorten/superdeno)：由超级代理驱动的库，用于测试 Deno HTTP 服务器。
- [task-runner-v2](https://github.com/ebebbington/deno-task-runner-v2)：deno-task-runner 的版本 2 解决方案。
- [textproto](https://github.com/denoland/deno_std/tree/master/textproto)。
- [time.ts](https://github.com/burhanahmeed/time.ts)：Time.ts，简便的 Deno 时区操作
- [ts-prometheus](https://github.com/marcopacini/ts-prometheus)：一个 prometheus 客户端。
- [type-fest](https://github.com/denoserverless/type-fest)：基本TypeScript类型的集合（sindresorhus端口/ type-fest）。
- [unexpected](https://github.com/unexpectedjs/unexpected)：可扩展的 BDD 断言工具包。
- [up](https://github.com/denorg/up)：检查是否在 Deno 中建立了网站。
- [vscode-deno](https://github.com/justjavac/vscode-deno)：VS Code 扩展，使用 typescript-deno-plugin 对 Deno 提供支持。
- [wasm-gzip](https://github.com/manyuanrong/wasm_gzip)：为 Deno 加密和解密 gzip。
- [watch](https://github.com/jinjor/deno-watch)：文件观察器（热更新）。
- [websocket_server](https://github.com/JohanWinther/websocket_server)：WebSocket 服务器库。 🔌
- [webview](https://github.com/eliassjogreen/deno_webview)：Webview 的 Deno 绑定，这是一个用于创建基于 Web 的桌面 GUI 的小型库。
- [wu-diff-js](https://github.com/bokuweb/wu-diff-js)：一个差异库，使用 wu（O（NP））算法计算两个切片之间的差异。
- [youtube-deno](https://github.com/akshgpt7/youtube-deno)：YouTube 数据 API 的 Deno 客户端库，用于与 YouTube 进行任何交互。
- ...逐步添加中，欢迎 Star & Fork & PR。

### 第三方工具

- [commands](https://github.com/buttercubz/commands)：为 Node.js 和 Deno 创建命令快捷方式。
- [clone](https://github.com/ekaragodin/clone)：一个方便克隆的简单实用程序。
- [dedep](https://github.com/egoist/dedep)：管理依赖版本。
- [denoget](https://github.com/syumai/denoget)：Deno 获取安装的可执行 Deno 脚本。
- [denoify](https://github.com/garronej/denoify)：对于希望支持 Deno 但不想编写和维护端口的 NPM 模块作者。
- [denoinit](https://github.com/syumai/deno-libs/tree/master/denoinit)：Denoinit 为 Deno 项目生成有用的文件。
- [denoliver](https://github.com/joakimunge/denoliver)：具有实时重新加载功能的简单，无依赖的文件服务器。
- [denomander](https://github.com/siokas/denomander)：Deno 命令行界面的灵感来自 commander.js。
- [denon](https://github.com/denosaurs/denon/blob/master/mod.ts)：具有 Await 生成器的文件监视程序。
- [denopkg](https://github.com/denopkg/denopkg.com)：在 Deno 项目中使用 GitHub 上的代码的更简单方法。
- [denoversion](https://github.com/lucascaro/denoversion)：Deno 的 SemVer + Git 版本管理。
- [denox](https://github.com/BentoumiTech/denox)：类似于 package.json 脚本，但在 Deno 上具有权限支持。
- [deno.mk](https://github.com/MarkTiedemann/deno.mk)：用于安装和运行 Deno 的跨平台 Makefile。
- [deno-docker](https://github.com/maxmcd/deno-docker)：一个 Docker 镜像。
- [deno-docker](https://github.com/hayd/deno-docker)：hayd 的几个 docker 映像。
- [deno-vscode](https://github.com/ameerthehacker/deno-vscode)：利用此扩展利用 VS Code 中内置的 typedef 和 intellisense。
- [dev_server](https://github.com/zhmushan/dev_server)：让 TypeScript 文件直接在 script 标签中使用。
- [dmm](https://github.com/drashland/dmm)：轻量级 Deno 模块管理器
- [dpm](https://github.com/BoltDoggy/deno#dpm)：Deno 软件包管理器，为 Deno 安装全局命令，比如 Denoget。—— DVM。
- [dep](https://github.com/denodep/dep)：Deno 依赖性管理工具。
- dvm
  - [dvm](https://github.com/justjavac/dvm)：Deno 版本管理器：管理多个活动的 Deno 版本。
  - [dvm](https://github.com/axetroy/dvm)：没有运行时相关性的 Deno 版本管理器。
  - [dvm.cmd](https://github.com/MarkTiedemann/dvm.cmd)：Windows 版 Deno 版本管理器，作为单个批处理文件编写。
- [elm-live-reload](https://github.com/jinjor/deno-playground/tree/master/elm-live-reload)：一个用 Deno 编写的 Elm Live Reloader。
- [make-deno-edition](https://github.com/bevry/make-deno-edition)：自动使 package.json 项目（例如 npm 软件包和 node.js 模块）与 Deno 兼容。
- [deno-nessie](https://github.com/halvardssm/deno-nessie)：为 PostgreSQL、MySQL 和 SQLite 创建，迁移和回滚迁移。
- [packer-provisioner-deno](https://github.com/dontlaugh/packer-provisioner-deno)：一个 Packer 插件，可轻松使用 Deno 脚本构建虚拟机映像。
- [pagic](https://github.com/xcatliu/pagic)：用 Deno 构建从 markdown 生成静态 html 页面的简单方法。
- [pika Deno plugin](https://github.com/pikapkg/builders/tree/master/packages/plugin-build-deno/)
- [starter](https://github.com/denorg/starter)：带有 GitHub Actions CI 的 Deno 模块入门模板。
- [deno-task-runner](https://github.com/jinjor/deno-task-runner)：像 NPM 脚本一样编写任务。
- [trex](https://github.com/crewdevio/Trex)：像 npm 一样的 deno 软件包管理。
- [typescript-deno-plugin](https://github.com/justjavac/typescript-deno-plugin)：Deno 语言服务插件，在编辑器中的 TypeScript 文件中提供智能感知。
- [deno-udd](https://github.com/hayd/deno-udd)：更新面依赖：将导入语句更新为最新发布的版本。
- [velociraptor](https://github.com/umbopepato/velociraptor)：Deno 的 npm 风格脚本运行器。
- [vscode-deno](https://github.com/denoland/vscode_deno)：VS Code 扩展，使用 TypeScript Deno 语言服务插件提供 Deno 支持。
- [Update Deno](https://github.com/marketplace/actions/update-deno)：Github Action，它将具有最新 Deno 版本的文件放入您的存储库。
- [denofn-selfhosted](https://github.com/denofn/denofn-selfhosted)：使用 Deno 和 Docker 构建的自托管 Deno 函数。
- [cloudbase-framework](https://github.com/TencentCloudBase/cloudbase-framework/tree/master/packages/framework-plugin-deno) - CloudBase Framework Deno Plugin : Deno 应用一键部署工具
- ...逐步添加中，欢迎 Star & Fork & PR。

### 在线沙箱

- [deno.town](https://deno.town)。
- [deno-playground.now.sh](https://deno-playground.now.sh)。
  - [@maman/deno-playground](https://github.com/maman/deno-playground)。
- [playground.denobr.com/](https://playground.denobr.com)。
- [repl.it/languages/deno](https://repl.it/languages/deno)。

## 解决方案

> 留坑，这里是未来探索的重点。主要罗列如何用 Deno 快速搭建起可供生产环境使用的解决方案。

如果你有好的解决方案，欢迎提供在这里！

## 项目模板（Demo）

* [deno-seed](https://github.com/tamasszoke/deno-seed) - 完整的开发样板 🌱。
* [deno-oak-mongo-demo](https://github.com/youngjuning/deno-oak-mongo-demo)。
* [deno-cloud-app](https://github.com/TencentCloudBase/cloudbase-templates/tree/master/deno)- 可以通过 CLI 一键部署的 Deno 云应用模板


### 开发 Deno 模块

- 如何开发 Deno （各种类别的）模块？
- ...逐步添加中，欢迎 Star & Fork & PR。

### 开发 Deno Web 服务端应用

- Deno + Oak + MySQL + RESTful 解决方案？
- Deno + Oak + MongoDB + GraphQL 解决方案？
- ...逐步添加中，欢迎 Star & Fork & PR。

### 开发 Deno Web 客户端应用

- Deno + React 解决方案？
- ...逐步添加中，欢迎 Star & Fork & PR。

## 技术教程

### 学习网站（简中）

- ...逐步添加中，欢迎 Star & Fork & PR。

### 学习网站（英文）

* [https://denobeginner.com](https://denobeginner.com)
- ...逐步添加中，欢迎 Star & Fork & PR。

### 技术专栏（简中）

- [juejin.im/tag/deno](https://juejin.im/tag/deno)：掘金标签。
- [Deno 开发者社区](https://zhuanlan.zhihu.com/denodev)：知乎专栏。
- [Deno 世界](https://zhuanlan.zhihu.com/denoland)：知乎专栏。
- [Deno 钻研之术](https://zhuanlan.zhihu.com/deno-tutorial)：知乎专栏。
- ...逐步添加中，欢迎 Star & Fork & PR。

### 技术专栏（英文）

- [freecodecamp.org/news/tag/deno](https://www.freecodecamp.org/news/tag/deno)：freeCodeCamp 标签。
- ...逐步添加中，欢迎 Star & Fork & PR。

### 系列文章（简中）

> 目前包括可能会写成电子书的资源。

- [Deno 进阶开发笔记](https://chenshenhai.com/deno_note)：不定时更新。
- ...逐步添加中，欢迎 Star & Fork & PR。

### 系列文章（英文）

- [V8 Docs for Deno](https://denolib.github.io/v8-docs/)：面向 Deno 的 V8 文档。
- [A Guide to Deno Core (Design & For Contributors)](https://denolib.gitbook.io/guide/)：(⚠ 内容过期），发布于 2019 年。
- [Deno 源码贡献指南（英文版）](https://denolib.gitbook.io/guide):托管于 Gitbook 上。
- ...逐步添加中，欢迎 Star & Fork & PR。

### 单篇文章（简中）

> 专注于收集高质量的博客文章，更多内容可以在谷歌/百度上搜索。目前 Deno 文章不多，尽可能多的罗列不设内容质量限制。

- [可能是首个支持部署 Deno 前后端应用的部署工具](https://zhuanlan.zhihu.com/p/189489957)：发布于 2020-08-19
- [从零开发一款Deno插件并发布](https://juejin.im/post/6859771063480352776)：发布于 2020-08-12。
- [基于 Deno 构建 HTTP Server 实践指南](https://juejin.im/post/6856447982905065486)：发布于 2020-08-03。
- [Deno从入门到跑路](https://juejin.im/post/6854573220432248839)：发布于 2020-07-27。
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

- [Continuous Integration with Deno](https://semaphoreci.com/blog/continuous-integration-with-deno)：发布于 2020-06-30。
- [Deploy a Deno Application on AWS Using Docker and Travis CI](https://dev.to/fhsinchy/deploy-a-deno-application-on-aws-using-docker-and-travis-ci-4p8o)：发布于 2020-06-14。
- [Create interactive mail utility CLI Tool using Deno](https://www.soubai.me/posts/create-interactive-mail-utility-cli-with-deno)：发布于 2020-06-11。
- [Develop and Dockerize a Blogging API With Deno, Oak, and MySQL](https://dev.to/fhsinchy/develop-and-dockerize-a-blogging-api-with-deno-oak-and-mysql-170e)：发布于 2020-06-10。
- [Building API's using Deno, Oak and MYSQL](https://codeforgeek.com/building-api-server-using-deno-and-mysql/)：发布于 2020-06-05。
- [Create your first News CLI app using Deno](https://medium.com/javascript-in-plain-english/creating-your-first-news-cli-app-using-deno-e1470398c627)：发布于 2020-06-02。
- [Create a simple Note-taking app with Deno](https://dev.to/jeferson_sb/create-a-simple-note-taking-app-with-deno-3k7g)：发布于 2020-05-21。
- [First thoughts about Deno](https://www.codegram.com/blog/first-thoughts-about-deno/)：发布于 2020-05-20。
- [Is Deno the new Node?](https://dev.to/smithg09/is-deno-the-new-node-7o4)：发布于 2020-05-20。
- [Deno vs. Node.js — Here are the most Important Differences](https://medium.com/javascript-in-plain-english/deno-vs-node-js-here-are-the-most-important-differences-62b547443be1)：发布于 2020-05-18。
- [From Node to Deno](https://dev.to/aralroca/from-node-to-deno-5gpn)：发布于 2020-05-17。
- [Why I Believe Deno is a Step in the Wrong Direction for JavaScript Runtime Environments](https://www.freecodecamp.org/news/why-deno-is-a-wrong-step-in-the-future/)：发布于 2020-05-14。
- [The Deno Handbook: A TypeScript Runtime Tutorial with Code Examples](https://www.freecodecamp.org/news/the-deno-handbook/)：发布于 2020-05-12。
- [Learn Deno: Chat app](https://aralroca.com/blog/learn-deno-chat-app)：发布于 2020-05-10。
- [Deno 1.0: What you need to know](https://blog.logrocket.com/deno-1-0-what-you-need-to-know/)：发布于 2020-05-06。
- [What is Deno? A ‘better’ Node.js](https://www.infoworld.com/article/3529779/what-is-deno-a-better-nodejs.html)：发布于 2020-02-28。
- [Forget NodeJS! Build native TypeScript applications with Deno 🦖](https://deepu.tech/deno-runtime-for-typescript/)：发布于 2020-02-18。
- - [Write a small API using Deno](https://dev.to/kryz/write-a-small-api-using-deno-1cl0)：发布于 2019-11-12。
- [Deno on AWS Lambda with Architect or SAM](https://blog.begin.com/deno-runtime-support-for-architect-805fcbaa82c3)：发布于 2019-11-21。
- [What's Deno, and how is it different from Node.js?](https://dev.to/bnevilleoneill/what-s-deno-and-how-is-it-different-from-node-js-366g)：发布于 2019-07-12。
- [What’s Deno, and how is it different from Node.js?](https://blog.logrocket.com/what-is-deno/)：发布于 2019-07-09。
- [Deno on Cloud Run](https://medium.com/google-cloud/deno-on-cloud-run-89ae64d1664d)：发布于 2019-05-14。
- [Getting started with Deno](https://dev.to/wuz/getting-started-with-deno-e1m)：发布于 2019-04-18。
- [Develop with Deno and Visual Studio Code](https://medium.com/@kitsonk/develop-with-deno-and-visual-studio-code-225ce7c5b1ba)：发布于 2019-01-05。
- [Ryan Dahl’s Node.js regrets lead to Deno](https://www.infoworld.com/article/3283250/ryan-dahls-nodejs-regrets-lead-to-deno.html)：发布于 2018-06-21。
- ...逐步添加中，欢迎 Star & Fork & PR。

### 翻译文章（简中）

> 这里专门抽来出来简中文章中，是翻译自其它语言（如英语）的文章。

- [Deno 1.0 即将发布，你需要知道的都在这里了](https://mp.weixin.qq.com/s/YZ39X_-nij-8Hl8vwsFBJA)：原文发布于 2020-05-06 日。
- ...逐步添加中，欢迎 Star & Fork & PR。

### 演讲稿（简中）

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

### 在线视频（简中）

- [Bilibilii | 【中英双语】Node 之父 - Deno，一个新的 JS 运行时](https://www.bilibili.com/video/BV124411Y74C)。
- [Deno 1.0 新特性了解一下](https://www.bilibili.com/video/BV14C4y1H76e)。
- ...逐步添加中，欢迎 Star & Fork & PR。

### 在线视频（英文）

- [Deno in 100 Seconds](https://www.youtube.com/watch?v=F0G9lZ7gecE)。
- ...逐步添加中，欢迎 Star & Fork & PR。

## 电子资源

> 专注收集公开免费的 PDF、PNG 以及电子书等资源，放置在本项目的 resources 文件夹下。

- [《Node.js 的设计缺陷（英文版）》](./resources/design-mistakes-in-node.pdf)。
- [《Node.js 的设计缺陷（简中版）》](./resources/design-mistakes-in-node-zh.pdf)。
- ...逐步添加中，欢迎 Star & Fork & PR。

## 技术社区

### 开源组织

> 重点收集专注于使用 & 回馈 Deno 生态圈的第三方 Github 组织。

- [github.com/denodev](https://github.com/denodev)。
- [github.com/denolib](https://github.com/denolib)。
- [github.com/denorg](https://github.com/denorg)。
- [github.com/denodep](https://github.com/denodep)。
- ...逐步添加中，欢迎 Star & Fork & PR。

### 社区列表（全网）

- [Deno Discord](https://discord.gg/TGMHGv6)：🌟，Discord 上的 Deno 官方聊天室，有简中社区。
- [deno.dev](https://deno.dev)：🌟，开发中。
- [deno.js.cn](https://deno.js.cn)：🌟，Deno 简中社区。
- [denocn.org](https://denocn.org)：🌟，Deno 简中社区。
- [yydeno](https://github.com/yydeno)：YY 大前端团队 Deno 仓库。
- ...逐步添加中，欢迎 Star & Fork & PR。

### 讨论热帖（简中）

- [Deno 会在短期内取代 Node 吗？](https://www.v2ex.com/t/674250)：发布于 2020-05-22。
- [@v2ex/Deno 1.0](https://v2ex.com/t/671449)：发布于 2020-05-13。
- [@v2ex/看了 Deno，感觉 TS 前景不可估量啊](https://www.v2ex.com/t/650730)：发布于 2020-03-08。
- ...逐步添加中，欢迎 Star & Fork & PR。

### 讨论热帖（英文）

- [Reddit 社区 | Deno](https://www.reddit.com/search/?q=deno)。
- ...逐步添加中，欢迎 Star & Fork & PR。

## 谁在用 Deno？

> 重点收集已经部署在生产环境的应用，欢迎推荐你的案例，逐步完善中。

* [UsingDeno](https://usingdeno.com/) - 使用 Deno 的 Web 应用程序和项目列表 🦕。
- ...逐步添加中，欢迎 Star & Fork & PR。

## 其它订阅

### 新闻媒体（英文）

- [Deno 新闻推送](https://deno.news)
- ...逐步添加中，欢迎 Star & Fork & PR。

### 社交媒体（英文）

- [twitter@deno_land](https://twitter.com/deno_land)：Deno Land 官方推特。
- ...逐步添加中，欢迎 Star & Fork & PR。

## 番外篇
  
### 从 Node.js 到 Deno.js

- [《Node.js 的设计缺陷》](http://tinyclouds.org/jsconf2018.pdf)：官方 PDF 演讲稿。
- [《Design Mistakes in Node》Node 之父 Ryan Dahl 演讲 PPT 简中版 (2018 JS Conf Berlin)](https://zhuanlan.zhihu.com/p/37637923)：发布于 2018-06-03。
- ...逐步添加中，欢迎 Star & Fork & PR。

### Deno 依赖的技术清单

> Deno 本身依赖的技术的清单库。

- [@dzharii/awesome-typeScript](https://github.com/dzharii/awesome-typescript)。
- [@semlinker/awesome-typeScript](https://github.com/semlinker/awesome-typescript)。
- [@rust-unofficial/awesome-rust](https://github.com/rust-unofficial/awesome-rust)。
- [@sindresorhus/awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs)。
- [@avelino/awesome-go](https://github.com/avelino/awesome-go)。
- [@jobbole/awesome-go-cn](https://github.com/jobbole/awesome-go-cn)。
- ...逐步添加中，欢迎 Star & Fork & PR。
  
### Deno 版本日志

从 v1.0 开始记录重要版本更新记录。

| 序号 | 发布日期 | Deno | 标准库 | 关键字 |
| --- | --- | --- | --- | --- |
| 01 | 2020-05-14  | v1.0.0 | v0.51.0 |
| 02 | 2020-05-21 | v1.0.1 | v0.52.0 |
| 03 | 2020-05-23 | v1.0.2 | v0.53.0 |
| 04 | 2020-05-30  | v1.0.3 | v0.54.0 |
| 05 | 2020-06-02 | v1.0.4 | v0.55.0 |
| 06 | 2020-06-04 | v1.0.5 | v0.56.0 |
| 07 | 2020-06-13 | v1.1.0 | v0.57.0 |
| 08 | 2020-06-20  | v1.1.1 | v0.58.0 |
| 09 | 2020-06-27 | v1.1.2 | v0.59.0 |
| 10 | 2020-07-04 | v1.1.3 | v0.60.0 |
| 11 | 2020-07-13 | v1.2.0 | v0.61.0 |
| 12 | 2020-07-24 | v1.2.1 | v0.62.0 |
| 13 | 2020-08-01 | v1.2.2 | v0.63.0 |

### 仓库更新日志

- [x] 2020-04-14 初始化本项目，填充独特的简中版内容。
- [x] 2020-04-14 跟进最新的（180+ Star） [@olivewind/awesome-deno-cn](https://github.com/olivewind/awesome-deno) 仓库内容。
- [x] 2020-05-13 新增《Deno 钻研之术》项目，将本项目作为前者的配套项目。
- [x] 2020-05-14 同步最新的 [@denolib/awesome-deno](https://github.com/denolib/awesome-deno) 仓库内容。
- [x] 2020-05-17 跟进简中化后大改版的（200+ Star） [@olivewind/awesome-deno-cn](https://github.com/olivewind/awesome-deno-cn) 仓库内容。
- [x] 2020-05-22 全网大量搜索 Deno 中英文资源并入库，发布 v1.0 版本并收录在[《Deno 钻研之术》](https://github.com/denolib/awesome-deno)第二篇中。
- [x] 2020-08-07 大幅更新：
  - [x] 跟随 Deno 主版本号同步发布 v1.2.2 版本
  - [x] 新增 all-contributor 贡献者机器人
  - [x] 增加如下章节：Deno 版本日志、解决方案
  - [x] 填充大量内容，新增贡献准则

## 贡献者 ✨

感谢如下贡献者的贡献 ([emoji key](https://allcontributors.org/docs/en/emoji-key))：

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/hylerrix"><img src="https://avatars1.githubusercontent.com/u/19285461?v=4" width="100px;" alt=""/><br /><sub><b>hylerrix</b></sub></a><br /><a href="#ideas-hylerrix" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/hylerrix/awesome-deno-cn/commits?author=hylerrix" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/JohannLai"><img src="https://avatars0.githubusercontent.com/u/10769405?v=4" width="100px;" alt=""/><br /><sub><b>JohannLai</b></sub></a><br /><a href="https://github.com/hylerrix/awesome-deno-cn/commits?author=JohannLai" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/champkeh"><img src="https://avatars3.githubusercontent.com/u/7316006?v=4" width="100px;" alt=""/><br /><sub><b>champ</b></sub></a><br /><a href="https://github.com/hylerrix/awesome-deno-cn/commits?author=champkeh" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/18510047382"><img src="https://avatars3.githubusercontent.com/u/45157599?v=4" width="100px;" alt=""/><br /><sub><b>Bd999</b></sub></a><br /><a href="https://github.com/hylerrix/awesome-deno-cn/commits?author=18510047382" title="Documentation">📖</a></td>
    <td align="center"><a href="https://youngjuning.js.org"><img src="https://avatars2.githubusercontent.com/u/13204332?v=4" width="100px;" alt=""/><br /><sub><b>杨俊宁</b></sub></a><br /><a href="https://github.com/hylerrix/awesome-deno-cn/commits?author=youngjuning" title="Documentation">📖</a></td>
    <td align="center"><a href="http://bookerzhao.com"><img src="https://avatars2.githubusercontent.com/u/7686861?v=4" width="100px;" alt=""/><br /><sub><b>Booker Zhao</b></sub></a><br /><a href="https://github.com/hylerrix/awesome-deno-cn/commits?author=binggg" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/zhmushan"><img src="https://avatars1.githubusercontent.com/u/24505451?v=4" width="100px;" alt=""/><br /><sub><b>木杉</b></sub></a><br /><a href="https://github.com/hylerrix/awesome-deno-cn/commits?author=zhmushan" title="Documentation">📖</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

本项目贡献者列表遵循 [all-contributors](https://github.com/all-contributors/all-contributors) 规范。欢迎你的参与，本仓库[贡献准则](./CONTRIBUTING.md)！

## 开源协议

本项目文档内容均采用 [CC-BY-SA-4.0](./LICENSE) 协议进行共享。
