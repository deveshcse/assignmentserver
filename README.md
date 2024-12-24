# Assignment Server

## 🌐 Project Overview
This server-side application is a Node.js backend developed to handle API requests, manage database interactions, and provide data for the client application. It utilizes Prisma ORM for efficient database management and integrates with Supabase for real-time data operations.

## 🍕 Features
- **Supabase Integration**: Connects with Supabase for database operations.
- **CRUD Operations**: API routes for creating, reading, updating, and deleting the student records.
- **Prisma ORM**: Simplified and efficient database interactions.
- **Environment Variables**: Secure handling of sensitive data like Supabase API keys.

## ⚙ Technology Stack
- **Backend Framework**: Node.js with Express.
- **Database**: Supabase for cloud-hosted PostgreSQL.
- **ORM**: Prisma for schema management and efficient database queries.

## 🌐 Server Deployment
The server-side application is live and can be accessed at:

[Live API](https://assignmentserver-r6wt.onrender.com)

## 🌐 Client Deployment
The client-side application is live and can be accessed at:

[Live Demo](https://assignmentdeveshcse.netlify.app/)



## 🚀 Getting Started

### Installation and Setup
1. Clone the repository:

```bash
git clone https://github.com/deveshcse/assignmentserver.git
cd assignment-server
```

2. Install dependencies:

```bash
npm install
```

3. Configure environment variables:

Create a `.env` file in the root directory and add the following:

```
PORT=4000
DATABASE_URL=your_supabase_database_url
SUPABASE_API_KEY=your_supabase_api_key
```

4. Run database migrations:

```bash
npx prisma migrate dev
```

5. Start the server:

```bash
npm start
```

The server will run at:

```
http://localhost:4000
```

## 📚 API Endpoints
- **GET /allstudents**: Fetch all students record from the database.
- **POST /addnewstudent**: Create a new student record.
- **PUT /updatestudent/:id**: Update an existing user record.
- **DELETE /deletestudent/:id**: Delete an student record by ID.

## 📝 License
This project is licensed under the MIT License.

---
Feel free to explore the server and its functionality!
