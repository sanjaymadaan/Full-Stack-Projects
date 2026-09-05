## Recommended MERN REST API Project Structure

## 📂 Project Structure

mern-rest-api/
│
├── server/
│   ├── config/
│   │   └── db.js
│   │
│   ├── controllers/
│   │   ├── authController.js
│   │   └── userController.js
│   │
│   ├── models/
│   │   ├── User.js
│   │   └── Product.js
│   │
│   ├── routes/
│   │   ├── authRoutes.js
│   │   └── userRoutes.js
│   │
│   ├── middleware/
│   │   ├── authMiddleware.js
│   │   ├── errorMiddleware.js
│   │   └── notFoundMiddleware.js
│   │
│   ├── services/
│   │   └── userService.js
│   │
│   ├── utils/
│   │   ├── generateToken.js
│   │   └── responseHandler.js
│   │
│   ├── validators/
│   │   ├── authValidator.js
│   │   └── userValidator.js
│   │
│   ├── app.js
│   ├── server.js
│   ├── package.json
│   └── .env
│
├── client/
│   └── React Application
│
├── .gitignore
└── README.md


## 📁 Folder Description

| Folder/File    | Purpose                                       |
| -------------- | --------------------------------------------- |
| `config/`      | Database and application configuration        |
| `controllers/` | Handles HTTP requests and responses           |
| `models/`      | MongoDB/Mongoose schemas                      |
| `routes/`      | Defines REST API endpoints                    |
| `middleware/`  | Authentication, validation and error handling |
| `services/`    | Business logic                                |
| `utils/`       | Reusable helper functions                     |
| `validators/`  | Request-data validation                       |
| `app.js`       | Express application configuration             |
| `server.js`    | Starts the Node.js server                     |
| `.env`         | Environment variables                         |
| `client/`      | React frontend application                    |
