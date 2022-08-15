# klara-app
AI fullstack app


Create virtual environment:
  ```
  python3 -m venv myvenv
  source ./myvenv/bin/activate
  pip3 install -r requirements.txt
  ```

Run Python API:
```
  uvicorn klara_api:app --reload

```

Create .env file:
```
  OPENAI_API_KEY = "<openai_api_key>"

```

Saving changes
```
  pip3 freeze > requirements.txt
  
```