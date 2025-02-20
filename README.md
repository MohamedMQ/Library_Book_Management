# Library Book Management

## Overview

Library Book Management is a comprehensive full-stack platform designed to help users organize their book collections while connecting with fellow book lovers. The application provides key functionalities like user registration, secure email verification, and a variety of book management tools, including adding, updating, sharing, and archiving books. It also supports book borrowing, with real-time availability checks, and book returns, including return approval processes. Security is ensured via JWT authentication, and the platform follows RESTful API standards. The backend is powered by Spring Boot 3 and Spring Security 6, while the frontend leverages Angular and Bootstrap for a responsive, user-friendly interface.

## Features

- User Registration: New users can create an account to join the platform.
- Email Verification: Account activation is handled through secure email validation codes.
- User Authentication: Registered users can securely log in to access their accounts.
- Book Management: Users can add, update, share, and archive books in their collection.
- Book Borrowing: The system verifies if a book is available for borrowing before proceeding.
- Book Returns: Borrowed books can be returned by users.
- Book Return Approval: A feature is in place to approve or deny book returns.

## Technologies

### Backend (book-network)

- Spring Boot 3
- Spring Security 6
- JWT Token Authentication
- Spring Data JPA
- OpenAPI and Swagger UI Documentation
- Docker

### Frontend (book-network-ui)

- Angular
- Component-Based Architecture
- Lazy Loading
- Authentication Guard
- OpenAPI Generator for Angular
- Bootstrap