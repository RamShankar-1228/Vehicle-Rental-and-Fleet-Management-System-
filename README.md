# Vehicle Rental and Fleet Management System (SB Group-12 Mini Project)

A clean, responsive **Vehicle Rental and Fleet Management System** developed as a college mini project. The project provides a complete front-end interface for customers to explore rental vehicles, view vehicle details, register/login, submit booking and pre-booking requests, preview payment options, while also providing an admin interface for fleet and booking management.

The project is designed using **HTML5 and CSS3** with a focus on responsive layouts, user-friendly navigation, vehicle presentation, rental forms, and separate customer and administrator interfaces.

---

## 🎯 Project Overview

The Vehicle Rental and Fleet Management System provides a structured web interface for a rental service where users can:

* Explore available cars, bikes, and SUVs
* Search vehicles using different criteria
* View detailed vehicle information
* Register and login as a customer
* Submit rental booking requests
* Submit pre-booking requests
* Preview available payment methods
* Access an administrator login interface
* View fleet and booking information
* Manage vehicle records through the fleet management interface

> **Note:** This is a front-end academic project. The login, booking, payment and administration modules are currently implemented as static/demo interfaces and do not use a backend database or real payment gateway.

---

## 👥 Project Contributors & Module Distribution

| Member                       | Assigned Pages / Modules                                                                                           | Branch                           |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------ | -------------------------------- |
| **Ram Shankar Singh (Lead)** | Base Architecture, Home, Vehicle Listing, Login Chooser, Shared CSS, Vehicle Images, Search & Filter, Availability | `feature/home-vehicle-listing`   |
| **Pratham Vishnani**         | Vehicle Details, Customer Login, Customer Registration                                                             | `feature/vehicle-details-search` |
| **Rajat**                    | Booking, Pre-booking, Payment Demo                                                                                 | `feature/booking-availability`   |
| **Priya Sharma**             | Admin Login, Admin Dashboard, Fleet Management                                                                     | `feature/admin-fleet`            |

---

## 🛠️ Technology Stack

* **HTML5** — Semantic page structure and web content
* **CSS3** — Styling, layouts, Flexbox, responsive design and UI components
* **Responsive Web Design** — Support for desktop, tablet and mobile screen layouts
* **Local Images** — Vehicle photographs and rental branding assets

### Current Project Scope

* No JavaScript implementation
* No backend server
* No database
* No external API
* No real payment gateway
* No browser storage/localStorage

The current implementation focuses on the **front-end UI and workflow demonstration**.

---

## 🚗 Vehicle Categories

The project includes a vehicle catalogue containing cars, bikes/scooters and SUVs.

### Cars

* Maruti Suzuki Swift
* Honda City
* Maruti Suzuki Ertiga
* Maruti Suzuki Omni

### Bikes & Scooters

* Royal Enfield Classic 350
* Yamaha R15
* Honda Activa
* Royal Enfield Hunter 350
* Hero Splendor
* TVS Raider 125

### SUVs

* Hyundai Creta
* Tata Nexon
* Toyota Fortuner Legender
* Mahindra Thar
* Mahindra Scorpio N
* Tata Safari Storme
* Mahindra XUV700

> Vehicle prices, configurations and availability shown in the project are sample academic project data.

---

## ✨ Key Features

### 🏠 Home & Vehicle Listing

* Modern landing page
* Featured vehicle section
* Vehicle categories
* Vehicle listing interface
* Vehicle availability overview
* Search and filter interface
* Responsive vehicle cards
* Local vehicle photographs

### 🔍 Vehicle Search & Details

* Search vehicle interface
* Vehicle category selection
* Vehicle type selection
* Price range selection
* Availability filter
* Detailed vehicle information
* Vehicle features and rental information

### 👤 Customer Module

* Customer login page
* Customer registration page
* Registration form
* Contact and account information fields
* Password and confirmation fields
* Reset functionality

### 📅 Booking Module

* Vehicle selection
* Rental basis selection
* Pickup and return dates
* Pickup and return time
* Pickup location
* Customer contact information
* Additional requirements
* Booking form validation through HTML form controls
* Reset option

### 📝 Pre-Booking Module

* Preferred vehicle selection
* Rental duration/basis
* Pickup and return details
* Customer information
* Additional requirements
* Pre-booking request interface

### 💳 Payment Module

* Payment method selection
* Payment information interface
* Rental summary
* Payment preview/demo workflow

> Payment functionality is currently a **demo interface** and does not process real transactions.

### 🔐 Admin Module

* Admin login interface
* Fleet overview dashboard
* Recent booking overview
* Vehicle records
* Add vehicle interface
* Edit vehicle interface
* Vehicle removal confirmation/demo controls
* Rental rate fields
* Fleet management interface

---

## 👤 User Roles

### Customer

Customers can:

* Browse rental vehicles
* Search and filter vehicles
* View vehicle details
* Check rental information
* Register an account
* Login through the customer interface
* Submit booking requests
* Submit pre-booking requests
* Preview payment options

### Admin

Administrators can:

* Access the admin login interface
* View fleet information
* View booking information
* Manage vehicle records
* Add vehicle information
* Edit vehicle information
* Remove vehicles through the demo interface
* View rental rate information

---

## 📄 Complete Page Structure

The project consists of **12 main HTML pages** divided among the four team members.

| Page                    | Module                                 | Owner             |
| ----------------------- | -------------------------------------- | ----------------- |
| `index.html`            | Home Page                              | Ram Shankar Singh |
| `vehicles.html`         | Vehicle Listing, Search & Availability | Ram Shankar Singh |
| `login.html`            | Login Selection                        | Ram Shankar Singh |
| `vehicle-details.html`  | Vehicle Details                        | Pratham Vishnani  |
| `customer-login.html`   | Customer Login                         | Pratham Vishnani  |
| `register.html`         | Customer Registration                  | Pratham Vishnani  |
| `booking.html`          | Vehicle Booking                        | Rajat             |
| `pre-booking.html`      | Pre-Booking                            | Rajat             |
| `payment.html`          | Payment Demo                           | Rajat             |
| `admin-login.html`      | Admin Login                            | Priya Sharma      |
| `admin-dashboard.html`  | Admin Dashboard                        | Priya Sharma      |
| `fleet-management.html` | Fleet Management                       | Priya Sharma      |

---

## 📁 Project Structure

```text
Vehicle-Rental-and-Fleet-Management-System/
│
├── index.html
├── vehicles.html
├── login.html
├── vehicle-details.html
├── customer-login.html
├── register.html
├── booking.html
├── pre-booking.html
├── payment.html
├── admin-login.html
├── admin-dashboard.html
├── fleet-management.html
│
├── css/
│   └── style.css
│
├── images/
│   ├── rental-logo.svg
│   ├── activa.jpg
│   ├── city.jpg
│   ├── classic.png
│   ├── creta.png
│   ├── ertiga.jpg
│   ├── fortuner.jpg
│   ├── hunter.avif
│   ├── nexon.jpg
│   ├── omni.jpg
│   ├── r15.jpg
│   ├── raider.jpg
│   ├── safari.webp
│   ├── scorpio.jpg
│   ├── splendor.jpg
│   ├── swift.jpg
│   ├── thar.jpg
│   └── xuv700.jpg
│
└── README.md
```

---

## 🎨 Design & UI

The project follows a clean and responsive design approach with:

* Consistent navigation
* Structured content sections
* Responsive layouts
* Vehicle cards
* Form-based interfaces
* Dashboard-style admin pages
* Reusable CSS styling
* Local vehicle imagery
* Rental service branding

---

## 🔄 System Workflow

```text
                    ┌─────────────────┐
                    │     Home Page   │
                    │   index.html    │
                    └────────┬────────┘
                             │
              ┌──────────────┴──────────────┐
              │                             │
              ▼                             ▼
      ┌───────────────┐             ┌────────────────┐
      │    Vehicles   │             │ Login Selection│
      │  vehicles.html│             │   login.html   │
      └───────┬───────┘             └───────┬────────┘
              │                             │
              ▼                     ┌───────┴────────┐
      ┌───────────────┐              │                │
      │Vehicle Details│              ▼                ▼
      └───────┬───────┘       Customer Login     Admin Login
              │                       │                │
              ▼                       ▼                ▼
         Booking /             Registration      Admin Dashboard
        Pre-Booking                                  │
              │                                      ▼
              ▼                              Fleet Management
         Payment Demo
```

---

## 📱 Responsive Design

The interface is designed to provide a usable experience across:

* 💻 Desktop
* 💻 Laptop
* 📱 Tablet
* 📱 Mobile devices

CSS Flexbox, responsive layouts and scalable UI elements are used throughout the project.

---

## 🚀 How to Run the Project

Since the project is a static HTML/CSS application, no server installation is required.

### 1. Clone the repository

```bash
git clone https://github.com/RamShankar-1228/Vehicle-Rental-and-Fleet-Management-System-.git
```

### 2. Open the project folder

```bash
cd Vehicle-Rental-and-Fleet-Management-System-
```

### 3. Run the project

Open:

```text
index.html
```

in any modern web browser.

You can also use **VS Code with Live Server** for easier development and preview.

---

## 📌 Project Limitations

This version is developed as a **college mini project / front-end prototype**. Therefore:

* Authentication is not connected to a backend
* User data is not stored in a database
* Booking data is not persisted
* Vehicle availability is demonstration data
* Payment is only a UI/demo flow
* Admin operations are front-end demonstrations
* No real payment transaction is performed
* No server-side validation is implemented

---

## 🔮 Future Enhancements

The project can be extended with:

* Backend using Node.js / PHP / Java / Python
* MySQL or MongoDB database
* Real user authentication
* Admin authentication and authorization
* Dynamic vehicle availability
* Real-time booking management
* Online payment gateway integration
* Customer booking history
* Admin analytics and reports
* Vehicle maintenance tracking
* Email/SMS booking confirmation
* JavaScript-based dynamic interactions
* REST API integration

---

## 🎓 Academic Project

**Project:** Vehicle Rental and Fleet Management System
**Section:** SB
**Group:** 12
**Project Type:** College Mini Project
**Development Focus:** Front-End Web Development

---

## 📜 License

This project is developed for **educational and academic purposes** as part of a college mini project.
