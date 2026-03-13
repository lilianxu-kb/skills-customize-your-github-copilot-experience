# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a REST API using the FastAPI framework in Python. Students will practice creating endpoints, validating request data, and returning structured JSON responses.

## 📝 Tasks

### 🛠️ Create a Basic FastAPI Application

#### Description
Set up a FastAPI project and implement core endpoints for a simple resource, such as tasks or books.

#### Requirements
Completed program should:

- Create a FastAPI app with at least one root endpoint (for example, `GET /`)
- Add at least two resource endpoints (for example, `GET /items` and `POST /items`)
- Return JSON responses with clear keys and values
- Run successfully with Uvicorn

### 🛠️ Add Validation and Error Handling

#### Description
Improve the API by adding request validation with Pydantic models and handling common error cases.

#### Requirements
Completed program should:

- Define at least one Pydantic model for request body validation
- Reject invalid input with appropriate HTTP status codes
- Handle missing resources with a clear error response (for example, `404 Not Found`)
- Include short endpoint descriptions using FastAPI route metadata
