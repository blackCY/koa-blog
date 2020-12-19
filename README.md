# koa2-blog

这是一个使用koa2/mongodb/layui实现的后台管理项目，是在学习NodeJS后写的，该项目使用了pug做后台模板引擎，使用cookie/session，在路由中使用中间件的方式实现对浏览器状态的记录，实现了一个可发表文章的后台管理项目

功能模块：
  1. 登录/注册；
  2. 个人文章的发表；
  3. 管理员对个人信息及其发表文章的管理

主要技术：
  1. 使用koa2/koa-router搭建项目；
  2. 使用layui、pug做页面及页面数据；
  3. 使用mongodb存储用户信息；
  4. 使用cookie/session做浏览器状态记录

#启动项目
```shell
cd tz44js-blog
npm i
mongod --dbpath database/db
node app
```
