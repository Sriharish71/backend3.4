# backend3.4
Run Locally:

git clone: https://github.com/Sriharish71/backend3.4.git
cd student-api
npm install

git repo link:

[https://github.com/Sriharish71/backend3.4.git](https://github.com/Sriharish71/backend3.4.git)

Create .env file:

MONGO_URI= mongodb+srv://sriharish7106_db_user:7106@clusterstudent.p7jentp.mongodb.net/studentAPIDB
PORT=3000

Start server:

npm start

API runs at http://localhost:5000

Deployed API

https://backend3-4.onrender.com
Add Student

POST /api/students

{
  "name": "Alice",
  "age": 20,
  "course": "BTech",
  "year": "2nd"
}

Get All Students

GET /api/students
