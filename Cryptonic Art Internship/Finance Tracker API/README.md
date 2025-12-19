Personal Finance Tracker API
A secure, high-performance RESTful API developed with Node.js and Express.js for comprehensive personal financial management. The system enables users to track transactions, organize budgets, and generate real-time financial reports.

🔒 Security & Reliability
Designed with a "Security-First" mindset to protect sensitive financial data:


Authentication: Implements JWT (JSON Web Tokens) with a dual-token system (Access/Refresh) and password hashing via bcrypt.


Traffic Management: Integrated Rate Limiting (5 attempts/min for login) to prevent brute-force attacks.


Data Integrity: Strict input sanitization and validation using express-validator to prevent injection vulnerabilities.


Isolation: Ensures strict user-specific transaction isolation so data is never leaked between accounts.

📊 Core Functionalities

Transaction Management: Efficient CRUD operations for income and expenses with advanced filtering by date range or category.


Custom Categorization: User-defined expense/income categories with custom color coding for UI integration.


Financial Analytics: Automatic calculation of current balances and period-based summaries grouped by category.


Interactive Documentation: Complete Swagger/OpenAPI 3.0 specification providing an interactive UI for API exploration and testing.

🚀 Quick Start
Clone the Repo: git clone (https://github.com/AbdulRahman-Alzoubi/Projects/tree/main/Cryptonic%20Art%20Internship/Finance%20Tracker%20API)

Install Dependencies: npm install 

Environment Setup: Configure your .env with MONGODB_URI and JWT_SECRET.

Run Server: npm start
