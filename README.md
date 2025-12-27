# Url-Shortener-FullStack-Project
A full-stack URL Shortener platform using Spring Boot, Spring Security, and React.js. Supports JWT authentication, role-based access control, secure URL redirection, and a responsive user interface.
## 📘 Project Explanation

This project follows a **modular full-stack architecture** where the frontend and backend are maintained as **independent repositories** and linked together using **Git Submodules**.

- The **frontend** (React.js) and **backend** (Spring Boot) are developed, versioned, and deployed independently.
- This parent repository acts as an **umbrella repository** that represents the complete system.
- Git Submodules allow this repository to reference specific commits of both frontend and backend without duplicating code.

### Why this approach?
- Clean separation of concerns
- Independent development and deployment
- Better scalability and maintainability
- Industry-standard practice used in real-world projects

This structure makes the project more professional, scalable, and suitable for enterprise-level applications.
