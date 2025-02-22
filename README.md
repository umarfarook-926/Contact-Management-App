# 📞 Contact Management App - Backend

A simple RESTful API for managing contacts using **Node.js, Express.js, and SQLite**.

## 🚀 Features
-  Create, Read, Update, and Delete (CRUD) contacts  
-  SQLite database for data storage  
-  Input validation using `express-validator`   
-  Error handling for invalid inputs and missing data  
-  Unit testing with **Jest & Supertest**  

## 🛠 Tech Stack
- **Backend:** Node.js, Express.js  
- **Database:** SQLite  
- **Validation:** express-validator  
- **Testing:** Jest, Supertest  

## 🔧 Installation & Setup
### 1️.Clone the Repository
`git clone https://github.com/your-username/contact-management-app.git`
cd contact-management-app

### 2. Install Dependencies
`npm install`

### 3. Set Up the Database
The application uses SQLite. A database file contacts.db will be created automatically when the server runs.

### 4. Start the Server
`node server.js`
Server runs on http://localhost:5000

### 5. Run Unit Tests
`npm test`

###  Data Validation
* Validation is handled using express-validator:
- name → must not be empty
- email → must be a valid email format
- phone → must have at least 10 digits

### API Documentation 
Postman API Docs 👉 https://documenter.getpostman.com/view/39206130/2sAYX9oLpu


### 📂 Project Structure

```contact-management-app/
│── config/
│   ├── db.js               # Database configuration
│── controllers/
│   ├── contactController.js  # Handles API logic
│── models/
│   ├── contactModel.js      # Contact schema & queries
│── routes/
│   ├── contactRoutes.js     # API routes
│── tests/
│   ├── contact.test.js      # Unit tests
│── server.js                # Main server file
│── package.json             # Dependencies & scripts
│── README.md                # Project documentation```

=======
