## COMPLAIN MANAGEMENT SYSTEM
ECOR-CMS is a Complaint Management System developed for the East Coast Railway Department during my internship. The system allows users to submit complaints, track their status, and enables admins to manage and resolve them efficiently.

## Table of Contents
- Features
- Technologies Used
- Installation
- Usage
- API Endpoints
- Project Structure
- Contributing
- License

# Features
--User registration and login
-- Submit complaints with file uploads
-- View submitted complaints and their status
-- Admin dashboard to view and manage complaints
-- Forward complaints to specific admins
-- Add remarks to complaints
-- Delete complaints
-- Dynamic admin list fetching

 # Technologies Used
Backend:
Node.js
Express.js
MongoDB
Mongoose
Frontend:
HTML
CSS
JavaScript
Other:
File Uploads: Multer
Authentication: bcrypt, express-session

# Installation
1. Clone the repository
bash
Copy
Edit
git clone https://github.com/yourusername/complaint-management-system.git
cd complaint-management-system
2. Install dependencies
bash
Copy
Edit
npm install
3. Set up MongoDB
Ensure MongoDB is installed and running.
Create a database named main server and a collection named complaints.
4. Configure environment variables
Create a .env file in the root directory and add:

plaintext
Copy
Edit
PORT=3000  
SESSION_SECRET=your-secret-key  
6. Start the server
bash
Copy
Edit
npm start
7. Open in browser
Navigate to:

plaintext
Copy
Edit
http://localhost:3000

 # Usage
 #Submit a Complaint
Fill out the complaint form and submit it.
A unique complaint ID will be generated for tracking.
#View Complaints
Log in to view the status of submitted complaints.
#Admin Management
View all complaints.
Forward complaints to specific admins.
Add remarks and close complaints as needed.
Delete complaints if necessary.
#API Endpoints

# complaint-management-system
├── public/                  # Frontend files
│   ├── home.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   └── ...
├── routes/                  # API route handlers
│   └── auth.js
├── models/                  # Mongoose models
│   ├── User.js
│   ├── complaint.js
│   ├── counter.js
│   └── remarks.js
├── db/                      # Database connection
│   └── connect.js
├── uploads/                 # Uploaded files
├── .env                     # Environment variables
├── index.js                 # Main server file
├── package.json             # Project metadata and dependencies
└── README.md                # Project documentation
# Contributing
Contributions are welcome!

If you find a bug or have suggestions, feel free to open an issue.
Submit a pull request with any improvements or fixes.






