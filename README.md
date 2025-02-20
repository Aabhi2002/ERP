COLLEGE ERP
College ERP using MERN Stack

Setup
Create a .env file in the server folder.
Copy the content of .env.example to the newly created .env file.
Change the MONGODB_URI to your MongoDB Atlas URI.
Open a terminal in the client folder and run:
sh
Copy
Edit
npm run start
Open another terminal in the server folder and run:
sh
Copy
Edit
npm run start
Go to localhost:3000/login/adminlogin.
After successfully running the server, a dummy admin account should be created.
🔑 Login Credentials (Important!)
Admin Login:
👤 Username: ADM202501001
🔑 Password: 123

Faculty Login:
👤 Username: FAC202501001
🔑 Password: 123

Student Login:
👤 Username: STU202501002
🔑 Password: 123

Tech Stack
Frontend: React.js, Tailwind CSS, Material UI Icons
Backend: Express.js, MongoDB, JWT Authentication
State Management: Redux
Real-time Communication: Socket.io (for video calling)
Features
✅ Admin Features:

Update profile details and password
Add, delete, or retrieve students, faculty, and other admins
Add new departments and subjects
Create new notices
✅ Faculty Features:

Update profile details and password
Create new tests
Mark student attendance
Upload test marks
✅ Student Features:

Update profile details and password
Check attendance, marks, and subject list
✅ Real-time Video Calling Between Students & Teachers (New!)

Technology Used: Socket.io
Feature: Allows teachers and students to have real-time video/audio communication.
How to Use: A student can initiate a call with their teacher, and vice versa.
✅ Integrated Quiz Feature (New!)

Quiz Link (Client): SMS Quiz
Quiz API (Server): Quiz Backend
Feature: Students can participate in real-time quizzes for self-assessment.
Built with: React.js & a custom backend.
✅ Other Features:

JWT-based authentication for secure login
Error handling and form validation
Modern UI with Material UI Icons
Future Improvements
🔹 Mobile responsiveness
🔹 Sections beyond academics
🔹 More admin controls for student, faculty, and subject management

Preview
Admin Panel:
🎥 Video Preview

Faculty Panel:
🎥 Video Preview

Student Panel:
🎥 Video Preview
