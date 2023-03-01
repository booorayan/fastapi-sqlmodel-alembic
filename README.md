# FastAPI + SQLModel + Alembic

The objective is to configure SQLAlchemy, SQLModel and Alembic to work with FastAPI asynchronously.

SQLModel is a library for interacting with SQL dbs from Python code, with Python objects.

Alembic is employed to handle database migrations

### Test
We can use curl to test the api like so:

`curl -d 
'{"name":"Huyu Kijana", "artist":"Wakadinali", "year":"2022"}'
-H "Content-Type: application/json" -X POST http://localhost:8004/songs`
