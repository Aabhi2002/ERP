🎓 COLLEGE ERP
A Complete College Management System using MERN Stack

🚀 Setup Instructions
📌 Follow these steps to set up the project:

1️⃣ Create a .env file in the server folder.
2️⃣ Copy the content from .env.example into your .env file.
3️⃣ Update the MONGODB_URI with your MongoDB Atlas URI.
4️⃣ Open a terminal in the client folder and run:

sh
Copy
Edit
npm run start
5️⃣ Open another terminal in the server folder and run:

sh
Copy
Edit
npm run start
6️⃣ Open your browser and visit: localhost:3000/login/adminlogin
7️⃣ A dummy admin account will be automatically created for testing.

🔐 Login Credentials (Important!)
🔹 Admin Login:
👤 Username: ADM202501001
🔑 Password: 123

🔹 Faculty Login:
👤 Username: FAC202501001
🔑 Password: 123

🔹 Student Login:
👤 Username: STU202501002
🔑 Password: 123

🛠 Tech Stack
Technology	Description
Frontend	React.js, Tailwind CSS, Material UI Icons
Backend	Express.js, MongoDB, JWT Authentication
State Management	Redux
Real-time Communication	Socket.io (for Video Calls)
✨ Features
✅ Admin Features:
✔️ Update profile details & password
✔️ Add, delete, or retrieve students, faculty, and other admins
✔️ Add new departments & subjects
✔️ Create new notices

✅ Faculty Features:
✔️ Update profile details & password
✔️ Create new tests
✔️ Mark student attendance
✔️ Upload test marks

✅ Student Features:
✔️ Update profile details & password
✔️ Check attendance, marks & subject list

🆕 Real-time Video Calling Between Students & Teachers
🔹 Technology Used: Socket.io
🔹 Feature: Enables real-time video/audio communication between students & teachers.
🔹 How to Use: A student can initiate a call with their teacher and vice versa.

🆕 Integrated Quiz Feature
📌 Quiz Link (Client): 📎 SMS Quiz
📌 Quiz API (Server): 📎 Quiz Backend
🔹 Feature: Students can participate in real-time quizzes for self-assessment.
🔹 Built with: React.js & a custom backend.

✅ Other Features:
✔️ Secure JWT-based authentication
✔️ Error handling & form validation
✔️ Modern UI with Material UI Icons

📌 Future Improvements
🔹 📱 Mobile responsiveness
🔹 📂 Sections beyond academics
🔹 🔧 More admin controls for student, faculty & subject management

🎥 Project Preview
📌 Admin Panel:

📌 Faculty Panel:

📌 Student Panel:
