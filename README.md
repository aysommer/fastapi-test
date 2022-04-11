### venv Installing
```python
python3 -m venv env
```

### venv Activation
```python
.\venv\Scripts\activate
source venv/bin/activate # unix
```

### Server Activation
```python
uvicorn main:app --reload
```

### requirements.txt Generation
```python
pip freeze > requirements.txt
```