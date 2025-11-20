# Student Portfolio Template

This project is a simple student portfolio website used for the COMP-2045 Cloud Infrastructure / DevOps module. The purpose of this template is to demonstrate containerization, deployment, and integration with backend services during the course labs.

## 📌 Project Overview
The portfolio is a static website that includes:
- A homepage describing the student
- A profile section with an image
- Basic layout and styling using HTML and CSS

This template is used together with:
- Docker containers  
- Nginx serving static content  
- Kubernetes deployments  
- Backend and database services (as part of the overall course architecture)

## 📁 Project Structure
The `studentportfolio` folder contains:

studentportfolio/
│── Dockerfile
│── index.html
│── README.md
│── css/
│ └── style.css
└── assets/
└── profile.jpg


### **index.html**
The main webpage for the portfolio.  
Contains introductory information and simple UI sections.

### **style.css**
Provides the visual appearance and layout of the portfolio.

### **Dockerfile**
Used to containerize the portfolio website so it can be deployed using Docker, Kubernetes, or Minikube.

### **assets**
Contains the profile image used by the website.
