1. 创建并激活虚拟环境 webenv
2. 虚拟环境中安装 django

```
pip install django
```

3. 创建 Django 项目：

```
cd road2_my_website/backend
django-admin startproject backend .
```

第二行命令中的 backend 表示 django 项目名称。
路径：road2_my_website/backend/backend/
第一个 backend 是文件夹名，第二个是项目名称。

4. 测试项目，运行开发服务器：

```
python manage.py runserver
```
