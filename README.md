Daily Expenses Sharing Application
This is a web-based application designed to help users track and share daily expenses between multiple participants. It allows users to split expenses equally or based on custom percentages and view their outstanding balance sheets.

Features:
Add and manage users
Track expenses
Split expenses by equal, exact, or percentage amounts
View and download balance sheets for individual users
/expenses-sharing-app
│
├── /models                # MongoDB schemas
│   ├── User.js            # User schema
│   └── Expense.js         # Expense schema
│
├── /routes                # API endpoints
│   ├── users.js           # User-related routes
│   └── expenses.js        # Expense-related routes
│
├── /node_modules          # Node dependencies
│
├── index.js               # Main server file
├── package.json           # Project metadata and dependencies
├── README.md              # Documentation
└── .env                   # Environment variables

Technologies Used
Node.js: Backend runtime.
Express.js: Framework for building web applications.
MongoDB: NoSQL database for storing data.
Mongoose: Object Data Modeling (ODM) library for MongoDB.
JSON Web Tokens (JWT): For authentication.
Joi: Data validation library.
CSV File Handling: For balance sheet downloads.
Jest/Mocha: For unit testing.
