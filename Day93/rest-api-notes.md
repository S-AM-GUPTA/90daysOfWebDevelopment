# REST API Notes - Day 93

## What is REST?
- Representational State Transfer
- Architectural style for designing networked applications
- Stateless: each request contains all needed information

## HTTP Methods
- GET: retrieve data
- POST: create new data
- PUT/PATCH: update existing data
- DELETE: remove data

## Status Codes
- 200 OK: success
- 201 Created: resource created
- 400 Bad Request: invalid input
- 401 Unauthorized: authentication required
- 404 Not Found: resource not found
- 500 Internal Server Error: server-side error

## Best Practices
- Use nouns for endpoints (not verbs)
- Version your API: /api/v1/
- Always return meaningful status codes
