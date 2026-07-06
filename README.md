# Week 1 – Understanding the Business Problem
### E-Commerce Order Management Database System

## 📌 Project Overview
This repository contains the Week 1 deliverables for the semester-long **E-Commerce Order Management Database System** project. The goal of Week 1 is to analyze the business requirements of the system and prepare the foundational documentation before database design (ER modeling, normalization, and SQL implementation) begins in later weeks.

## 🎯 Objective
Analyze the business operations of an e-commerce order management platform, identify its business requirements, and prepare a Software Requirement Specification (SRS) that will serve as the foundation for the database design.

## 🏢 Business Scenario
A rapidly growing e-commerce company needs a centralized database to manage customer registration, product management, inventory tracking, order processing, payment management, shipment tracking, and customer reviews — while reducing data redundancy and enabling meaningful business reporting.

## 🧩 Core Entities
The project uses **nine mandatory core entities** (no entities/attributes may be added, removed, or renamed):

| Entity | Key Attributes |
|---|---|
| Customer | Customer ID, Name, Email, Mobile Number, Address, Registration Date |
| Category | Category ID, Category Name, Description |
| Product | Product ID, Product Name, Price, Stock Quantity, Category ID |
| Supplier | Supplier ID, Supplier Name, Contact Information |
| Order | Order ID, Customer ID, Order Date, Total Amount, Order Status |
| Order Details | Order Detail ID, Order ID, Product ID, Quantity, Unit Price |
| Payment | Payment ID, Order ID, Payment Method, Payment Date, Payment Status |
| Shipment | Shipment ID, Order ID, Delivery Address, Shipment Date, Delivery Status |
| Review | Review ID, Customer ID, Product ID, Rating, Comments |

## 📂 Repository Structure
```
Week1/
│── Requirement_Analysis_Report.pdf      # Entity purposes, business processes, analysis approach
│── Business_Requirement_Document.pdf    # Stakeholders, functional & non-functional requirements, scope, assumptions/constraints
│── SRS_Document.pdf                     # Formal Software Requirement Specification
│── README.md                            # This file
```

## ✅ Week 1 Activities Completed
- [x] Studied and analyzed the business scenario
- [x] Explained the purpose of each core entity
- [x] Identified the major business processes
- [x] Identified stakeholders and their roles
- [x] Listed functional requirements
- [x] Listed non-functional requirements
- [x] Defined project scope
- [x] Identified assumptions and constraints
- [x] Prepared the SRS document

## 📄 Deliverables
1. **Requirement Analysis Report** – business scenario, entity purposes, business processes.
2. **Business Requirement Document** – stakeholder analysis, functional/non-functional requirements, scope, assumptions & constraints.
3. **Software Requirement Specification (SRS)** – formal consolidated specification for database design.
4. **README.md** – project summary (this file).

## 🚀 Next Steps
Week 2 onward: ER diagram design, normalization (up to 3NF/BCNF), schema creation, SQL implementation, and report generation — all built strictly on the entities defined above.

## 👤 Author
Name: S.Kartheeswar
