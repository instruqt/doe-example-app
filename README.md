# DevOps Engineer Example Application

This is an example application that can be used throughout the DevOps Engineer curriculum.

## Installation

Create a virtual env:
```
python -m venv env
source env/bin/activate
```

Install dependencies:
```
pip install --upgrade pip
pip install -r requirements.txt
```

Generate database:
```
python init_db.py
```

Run application:
```
flask run
```
