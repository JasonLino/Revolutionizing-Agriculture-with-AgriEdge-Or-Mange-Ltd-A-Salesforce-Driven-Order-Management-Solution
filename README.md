# Revolutionizing Agriculture with AgriEdge Or-Mange Ltd

### A Salesforce-Driven Order Management System (OMS)

This project introduces a Salesforce-based Order Management System (OMS) built for AgriEdge Or-Mange Ltd, a company in the agriculture and food production industry. The system transforms traditional manual workflows into a modern, automated, and data-driven solution for managing orders, products, and shipments.

---
Demo Link: https://drive.google.com/file/d/1LgdU_NwxxI09nG2cg3x_1ZBLPSrkmavy/view?usp=drive_link
---

## Project Overview

AgriEdge Or-Mange Ltd deals with a wide range of agricultural products — from seeds and fertilizers to harvested crops and processed goods. Before automation, the company struggled with:

- Manual order entry errors
- Delayed updates and order processing
- Lack of real-time visibility in inventory and shipment tracking
- Disconnected customer service channels

To solve these issues, the project leverages Salesforce CRM to create a centralized and intelligent OMS that improves order tracking, inventory accuracy, and customer satisfaction.

---

## Key Features

- Automated Order Lifecycle – From creation to delivery tracking
- Dynamic Price and Status Updates using Apex logic
- Real-Time Inventory Monitoring through related records
- Email Notifications and Task Automation via Flows and Process Builder
- Role-Based Access Control for Admin, Manager, and Agent
- Reports and Dashboards for performance insights
- Scalable Architecture ready for shipment and customer portal integration

---

## Technologies Used

- Salesforce CRM (Developer Edition)
- Apex Programming: Classes, Triggers, Test Classes
- Flow Automation and Process Builder
- Validation Rules and Formula Fields
- Profiles, Roles, and Permission Sets
- Reports and Dashboards Builder (Lightning)

---

## Data Model

### Custom Objects

| Object Name             | Description                          | Key Fields                                               |
| ----------------------- | ------------------------------------ | -------------------------------------------------------- |
| AgriEdge_Order\_\_c     | Stores order information             | Order Date, Total Amount, Status, Payment Status         |
| AgriEdge_OrderItem\_\_c | Represents individual order products | Product Name, Quantity, Unit Price, Subtotal             |
| AgriEdge_Shipment\_\_c  | Tracks delivery details              | Shipment Date, Carrier, Tracking Number, Delivery Status |

### Standard Objects Used

- Account – Customer information
- User – Salesforce user roles (Admin, Sales Rep, Manager)

---

## Automation Highlights

### Apex Logic

- Trigger to auto-update Order Total when Order Items are created or modified.
- Apex Class for handling business rules such as payment validation and shipment creation.

### Flow and Process Builder

- Record-triggered Flows to send email notifications when orders are shipped.
- Auto-create follow-up tasks for agents when new orders are placed.

### Validation Rules

- Prevent negative quantities or missing shipment data.
- Ensure Delivery Date is later than Order Date for valid records.

---

## Reports and Dashboards

- Order Summary Report – View total orders and revenue by status.
- Top Products Report – Identify best-selling agricultural products.
- OMS Dashboard – Visual overview of orders, shipments, and agent performance.

---

## Security Configuration

- Role Hierarchy: Admin → Manager → Agent
- Profiles: Define CRUD access for each user type
- Field-Level Security: Protect sensitive financial and customer data
- Sharing Rules: Control visibility across regional teams

---

## Future Enhancements

- Integration with logistics APIs for real-time shipment tracking
- Mobile App access for field agents
- Automated invoice generation
- WhatsApp or SMS notifications for order updates
- AI-driven forecasting using Salesforce Einstein
- Multilingual support for global and rural users

---

## Author and Learning Outcomes

This project demonstrates practical knowledge in:

- Salesforce Data Modeling
- Process Automation using Flow and Apex
- User and Security Management
- Report and Dashboard Creation
- Change Set Deployment and Testing

---

**Project by:** Jason Lino
---
**Platform:** Salesforce Developer Edition
---
**Course:** Salesforce Capstone Project — Revolutionizing Agriculture with AgriEdge Or-Mange Ltd
