## 使用spring boot作为后台创建的博客小项目
### 项目说明
本项目旨在练习spring boot各知识点的应用，以java后端为主，某些地方可能会显得是为了应用而应用。<br/>
前端技术在于简单联系和熟悉，参考价值可能不是太大。<br/>
同时，本项目希望努力做成一个方便本地使用的文件管理系统，包含单不限于博客文章、pdf书籍阅读、资料管理等功能</br>

### 基础环境和相关技术说明
>spring boot 版本1.5.4  后台主框架<br/>
>java 版本1.8  后台编程语言<br/>
>maven 版本3.2.5  项目构建和依赖管理<br/>
>使用spring boot结合thymeleaf模板    页面渲染<br/>
>mysql5.6  数据持久化<br/>
>jpa  持久层框架操作mysql<br/>
>bootstrap4 页面美化<br/>
>jquery3.2.1 操作html页面<br/>
>markdown 页面渲染<br/>
>html 页面渲染<br/>
>css 页面样式<br/>
>git 提交到github<br/>

### 基础效果截图如下：
![页面布局截图](/images/index.png)

### 历程
**2017-9-26:** 基础页面布局，初次提交到github</br>
**2017-9-28:** 后台基础代码编写和数据库设计</br>
**2017-9-29:** 前端页面增加对markdown语法的支持</br>
**2017-11-27:** 增加login页面，使用ajax请求，同时基础页面布局增加bootstrap支持</br>
**2017-11-28:** 优化登录功能，实现后台逻辑验证及验证后的前台提示</br>
![login](../../images/login.png)

### 预计功能说明
1. 实现类似博客的文章访问功能，如文章标题、内容
1. 实现文章统计功能，如字数、时间、分类
1. 实现pdf书籍阅读功能
1. 实现资料上传和下载、资料列表功能
1. 实现基础的登录注册功能
1. 根据不同用户展现不同页面，用户权限
1. 实现推送功能
1. 实现评论邮件提醒功能