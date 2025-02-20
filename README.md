<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>College ERP - README</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
            padding: 20px;
            background-color: #f4f4f4;
        }
        h1, h2, h3 {
            color: #2c3e50;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        pre {
            background: #2c3e50;
            color: #fff;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
        .copy-btn {
            background: #3498db;
            color: #fff;
            border: none;
            padding: 5px 10px;
            cursor: pointer;
            border-radius: 5px;
            font-size: 14px;
        }
        .highlight {
            color: #e74c3c;
            font-weight: bold;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 10px;
        }
        table, th, td {
            border: 1px solid #ddd;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
        th {
            background: #2c3e50;
            color: white;
        }
        .link {
            color: #3498db;
            text-decoration: none;
            font-weight: bold;
        }
        .link:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>🎓 College ERP - README</h1>
    <p>A Complete College Management System using <strong>MERN Stack</strong>.</p>

    <h2>🚀 To Run Locally</h2>
    <p><strong>Clone the project:</strong></p>
    <pre>
        git clone https://github.com/your-username/College-ERP.git
        <button class="copy-btn" onclick="copyToClipboard('git clone https://github.com/your-username/College-ERP.git')">📋 Copy</button>
    </pre>

    <p><strong>Go to the project directory:</strong></p>
    <pre>
        cd College-ERP
        <button class="copy-btn" onclick="copyToClipboard('cd College-ERP')">📋 Copy</button>
    </pre>

    <p><strong>Install dependencies:</strong></p>
    <pre>
        npm install
        <button class="copy-btn" onclick="copyToClipboard('npm install')">📋 Copy</button>
    </pre>

    <p><strong>Start the server:</strong></p>
    <pre>
        npm run start
        <button class="copy-btn" onclick="copyToClipboard('npm run start')">📋 Copy</button>
    </pre>

    <h2>🔐 Login Credentials</h2>
    <table>
        <tr>
            <th>Role</th>
            <th>Username</th>
            <th>Password</th>
        </tr>
        <tr>
            <td><strong>Admin</strong></td>
            <td>ADM202501001</td>
            <td>123</td>
        </tr>
        <tr>
            <td><strong>Faculty</strong></td>
            <td>FAC202501001</td>
            <td>123</td>
        </tr>
        <tr>
            <td><strong>Student</strong></td>
            <td>STU202501002</td>
            <td>123</td>
        </tr>
    </table>

    <h2>🛠 Tech Stack</h2>
    <ul>
        <li><strong>Frontend:</strong> React.js, Redux, Tailwind CSS, Material UI Icons</li>
        <li><strong>Backend:</strong> Express.js, MongoDB, JWT Authentication, Socket.io</li>
        <li><strong>Deployment:</strong> Netlify (Client), Render (Socket.io), Cyclic (Backend)</li>
    </ul>

    <h2>✨ Features</h2>
    <h3>✅ Admin Controls:</h3>
    <ul>
        <li>Add, delete, or update students, faculty, and admins</li>
        <li>Create and manage departments & subjects</li>
        <li>Publish notices for the college</li>
    </ul>

    <h3>✅ Faculty Features:</h3>
    <ul>
        <li>Mark student attendance</li>
        <li>Conduct tests & upload marks</li>
        <li>One-on-one video call with students</li>
    </ul>

    <h3>✅ Student Features:</h3>
    <ul>
        <li>View attendance, marks & subject list</li>
        <li>Ask doubts & receive real-time solutions</li>
        <li>Participate in quizzes for self-assessment</li>
    </ul>

    <h3>✅ Real-time Video Calling <span class="highlight">(New!)</span></h3>
    <ul>
        <li><strong>Technology Used:</strong> Socket.io</li>
        <li><strong>Feature:</strong> Live video/audio communication between teachers and students</li>
        <li><strong>Usage:</strong> A student can initiate a call with their teacher, and vice versa</li>
    </ul>

    <h3>✅ Integrated Quiz System <span class="highlight">(New!)</span></h3>
    <ul>
        <li><strong>Client:</strong> <a href="https://sms-quiz.netlify.app/" class="link">📎 SMS Quiz</a></li>
        <li><strong>Server:</strong> <a href="https://ill-blue-wildebeest-kilt.cyclic.app" class="link">🌐 Quiz Backend</a></li>
        <li>Real-time quiz participation for students</li>
    </ul>

    <h2>🔗 Live Links</h2>
    <ul>
        <li>📌 <strong>Client (Main Dashboard):</strong> <a href="#" class="link">🚀 College ERP</a></li>
        <li>📌 <strong>Video Call:</strong> <a href="#" class="link">🎥 Live Video Call</a></li>
        <li>📌 <strong>Quiz:</strong> <a href="https://sms-quiz.netlify.app/" class="link">📝 Take a Quiz</a></li>
        <li>📌 <strong>Server (Backend):</strong> <a href="https://ill-blue-wildebeest-kilt.cyclic.app" class="link">🌐 API Server</a></li>
    </ul>
</div>

<script>
    function copyToClipboard(text) {
        navigator.clipboard.writeText(text).then(() => {
            alert("Copied to clipboard: " + text);
        }).catch(err => {
            console.error("Failed to copy: ", err);
        });
    }
</script>

</body>
</html>
