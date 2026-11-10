# Python API Course

A beginner-friendly Python API course focused on building, testing, and deploying REST APIs with Python.

This repository is a starting point for learning the basics of API development in Python, including working with HTTP requests, routes, JSON, and backend logic.

## Course Goals

By the end of this course, you will be able to:

- Understand how APIs work and how clients communicate with servers
- Build simple REST APIs using Python
- Work with JSON data and request/response handling
- Create routes and endpoints
- Validate input and handle errors
- Connect an API to data storage or a database
- Test API endpoints and debug issues
- Deploy a Python API locally or in a cloud environment

## Prerequisites

Before starting, make sure you have:

- Python 3.10 or newer installed
- A code editor such as VS Code
- Basic Python syntax knowledge
- Familiarity with command line usage

## Environment Setup

Create a virtual environment in the project folder:

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

Upgrade pip:

```bash
python -m pip install --upgrade pip
```

Install common dependencies for API work:

```bash
pip install fastapi uvicorn requests
```

You can also use Flask if your course prefers it.

## Project Structure

```text
initial/
├── .venv/                # Virtual environment
├── .gitignore            # Git ignore settings
├── README.md             # Course overview and setup guide
├── test.py               # Simple Python example script
└── ...                   # API project files as the course progresses
```

## Running the Example Script

The repository currently includes a simple script:

```bash
python test.py
```

This script asks for your name and prints a greeting.

## Suggested Learning Path

1. Python basics
2. HTTP and web concepts
3. REST API principles
4. Request handling and JSON
5. Building endpoints
6. Validation and error handling
7. Databases and persistence
8. Testing APIs
9. Deployment and security

## Common API Tools

These are commonly used in Python API development:

- FastAPI
- Flask
- Django REST Framework
- Requests
- Postman or Insomnia
- Swagger / OpenAPI docs

## Beginner API Example

A basic API endpoint may look like this:

```python
from fastapi import FastAPI

app = FastAPI()

@app.get("/")
def read_root():
    return {"message": "Hello from the API!"}
```

Run it using:

```bash
uvicorn main:app --reload
```

## Notes

This project can be used as a learning workspace as you progress through the course. Add new files and modules as you build more advanced API features.

## Helpful Resources

- Python official documentation
- FastAPI documentation
- HTTP status code reference
- JSON basics
- REST API tutorials

## Next Steps

Start by learning the basics of Python functions, modules, and working with JSON, then move into building simple API endpoints and expanding the project step by step.
