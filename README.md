REST API Fundamentals - Backend Project 1
 About This Project

This is my first backend development project as part of DecodeLabs Industrial Training (Batch 2026). I built a REST API using Node.js and Express.js that serves JSON data. I tested all API endpoints using  Thunder Client in VS Code.

What This API Does

- Creates a local server on port 3000
- Handles GET, POST, PUT, DELETE requests
- Stores user data in memory
- Returns structured JSON responses
- Uses proper HTTP status codes

API Endpoints

| Method | URL | What it does |
|--------|-----|---------------|
| GET | http://localhost:3000/users | Get all users |
| GET | http://localhost:3000/users/1 | Get user with ID 1 |
| POST | http://localhost:3000/users | Create new user |
| PUT | http://localhost:3000/users/1 | Update user with ID 1 |
| DELETE | http://localhost:3000/users/1 | Delete user with ID 1 |

How to Run This Project

1. Install Node.js on your computer
2. Clone this repository
3. Open terminal in project folder
4. Run `npm install express`
5. Run `node server.js`
6. Open Thunder Client in VS Code
7. Test the API endpoints

 Technologies Used

- Node.js
- Express.js
- Thunder Client (for testing)
- JSON

 What I Learned

- REST APIs are stateless (server doesn't remember you)
- GET is for reading, POST is for creating
- Always use `express.json()` middleware to read JSON data
- Status codes matter (200 = success, 201 = created, 404 = not found)
- Thunder Client makes API testing easy
 Project Status

✅ Completed

Connect

DecodeLabs  
Greater Lucknow, India  
www.decodelabs.tech
