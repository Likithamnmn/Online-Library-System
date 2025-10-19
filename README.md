📚 Goodreads Application

A modern web-based Goodreads clone that allows users to explore, review, and manage their favorite books. Built using Node.js, Express, SQLite, and modern front-end tools for a smooth and interactive experience.

🚀 Features

🔐 User authentication (Sign up & Login)

📖 Browse, search, and view book details

📝 Add, edit, and delete reviews

❤️ Mark books as favorites or “to read”

📊 Track reading history and progress

⚙️ RESTful APIs using Express + SQLite

🧠 Tech Stack

Frontend: HTML, CSS, JavaScript, React (optional)
Backend: Node.js, Express.js
Database: SQLite3
Version Control: Git & GitHub

🗂️ Folder Structure
goodreadsapp/
│
├── backend/
│   ├── app.js
│   ├── database.sqlite
│   ├── routes/
│   └── controllers/
│
├── frontend/
│   ├── index.html
│   ├── styles.css
│   └── scripts.js
│
├── package.json
└── README.md

⚙️ Setup Instructions
Clone the Repository
git clone https://github.com/Likithamnmn/Online-Library-System.git
cd Online-Library-System

Install Dependencies
npm install

Run the App
node app.js


The app runs on http://localhost:3000

🧩 API Endpoints (Example)
Method	Endpoint	Description
GET	/books	Get all books
POST	/books	Add a new book
GET	/books/:id	Get book details
PUT	/books/:id	Update book info
DELETE	/books/:id	Delete a book
💡 Future Enhancements

Add JWT authentication

Integrate with Google Books API

Dark/light theme toggle

Social sharing for reviews
