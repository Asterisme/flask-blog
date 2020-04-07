# 2. flask-blog

## 2.1 Backend

```bash
$ cd back-end
$ python -m venv venv
$ venv/Scripts/activate.bat
(venv)$ pip install -r requirements.txt

# Flask-Migrate create database
(venv)$ flask db upgrade

# create back-end/.env file, like this
FLASK_APP=madblog.py
FLASK_DEBUG=1

(venv)$ flask run
```

浏览器访问: `http://localhost:5000/api/ping`

## 2.2 Frontend

Opne a new terminal:

```bash
$ cd front-end
$ npm install
$ npm run dev
```

浏览器访问: `http://localhost:8080`