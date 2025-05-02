# Shareholder Online Voting System

## Overview

A secure, modern, and intuitive **online voting system** for shareholders, built using **Flutter** and **Dart**. Designed for seamless and authenticated remote participation in shareholder meetings, this system features elegant animations, real-time verification, and a multi-layered authentication process, ensuring both **integrity** and **ease of use**.

---

## Features

### 🎯 Purpose-Built for Shareholder Voting

- Remote voting for shareholder meetings.
- Intuitive and accessible interface across devices.
- Live status updates for each voting session.

---

### 🧠 State Management with BLoC

- Uses the **BLoC (Business Logic Component)** pattern for state management.
- Separates business logic from UI for better **scalability** and **testability**.
- Ensures **consistent state updates**, **robust error handling**, and **clean architecture** across the entire app.
- Makes the app easier to maintain and extend — perfect for large-scale enterprise voting workflows.

---

### 🔐 Multi-Phase Authentication

- Ensures each vote is cast by the **correct verified shareholder** using a layered approach:
  - **Username & Password** login.
  - **EKYC Verification**:
    - Live **video capture** of the user.
    - Upload and OCR scan of **National ID**.
    - **Face comparison** between live video and ID photo using facial recognition.
  - Real-time validation and feedback on user identity before allowing voting access.

---

### 🎥 Video Demo

> Watch the system in action through a full demo walkthrough:

https://github.com/user-attachments/assets/54fe6396-111f-4f59-b90f-f52d6df4c95e

---

### 💡 UI & UX Highlights

- **Fluid Animations** across all screens and transitions.
- **Clean Material Design** for ease of navigation.
- Responsive layouts for **mobile**, **tablet**, and **web** support.
- User-centric flow ensures non-technical users can complete the process confidently.

---
### 🌐 Multi-language Support

- Supports **three languages** with dynamic localization.
- Automatically adapts content based on user language settings.

### 🌙 Theme Support

- Toggle between **Light** and **Dark** themes.
- Consistent and responsive styling for all components.
  
## Tech Stack

- **Frontend**: Flutter, Dart
- **State Management**: BLoC
- **Authentication**: EKYC, Face Recognition, National ID OCR
- **Backend**: .NET Core and Pyhton for image processing
- **Video & Image Processing**: Integrated with live camera input and face matching logic

