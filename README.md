# django Line Bot

```python
1.python -m venv venv(finish)

2.venv\Script\activate(非必要)

3.pip install -r requirements.txt(finish)

4.python manage.py runserver

5.cd "C:\Redis-7.2.4-Windows-x64-msys2"

6. ./redis-server

7.(建新終端機)celery -A mylinebot worker --loglevel=info

8.(建新終端機)celery -A mylinebot beat --loglevel=info

./ngrok http 8000

python excel.py
```
