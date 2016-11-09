# LeanEngine 静态站点示例
这个项目提供了一个全屏滑动的产品介绍页（`/`）和一个移动应用下载页面（`/app.html`）作为静态站点的示例，你可以轻松地修改它们，为你的产品或应用创建一个网站。

## 本地运行

首先确认本机已经安装 [Node.js](http://nodejs.org/) 运行环境和 [LeanCloud 命令行工具](https://www.leancloud.cn/docs/leanengine_cli.html)，然后执行下列指令：

```
$ git clone git@github.com:leancloud/static-getting-started.git
$ cd static-getting-started
```

安装依赖：

```
npm install
```

关联应用：

```
lean app add origin <appId>
```

这里的 appId 填上你在 LeanCloud 上创建的某一应用的 appId 即可。origin 则有点像 Git 里的 remote 名称。

启动项目：

```
lean up
```

应用即可启动运行：[localhost:3000](http://localhost:3000)

## 部署到 LeanEngine

部署到预备环境（若无预备环境则直接部署到生产环境）：
```
lean deploy
```

将预备环境的代码发布到生产环境：
```
lean publish
```

## 相关文档

* [LeanEngine 指南](https://leancloud.cn/docs/leanengine_guide-node.html)
* [命令行工具详解](https://leancloud.cn/docs/cloud_code_commandline.html)
* [LeanEngine FAQ](https://leancloud.cn/docs/cloud_code_faq.html)

## License
Apache 2.0, Based on [awesome-app-landing-page](https://github.com/joshbuchea/awesome-app-landing-page), [bootstrap](https://github.com/twbs/bootstrap), [fullPage.js](https://github.com/alvarotrigo/fullPage.js) and [jquery](https://github.com/jquery/jquery).
