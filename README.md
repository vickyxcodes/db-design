# 📚 Database Design Assignments

This repository contains a collection of ER diagram assignments focused on designing real-world systems. Each assignment explores a different domain and helps build strong database design fundamentals.

---

## 📌 Assignments Included

### 1. 📸 Instagram Thrift Creator Store  
Design of a platform where thrift sellers manage products, orders, and customers through an Instagram-style business setup.

<details>
<summary>📄 View Project README</summary>

# 📸 Instagram Thrift Creator Store

## Overview  
ER diagram for a thrift store system where creators sell products via social platforms.

## Core Entities  
- Users (sellers & buyers)  
- Products  
- Orders  
- Payments  

## Key Points  
- One seller → many products  
- One buyer → many orders  
- Orders handle product purchases  
- Payments linked to orders  

## Summary  
Simple commerce-based design focused on product listings and order flow.

</details>

---

### 2. 🏋️ Fitness Influencer Coaching Platform  
Design of an online coaching system where trainers manage clients, sell plans, schedule sessions, and track progress.

<details>
<summary>📄 View Project README</summary>

# 🏋️ Fitness Influencer Coaching Platform

## Overview  
ER diagram for a coaching platform where trainers manage clients and provide structured fitness services.

## Core Entities  
- Users (trainers & clients)  
- Plans (diet/workout)  
- Subscriptions  
- Sessions  
- Progress  
- Payments  

## Key Points  
- Trainer → many clients  
- Client ↔ plans via subscriptions  
- Sessions for consultations  
- Progress stored separately  
- Payments tied to subscriptions  

## Summary  
Structured design supporting subscriptions, tracking, and coaching workflows.

</details>

---

### 3. 🏥 Clinic Appointment and Diagnostics Platform  
Design of a system where clinics manage doctors, patients, appointments, consultations, tests, and reports.

<details>
<summary>📄 View Project README</summary>

# 🏥 Clinic Appointment and Diagnostics Platform

## Overview  
ER diagram for a clinic system handling appointments, consultations, diagnostics, and reports.

## Core Entities  
- Patients  
- Doctors  
- Appointments  
- Consultations / Visits  
- Diagnostic Tests  
- Reports  
- Payments  

## Key Points  
- One patient → many appointments/visits  
- One doctor → many patients  
- Appointment may or may not lead to consultation  
- One consultation → multiple tests  
- Reports linked to tests and visits  
- Payments tied to appointments or consultations  

## Summary  
Clean and practical design covering the full clinic flow from booking to diagnosis and reporting.

</details>

---

### 4. 🚗 Comic-Con Parking System  
Design of a multi-zone parking system for a large event with vehicle tracking, spot allocation, sessions, and payments.

<details>
<summary>📄 View Project README</summary>

# 🚗 Comic-Con Parking System

## Overview  
ER diagram for an event parking system handling vehicles, parking spots, sessions, and payments across zones and levels.

## Core Entities  
- Vehicles  
- Vehicle Categories  
- Parking Spots  
- Parking Zones / Levels  
- Parking Sessions  
- Tickets  
- Payments  

## Key Points  
- One vehicle → many parking sessions  
- One spot → reused across sessions  
- Sessions store entry & exit time  
- Spots belong to zones/levels  
- Reserved categories (VIP, staff, EV, etc.) supported  
- Payments linked to sessions  

## Summary  
Scalable design for managing high-volume event parking with proper tracking and allocation.

</details>

---

### 5. 🏢 Smart Elevator Control  
Design of a multi-building system that manages elevators, ride requests, assignments, and maintenance tracking.

<details>
<summary>📄 View Project README</summary>

# 🏢 Smart Elevator Control

## Overview  
ER diagram for an intelligent elevator system managing multiple buildings, elevators, requests, and ride logs.

## Core Entities  
- Buildings  
- Floors  
- Elevators  
- Elevator Shafts  
- Floor Requests  
- Ride Assignments / Logs  
- Maintenance Records  

## Key Points  
- One building → many floors & elevators  
- Elevators serve multiple floors  
- Floors can be served by multiple elevators  
- Requests generated from floors  
- Requests assigned to elevators  
- Ride logs track usage history  
- Maintenance stored separately from elevator data  

## Summary  
Structured design for handling real-time elevator operations, tracking, and infrastructure management.

</details>

---

## ✅ Completed Assignments

All assignments in this repository are part of the Web Dev Cohort 2026 database module.

---

## 🎯 Purpose

- Practice ER diagram design  
- Understand real-world data modeling  
- Improve thinking around relationships and structure  

---

## 🚀 Goal

Build clean, practical, and scalable database designs that can be used in real applications.

---

Stay consistent and keep building 🔥
