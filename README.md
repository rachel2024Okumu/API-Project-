# User management API

Setup

Clone the repository
Run `npm install`
Start the server: `node index.js`
API will be available at `https://localhost:3000`

API Endpoints

Get User by ID

URL Params: `/api/users/:id`
Method:`Get`
URL Params:`[id=interger]`
Success Response:
code: 200
content: `{id: 1, name: "John", email: "john@example.com}`
Error Response:
code: 404
Content: `{message: "user not found"}`

Retrieve 

Error Handling
All error responses will be in JSON format and will include a error message describing the error

Example Error Responses
404 Not Found: `{message user not found}` 
404 Bad Request: `{message : name and email are required}`