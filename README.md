🏠 Smart Home Automation System (Java)

A Java Swing–based Smart Home Automation System implementing role-based access control, device automation, and scheduling using Object-Oriented Programming principles.

🚀 Project Highlights

Role-based authentication (Admin / User)

GUI-driven device control using Java Swing

Automation & scheduling for smart devices

Modular, extensible OOP design

Real-world simulation of smart home functionality

✨ Features
🔐 Authentication & Authorization

Secure login for all users

Admin

Add/remove users

Add/remove devices

View system & security logs

Regular User

Control devices

Create and manage schedules

Restricted from admin operations

💡 Supported Devices

Light

On/Off control

Brightness adjustment

Motion-activated lighting

Color selection (White, Warm White, Blue, Red)

Fan

On/Off control

Speed levels (1–5)

Air Conditioner

Temperature control (16–30°C)

Modes: Cool / Heat / Fan / Dry / Auto

Energy-saving mode

Auto temperature adjustment (time-based)

Security System

Arm / Disarm

Home / Away modes

Motion detection

Alarm activation

Security event logs

🤖 Automation & Scheduling

Motion-based automation (e.g., lights)

Time-based automation (daily/weekly)

Device-specific scheduled tasks

Background scheduler executes tasks every minute

🖥️ User Interface

Login screen with authentication

Dashboard showing all devices

Device-specific control panels

Scheduling manager per device

Admin dialogs for user & device management

Permission-aware UI components

🧱 Project Structure
src/
└── com/smarthome/
    ├── SmartHomeApp.java
    ├── gui/
    │   └── SmartHomeGUI.java
    ├── system/
    │   └── SmartHomeSystem.java
    ├── models/
    │   ├── Device.java
    │   ├── Light.java
    │   ├── Fan.java
    │   ├── AirConditioner.java
    │   ├── SecuritySystem.java
    │   ├── ScheduledTask.java
    │   ├── User.java
    │   └── AdminUser.java
    ├── interfaces/
    │   ├── Switchable.java
    │   └── Dimmable.java
    └── exceptions/
        ├── AuthenticationException.java
        └── DeviceNotFoundException.java

🛠️ Tech Stack

Language: Java

GUI: Java Swing

Core Concepts: OOP (Inheritance, Polymorphism, Encapsulation)

Design Patterns: Singleton (System Manager)

Scheduling: Java Timer

Architecture: Modular, MVC-like separation

▶️ How to Run

Clone the repository

git clone <repo-url>


Open the project in any Java IDE (IntelliJ / Eclipse / VS Code)

Ensure JDK 8+ is installed

Run SmartHomeApp.java

Login using default admin credentials (configured in code)

🧪 Example Use Cases

Automatically turn on lights when motion is detected

Schedule AC to turn on at 6 PM on weekdays

Switch security system to Away mode when leaving home

Admin dynamically adds users and devices

🔧 Extensibility

Add new devices by extending the Device abstract class

Plug in new automation rules in SmartHomeSystem

GUI dynamically adapts to new device features

📚 Learning Outcomes

Hands-on application of OOP concepts

Event-driven GUI development

Role-based access control

Real-world automation system design

Scalable and extensible architecture

👥 Team

Group 53 – OOPS Project
