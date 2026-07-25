# Express.js Notes - Day 92

## Setup
- Install with: npm install express
- Import: const express = require('express')
- Create app: const app = express()

## Routing
- GET: app.get('/path', handler)
- POST: app.post('/path', handler)
- PUT: app.put('/path', handler)
- DELETE: app.delete('/path', handler)

## Middleware
- Functions that execute during request/response cycle
- Use app.use() to apply middleware globally
- express.json() to parse JSON request bodies
