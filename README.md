# promanage-backend
Fullstack Project Management App (React + Node + MySQL)

🔐 Milestone 2: User Auth & Roles
 Create User model with hashed passwords (bcrypt)

 JWT Access + Refresh Token implementation

 Login, Register API

 Role-based middleware (Admin, Team Lead, Member)

 Logout + Token Blacklist

👥 Milestone 3: Teams & Members
 Create Team model

 Add user-to-team association (Many-to-Many)

 API to add/remove users from teams

 Get team details with members

📁 Milestone 4: Projects & Tasks
 Create Project model (one-to-many with Team)

 Create Task model (one-to-many with Project)

 Task APIs: create, update, assign, delete

 Add filtering, search, and pagination

📎 Milestone 5: File Uploads
 Configure multer for file uploads

 Upload attachments on task

 Store file metadata in DB

 Serve/download files securely

💬 Milestone 6: Comments System
 Add Comment model linked to Task & User

 Create/list/delete comments API

🔄 Milestone 7: Real-Time Updates
 Setup socket.io on backend

 Emit task updates (status change, new comment)

🛡️ Milestone 8: Security & Performance
 Add helmet, cors, input sanitization

 Global error handler

 Rate limit login/public APIs

 Winston logger setup

🧪 Milestone 9: Testing
 Setup Jest + Supertest

 Write tests for auth, tasks, comments

🚀 Milestone 10: Deployment & Docs
 Add .env examples

 PM2 config for production

 Write API documentation in Postman or Swagger
