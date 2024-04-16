# FastAPI Task Manager application
Task Manager FastAPI is a simple task management API built using FastAPI + PostgreSQL. It provides basic CRUD operations for tasks and includes real-time updates for task status changes via WebSocket.

## Features:
* User registration and authentication (OAuth2 + JWT)
* Access and refresh token usage
* Real-time updates for task status changes using WebSocket
* Custom logger
* Asynchronous routes
* Asynchronous database access (asyncpg)
* Alembic database migrations
* Easy to installation (poetry)

## Getting started
### Prerequisites
Before running the application, make sure you have the following prerequisites installed:

* Python 3.11
* PostgreSQL

### Installation
1. Clone the repository

   ```bash
   cd task_manager_fastapi
   ```

2. Install [Poetry](https://python-poetry.org/docs/#installation)
3. Create a virtual environment

   ```bash
   poetry install
   ```

## Usage
### Running the Application

To run the FastAPI application locally, use the following command:

```bash
poetry run python main.py
```
