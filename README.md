# 🏺 Historical Artifacts Tracker

A modern, interactive web application for discovering, exploring, comparing, and preserving information about historical artifacts.

Historical Artifacts Tracker provides a centralized platform where users can explore historical objects, learn about their backgrounds, contribute new artifacts, and interact with historical information through comments, comparisons, quizzes, and other interactive features.

## 🌐 Live Application

**Live Website:** https://assignment-11-1588b.web.app

---

## 📖 Project Overview

Historical artifacts provide valuable insights into ancient civilizations, cultures, technologies, and human history. However, information about these artifacts is often scattered across different sources.

Historical Artifacts Tracker aims to make historical information more accessible and engaging through an interactive web platform.

Users can discover historical artifacts, explore detailed information, contribute their own discoveries, compare historical objects, participate in knowledge-based quizzes, and interact with other users.

The application focuses on combining historical knowledge with modern web technologies to create an engaging and user-friendly experience.

## ✨ Key Features

### 1. Historical Artifact Discovery
- Explore a collection of historical artifacts from different periods and categories.
- Search artifacts by name.
- Discover featured artifacts based on popularity and like counts.
- View detailed historical information, including historical context, creation period, discovery details, discoverer, and present location.

### 2. Artifact Management
- Add new historical artifacts through an interactive form.
- Upload artifact images directly from local devices using Cloudinary.
- Update and delete personal artifact contributions.
- View and manage individually submitted artifacts.

### 3. Authentication & Protected Routes
- User authentication using Firebase Authentication.
- Support for Email/Password and Google sign-in.
- JWT-based authentication flow for protected application features.
- User-specific pages and protected navigation.
- Conditional navigation based on authentication status.

### 4. Interactive Comment System
- Post comments on individual artifacts.
- View comments shared by other users.
- Edit and delete personal comments.

### 5. Side-by-Side Artifact Comparison
- Compare two historical artifacts side by side.
- Examine differences between historical objects.
- Write personal comparison notes.
- View, update, and delete saved comparison notes.

### 6. Dynamic Historical Quiz
- Generate quiz questions dynamically using available artifact data.
- Test historical knowledge through artifact-related questions.
- View quiz results, including total questions, correct answers, and incorrect answers.

### 7. Interactive Like & Dislike System
- Like or dislike historical artifacts.
- Toggle between liked and disliked states.
- Display updated like counts.
- Synchronize interaction states with stored application data.
- Discover popular artifacts through featured sections.

### 8. Responsive User Interface
- Responsive layouts for mobile, tablet, and desktop devices.
- Modern interface built with Tailwind CSS and DaisyUI.
- Interactive animations using Framer Motion.
- Image sliders and carousels.
- Loading indicators and user-friendly notifications.

### 9. Additional Application Features
- Dynamic document titles based on the current route.
- Custom 404 Not Found page.
- Loading spinners for asynchronous operations.
- Success and error notifications.
- Interactive navigation and user profile dropdown.

---

## 🛠️ Technologies Used

### Frontend
- **React.js** – Component-based user interface development.
- **React Router** – Client-side routing and navigation.
- **Vite** – Frontend development server and build tooling.
- **Tailwind CSS** – Utility-first CSS framework.
- **DaisyUI** – Reusable UI components built on Tailwind CSS.
- **Framer Motion** – UI animations and transitions.

### Authentication & Integration
- **Firebase Authentication** – User authentication.
- **Axios** – HTTP requests and API communication.
- **JSON Web Token (JWT)** – Token-based authentication integration.

### UI Components & Libraries
- **Swiper** – Interactive sliders and carousels.
- **React Slick** – Carousel functionality.
- **React Icons** – Icon components.
- **SweetAlert2** – Interactive alert dialogs.
- **React Hot Toast** – Toast notifications.
- **React Toastify** – Notification management.
- **Lottie React Player** – Animated visual elements.

### Image Management
- **Cloudinary** – Image uploading, storage, and optimization.

---

## 📸 Application Highlights

The application brings together several interactive features:

- Historical artifact exploration.
- User-generated historical content.
- Personal artifact management.
- Interactive discussions.
- Artifact comparison.
- Knowledge-based quizzes.
- User engagement through likes and dislikes.

---

## 💻 Getting Started

Follow these steps to run the client-side application locally.

### Prerequisites

Make sure you have installed:

- Node.js
- npm
- Git

### Installation

**1. Clone the repository**

```bash
git clone YOUR_CLIENT_REPOSITORY_URL
```

**2. Navigate to the project directory**

```bash
cd YOUR_PROJECT_DIRECTORY
```

**3. Install dependencies**

```bash
npm install
```

**4. Configure environment variables**

Create a `.env` file in the root directory and configure the required environment variables.

Example:

```env
VITE_apiKey=your_firebase_api_key
VITE_authDomain=your_firebase_auth_domain
VITE_projectId=your_firebase_project_id
VITE_storageBucket=your_firebase_storage_bucket
VITE_messagingSenderId=your_firebase_messaging_sender_id
VITE_appId=your_firebase_app_id
```

Use the actual environment variable names referenced in your project source code.

Never commit private credentials or sensitive configuration files to a public repository.

**5. Start the development server**

```bash
npm run dev
```

The application will be available at the local development URL provided by Vite.

### Production Build

To generate an optimized production build:

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```

---

## 🚀 Deployment

- **Frontend Hosting:** Firebase Hosting
- **Authentication:** Firebase Authentication
- **Image Management:** Cloudinary

The frontend application is deployed and accessible through the live website link provided above.

---

## 👨‍💻 Developer

**MD Yasin**

Full-Stack Web Developer

- **Email:** mdyasin48902@gmail.com

---

## 🎯 Project Goals

This project represents practical experience in building an interactive, data-driven React application.

It demonstrates the implementation of component-based architecture, client-side routing, authentication integration, API communication, protected user experiences, dynamic UI updates, image management, and responsive interface development.

The primary goal was to create a meaningful application that combines historical education, user interaction, and modern frontend development practices.

---

**Built with React.js and a passion for making historical knowledge more accessible.** 🏺
