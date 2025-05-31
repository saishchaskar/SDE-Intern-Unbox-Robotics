# 🧪 PCB Testing Tool & UART Integration – Internship Project

This repository contains the source code and project details of a 6-month fullstack software development internship at **Unbox Robotics**. The primary focus was on developing an **automated PCB Testing Tool** and implementing **UART communication in C++** for real-time sensor data integration.

---

## 📌 Overview

### 🚀 Company: Unbox Robotics
Unbox Robotics is a leading automation machinery manufacturing company specializing in robotics-based fulfillment solutions for e-commerce, retail, and logistics enterprises.

### 👨‍💻 Intern: Saish Chaskar  
**Internship Period:** Jan 15, 2025 – July 15, 2025  
**Role:** Fullstack Software Development Intern

---

## 📂 Projects Undertaken

### 1. 🔧 PCB Testing Tool

A browser-based tool to automate the testing process of Printed Circuit Boards (PCBs) across different robot versions.

- **Frontend:** React (Vite.js)
- **Backend:** FastAPI (Python)
- **Middleware:** C++ (Serial Communication)
- **Communication Protocol:** WebSocket
- **Database:** PostgreSQL
- **Architecture:** MVC

#### ✅ Key Features:
- Real-time serial data visualization
- CSV report generation
- Modular test case handling
- Seamless PCB version scaling
- WebSocket integration for live communication with embedded systems

#### 🧪 Outcome:
- Testing time reduced from **2-3 hours to ~5 minutes**
- Enhanced production efficiency and UI/UX consistency

---

### 2. 🧬 UART Integration in C++

Implemented UART communication on an **Intel Atom Up Squared 2 processor** to integrate a PDS sensor while minimizing USB port usage.

#### ✅ Key Features:
- Reads 824 bytes every 43 ms
- Maintains CPU usage below 1.5%
- Reliable packet handling and error resolution
- CSV-based data logging

#### 🧪 Outcome:
- Real-time sensor data processing with minimal overhead
- Seamless sensor integration into robotic platforms

---

## 🛠️ Skills Developed

- Fullstack development (React, FastAPI, PostgreSQL)
- WebSocket real-time data flow
- Embedded systems & UART protocols
- C++ for middleware and serial data processing
- Testing automation and performance optimization
- Agile collaboration and stakeholder communication

---

## 📊 Architecture Overview

### 🧱 PCB Testing Tool Stack

```text
React (Vite.js) ↔ WebSocket ↔ FastAPI ↔ WebSocket ↔ C++ Middleware ↔ PCB
                                   ↓
                               PostgreSQL
