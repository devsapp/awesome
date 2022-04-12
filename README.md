![](https://serverless-article-picture.oss-cn-hangzhou.aliyuncs.com/1638187918372_20211129121158776024.png)

<p align="center"><b> 中文 | <a href="./README_en.md"> English </a>  </b></p>

> 本仓库是Serverless Devs阿里云系列的Awesome，在这里可以查看到关于阿里云相关组件的大部分内容。除了下面正文中的详细信息，您还可能需要关注：
> 1. [Serverless Devs与CICD的结合](https://github.com/Serverless-Devs/Serverless-Devs/blob/master/docs/zh/cicd.md)
> 2. [函数计算组件文档](https://github.com/devsapp/fc) 与 [函数计算快速入门文档](https://github.com/devsapp/start-fc)
> 3. [Serverless 应用引擎（SAE）文档](https://github.com/devsapp/sae) 与 [Serverless 应用引擎（SAE）快速入门文档](https://github.com/devsapp/start-sae)    
> 更多关于案例和内容，可以参考以下目录。

- [Hello World](#Hello-World)
- [Web Framework应用案例](#Web-Framework应用案例)
- [静态网站应用案例](#静态网站应用案例)
- [场景合集](#场景合集)
    - [AI场景](#AI场景)
    - [音视频处理案例](#音视频处理案例)
    - [Serverless架构下数据库使用](#Serverless架构下数据库使用)
    - [其他](#其他)

## Hello World

<table>
<tr>
<th>HTTP函数</th>
<th>Event函数</th>
<th>Custom Runtime</th>
<th>Custom Container</th>
</tr>
<tr>
<td align="center">
<a href="https://github.com/devsapp/start-fc/tree/master/http-function/fc-http-node.js6/src">fc-http-node.js6</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/http-function/fc-http-node.js8/src">fc-http-node.js8</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/http-function/fc-http-node.js10/src">fc-http-node.js10</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/http-function/fc-http-node.js12/src">fc-http-node.js12</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/http-function/fc-http-node.js14/src">fc-http-node.js14</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/http-function/fc-http-php7.2/src">fc-http-php7.2</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/http-function/fc-http-python2.7/src">fc-http-python2.7</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/http-function/fc-http-python3.6/src">fc-http-python3.6</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/http-function/fc-http-java8/src">fc-http-java8</a><br>
        <a href="https://github.com/devsapp/start-fc/blob/master/event-function/fc-http-golang1.x/src">fc-http-golang</a>
</td>
<td align="center">
<a href="https://github.com/devsapp/start-fc/tree/master/event-function/fc-event-node.js6/src">fc-event-node.js6</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/event-function/fc-event-node.js8/src">fc-event-node.js8</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/event-function/fc-event-node.js10/src">fc-event-node.js10</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/event-function/fc-event-node.js12/src">fc-event-node.js12</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/event-function/fc-event-node.js14/src">fc-event-node.js14</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/event-function/fc-event-php7.2/src">fc-event-php7.2</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/event-function/fc-event-python2.7/src">fc-event-python2.7</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/event-function/fc-event-python3.6/src">fc-event-python3.6</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/event-function/fc-event-java8/src">fc-event-java8</a><br>
        <a href="https://github.com/devsapp/start-fc/blob/master/event-function/fc-event-golang1.x/src">fc-event-golang</a>
</td>
<td align="center">
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/golang/fc-custom-golang-event/src">Golang Event函数</a><br>
<a href="https://github.com/devsapp/start-fc/blob/master/custom-function/golang/fc-custom-golang-websocket/src">Golang Websocket函数</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/nodejs10/fc-custom-nodejs10-event/src">Nodejs10 Event函数</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/nodejs10/fc-custom-nodejs10-websocket/src">Nodejs10 Websocket函数</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/nodejs12/fc-custom-nodejs12-event/src">Nodejs12 Event函数</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/nodejs12/fc-custom-nodejs12-websocket/src">Nodejs12 Websocket函数</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/php74/fc-custom-php74-event/src">PHP74-Swoole Event函数</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/php74/fc-custom-php74-http/src">PHP74-Swoole HTTP函数</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/python37/fc-custom-python37-event/src">Python37 Event函数</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/python37/fc-custom-python37-http/src">Python37 HTTP函数</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/python37/fc-custom-python37-websocket/src">Python37 Websocket函数</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/cpp/fc-custom-cpp-event/src">C++ Event函数</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/cpp/fc-custom-cpp-http/src">C++ HTTP函数</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/java8/fc-custom-java8-http/src">Java8-SpringBoot</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/ruby/fc-custom-ruby-event/src">Ruby example</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/powershell/fc-custom-powershell-event/src">Powershell example</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/f#/fc-custom-fsharp-http/src">F# example</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/typescript/fc-custom-typescript-event/src">TypeScript example</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/lua/fc-custom-lua-event/src">Lua example</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/dart/fc-custom-dart-event/src">Dart example</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/rust/fc-custom-rust-event/src">Rust example</a>
</td>
<td align="center">
<a href="https://github.com/devsapp/start-fc/tree/master/custom-container-function/fc-custom-container-event-cpp/src">C++ Event函数</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-container-function/fc-custom-container-event-nodejs14/src">Node.js 14 Event函数</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-container-function/fc-custom-container-event-python3.9/src">Python3.9 Event函数</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-container-function/fc-custom-container-http-cpp/src">C++ HTTP函数</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-container-function/fc-custom-container-http-springboot/src">Springboot HTTP函数</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-container-function/fc-custom-container-http-aspdotnetcore/src">ASP.Net Core HTTP函数</a><br>
<a href="https://github.com/devsapp/start-fc/blob/master/custom-container-function/fc-custom-container-websocket-golang/src">Golang Websocket函数</a><br>
<a href="https://github.com/devsapp/start-fc/blob/master/custom-container-function/fc-custom-container-websocket-nodejs14/src">Node.js14 Websocket函数</a><br>
<a href="https://github.com/devsapp/start-fc/blob/master/custom-container-function/fc-custom-container-websocket-python3.9/src">Python3.9 Websocket函数</a>
</td>
</tr>
</table>


## Web Framework应用案例

将一个传统框架部署到阿里云Serverless平台的方法有很多，可以选择Custom、Custom Container以及原生编程语言的运行时。这其中Custom和原生语言运行时方案，除了启动命令/入口函数不同之外，区别并不是很大，可以根据自己需求进行实现，Custom Container方案相对来说更简单，但是镜像的冷启动速度相对Custom和原生语言运行时比较慢。

目前函数计算仓库收录以下常见框架的部署案例：

<table>
<tr>
<th>No.</th>
<th>:fire:Nodejs</th>
<th>Python</th>
<th>PHP</th>
<th>Go</th>
<th>Java</th>
<th>Others</th>
</tr>
<tr>
<td align="center">1</td>
<td align="center">:fire:<a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/custom-runtime/express/src">Express [custom]</a></td>
<td align="center">:fire::fire:<a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/python/flask/src">Flask [python3]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/thinkphp/src">Think PHP [custom]</a></td>
<td align="center">BeeGo</td>
<td align="center">Tomcat/Jetty</td>
<td align="center">Gatsby</td>
</tr>
<tr>
<td align="center">2</td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/custom-runtime/egg/src">Egg [custom]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/python/tornado/src">Tornado [custom]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/laravel/src">laravel [custom]</a></td>
<td align="center">Gin</td>
    <td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/java/springboot">SpringBoot [custom]</a></td><td>Hugo</td>
</tr>
<tr>
<td align="center">3</td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/custom-runtime/next/src">Nextjs [custom]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/python/bottle/src">Bottle [python3]</a></td>
    <td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/discuz/src">Discuz [custom]</a></td><td></td><td align="center">Quarkus</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">4</td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/custom-runtime/nuxt-ssr/src">Nuxtjs [custom]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/python/webpy/src">Web.py [python3]</a></td>
<td align="center"> :fire::fire::fire: <a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/wordpress/src" >WordPress [custom]</a></td><td></td><td></td>
<td align="center"></td>
</tr>
<tr>
<td align="center">5</td>
<td align="center"> :fire::fire::fire: <a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/hapi/src" >Hapi [custom]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/python/django/src" >Django [python3]</a></td>
<td align="center"> :fire::fire::fire: <a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/zblog/src" >Zblog [custom]</a></td><td></td><td></td>
<td align="center"></td>
</tr>
<tr>
<td align="center">6</td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/custom-runtime/koa/src">Koa [custom]</a></td>
    <td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/python/fastapi/src" >FastAPI [custom]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/ecshop/src" >Ecshop [custom]</a></td><td></td><td></td><td></td>
</tr>
<tr>
<td align="center">7</td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/nodejs-runtime/nest/src">Nest [nodejs12]</a></td>
<td align="center">Web2py</td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/metinfo/src" >Metinfo [custom]</a></td>
    <td></td><td></td><td></td>
</tr>
<tr>
<td align="center">8</td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/custom-runtime/midway-koa/src">Midway-koa [custom]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/python/pyramid/src" >Pyramid [python3]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/whatsns/src" >Whatsns [custom]</a></td><td></td><td></td><td></td>
</tr>
<tr>
<td align="center">9</td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/nodejs-runtime/thinkjs/src">Think.js [nodejs12]</a></td>
<td align="center"></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/typecho/src" >Typecho [custom]</a></td><td></td><td></td><td></td>
</tr>
    <tr>
<td align="center">9</td>
<td align="center"></td>
<td align="center"></td>
<td align="center"><a href="https://github.com/devsapp/start-fc-kodbox" >Kodbox [custom]</a></td><td></td><td></td><td></td>
</tr>
</table>

> 除了上面的案例之外，还提供了两个简单的实践应用：
> - [基于Express框架的todoList应用](https://github.com/devsapp/start-web-framework/blob/master/example/todolist-app/src)：`s init todolist-app`
> - [基于Django框架的博客应用](https://github.com/devsapp/start-web-framework/blob/master/example/django-blog/src)：`s init django-blog`    

> SSR 框架：
> - [nuxt-ssr](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/custom-runtime/nuxt-ssr/src): `s init start-nuxt-ssr`

> 为了对比Custom运行时和编程语言原生运行时的框架迁移区别，可以参考以下案例进行自行对比：
>
> | 框架名 | Custom运行时 | Node.js 12运行时 |
> | ----- | ----------- | ----------------|
> | Egg.js | [egg](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/custom-runtime/egg/src) | [egg-app](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/nodejs-runtime/egg/src) |
> | Express.js | [express](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/custom-runtime/express/src) | [express-app](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/nodejs-runtime/express/src) |
> | Koa.js | [koa](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/custom-runtime/koa/src) | [koa-app](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/nodejs-runtime/koa/src) |
> | Hapi.js | [hapi](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/custom-runtime/hapi/src) | [hapi-app](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/nodejs-runtime/hapi/src) |

## 静态网站应用案例

- 静态网站案例：
    - [hexo应用](https://github.com/devsapp/start-website/tree/master/hexo/src) `s init website-hexo`
    - [docusaurus应用](https://github.com/devsapp/start-website/tree/master/docusaurus/src) `s init website-docusaurus`
    - [vuepress应用](https://github.com/devsapp/start-website/tree/master/vuepress/src) `s init website-vuepress`

> 当然，上面所列举的静态网站案例都是build之后部署到对象存储等，您也可以直接部署到函数计算（尽管这并不是一个值得推荐的做法），您可以参考[start-static-site文档](https://github.com/devsapp/start-static-site) , 也可以尝试执行命令`s init start-static-site`进行初始化

## 场景合集

### AI场景

- [PyTorch案例](https://github.com/devsapp/start-ai/tree/master/start-pytorch/src) `s init start-pytorch`
- [Tensorflow案例](https://github.com/devsapp/start-ai/tree/master/start-tensorflow/src) `s init start-tensorflow`
- [OCR案例](https://github.com/devsapp/start-ai/tree/master/start-ocr/src) `s init start-ocr`
- [目标检测案例](https://github.com/devsapp/start-ai/tree/master/image-prediction-app/src) `s init image-prediction-app`

### 音视频处理案例

- [弹性高可用的高度自定义音视频处理](https://github.com/devsapp/start-ffmpeg/tree/master/ffmpeg-app/src): `s init ffmpeg-app`
- [对直播视频流截图的应用](https://github.com/devsapp/start-ffmpeg/tree/master/rtmp-snapshot/src): `s init rtmp-snapshot`
- [一个对浏览器全景录制](https://github.com/devsapp/start-ffmpeg/tree/master/headless-ffmpeg/src): `s init headless-ffmpeg`

### Serverless架构下数据库使用

- python案例
    - [mysql案例](https://github.com/devsapp/start-fc-db/tree/main/python/mysql/src): `s init start-fc-mysql-python`
    - [redis案例](https://github.com/devsapp/start-fc-db/tree/main/python/redis/src): `s init start-fc-redis-python`
    - [mongodb案例](https://github.com/devsapp/start-fc-db/tree/main/python/mongodb/src): `s init start-fc-mongodb-python`
    - [sql-server案例](https://github.com/devsapp/start-fc-db/tree/main/python/sql_server/src): `s init start-fc-sql-server-python`
    - [postgresql案例](https://github.com/devsapp/start-fc-db/tree/main/python/postgresql/src): `s init start-fc-postgresql-python`
    - [Lindorm案例](https://github.com/devsapp/start-fc-db/tree/main/python/lindorm/src): `s init start-fc-lindorm-python`

### 其他
- 基于 puppeteer 的截图 Web 应用: 
    - [基于Node.js的案例](https://github.com/devsapp/start-puppeteer/tree/master/puppeteer-nodejs/src): `s init puppeteer-nodejs`
    - [基于Container的案例](https://github.com/devsapp/start-puppeteer/tree/master/puppeteer-container/src): `s init puppeteer-container`
- [word转pdf的应用](https://github.com/devsapp/start-word2pdf): `s init start-word2pdf`
- [pdf转图片的应用](https://github.com/devsapp/start-pdf2img): `s init start-pdf2img`
- [电商后端管理系统](https://github.com/devsapp/start-fc-mall-admin): `s init start-fc-mall-admin`
- [现代应用解决方案](https://github.com/devsapp/modern-web-application): `s init modern-web-application`

#### 活动场景

> 这一部分记录的是一些活动的小案例，仅供学习使用

- [基于函数计算的红白机游戏](https://github.com/devsapp/fc-nes-game): `s init fc-nes-game`
- [基于函数计算的盲盒游戏](https://github.com/devsapp/blindbox-game): `s init blindbox-game`
- [创意活动Jamsatck站点](https://github.com/devsapp/start-jamstack-activities): `s init start-jamstack-activities`
- [Serverless架构的弹幕应用](https://github.com/devsapp/start-barrage): `s init start-barrage`
