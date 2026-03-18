# 📘 Assignment: Building REST APIs with FastAPI framework

## 🎯 Objective

Learn to design and build a RESTful API with FastAPI, including endpoints, request validation, and response handling. Students will practice building real API routes and using JSON input/output.

## 📝 Tasks

### 🛠️ Create the basic FastAPI app

#### Description
Initialize a FastAPI app and add a root endpoint that returns a welcome message and API status.

#### Requirements
Completed program should:

- Include `from fastapi import FastAPI`
- Instantiate an app object: `app = FastAPI()`
- Create `GET /` endpoint returning JSON: `{"message": "Welcome to FastAPI API"}`
- Run with `uvicorn` if local testing is needed

### 🛠️ Implement CRUD endpoints for a resource

#### Description
Create endpoints for a simple resource like `books` that support create, read, update, and delete actions using in-memory storage.

#### Requirements
Completed program should:

- Add in-memory list `books = []`
- Create `GET /books` returns all books
- Create `GET /books/{book_id}` returns one book or 404 error
- Create `POST /books` accepts book details and returns created resource
- Create `PUT /books/{book_id}` updates book data
- Create `DELETE /books/{book_id}` removes book and returns success status

### 🛠️ Add data validation and schema models

#### Description
Use Pydantic models to validate incoming request bodies and define response models.

#### Requirements
Completed program should:

- Define `BookCreate` / `Book` Pydantic models with `title`, `author`, `year`
- Use model types in route signatures for request body validation
- Return response models in query endpoints
- Handle invalid data with clear error responses

## 💡 Optional extensions

- Add persistence by reading/writing `books` to a JSON file
- Add query parameters for filtering (e.g., author, year)
- Add authentication with API keys
