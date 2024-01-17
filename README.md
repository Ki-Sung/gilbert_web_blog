# gilbert_web_blog
- 웹 배포용 블로그
- 웹 배포용 호스팅 제공자: Render
- 사용 DB: PostgreSQL
- URL: https://gilbert-blog.onrender.com
### Get Start
Set up Python virtual environment
```
python -m venv <virtual env name>
```

Install pip packages
```
pip install -r requirements.txt
```

Start Flask Application
```
gunicorn main:app
```
