🚴‍♂️ Bike-4-Rent

A full-stack bike rental web application built with Node.js, Express, MongoDB (backend) and React (frontend). It enables users to browse available bikes, book rentals, and manage bookings — all through an intuitive UI.

🛠️ Features

✔ User registration & login
✔ Browse available bikes
✔ Bike booking & rental management
✔ MongoDB for database storage
✔ REST API with Express
✔ React frontend with modern UI

📁 Tech Stack
Layer	Technology
Frontend	React.js, HTML, CSS, JavaScript
Backend	Node.js, Express
Database	MongoDB
Authentication	JWT / Sessions
🚀 Live Demo (if available)

(Add link here when deployed)

bike-4-rent/
├── backend/             # Backend API
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── app.js
│   └── server.js
├── frontend/            # React client
│   ├── src/
│   ├── public/
│   └── package.json
├── .gitignore
├── package.json
└── README.md

⚙️ Getting Started
1. Clone the repo
git clone https://github.com/jainygandhi04/bike-4-rent.git
cd bike-4-rent
2. 👩‍💻 Backend Setup
cd backend
npm install

Create a .env file:

PORT=5000
MONGO_URI=<Your MongoDB connection string>
JWT_SECRET=<Your JWT secret>

Start the server:

npm start
3. 🧠 Frontend Setup
cd frontend
npm install
npm start

App should run on: http://localhost:3000

🌐 API Endpoints (Example)
Method	Route	Description
POST	/api/auth/register	Register User
POST	/api/auth/login	Login User
GET	/api/bikes	List Bikes
POST	/api/bookings	Create Booking
GET	/api/bookings	Get User Bookings

📌 Environment Variables
Make sure to set these in your .env:
PORT
MONGO_URI
JWT_SECRET

🤝 Contributing
Fork the repo
Create a new branch (git checkout -b feature/xyz)
Commit your changes
Push to your fork
Open a pull request

GitHub: https://github.com/jainygandhi04
