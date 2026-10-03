# WhatNext-Vision-Motors
Salesforce CRM for vehicle, customer, dealer, order, test drive &amp; service management with automated workflows
# WhatNext Vision Motors: Shaping the Future of Mobility with Innovation and Excellence

A Salesforce CRM solution built for **WhatNext Vision Motors**, an automotive company. It streamlines vehicle sales, dealer management, customer engagement, test drives, and order processing on one cloud platform.

## Problem Statement
Traditional automotive businesses manage dealers, customers, inventory, and orders across disconnected systems. This causes delayed order processing, poor stock visibility, and a weak customer experience. This project centralizes everything in Salesforce and automates the repetitive work.

## Key Features
- **Vehicle & Inventory Management**: track models, variants, pricing, and stock levels
- **Dealer Management**: maintain dealer records and link them to orders
- **Customer Management**: store customer details and purchase history
- **Test Drive Booking**: schedule test drives with automated confirmation and reminders
- **Order Management**: place and track vehicle orders from Pending to Confirmed
- **Automation**: Flows, Apex Triggers, and Batch Apex to cut manual work
- **Email Alerts**: automatic notifications for order and test drive updates
- **Reports & Dashboards**: real-time sales and inventory insights

## Data Model (Custom Objects)
| Object | Purpose |
|---|---|
| Vehicle | Stores vehicle model, type, price, and stock |
| Vehicle Dealer | Dealer details and location |
| Vehicle Customer | Customer information |
| Vehicle Order | Orders linked to customer, dealer, and vehicle |
| Vehicle Test Drive | Test drive bookings and status |

## Tech Stack
- Salesforce Platform (Lightning Experience)
- Apex (Triggers, Batch Apex, Scheduled Apex)
- Salesforce Flows (Record-Triggered, Scheduled)
- Lightning App Builder
- Reports & Dashboards
- Email Templates & Alerts
- Profiles, Roles, and Permission Sets

## Automation Overview
- **Record-Triggered Flow**: sends a confirmation email when a test drive is booked
- **Apex Trigger**: updates vehicle stock when an order is placed
- **Batch Apex**: processes pending orders and confirms them if stock is available
- **Scheduled Flow**: sends test drive reminders before the booking date

## Project Structure
```
WhatNext-Vision-Motors/
├── force-app/main/default/
│   ├── classes/        # Apex classes & batch jobs
│   ├── triggers/       # Apex triggers
│   ├── objects/        # Custom objects & fields
│   ├── flows/          # Flow definitions
│   └── lwc/            # Lightning Web Components (if any)
└── README.md
```

## Getting Started

### Prerequisites
- A Salesforce Developer Org ([sign up free](https://developer.salesforce.com/signup))
- Salesforce CLI and VS Code with Salesforce Extension Pack (optional)

## Usage
1. Open the **WhatNext Vision Motors** app from the App Launcher
2. Add vehicles, dealers, and customers
3. Create a Vehicle Order or book a Test Drive
4. Check the dashboards for sales and inventory insights

## Future Enhancements
- Customer portal using Experience Cloud
- AI-based vehicle recommendations with Einstein
- Service and maintenance request tracking
- Mobile app support

## Author
**Mariselvan M**
