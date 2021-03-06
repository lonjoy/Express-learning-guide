## 安装脚手架工具

对于初学者来说，建议安装脚手架工具`express-generator`。

```
npm install -g express-generator
```

运行完上面命令，就会在本地安装\`express\`命令，可以用它来初始化项目骨架。

## 创建项目

比如，创建项目**demo**。参数说明

* `demo`：项目所在目录。
* `-e`：初始化的项目，用ejs做为模板引擎。


```
➜  /tmp express -e demo

   create : demo
   create : demo/package.json
   create : demo/app.js
   create : demo/public
   create : demo/public/javascripts
   create : demo/routes
   create : demo/routes/index.js
   create : demo/routes/users.js
   create : demo/public/stylesheets
   create : demo/public/stylesheets/style.css
   create : demo/views
   create : demo/views/index.ejs
   create : demo/views/error.ejs
   create : demo/public/images
   create : demo/bin
   create : demo/bin/www

   install dependencies:
     $ cd demo && npm install

   run the app:
     $ DEBUG=demo:* npm start
```

## 安装项目依赖

安装指示安装依赖

```
➜  /tmp cd demo 
➜  demo npm install
```

## 启动项目

通过下面命令启动项目。默认监听端口为3000.

```
➜  demo npm start

> demo@0.0.0 start /private/tmp/demo
> node ./bin/www
```

试下在浏览器里访问 http://127.0.0.1:3000 恭喜你，迈出成功第一步。

