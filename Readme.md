# 2018-08-17

* 开始正式学习 `webpack`
    * `Node` 版本需求 : `Node 8.2/npm 5.2.0 +`
    * 当前 `webpack` 版本 : `v4.16.5`
    * [官方参考文档](https://webpack.js.org/guides/getting-started/)
    * [其他参考文档](http://ife.baidu.com/note/detail/id/2183)

* 今日学习进度和要点

    1. 传统方式 : `HTML`中使用`<script>`直接引入`js`文件和库
        * 这种模式通常是基于`freemarker/velocity`等模板技术的服务端`Web`页面开发的常用手段
    2. 无配置`webpack`缺省方式 : `npx webpack`
        * 分开源`js`和发布`js`
            * 源`js` : `src/index.js`
            * 目标`js` : `dist/main.js`
        * `HTML`中不再使用`<script>`引入库
        * `js`文件中使用三方`js`库使用`import`
    3. 使用一个和缺省配置一致的配置文件
        * 指定配置文件的构建 `npx webpack --config webpack.config.js`