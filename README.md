# 🎯 AI Resume Builder

A modern, responsive AI-powered resume builder application built with **MERN Stack** (MongoDB, Express.js, React, Node.js). Features user authentication, multiple resume templates, AI-enhanced content optimization, live preview, and seamless resume sharing.

![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

## 🌟 Features

### 🎨 Frontend

- **User Authentication** - Sign up and login with JWT authentication
- **Resume Management** - Create, edit, delete multiple resumes
- **Live Preview** - Real-time resume preview while editing
- **Multiple Templates** - Choose from various professional resume templates
- **Theme Customization** - Customize resume colors and styles
- **Responsive Design** - Mobile-first approach with beautiful UI
- **Modern Typography** - Clean, readable Outfit font

### ⚡ Resume Builder

- **Personal Information** - Add name, contact, profession details
- **Professional Summary** - AI-enhanced summary section
- **Work Experience** - Add multiple work experiences with AI optimization
- **Education** - Manage education history
- **Projects** - Showcase your projects with descriptions
- **Skills** - List technical and soft skills
- **Image Upload** - Profile picture with background removal
- **Download PDF** - Export resume as PDF for printing

### 🤖 AI Features

- **AI Enhancement** - Improve resume content using Google Gemini AI
- **Content Optimization** - AI-powered suggestions for professional summaries
- **Job Description Enhancement** - Optimize experience descriptions
- **Background Removal** - Automatic background removal for profile images using ImageKit

### 🔧 Backend & Database

- **REST API** - Built with Express.js
- **MongoDB Integration** - Efficient data storage and retrieval
- **User Management** - Secure authentication and authorization
- **Resume CRUD Operations** - Complete resume management functionality
- **Image Processing** - ImageKit integration for media optimization
- **Public Sharing** - Generate shareable public links for resumes

## 🚀 Demo

🌐 **Live Demo (Client)**: [ai-powered-resume-builder-app.vercel.app](https://ai-powered-resume-builder-app.vercel.app/)  
🖥️ **Live API (Server)**: [ai-powered-resume-builder-api.vercel.app](https://ai-powered-resume-builder-api.vercel.app/)

## 📸 Screenshots

### Home Page

![Home page](./screenshots/Home%20Page.png)

### Login Page

![Login page](./screenshots/Login%20Page.png)

### User Dashboard

![User Dashboard](./screenshots/User%20Dashboard.png)

### Resume Builder Interface

![Resume Builder Interface](./screenshots/Resume%20Builder%20Interface.png)

### Template and Color Customization

![Template Customization](./screenshots/Template%20Customization.png)

![Template Customization](./screenshots/Color%20Customization.png)

### AI Enhancement

![AI Enhancement](./screenshots/AI%20Enhancement.gif)

### Resume Templates

![Resume Template 1](./screenshots/Classic%20Template.png)

![Resume Template 2](./screenshots/Modern%20Template.png)

![Resume Template 3](./screenshots/Minimal%20Image%20Template.png)

![Resume Template 4](./screenshots/Minimal%20Template.png)

## 🛠️ Tech Stack

| Frontend     | Backend     | Database | AI & Media       |
| ------------ | ----------- | -------- | ---------------- |
| React 18     | Node.js     | MongoDB  | Google Gemini AI |
| Vite         | Express.js  | Mongoose | ImageKit         |
| Tailwind CSS | JWT Auth    | -        | -                |
| React Router | RESTful API | -        | -                |
| Lucide React | -           | -        | -                |

## 🚀 Quick Start

### Prerequisites

- Node.js (v14 or higher)
- MongoDB Atlas account
- ImageKit account
- Google Gemini API key

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/ai-resume-builder.git
cd ai-resume-builder
```

### 2. Install Dependencies

#### Backend Setup

```bash
cd server
npm install
```

#### Frontend Setup

```bash
cd client
npm install
```

### 3. Environment Setup

Create a `.env` file in the **server** directory:

```env
# MongoDB
MONGODB_URI=your_mongodb_connection_string

# JWT
JWT_SECRET=your_jwt_secret_key

# ImageKit
IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
IMAGEKIT_URL_ENDPOINT=your_imagekit_url_endpoint

# Google Gemini AI
GEMINI_API_KEY=your_google_gemini_api_key

# Server
PORT=5000
```

### 4. Run Development Server

#### Start Backend Server

```bash
cd server
npm run dev
```

#### Start Frontend Server

```bash
cd client
npm run dev
```

### 5. Open Your Browser

Navigate to `http://localhost:5173` to view the application.

## 🔗 API Endpoints

### Authentication

| Method | Endpoint           | Description       |
| ------ | ------------------ | ----------------- |
| `POST` | `/api/auth/signup` | Register new user |
| `POST` | `/api/auth/login`  | User login        |

### Resume Management

| Method   | Endpoint              | Description            |
| -------- | --------------------- | ---------------------- |
| `GET`    | `/api/resumes`        | Get all user resumes   |
| `POST`   | `/api/resumes`        | Create new resume      |
| `GET`    | `/api/resumes/:id`    | Get specific resume    |
| `PUT`    | `/api/resumes/:id`    | Update resume          |
| `DELETE` | `/api/resumes/:id`    | Delete resume          |
| `POST`   | `/api/resumes/upload` | Upload existing resume |

### AI & Media

| Method | Endpoint            | Description            |
| ------ | ------------------- | ---------------------- |
| `POST` | `/api/ai/enhance`   | AI content enhancement |
| `POST` | `/api/upload/image` | Upload profile image   |

## 🎨 Resume Templates

The application includes multiple professional resume templates:

1. **Classic** - Traditional professional layout
2. **Modern** - Contemporary design with accent colors
3. **Minimal** - Clean and simple design
4. **Creative** - Unique layout with profile image support

## 🚀 Deployment

### Backend Deployment (Vercel)

1. Push your code to GitHub
2. Connect your repository to vercel
3. Add enviroment variables
4. Deploy automatically

### Frontend Deployment (Vercel)

1. Push code to GitHub
2. Connect repository to Vercel or Netlify
3. Configure build settings:
   - Build command: `npm run build`
   - Output directory: `dist`
4. Add environment variables
5. Deploy

## 🔮 Future Enhancements

- [ ] **More Templates** - Additional resume designs
- [ ] **Multi-language Support** - Support for multiple languages
- [ ] **Export Formats** - Word and HTML export options
- [ ] **Collaborative Editing** - Share and edit with others
- [ ] **Resume Analytics** - Track resume views and downloads
- [ ] **ATS Optimization** - Applicant Tracking System compatibility checker
- [ ] **Cover Letter Builder** - Companion cover letter creation
- [ ] **LinkedIn Import** - Import data from LinkedIn profile

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Personal Info

**Avijit Das**

- GitHub: [@Avijit-Das2301](https://github.com/Avijit-Das2301)
- LinkedIn: [avijit2301](https://www.linkedin.com/in/avijit2301/)
