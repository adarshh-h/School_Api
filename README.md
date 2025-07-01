# 📘 School Management API

This is a Node.js + Express.js + MySQL REST API project for managing school data.  
It allows users to add new schools and retrieve a list of schools sorted by proximity to a given location.

---

## ✅ Live API Endpoints (for testing)

- Base URL: https://school-api-cmst.onrender.com  
- POST Add School: https://school-api-cmst.onrender.com/addSchool  
- GET List Schools: https://school-api-cmst.onrender.com/listSchools?latitude=19.05&longitude=72.89
  
Use this link to test API endpoints via Postman or browser.


## 🛠 Technologies Used

- Node.js
- Express.js
- MySQL (hosted on Railway)
- Render (for deployment)
- Postman (for testing)



## 📦 Installation & Setup (Local Development)

1. Clone the repository  
   ```bash
   git clone https://github.com/YOUR_USERNAME/School_API.git
   cd School_API
   npm install
2. Create a .env file in the root directory with the following content:
   ```bash
     DB_HOST=your_mysql_host
     DB_USER=your_mysql_user
     DB_PASSWORD=your_mysql_password
     DB_NAME=your_database_name
     DB_PORT=3306

3. Start the server
   ```bash
    npm start
