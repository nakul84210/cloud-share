# cloud-share
# CloudShare – Full Stack File Sharing Web Application

## Overview

CloudShare is a full-stack cloud-based file sharing platform that allows users to upload, manage, and share files securely through a modern web interface. The application provides authentication, file management, public file sharing, dashboard analytics, and subscription-related functionality.

This project is built using:

* **Frontend:** React.js + Vite + Tailwind CSS
* **Backend:** Spring Boot (Java)
* **Database:** MongoDB
* **Authentication:** Clerk Authentication
* **API Communication:** Axios

---

# Features

## User Authentication

* Secure user authentication using Clerk
* Login and signup functionality
* Protected dashboard routes

## File Upload & Management

* Upload files securely
* View uploaded files
* Delete files
* Recent files section
* File list management dashboard

## File Sharing

* Generate shareable public links
* Public file view page
* Easy sharing functionality

## Dashboard

* User dashboard with file statistics
* Credits display system
* Upload management interface
* Transactions and subscription pages

## Responsive UI

* Modern responsive design using Tailwind CSS
* Reusable React components
* Clean dashboard layout

---

# Tech Stack

## Frontend

* React.js
* Vite
* Tailwind CSS
* React Router DOM
* Axios
* Clerk Authentication
* Lucide React Icons

## Backend

* Java 21
* Spring Boot 3
* REST APIs
* Maven

## Database

* MongoDB

---

# Project Structure

```bash
cloud-share/
│
├── cloudshareapi/          # Spring Boot Backend
│   ├── src/main/java
│   ├── src/main/resources
│   ├── pom.xml
│   └── Dockerfile
│
├── cloudsharewebapp/       # React Frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── layout/
│   │   ├── context/
│   │   └── util/
│   ├── package.json
│   └── vite.config.js
│
└── README.md
```

---

# Frontend Pages

| Page             | Description                              |
| ---------------- | ---------------------------------------- |
| Landing          | Home page with features and testimonials |
| Dashboard        | User dashboard overview                  |
| Upload           | Upload files page                        |
| My Files         | View uploaded files                      |
| Transactions     | User transaction history                 |
| Subscription     | Subscription plans                       |
| Public File View | Publicly shared file access              |

---

# Installation & Setup

## Prerequisites

Make sure the following are installed:

* Node.js
* Java 21
* Maven
* MongoDB
* Git

---

# Backend Setup (Spring Boot)

## Step 1: Navigate to Backend Folder

```bash
cd cloudshareapi
```

## Step 2: Configure Application Properties

Update `application.properties` with your MongoDB configuration.

Example:

```properties
spring.data.mongodb.uri=YOUR_MONGODB_URI
```

## Step 3: Run Backend Server

Using Maven:

```bash
./mvnw spring-boot:run
```

Or:

```bash
mvn spring-boot:run
```

Backend runs on:

```bash
http://localhost:8080
```

---

# Frontend Setup (React + Vite)

## Step 1: Navigate to Frontend Folder

```bash
cd cloudsharewebapp
```

## Step 2: Install Dependencies

```bash
npm install
```

## Step 3: Start Development Server

```bash
npm run dev
```

Frontend runs on:

```bash
http://localhost:5173
```

---

# Environment Variables

Create a `.env` file inside `cloudsharewebapp`.

Example:

```env
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_key
VITE_API_BASE_URL=http://localhost:8080
```

---

# API Architecture

The frontend communicates with the backend using REST APIs.

Main functionalities include:

* File upload APIs
* File retrieval APIs
* File deletion APIs
* Public sharing APIs
* User-related APIs

---

# UI Components

Some reusable React components used in the project:

* Navbar
* SideMenu
* UploadBox
* FileCard
* LinkShareModal
* RecentFiles
* ConfirmationDialog
* CreditsDisplay

---

# Future Improvements

* Drag and drop file upload
* File preview support
* Dark mode
* Real-time notifications
* File encryption
* Cloud deployment
* Payment gateway integration

---

# Learning Outcomes

Through this project, the following concepts were practiced:

* Full-stack web development
* REST API development
* React state management
* Authentication integration
* MongoDB integration
* Component-based architecture
* Responsive UI design
* Client-server communication

---

# Author

**Nakul Indurkar**

GitHub: [https://github.com/nakul84210](https://github.com/nakul84210)

---

# Resume Description

Developed a full-stack cloud-based file sharing web application using React.js, Spring Boot, and MongoDB. Implemented secure authentication, file upload and sharing functionality, REST APIs, and a responsive dashboard interface for managing files and subscriptions.

---

# License

This project is for educational and learning purposes.
