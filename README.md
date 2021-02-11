# Fast API - Hello-World
#### Virtual Environment

Create Environment

```bash
python -m venv PATH\venv --system-site-packages
```

Run Environment

```bash
.\venv\Scripts\activate.bat
```

Install modules

```bash
pip install -r requirements.txt
```

#### Run APP

```bash
hypercorn main:app --reload
```

View Swagger

| Documentation Type | URL                         |
| ------------------ | --------------------------- |
| Swagger            | http://127.0.0.1:8000/docs  |
| Redoc              | http://127.0.0.1:8000/redoc |
