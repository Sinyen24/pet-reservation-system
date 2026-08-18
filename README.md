# 🐾 Pet Boarding & Daycare Reservation System

A console-based Java application developed to manage pet boarding and daycare reservations. The system allows clients to manage pet profiles, browse and book services, view booking history, and make payments, while administrators can manage pets, services, bookings, and staff.

> 🎓 This project was developed as a group assignment for the Object-Oriented Application Development course at Universiti Tunku Abdul Rahman (UTAR).

## ✨ Features

### 👤 Client
- User registration and login
- View pet profiles
- Browse available pet services
- Make service reservations
- Select booking date and time
- Process booking payments
- View active, expired, and cancelled bookings
- View pet and booking history

### 🔐 Administrator
- Manage pet profiles
- Add, search, update, and delete pet records
- Manage pet boarding and daycare services
- Add, edit, and delete services
- View all client bookings
- Cancel bookings
- Manage staff information

## 🛠️ Technologies & Concepts

- **Java**
- **Object-Oriented Programming (OOP)**
  - Encapsulation
  - Inheritance
  - Polymorphism
  - Abstraction
- File Handling
- Exception Handling
- Input Validation
- Console-based User Interface

## 💡 System Design

The application applies object-oriented programming principles by separating different responsibilities into classes representing system entities such as:

- User
- Client
- Admin
- Pet
- Service
- Staff
- Registration Service

Data is stored using file handling, allowing records such as users, pets, bookings, services, and staff information to persist between program executions.

## 🖥️ Sample Output

### Main Menu

![Main Menu](screenshots/main-menu.png)

### User Registration & Login

![Registration and Login](screenshots/registration-login.png)

### Client Dashboard

![Client Dashboard](screenshots/client-dashboard.png)

### Service Booking

![Booking Process](screenshots/booking-process.png)

### Admin Dashboard

![Admin Dashboard](screenshots/admin-dashboard.png)

### Service Management

![Service Management](screenshots/service-management.png)

## 📚 What I Learned

Through this project, I gained practical experience in:

- Applying Java object-oriented programming concepts to a complete application
- Designing classes with different responsibilities
- Working with inheritance and relationships between objects
- Implementing file handling for persistent data storage
- Handling invalid user input and exceptions
- Implementing role-based functionality for clients and administrators
- Developing booking and management workflows in a console application

## 📄 Documentation

The complete assignment report, including system requirements, use cases, functional requirements, implementation details, and sample outputs, is available in the [`documentation`](documentation/) folder.

## ℹ️ Project Note

This repository is maintained as a portfolio showcase of a university group project. The original Java source code is no longer available, so the repository contains the project documentation and sample outputs from the completed implementation.
