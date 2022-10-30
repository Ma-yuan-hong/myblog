# Zhangsan Blog
## 个人博客系统
Zhangsan Blog是由SpringBoot1.5 + MyBatis + Thymeleaf等技术实现的个人网站。
### 技术栈
#### 后端
* 核心框架：SpringBoot
* 持久层框架：MyBatis
* 模板框架：Thymeleaf
* 分页插件：PageHelper
* 缓存框架：Ehcache
* Markdown：Commonmark

#### 前端
* JS框架：Jquery
* CSS框架：Bootstrap
* 富文本编辑器：editor.md
* 文件上传：dropzone
* 弹框插件：sweetalert


### 预览效果
#### 前端效果
![首页](src/main/resources/display/fronted/首页.png)

![归档](src/main/resources/display/fronted/归档.png)

![分类](src/main/resources/display/fronted/分类.png)

![标签](src/main/resources/display/fronted/标签.png)

![关于](src/main/resources/display/fronted/关于.png)



#### 后端效果
![登录](src/main/resources/display/fronted/登录.png)

![仪表盘](src/main/resources/display/backend/仪表盘.png)

![发布文章](src/main/resources/display/backend/发布文章.png)

![文章管理](src/main/resources/display/backend/文章管理.png)

![评论管理](src/main/resources/display/backend/评论管理.png)

![分类标签](src/main/resources/display/backend/分类标签.png)


### 安装
执行sql文件，然后修改application-dev.yml文件中连接数据库的用户名、密码。运行项目即可。

前端访问地址：http://localhost:8888

后台访问地址：http://localhost:8888/admin 用户名：admin 密码：123456

