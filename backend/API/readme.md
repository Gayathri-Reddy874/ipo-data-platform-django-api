
# Bluestock Fintech IPO REST API Design

This project is a REST API developed for Bluestock Fintech to manage and showcase IPOs (Initial Public Offerings) to users. The application is built using Django and Django Rest Framework, with PostgreSQL (NeonDB) as the database. The admin can perform CRUD operations, while users can access protected endpoints through JWT authentication.

## Objectives

- Provide a REST API to showcase IPOs to users.
- Enable CRUD operations for IPOs through the admin interface.
- Secure user endpoints with JWT tokens and authentication routes.

## Features

### Admin CRUD Operations
- **POST /administrator/api/v1/ipo-list/**: Create a new IPO.
- **GET /administrator/api/v1/ipo-list/**: get details of existing IPOs.
- **PUT /administrator/api/v1/ipo-list/1/**: Update the details of an existing IPO.
- **DELETE /administrator/api/v1/ipo-list/3/**: Delete an existing IPO.

### User Operations
- **POST /api/user/register/**: Register a new user.
- **POST /api/user/login/**: Authenticate and login a user.
- **POST /api/user/changepassword/**: Change the password of a logged-in user.
- **GET /api/user/ipo/**: get a list of IPOs available to the user.
- **GET /api/user/profile/**: get the profile details of the logged-in user.
- **POST /api/user/send-reset-password-email/**: Send an email to reset the user's password.
- **POST /api/user/reset-password/<uid>/<token>/**: Reset the user's password using a token sent via email.

## Getting Started

### Prerequisites

- Python 3.12
- PostgreSQL (NeonDB)
- Django 5.0.7
- Django Rest Framework
- Postman or any API testing tool

### API Documentation

You can use tools like Postman to test the endpoints listed in the features section. Make sure to include the JWT token in the Authorization header for protected endpoints.

## License

This project is licensed by Bluestock Fintech License.
https://bluestock.in/
---
