# CRUD FastAPI Postgres

Bookstore db CRUD API built with FastAPI and PostgreSQL.

## Project Structure

| File | Description |
|------|-------------|
| `main.py` | FastAPI app and routes (GET, POST, PUT, DELETE for books) |
| `db.py` | Database connection, engine, and session setup |
| `models.py` | SQLAlchemy Book model (table definition) |
| `schemas.py` | Pydantic schemas for request/response validation |
| `services.py` | CRUD business logic |
| `requirements.txt` | Python dependencies |

