## 跳蚤市场

**🕊**

闲置交易市场网站，基于[`Python3.7`](https://www.python.org/)和[`Django2.0`](https://www.djangoproject.com/)

源repo：[laowuniubi/GraduateDesign](https://github.com/laowuniubi/GraduateDesign)

一个B站教程：[天天生鲜Django项目](https://www.bilibili.com/video/BV14J411r7hn)

Django框架的intro：[Django 开始](https://docs.djangoproject.com/zh-hans/3.2/intro/)

----------

**注意：** 本项目为Github用户[laowuniubi](https://github.com/laowuniubi/)原创，本repo仅作参考研究，未经原作者授权禁止抄袭为重要的学术作品或用于商业用途。

----------

## 环境搭建：
 
### 推荐使用[conda](https://anaconda.org/anaconda/conda)

`$conda create -n webstore python==3.7 Pillow==7.0.0 pytz==2018.7`

使用pip安装其余的依赖

`$pip install Django==2.0.7 django-tinymce==2.7.0`

如果太慢可以换源

### 数据库配置

数据库默认使用`Django`项目默认数据库后台`sqlite3`

## 运行项目

创建管理员账户

`$python manage.py createsuperuser`

必要时进行数据库迁移

`$ python manage.py makemigrations TestModel`
`$ python manage.py migrate TestModel`

### 开始运行

终端下执行:

`$python manage.py runserver`

默认普通用户页面: [前端主页](http://localhost:8000)

默认管理员登录页面: [管理页面](http://localhost/admin:8000) 
