# SEEK GenAI-Enhanced Learning Portal

## Overview

The SEEK GenAI-Enhanced Learning Portal is an advanced educational platform designed to transform the learning experience at IIT Madras. Leveraging Generative AI, the portal provides instant AI-powered support for students and robust administrative tools for course management. This project was developed by **Sarvagya Rastogi** and **Dev Khatri**.

---

## Table of Contents

- [Features](#features)
- [User Experience](#user-experience)
- [System Architecture](#system-architecture)
- [API Endpoints](#api-endpoints)
- [Technologies Used](#technologies-used)
- [Testing](#testing)
- [How to Run](#how-to-run)
- [Development Process](#development-process)
- [Authors](#authors)
- [Acknowledgments](#acknowledgments)

---

## Features

### For Students
- Watch video lectures and receive instant AI-powered answers to doubts.
- Access course announcements and updates.
- Practice and submit programming assignments with instant feedback.
- Use a GenAI chatbot for course queries, lecture doubts, and code correction suggestions.

### For Admins
- Upload and manage course content, assignments, and lectures.
- Manage users and view feedback and reports.

---

## User Experience

**Without GenAI:**  
- Doubts are posted to forums and answered by instructors/TAs.
- Course support is accessed via email.
- Debugging failed assignments is manual.

**With GenAI:**  
- Doubts about lectures are answered instantly by the AI assistant.
- Course support is available through the chatbot.
- GenAI suggests reasons for failed test cases and offers debugging tips.

---

## System Architecture

**Frontend:**  
- Vue 3 CLI, Vue Router, Vuex  
- JavaScript, Bootstrap, HTML/CSS

**Backend:**  
- Flask, Flask-RESTful, SQLAlchemy  
- Pytest (testing), Swagger (API docs)

**Database:**  
- Users, Courses, Lectures, Assignments, Announcements, Documents, SupportRequests, Profiles, Content, Admins

**DevOps/Tools:**  
- GitHub (version control), Jira (project management), draw.io (UML), Canva (reports)

---

## API Endpoints

- `/register` – User registration
- `/login` – User login
- `/user`, `/user/{user_id}` – User profile and management
- `/study`, `/study/lectures`, `/study/lectures/{lecture_id}` – Course and lecture access
- `/dashboard/admin` – Admin dashboard
- `/execute` – Code execution and feedback
- `/videochat`, `/codechat`, `/supportchat` – GenAI chatbots for various support functions
- `/logout` – End session

---

## Technologies Used

- **Frontend:** Vue 3, JavaScript, Bootstrap, HTML/CSS
- **Backend:** Python 3.10, Flask, Flask-RESTful, SQLAlchemy
- **AI/ML:** GenAI models for chat and code feedback
- **Testing:** Pytest
- **Documentation:** Swagger
- **DevOps:** GitHub, Jira, draw.io, Canva

---

## Testing

- Comprehensive unit and integration tests using Pytest.
- Test coverage includes registration, login, dashboard, study content, lectures, and code execution.

---

## How to Run

### Backend
1. Install Python 3.10 and create a virtual environment.
2. Install dependencies:
```
pip install -r requirements.txt
```
3. Run the backend server:
```
python app.py
```

### Frontend
1. Install Node.js and npm.
2. Install dependencies:
3. Start the frontend server:
```
npm run serve
```
4. Access the portal at `http://localhost:8080/`.

---

## Development Process

- Agile methodology: 9 sprints from requirements gathering to integration.
- Regular scrum meetings and progress tracking via Jira.
- Version control with GitHub.

---

## Authors

- **Sarvagya Rastogi**
- **Dev Khatri**

---

## Acknowledgments

- IIT Madras SEEK team for project guidance
- All contributors and testers

---

