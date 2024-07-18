## Deployed API Link
```bash
http://ec2-3-108-252-225.ap-south-1.compute.amazonaws.com:3000
```
# Note  Backend

This is the backend server for the Note Keeper application. It provides APIs for user authentication and note management.

## Features

- User Registration
- User Login
- Create, Read, Update, Delete Notes
- Notes can have multiple tags, colors, and reminders
- Notes can be archived and trashed

## Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT (JSON Web Tokens) for authentication

## Prerequisites

- Node.js and npm installed
- MongoDB installed and running

## Getting Started

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/note-keeper-backend.git
   npm i

## login 
1.json sample 
```bash
{
  "email": "a@gmail.com",
  "password": "a1234"
}
```

## post notes
```bash
{
  "title": "Gym",
  "content": "Gym >>GYM",
  "tags": ["hit", "gym"],
  "color": "#FFFFFF",
  "reminder": "2024-07-20T10:00:00Z"
}

