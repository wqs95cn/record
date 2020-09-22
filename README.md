# record
about record my study or life

## 安装
#### 1、F:\java\code-aliyun\record>nrm ls     看一下使用的是哪一个网站
```
  npm -------- https://registry.npmjs.org/
  yarn ------- https://registry.yarnpkg.com/
  cnpm ------- http://r.cnpmjs.org/
* taobao ----- https://registry.npm.taobao.org/
  nj --------- https://registry.nodejitsu.com/
  npmMirror -- https://skimdb.npmjs.com/registry/
   edunpm ----- http://registry.enpmjs.org/
```
##### 将vue-cli用作Vue应用程序和组件的零配置开发工具，请查看[docs](https://github.com/vuejs/vue-cli/blob/HEAD/docs/build.md)
#### 2、先决条件：Node.js（> = 6.x，首选8.x），npm 3+版本和Git。
```
cnpm安装
$ cnpm install -g vue-cli

用法
$ vue init <模板名称> <项目名称>

例：
$ vue init webpack 我的项目
```
##### 上面的命令从vuejs-templates / webpack中提取模板，提示您输入一些信息，并在生成项目./my-project/。
```
F:\java\code-aliyun\record>vue init webpack
直接运行会报错 "Missing required argument <app-name>",
即必须要指定项目名称。
正确指令是：
F:\java\code-aliyun>vue init webpack record
```
#### 3、安装：
> F:\java\code-aliyun>vue init webpack record
>
> ? Target directory exists. Continue? (Y/n) 输入：y
> ? Target directory exists. Continue? Yes
>
> / downloading template
>
> ? Project name (record)  回车
> ? Project name record
>
> ? Project description (A Vue.js project) 回车
> ? Project description A Vue.js project
>
> ? Author (wqs95cn <71604538+wqs95cn@users.noreply.github.com>)
> ? Author wqs95cn                      输入：wqs95cn
>
> ? Vue build (Use arrow keys)
> > Runtime + Compiler: recommended for most users            回车
>   Runtime-only: about 6KB lighter min+gzip, but templates
>   (or any Vue-specific HTML) are ONLY allowed in
>   .vue files - render functions are required elsewhere
>
> ? Install vue-router? (Y/n)            输入：y
> ? Install vue-router? Yes
>
> ? Use ESLint to lint your code? (Y/n)  输入：n
> ? Use ESLint to lint your code? No
>
> ? Set up unit tests? (Y/n)             输入：n
> ? Set up unit tests No
>
> ? Setup e2e tests with Nightwatch? (Y/n)  输入：n
> ? Setup e2e tests with Nightwatch? No
>
> ? Should we run `npm install` for you after the project has been created? (recommended) (Use arrow keys)
> > Yes, use NPM
>   Yes, use Yarn
>   No, I will handle that myself
>
> ? Should we run `npm install` for you after the project has been created? (recommended) npm
>
>    vue-cli · Generated "record".
>
>
>  \# Installing project dependencies ...
>  \# ========================
>
> npm WARN deprecated extract-text-webpack-plugin@3.0.2: Deprecated. Please use https://github.com/webpack-contrib/mini-css-extract-plugin
> npm WARN deprecated browserslist@2.11.3: Browserslist 2 could fail on reading Browserslist >3.0 config used in other tools.
> npm WARN deprecated bfj-node4@5.3.1: Switch to the `bfj` package for fixes and new features!
> npm WARN deprecated chokidar@2.1.8: Chokidar 2 will break on node v14+. Upgrade to chokidar 3 with 15x less dependencies.
> npm WARN deprecated core-js@2.6.11: core-js@<3 is no longer maintained and not recommended for usage due to the number of issues. Please, upgrade your dependencies
>  to the actual version of core-js@3.
> npm WARN deprecated fsevents@1.2.13: fsevents 1 will break on node v14+ and could be using insecure binaries. Upgrade to fsevents 2.
> npm WARN deprecated browserslist@1.7.7: Browserslist 2 could fail on reading Browserslist >3.0 config used in other tools.
> npm WARN deprecated resolve-url@0.2.1: https://github.com/lydell/resolve-url#deprecated
> npm WARN deprecated urix@0.1.0: Please see https://github.com/lydell/urix#deprecated
>
> > core-js@2.6.11 postinstall F:\java\code-aliyun\record\node_modules\core-js
> > node -e "try{require('./postinstall')}catch(e){}"
>
> Thank you for using core-js ( https://github.com/zloirock/core-js ) for polyfilling JavaScript standard library!
>
> The project needs your help! Please consider supporting of core-js on Open Collective or Patreon:
> > https://opencollective.com/core-js
> > https://www.patreon.com/zloirock
>
> Also, the author of core-js ( https://github.com/zloirock ) is looking for a good job -)
>
>
> > ejs@2.7.4 postinstall F:\java\code-aliyun\record\node_modules\ejs
> > node ./postinstall.js
>
> Thank you for installing EJS: built with the Jake JavaScript build tool (https://jakejs.com/)
>
>
> > uglifyjs-webpack-plugin@0.4.6 postinstall F:\java\code-aliyun\record\node_modules\webpack\node_modules\uglifyjs-webpack-plugin
> > node lib/post_install.js
>
> npm notice created a lockfile as package-lock.json. You should commit this file.
> npm WARN notsup Unsupported engine for watchpack-chokidar2@2.0.0: wanted: {"node":"<8.10.0"} (current: {"node":"14.8.0","npm":"6.14.7"})
> npm WARN notsup Not compatible with your version of node/npm: watchpack-chokidar2@2.0.0
> npm WARN ajv-keywords@3.5.2 requires a peer of ajv@^6.9.1 but none is installed. You must install peer dependencies yourself.
> npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.2.13 (node_modules\webpack-dev-server\node_modules\fsevents):
> npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.13: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})
> npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.2.13 (node_modules\watchpack-chokidar2\node_modules\fsevents):
> npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.13: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})
> npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@2.1.3 (node_modules\fsevents):
> npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@2.1.3: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})
>
> added 1269 packages from 673 contributors in 59.25s
>
> 32 packages are looking for funding
>   run `npm fund` for details
>
>
> \# Project initialization finished!
> \# ========================
>
> To get started:
>
>   cd record
>   npm run dev
>
> Documentation can be found at https://vuejs-templates.github.io/webpack

