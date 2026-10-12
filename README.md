# Hotel Management System (HMS)

## Overview

The **Hotel Management System (HMS)** is a web-based system designed to streamline hotel operations in one application. It focuses on room reservations, guest check-in and check-out, billing and payment handling, inventory management, and management reporting.

Its goal is to reduce manual work, improve operational efficiency, and provide a better experience for hotel guests.

## Key Features

- **Room Reservations** – View room availability, select rooms, and record booking details.
- **Guest Check-In and Check-Out** – Record guest arrivals and departures and update room occupancy status.
- **Billing and Payments** – Calculate bills, record payments, include additional charges, and issue invoices or receipts.
- **Inventory Management** – Track room supplies and notify staff when stock levels are low.
- **Reports and Analytics** – Generate reports on room occupancy, revenue, guest numbers, and feedback.
- **Room and Pricing Management** – Manage room information, rates, and promotions.
- **Staff and Account Management** – Manage staff roles, user accounts, and work schedules.
- **Housekeeping and Guest Feedback** – Update room-cleaning status, handle housekeeping requests, and record guest feedback.

## User Roles

- **Guest** – Makes reservations, requests housekeeping, and submits feedback.
- **Receptionist** – Handles reservations, room allocation, check-in, check-out, and billing.
- **Housekeeper** – Updates room status and manages housekeeping tasks.
- **Administrator** – Manages room details, pricing, system configuration, and staff accounts.
- **Hotel Manager** – Uses reports and analytics to monitor hotel operations.

## Operating Environment

The system requirements specify the following environment:

- **Application:** Web-based application accessible through desktop and mobile browsers.
- **Database:** MySQL or a compatible SQL database implementation.
- **Hardware:** Desktop computers, tablets, self-check-in kiosks, printers, and POS equipment where applicable.
- **Connectivity:** Stable internet connection for real-time operations.
- **Security:** Encrypted data transmission using HTTPS/TLS and regular database backups.

## Reservation Workflow

1. The guest or receptionist checks room availability.
2. The guest selects an available room.
3. Guest and booking details are entered.
4. The system records the reservation and updates the room status.
5. Payment is processed according to the implemented payment process.
6. A booking confirmation is provided.
7. Staff update room and housekeeping statuses during the guest's stay.
8. At check-out, the system calculates the final bill, records payment, and updates the room status.
9. The guest may submit feedback after the stay.

## System Requirements

The Software Requirements Specification (SRS) identifies the following targets:

- Support up to **100 concurrent users**.
- Respond to requests within **2 seconds**.
- Handle booking and check-in/check-out operations for **500 or more rooms**.
- Target system availability of **99.9%**.
- Protect sensitive guest information through encryption.
- Validate system functionality, performance, and security through testing and User Acceptance Testing (UAT).

These are requirements specified in the SRS and do not necessarily indicate that the implemented system has already achieved them.

## Project Scope

The system covers:

- Room booking and reservation management
- Guest records and room status
- Check-in and check-out
- Billing and payment records
- Inventory management
- Reports and analytics
- Staff and housekeeping operations
- Administrative functions

Third-party integrations, such as online travel agencies and external payment platforms, are identified as outside the stated scope of the SRS.

## Documentation

The accompanying Software Requirements Specification (SRS) contains detailed system requirements and design documentation, including:

- Use Case Diagrams
- Activity Diagrams
- Class Diagrams
- Package Diagrams
- Sequence Diagrams
- Data Flow Diagrams (DFDs)
- Acceptance Criteria
- Glossary of Terms

## Installation and Setup

Installation and setup instructions will be added once the actual development technologies, source-code structure, and database configuration have been established.

The following details should be documented before deployment:

1. Frontend and backend technologies
2. Database configuration and schema
3. Required environment variables
4. Installation and development commands
5. Authentication and security configuration
6. Testing procedures
7. Deployment instructions

## Testing and Acceptance

According to the SRS, the system should undergo:

- Functional testing to verify the required features.
- Performance testing to evaluate response times and system capacity.
- Security testing to protect sensitive information.
- User Acceptance Testing (UAT) involving hotel staff and intended users.

The system should be accepted when the specified requirements are met and the intended users approve its usability and performance.
