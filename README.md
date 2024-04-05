# python
## Django学习
### 安装
pycharm 终端
pip install Django
### 运行
创建一个项目  

```
django-admin startproject mysite
```  

运行Django项目  

```
python manage.py runserver 0.0.0.0:8000
```  

在浏览器输入网址：```127.0.0.1:8000```  

### MTV模式
module 数据库管理员  

template 模版引擎  

views 接口引擎  

浏览器输入地址——>urls.py——>views——>model——>数据库——>views——>templates——>response(字节bytes)  

### 请求与响应
request ——> urls(path)

response ——> views (HttpResponse,TemplateResponse)

### 路由分层
子路由```path('test/',test)```默认为```127.0.0.1:8000/test/```
