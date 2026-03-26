# HealthAI Dashboard

## Overview

HealthAI Dashboard is a modern, responsive healthcare management web application built using React and related technologies. The application simulates a real-world dashboard used for managing patient records and medical reports, with authentication and protected routes.

This project demonstrates practical implementation of frontend architecture, state management, and UI design using industry-standard tools.

---

## Features

### Authentication

* User Signup and Login functionality
* Validation using localStorage
* Protected routes using React Router
* Session persistence

### Dashboard

* Displays key statistics:

  * Total Patients
  * Total Reports
  * Latest Accuracy
* Personalized greeting:

  * "Hello, username"

### Patient Management

* Add new patients with attributes:

  * Name
  * Age
  * Disease
* Edit patient details dynamically
* Data persistence using Redux and localStorage

### Report Management

* Add reports with attributes:

  * Patient Name
  * Result
  * Accuracy
* Edit reports dynamically
* Automatically updates dashboard metrics

### UI and UX

* Clean and responsive design using Tailwind CSS
* Card-based layout for better visualization
* Hover effects and smooth transitions
* Modular and reusable components

### Data Visualization

* Charts implemented using Recharts
* Displays analytical insights in dashboard

---

## Tech Stack

* React (Vite)
* Redux Toolkit
* React Router DOM
* Tailwind CSS
* Axios
* Recharts

---

## Project Structure

src/

* components/ → Reusable UI components
* pages/ → Application pages
* features/ → Redux slices
* app/ → Store configuration
* layouts/ → Layout structure
* services/ → API calls

---

## Installation and Setup

1. Clone the repository:
   git clone https://github.com/your-username/healthai-dashboard.git

2. Navigate to project folder:
   cd healthai-dashboard

3. Install dependencies:
   npm install

4. Start development server:
   npm run dev

---

## Usage

* Open the application in browser
* Register a new user
* Login using credentials
* Add patients and reports
* View data updates in dashboard

---

## Key Learnings

* Implemented state management using Redux Toolkit
* Built protected routing with authentication flow
* Designed scalable folder structure
* Created reusable UI components
* Managed persistent data using localStorage
* Developed dynamic dashboards with real-time updates

---

## Future Enhancements

* Backend integration (Node.js, Express)
* Database support (MongoDB)
* JWT-based authentication
* Edit/Delete using modal UI
* Search and filter functionality
* Role-based access control

---

## Author

Developed as a learning and portfolio project to demonstrate frontend development skills and real-world application design.
