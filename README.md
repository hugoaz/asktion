## Node-blog

使用 Express + MongoDB 搭建多人博客
主要为了与朋友做交流用，互相提问，互相解答
 
### [demo](112.90.182.214:3000)
## 开发环境

- Node.js: `6.9.1`
- MongoDB: `3.2.10`
- Express: `4.14.0`

## 目录
.
|-- README.md  			说明文档

|-- config		配置目录

|   `-- default.js		配置文档

|-- index.js			启动程序

|-- lib			库目录

|   `-- mongo.js		数据库操作目录

|-- logs		日志目录

|-- middlewares		路由中间件目录

|   `-- check.js		查看是否登录的中间间

|-- models		模型目录

|   |-- comments.js		留言模型

|   |-- posts.js		发布文章模型

|   `-- users.js		用户模型

|-- package.json		node配置文件

|-- public		公共文件

|   |-- css		    css目录

|   |   `-- style.css		公共css

|   |-- img		    用户头像目录

|   `-- wechat.jpg		微信联系方式

|-- routes		路由目录

|   |-- index.js		路由汇总配置

|   |-- posts.js		提交

|   |-- signin.js		登录

|   |-- signout.js		登出

|   `-- signup.js		注册

|-- test		单元测试

|   |-- avatar.png		

|   `-- signup.js		注册部分

|-- test.txt

`-- views		模板目录

|-- 404.ejs			404页面

|-- components	     模块

|   |-- comments.ejs	留言部分

|   |-- nav-setting.ejs	设置-导航部分

|   |-- nav.ejs		导航

|   |-- notification.ejs	提醒

|   `-- post-content.ejs	提交

|-- create.ejs		新建文章

|-- edit.ejs		编辑文章

|-- error.ejs		错误

|-- footer.ejs		底部

|-- header.ejs		头部

|-- post.ejs		提交留言

|-- posts.ejs		提交文章

|-- signin.ejs		登录

`-- signup.ejs		登出



