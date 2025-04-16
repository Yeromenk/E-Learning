# 📚 E-Learning Platform

## 🎯 Project Overview

Welcome to our E-Learning Platform, a web application designed to support online education and connect students and teachers.
The platform offers interactive educational experiences with courses, assignments, quizzes, and real-time communication.

---

## 🚀 Features

### 👥 User Roles

- **Students**: Enroll in courses, complete assignments, take quizzes, and track progress.  
- **Teachers**: Create courses, upload materials, assign tests/quizzes, and evaluate students.  

---

### 📖 Educational Features

- **Course Management**: Teachers can create and manage courses while students can enroll.  
- **Assignments and Tests**: Students complete tasks with deadlines, teachers grade them.  

---

### 💰 Monetization 

- **Free and Premium Courses**: Basic courses with ads, premium courses for paying users.
  
---

## 🛠️ Tech Stack

- Next.js
- **Database**: PostgreSQL  
- **Authentication**: Authentication system with hashed passwords (bcrypt), NextAuth 
- **Payment Integration**: Stripe

---

## 📌 Installation and Setup


### Clone the repository
```bash
git clone https://github.com/your-username/E-Learning.git
```
### Navigate to project directory
```bash
cd E-Learning
```
### Install dependencies
```bash
npm install
```
### Set up environment variables
### Create a .env file with:
```bash
DATABASE_URL="postgresql://username:password@localhost:5432/elearning"
```
### Set up the database
```bash
npx prisma migrate dev
npx prisma db seed
```
### Run the project
```bash
npm run dev
```
## 🏗️ Development Workflow
- Using Agile methodology with two-week sprints.
- Implementing feature branches and pull requests for code review.
