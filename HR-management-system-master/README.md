# HR-management

It's HR Management System.

## Table of Contents

- [HR-management](#HR-management)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Installation](#installation)
    - [Local DB changes](#local-db-changes)

## Features

- User(admin) can register.
- We can add candidate profiles and update their status according to the HR process.
- We can download resumes and can delete candidate.
- Search candidate with concept of debouncing.
- Filter candidates based on the status and position.
- Login and Logout Functionality.

## Installation

Open your terminal and follow the commands:



To run project on local, open terminal and follow these steps:

```bash
cd frontend
npm start
cd server
nodemon or node index.js
```

### Local DB changes

- Create .env file on root of the server Folder.
- open .env file and add 
   MONGO_URI= mongodb://localhost:27017/hr_management
   SECRET_JWT= mongodb://localhost:27017/hr_management
