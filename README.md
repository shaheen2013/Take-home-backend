# Backend Installation Guide

This is the backend for the project, built with Node.js, Express, and Prisma. Follow the steps below to set up and run the server locally.

## Prerequisites

Ensure you have the following installed on your system:

- **Node.js** (version 16.x or higher)
- **npm** or **yarn**
- **MySQL** (download from the official website: https://dev.mysql.com/downloads/)

## Installation Steps

1. **Clone the Repository**  
   git clone https://github.com/shaheen2013/Take-home-backend.git
   cd Take-home-backend

2. **Install Dependencies**  

```
npm install  
```


3. **Set Up MySQL Database**  
   - Download and install MySQL from the official website.  
   - Create a new database for the project.

4. **Set Up Environment Variables**  
   - edit the `.env` file in the root directory.  
   - Add the required environment variables, including the MySQL connection details (e.g., `DATABASE_URL`).

5. **Run Prisma Migrations**  
   To set up the database schema, run the following command:  
```
   npx prisma migrate dev
```


6. **Start the Development Server**  
```
npm run dev  
```

 The server will be running at:  
 http://localhost:3001
