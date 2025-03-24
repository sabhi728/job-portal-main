# Job Portal Server

A robust backend server for a job portal website built with Node.js, Express, and MongoDB as part of the MERN stack.

## 🌐 Live Demo
[View Live Demo](https://job-portal-backend-a057.onrender.com)

## 🚀 Features
- Job posting and management
- Job search and filtering
- User authentication and authorization
- RESTful API architecture
- MongoDB database integration
- Secure data handling

## 🛠️ Tech Stack
- Node.js
- Express.js
- MongoDB
- RESTful API
- JWT Authentication

## 📋 Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn package manager

## 🔧 Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/job-portal-server.git
cd job-portal-server
```

2. Install dependencies
```bash
npm install
```

3. Create a `.env` file in the root directory and add your environment variables
```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

4. Start the server
```bash
npm start
```

## 📚 API Documentation

### Available Endpoints

#### Jobs
- `GET /all-jobs` - Get all available jobs
- `POST /post-job` - Create a new job posting
- `GET /job/:id` - Get job details by ID
- `PUT /job/:id` - Update job details
- `DELETE /job/:id` - Delete a job posting

#### Users
- `POST /register` - Register a new user
- `POST /login` - User login
- `GET /profile` - Get user profile
- `PUT /profile` - Update user profile

## 🔒 Environment Variables
Create a `.env` file with the following variables:
```
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
## 📝 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors
- Your Name - Initial work

