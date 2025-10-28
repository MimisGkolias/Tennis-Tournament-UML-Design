# Tennis Tournament Management System - UML Design

[![Live Demo](https://img.shields.io/badge/Live-Demo-green)](https://mimisgkolias.github.io/Tennis-Tournament-UML-Design/)
[![UML](https://img.shields.io/badge/UML-Enterprise%20Architect-blue)](https://sparxsystems.com/)

A comprehensive system design and specification for a **Tennis Tournament Management Software**, developed as part of the Software Engineering course of Warsaw's Polytechnic during my Erasmus semester. This project demonstrates professional UML modeling practices and complete system architecture design using industry-standard tools.

## 🎯 Project Overview

This project presents a full-scale UML model for a tennis tournament management system, covering all aspects from user interactions to system deployment. The design follows software engineering best practices and provides a complete blueprint for developing a real-world tournament management application.

**Key Features Modeled:**
- Tournament creation and management
- Player registration and management  
- Match scheduling and court assignment
- Real-time match tracking and result entry
- Comprehensive user role management (Organizers, Referees, Players)

---

## 🚀 View the Live Project

Experience the interactive UML model through our hosted documentation:

**[🔗 View Live UML Model](https://mimisgkolias.github.io/Tennis-Tournament-UML-Design/)**

---

## 📋 System Features & Use Cases

The system design covers **15 comprehensive use cases** organized by functional areas:

### **🏆 Tournament Management (UC1-UC3)**
- **UC1: Create Tournament** - Initialize new tournaments with parameters
- **UC2: Manage Tournament Info** - Update tournament details and settings
- **UC3: Manage Player Applications** - Handle player registration requests

### **👥 Player Registration & Management (UC4-UC6)**  
- **UC4: Register as Player** - New user registration in the system
- **UC5: Register for Tournament** - Player enrollment in specific tournaments
- **UC6: Withdraw from Tournament** - Handle player withdrawals and substitutions

### **🎯 Match Organization & Scheduling (UC7-UC8)**
- **UC7: Generate Match Draw** - Create tournament brackets and pairings
- **UC8: Assign Court and Match Times** - Schedule matches with court assignments

### **⚡ Match Execution & Results (UC9-UC13)**
- **UC9: Enter Match Result** - Record match outcomes and scores
- **UC10: User is logged in** - Authentication and session management
- **UC11: Notify players and users** - Communication and alert system
- **UC12: Update Player Rankings** - Automatic ranking calculations
- **UC13: Show detailed statistics of the match** - Comprehensive match analytics

### **📊 Information Access & Reporting (UC14-UC15)**
- **UC14: View Tournament Schedule** - Display tournament timeline and matches
- **UC15: View Results and Rankings** - Tournament standings and player statistics

---

## 🛠️ Technical Specifications

- **Modeling Tool:** Sparx Systems Enterprise Architect
- **UML Version:** 2.5
- **Documentation Format:** Interactive HTML with navigation
- **Export Formats:** HTML, Images (PNG), Enterprise Architect Project Files
- **Methodology:** Object-Oriented Analysis and Design (OOAD)

---

## 💻 Project Contents

This comprehensive model includes **280+ detailed UML diagrams** across multiple categories:

### **Behavioral Diagrams**
*   **Use Case Diagrams:** Complete actor-system interaction modeling
    - UC1: Create Tournament
    - UC2: Manage Tournament Info
    - UC3: Manage Player Applications
    - UC4: Register as Player
    - UC5: Register for Tournament
    - UC6: Withdraw from Tournament
    - UC7: Generate Match Draw
    - UC8: Assign Court and Match Times
    - UC9: Enter Match Result
    - UC10: User is logged in
    - UC11: Notify players and users
    - UC12: Update Player Rankings
    - UC13: Show detailed statistics of the match
    - UC14: View Tournament Schedule
    - UC15: View Results and Rankings

*   **Activity Diagrams:** Detailed workflow processes
    - Tournament creation and management workflow
    - Player registration and application process
    - Match draw generation and scheduling
    - Match execution and result entry lifecycle
    - User authentication and notification flows

*   **State Machine Diagrams:** System state transitions
    - Match state machine (Created → In Progress → Paused → Completed/Cancelled)
    - Tournament lifecycle management (Open → Registration → Draw → In Progress → Completed)
    - Player registration and withdrawal states
    - User authentication and session management states

*   **Sequence Diagrams:** Inter-object communication patterns
    - Tournament creation and management sequences
    - Player registration and application processing
    - Match draw generation and court assignment
    - Match result entry and ranking updates
    - Notification and communication workflows
    - Statistics generation and reporting interactions

### **Structural Diagrams**  
*   **Class Diagrams:** Complete system class hierarchy and relationships
    - Core domain classes (Tournament, Player, Match, Court, Referee)
    - User management classes (Organizer, Participant, Administrator)
    - Business logic components (Ranking System, Notification Service)
    - Data management and persistence layers

*   **Component Diagrams:** System modularity and component interactions
    - Tournament management module
    - Player registration and management component
    - Match scheduling and court assignment system
    - Result processing and ranking calculation component
    - User authentication and notification services
    - Statistics and reporting module

*   **Deployment Diagrams:** Physical system architecture and deployment strategy
    - Client-server architecture
    - Database deployment configuration
    - System integration points

### **Implementation Details**
*   **Package Diagrams:** System organization and modular structure
*   **Object Diagrams:** Runtime object relationships and configurations

---

## 🔧 Viewing the Project Locally

For offline exploration or detailed analysis:

1. **Download Repository**
   ```bash
   git clone https://github.com/MimisGkolias/Tennis-Tournament-UML-Design.git
   ```

2. **Open Local Documentation**
   - Navigate to the downloaded folder
   - Open `index.htm` in any modern web browser
   - Use the navigation panel to explore all diagrams and documentation

3. **Enterprise Architect Integration**
   - EA project files included for full editing capability
   - Requires Sparx Systems Enterprise Architect license
