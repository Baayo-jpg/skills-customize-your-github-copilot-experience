# 📘 Assignment: FastAPI REST API

## 🎯 Objective

Build a REST API with the FastAPI framework to practice defining endpoints, validating JSON payloads, and returning structured responses.

## 📝 Tasks

### 🛠️ Create API Endpoints

#### Description
Create a FastAPI application that exposes endpoints for managing simple items in an in-memory data store.

#### Requirements
Completed program should:

- define a `FastAPI()` application instance
- implement a `GET /items/{item_id}` endpoint to retrieve a single item by ID
- implement a `POST /items` endpoint to create a new item
- return JSON responses for both successful and missing-item requests
- use an in-memory store such as a Python dictionary for items

### 🛠️ Add Validation and Documentation

#### Description
Use Pydantic models to validate incoming request data and take advantage of FastAPI's automatic documentation features.

#### Requirements
Completed program should:

- define a Pydantic model for item data
- validate request payloads for `POST /items`
- return a validation error response when input is invalid
- confirm that interactive API docs are available at `/docs` or `/redoc`
