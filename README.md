# Gen-AI-Code-Reviewer

AI-Powered Code Reviewer
Welcome to the AI-Powered Code Reviewer, a cutting-edge application built using the MERN Stack (Express.js, React, Node.js) and integrated with the latest Google Gemini API to provide intelligent code analysis, review, and improvement suggestions. This tool aims to enhance development efficiency by automating code reviews and offering actionable feedback to developers. 🚀

## 🌟 Features

AI-Driven Code Analysis: Leverages Google Gemini API to analyze code for syntax errors, logical flaws, and performance issues.
Real-Time Feedback: Get instant suggestions for code improvements directly in the browser.
Multi-Language Support: Supports various programming languages, including JavaScript, Python, and more.
User-Friendly Interface: Built with React for a seamless and interactive front-end experience.
Scalable Backend: Powered by Node.js, Express.js, and API handling.
Secure Authentication: Implements user authentication to manage access and review history.
Customizable Rules: Configure review preferences to align with your project’s coding standards.


## 🛠️ Tech Stack

Frontend: React.js
Backend: Node.js, Express.js
AI Integration: Google Gemini API
Other Tools: Axios for API calls, JWT for authentication, ESLint for code linting


## 📋 Prerequisites
Before you begin, ensure you have the following installed:

Node.js (v16 or higher)
A valid Google Gemini API Key (Obtain from Google Cloud Console)


## 🚀 Getting Started
Follow these steps to set up and run the project locally:
1. Clone the Repository

2. Install Dependencies
Install the dependencies for both the backend and frontend.
Backend:
cd backend
npm install

Frontend:
cd ../frontend
npm install

3. Configure Environment Variables
Create a .env file in the backend directory and add the following:

GEMINI_API_KEY=your_google_gemini_api_key

Create a .env file in the frontend directory (if needed) for frontend-specific configurations, such as API base URL:
REACT_APP_API_URL=http://localhost:5000/api

4. Run the Application
Start the backend and frontend servers in separate terminal windows.
Backend:
cd backend
npm start

Frontend:
cd frontend
npm start

The backend will run on http://localhost:5000, and the frontend will run on http://localhost:3000.
5. Access the Application
Open your browser and navigate to http://localhost:3000 to start using the AI-Powered Code Reviewer.

## 📖 Usage

Sign Up / Log In: Create an account or log in to access the code review dashboard.
Upload Code: Paste your code or upload a file in the provided editor.
Review Code: Click the "Review" button to trigger the AI analysis powered by Google Gemini API.
View Suggestions: Receive detailed feedback, including error detection, optimization suggestions, and best practices.
Apply Changes: Manually apply suggested changes or use the one-click fix feature (where applicable).


## 🛠️ Project Structure
code-review/
├── backend/                  # Node.js + Express.js server
│   ├── config/               # Database configuration
│   ├── controllers/          # API route handlers
│   ├── models/               # MongoDB schemas
│   ├── routes/               # API routes
│   ├── middleware/           # Authentication and error handling
│   └── .env                  # Environment variables
├── frontend/                 # React frontend
│   ├── src/                  # React components, pages, and utilities
│   ├── public/               # Static assets
│   └── .env                  # Frontend environment variables
├── README.md                 # Project documentation
└── package.json              # Project metadata and scripts

## 🤝 Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Make your changes and commit (git commit -m "Add your feature").
Push to the branch (git push origin feature/your-feature).
Open a pull request on GitHub.

Please ensure your code follows the project’s coding standards and includes appropriate tests.

## 🙌 Acknowledgments

Google Gemini API for powering the AI-driven code review.
MERN Stack Community for excellent tools and documentation.
GitHub for hosting the repository.


Happy coding! 🎉
