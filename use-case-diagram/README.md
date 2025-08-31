# Use Case Diagram - Airbnb Clone Backend

## Overview
This document explains the **Use Case Diagram** for the Airbnb Clone backend system.  
The diagram highlights the main actors, their roles, and how they interact with the system to achieve key functionalities such as authentication, property management, bookings, payments, and messaging.

---

## Actors
1. **Guest**
   - Represents users who use the platform to search, book, and pay for properties.
   
2. **Host**
   - Represents users who list properties and manage bookings.
   
3. **Admin**
   - Represents system administrators who oversee the platform, ensuring smooth operations.
   
4. **Payment Gateway**
   - Represents external third-party services (e.g., Stripe, PayPal) that securely process payments.

---

## Use Cases and Relationships

### Guest
- **Register / Login**: Guests can create accounts or log in to access features.
- **Manage Profile**: Guests can update their personal information.
- **Search Property**: Guests can browse, search, and filter property listings.
- **Book Property**: Guests can book available properties.
- **Make Payment**: Guests pay for bookings via a connected payment gateway.
- **Leave Review**: Guests can rate and review properties after their stay.
- **Send Message**: Guests can communicate with hosts regarding bookings or inquiries.

### Host
- **Register / Login**: Hosts create accounts or log in to manage their properties.
- **Manage Profile**: Hosts can update their personal and hosting details.
- **Create / Update / Delete Property**: Hosts can list new properties and update or remove existing ones.
- **Manage Booking (confirm/cancel)**: Hosts can accept, reject, or cancel bookings.
- **Send Message**: Hosts can communicate with guests directly through the platform.

### Admin
- **Manage Users / Listings / Bookings**: Admins oversee all users, property listings, and bookings. They can moderate, update, or remove content as necessary.

### Payment Gateway
- **Make Payment (External Service)**: This interaction ensures secure processing of booking payments through services like **Stripe** or **PayPal**.

---

## Diagram

<img width="768" height="555" alt="airbnb_usecase" src="https://github.com/user-attachments/assets/d335c3ff-7d88-4f1c-bba7-4e8e85e99444" />

## Summary
The use case diagram demonstrates how **Guests**, **Hosts**, and **Admins** interact with the **Airbnb Clone backend system**. It also shows integration with external **Payment Gateways** to process financial transactions. This ensures a secure, reliable, and user-friendly platform for all stakeholders.
