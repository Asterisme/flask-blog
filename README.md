# Flask-blog
# 1.1 如何使用
基于python3.6，Linux环境下
## 1.2 Backend

Opne a new terminal:

```bash
$ cd back-end
$ python -m venv venv
$ source venv/bin/activate
(venv)$ pip install -r requirements.txt

# Flask-Migrate create database
(venv)$ flask db upgrade

# create back-end/.env file, like this
FLASK_APP=madblog.py
FLASK_DEBUG=1

(venv)$ flask run
```

浏览器访问: `http://localhost:5000/api/ping`

## 2.3 Frontend

Opne a new terminal:

```bash
$ cd front-end
$ npm install
$ npm run dev
```

浏览器访问: `http://localhost:8080`
