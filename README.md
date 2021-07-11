# Flask-Blog-App
This is a blogging web-app developed by using Flask (Python web framework). In this app user can create account, then login, and then can post some blogs with a title. User can also edit and delete their posts. 

## Technologies used:
* Pythoon-Flask
* SQL, SQLite(database)
* HTML5, CSS3, Bootstrap4


## File Structure (Tree)
└── Flask-Project
    ├── config.json
    ├── flask_app
    │   ├── config.py
    │   ├── errors
    │   │   ├── handlers.py
    │   │   ├── __init__.py
    │   │   └── __pycache__
    │   │       ├── handlers.cpython-38.pyc
    │   │       └── __init__.cpython-38.pyc
    │   ├── __init__.py
    │   ├── main
    │   │   ├── __init__.py
    │   │   ├── __pycache__
    │   │   │   ├── __init__.cpython-38.pyc
    │   │   │   └── routes.cpython-38.pyc
    │   │   └── routes.py
    │   ├── models.py
    │   ├── posts
    │   │   ├── forms.py
    │   │   ├── __init__.py
    │   │   ├── __pycache__
    │   │   │   ├── forms.cpython-38.pyc
    │   │   │   ├── __init__.cpython-38.pyc
    │   │   │   └── routes.cpython-38.pyc
    │   │   └── routes.py
    │   ├── __pycache__
    │   │   ├── config.cpython-38.pyc
    │   │   ├── __init__.cpython-38.pyc
    │   │   └── models.cpython-38.pyc
    │   ├── site.db
    │   ├── static
    │   │   ├── main.css
    │   │   └── profile_pics
    │   │       ├── 074eef5cc1ef55f6tanmay.jpg
    │   │       ├── 1bbc55093eafb0f2IMG_20200918_171644_658_COPY_edited.jpg
    │   │       ├── 8c38231dddc08b8edefault.jpg
    │   │       ├── 914722b531a6e699IMG_20200918_171644_658_COPY_edited.jpg
    │   │       ├── c02f79bd50fa29a3IMG_20200918_171644_658_COPY_edited.jpg
    │   │       ├── ccf6dea44d9a9fbddp.jpg
    │   │       ├── d1b0c65a4a4ad51dgoogle.jpg
    │   │       ├── d864b3f32e7890f8IMG_20200918_171644_658_COPY_edited.jpg
    │   │       ├── default.jpg
    │   │       └── fba374da26f07465dp.jpg
    │   ├── templates
    │   │   ├── about.html
    │   │   ├── account.html
    │   │   ├── create_post.html
    │   │   ├── errors
    │   │   │   ├── 403.html
    │   │   │   ├── 404.html
    │   │   │   └── 500.html
    │   │   ├── home.html
    │   │   ├── layout.html
    │   │   ├── login.html
    │   │   ├── post.html
    │   │   ├── register.html
    │   │   ├── reset_request.html
    │   │   ├── reset_token.html
    │   │   └── user_posts.html
    │   └── users
    │       ├── forms.py
    │       ├── __init__.py
    │       ├── __pycache__
    │       │   ├── forms.cpython-38.pyc
    │       │   ├── __init__.cpython-38.pyc
    │       │   ├── routes.cpython-38.pyc
    │       │   └── utils.cpython-38.pyc
    │       ├── routes.py
    │       └── utils.py
    ├── Procfile
    ├── requirements.txt
    └── run.py
