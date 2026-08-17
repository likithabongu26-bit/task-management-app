# task-management-app
Developed a full-stack task management web application featuring user authentication, task CRUD operations, API integration, MongoDB database connectivity, and responsive UI design.
task-management-app/

├── client/
│   ├── package.json
│   └── src/
│       ├── App.js
│       ├── index.js
│       ├── index.css
│       ├── pages/
│       │   ├── Login.js
│       │   ├── Register.js
│       │   └── Dashboard.js
│       ├── services/
│       │   └── api.js
│       └── components/
│           └── ProtectedRoute.js
│
├── server/
│   ├── package.json
│   ├── server.js
│   ├── models/
│   │   ├── User.js
│   │   └── Task.js
│   ├── routes/
│   │   ├── auth.js
│   │   └── tasks.js
│   ├── middleware/
│   │   └── authMiddleware.js
│   └── .env
│
├── .gitignore
└── README.md
