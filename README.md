# MCTMS
Medical Card Transaction Management System

medical-card-transaction-system/
│
├── client/                     # Frontend files
│   ├── index.html              # Main HTML file
│   ├── css/                    # CSS files
│   │   └── styles.css          # Main stylesheet
│   ├── js/                     # JavaScript files
│   │   └── app.js              # Main JavaScript file
│   └── images/                 # Images used in the application
│
├── server/                     # Backend files
│   ├── server.js               # Main server file
│   ├── routes/                 # API routes
│   │   └── transactions.js      # Routes for transaction management
│   ├── models/                 # Database models
│   │   └── transactionModel.js  # Transaction model for MongoDB
│   ├── controllers/            # Controllers for handling requests
│   │   └── transactionController.js # Logic for transaction operations
│   ├── config/                 # Configuration files
│   │   └── db.js               # Database connection setup
│   └── middleware/             # Middleware for authentication, error handling, etc.
│       └── auth.js             # Example middleware for authentication
│
├── .env                        # Environment variables (e.g., MongoDB URI)
├── package.json                # Node.js dependencies and scripts
└── README.md                   # Project documentation

