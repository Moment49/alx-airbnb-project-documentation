
## ✅ `data-flow-diagram/README.md`

````markdown
# 📊 Data Flow Diagram (DFD) – ALX Airbnb Clone Project

## 🧾 Overview

This directory contains the **Data Flow Diagram (DFD)** for the `alx-airbnb-project-documentation` repository. The DFD visualizes how data flows between users, internal processes, databases, and external services within the Airbnb-like system.

The diagram provides a **Level 1 overview** of core backend operations such as user registration, property listing, booking flow, and payments. It’s intended to support both backend development and system design validation.

---

## 🎯 Objective

To map out how data moves through the system — from external actors (like users) into backend processes and data stores — in support of:

- User registration and authentication  
- Listing creation and updates  
- Booking management  
- Payment processing  
- Notifications and reviews

---

## 📦 File Structure

```bash
data-flow-diagram/
├── data-flow.png         # Exported DFD PNG image
└── README.md             # This documentation file
````

---

## 🔧 DFD Components

**External Entities**

* Users (Guests / Hosts)
* Admin
* Payment Gateway (Stripe / PayPal)

**Processes**

* User Auth & Profile Management
* Listing Management
* Search & Filter
* Booking System
* Payment Engine
* Notification & Review Service

**Data Stores**

* Users DB
* Listings DB
* Bookings DB
* Payments DB
* Reviews DB

---

## 📷 Diagram Preview

> See: `data-flow-diagram/data-flow.png`

---

## ✍️ Author

> Designed and documented by the backend team as part of the ALX Software Engineering Program – Airbnb Project.

```

---

## 🧠 Level 1 DFD Overview (Concept)

```

\[Guest / Host] ---> (User Auth) ---> \[Users DB]
(Profile Update)
(Listing CRUD) ---> \[Listings DB]
(Search Engine) --> \[Listings DB]

\[Guest] ---> (Booking System) --> \[Bookings DB]
\--> (Payment Engine) --> \[Payments DB]
\---> \[Payment Gateway]

(Review System) <--> \[Reviews DB]

(Admin) ---> (Admin Dashboard) --> \[Users DB], \[Listings DB], \[Bookings DB]

```
