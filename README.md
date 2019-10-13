# DataBaseDesign
基于Web的考生信息查询系统
1. #### 文件结构：

```
.
├── README.md
├── __pycache__
│   └── app.cpython-37.pyc
├── app.py
├── app.pyc
├── data.sqlite
├── migrations
│   ├── README
│   ├── __pycache__
│   ├── alembic.ini
│   ├── env.py
│   ├── env.pyc
│   ├── script.py.mako
│   └── versions
├── requirements.txt
├── static
│   ├── styles.css
│   └── view.jpg
├── templates
│   ├── 404.html
│   ├── 500.html
│   ├── add_user.html
│   ├── base.html
│   ├── edit_user.html
│   ├── index.html
│   └── login.html
└── venv
    ├── bin
    ├── include
    └── lib

10 directories, 20 files
```

2. #### 运行方法:

   ##### 准备：

   1. 安装virtualenv:
      `pip install virtualenv`
   2. 创建虚拟环境:
      `virtualenv venv`
   3. 进入虚拟环境:
      `source venv/bin/activate`
   4. 安装依赖的包:
      `pip install -r requirements.txt`
   5. 退出虚拟环境:
      `deactivate`

   ##### 运行：

   1. 更新数据库：`python app.py db upgrade`
   2. 生成管理员用户：`python app.py init`
   3. 运行：`python app.py runserver`

   ##### 初始管理员账户：

   ```
   学号：000000
   密码：666666
   ```

   

3. #### 效果预览![view](/Users/zhaowanru/class/DBMS/flask-demo/static/view.jpg)