
# WhatNext Vision Motors
### Shaping the Future of Mobility with Innovation and Excellence

A Salesforce CRM application designed to streamline vehicle sales, customer management, dealer coordination, inventory tracking, test drive scheduling, and order processing.

The project uses Salesforce custom objects, Flows, Apex Triggers, Batch Apex, and Scheduled Apex to automate dealership operations.

## Problem Statement

Traditional automotive businesses often manage vehicle inventory, customer records, dealer information, and orders across separate systems. This leads to delayed order processing, inaccurate stock information, and inefficient customer service.

**WhatNext Vision Motors** addresses these challenges through a centralized Salesforce CRM application that improves data management and automates key business processes.

## Key Features

- **Vehicle Management:** Manage vehicle models, brands, prices, and stock quantities.
- **Dealer Management:** Maintain dealer records and support location-based dealer assignment.
- **Customer Management:** Store customer details and order information.
- **Order Management:** Create, manage, and track vehicle orders.
- **Stock Validation:** Prevent orders when vehicles are out of stock.
- **Test Drive Management:** Schedule test drives and automate reminders.
- **Service Request Management:** Manage customer vehicle service requests.
- **Batch Processing:** Process pending orders based on vehicle availability.
- **Scheduled Automation:** Execute batch operations automatically at configured intervals.

## Data Model – Custom Objects

| Custom Object | Purpose |
|---|---|
| Vehicle | Stores vehicle models, prices, and stock details |
| Vehicle Dealer | Maintains dealer information and locations |
| Vehicle Customer | Stores customer details |
| Vehicle Order | Manages customer vehicle orders |
| Vehicle Test Drive | Records test drive bookings |
| Vehicle Service Request | Manages vehicle service requests |

## Technology Stack

- Salesforce Lightning Experience
- Salesforce Object Manager
- Salesforce Lightning App Builder
- Salesforce Record-Triggered Flows
- Apex Classes and Triggers
- Batch Apex
- Scheduled Apex
- Salesforce Developer Console

## Automation Overview

### 1. Dealer Assignment Flow

Automatically assigns suitable dealers based on configured customer-location criteria, reducing manual effort during order processing.

### 2. Vehicle Stock Validation Trigger

Validates stock availability before processing vehicle orders. If the selected vehicle is out of stock, the system blocks the transaction and displays an error message.

### 3. Batch Apex

Processes existing pending vehicle orders in bulk and updates their statuses according to vehicle stock availability.

### 4. Scheduled Apex

Automates batch execution at predefined intervals to support regular order processing.

### 5. Test Drive Automation

Supports automated notifications and reminders for scheduled customer test drives.

## Getting Started

### Prerequisites

- Salesforce Developer Edition account
- Salesforce Setup and Object Manager access
- Salesforce Developer Console
- Basic knowledge of Salesforce Flows and Apex

### Application Setup

1. Log in to Salesforce Developer Edition.
2. Create the required custom objects and fields.
3. Configure lookup relationships between objects.
4. Create custom tabs and a Salesforce Lightning application.
5. Configure record-triggered flows.
6. Implement Apex classes and triggers for stock validation.
7. Configure Batch Apex and Scheduled Apex.
8. Test the application using Salesforce test scenarios.

## Application Usage

1. Open **WhatNext Vision Motors** from the Salesforce App Launcher.
2. Add vehicle, dealer, and customer records.
3. Create vehicle orders and validate stock availability.
4. Schedule customer test drives.
5. Manage vehicle service requests.
6. Monitor order processing and automation.

## Project Documentation

The project report includes:

- Introduction and User Story
- Ideation Phase
- Requirement Analysis Phase
- Project Design Phase
- Project Planning and Scheduling
- Project Development Phase
- Testing and Validation Phase
- Results and Discussion
- Conclusion and Future Enhancements

**Project Report:** [WhatNext_Doc.docx](WhatNext_Doc.docx)

## Future Enhancements

- AI-based vehicle recommendations
- Real-time dealership inventory updates
- GPS-based nearest dealer recommendations
- Customer self-service portal
- Advanced Salesforce reports and dashboards
- Mobile application integration

## Author

**Mariselvan M**

**Department:** Computer Science and Engineering

