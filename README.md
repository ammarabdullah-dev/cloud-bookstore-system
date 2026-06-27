# Cloud-Based Bookstore System ☁️📚

## Overview

Cloud-Based Bookstore System is a web-based application designed to provide an online platform for managing books, users, inventory, and orders.

The project focuses on applying cloud computing concepts to improve scalability, accessibility, and efficient data management. The application integrates cloud storage and database services to provide a reliable bookstore management solution.

---

## Features

- User-friendly online bookstore interface
- Browse and search available books
- Book inventory management
- User and order management
- Secure data storage
- Cloud-based deployment architecture
- Database integration for storing book and user details
- Scalable application structure

---

## Technologies Used

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Python + Django

### Database
- MySQL

### Cloud Services
- AWS EC2
- AWS S3

### Tools
- Git
- GitHub
- VS Code

---

## System Architecture

The application follows a cloud-based architecture:

User → Web Application → Cloud Server → Database / Storage

- AWS EC2 is used for application hosting
- AWS S3 is used for storing files and resources
- Database manages users, books, and order information

---

## Future Improvements

- Add payment gateway integration
- Implement user authentication with IAM/security services
- Add recommendation system
- Deploy using CI/CD pipeline
- Improve monitoring and logging using cloud services

---

## Learning Outcomes

- Understanding cloud-based application deployment
- Working with AWS services
- Database integration
- Web application development
- Version control using Git

## 📁 Project Structure

```text
cloud-bookstore-system/
├── .github/
│   └── workflows/              # CI/CD pipelines (e.g., GitHub Actions)
├── frontend/
│   ├── public/                 # Static assets (images, icons)
│   ├── src/
│   │   ├── components/         # Reusable UI components (Navbar, BookCard)
│   │   ├── services/           # API call functions to communicate with backend
│   │   ├── utils/              # Helper functions
│   │   ├── app.js              # Main application logic
│   │   └── style.css           # Global styling
│   ├── index.html
│   └── Dockerfile              # Docker configuration for frontend hosting
├── backend/
│   ├── config/                 # Database and environment configurations
│   ├── controllers/            # Request handlers (processes route logic)
│   ├── models/                 # Database schemas (Book, User, Order)
│   ├── routes/                 # API endpoint definitions (/api/books, /api/orders)
│   ├── middleware/             # Auth guards, logging, and error handling
│   ├── tests/                  # Unit and integration tests
│   ├── server.js (or main.py)  # Application entry point
│   ├── package.json            # Dependencies (if Node) or requirements.txt (if Python)
│   └── Dockerfile              # Docker configuration for backend hosting
├── database/
│   ├── migrations/             # Database version control scripts
│   ├── seeds/                  # Mock data to populate books for testing
│   └── schema.sql              # Core database structural blueprint
├── .gitignore                  # Files to ignore in git (e.g., node_modules, .env)
├── docker-compose.yml          # Spins up frontend, backend, and DB locally with one command
└── README.md
