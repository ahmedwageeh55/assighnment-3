# Assignment 3

## Part 1: Node Internals

This part covers the following Node.js concepts:

1. Node.js Event Loop
2. Libuv and its role in Node.js
3. How Node.js handles asynchronous operations
4. Call Stack, Event Queue, and Event Loop
5. Node.js Thread Pool and how to set its size
6. Blocking and Non-Blocking code execution

## Part 2: Simple CRUD Operations Using Express.js

The APIs use the `fs` module to read and write users from a JSON file.

### APIs

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/user` | Add a new user |
| PATCH | `/user/:id` | Update user data |
| DELETE | `/user/:id` | Delete a user |
| GET | `/user/getByName` | Get user by name |
| GET | `/user` | Get all users |
| GET | `/user/filter` | Filter users by minimum age |
| GET | `/user/:id` | Get user by ID |

## Bonus

Solved the **Longest Common Prefix** problem on LeetCode.

The solution is available in:

`bonus.js`
