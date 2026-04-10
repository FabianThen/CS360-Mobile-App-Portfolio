# CS 360 Mobile Architecture and Programming
## Jose Fabian | Southern New Hampshire University

---

## Course Overview
This repository contains all projects and assignments completed in CS 360 Mobile Architecture and Programming. The course covered mobile application development principles, user-centered UI design, and the full development lifecycle of an Android application.

---

## Projects

### Project One Milestone — App Selection and Research
Selected the Weight-Tracking App as the development project for the course. Completed preliminary research on the app's goals, user types, and competitive landscape.

### Project One — App Development Proposal
Created a full app development proposal for the Weight-Tracking App including:
- App goals and major components
- Three identified user types (weight-loss, maintenance, muscle-gain)
- Screen flow diagram and UI design description
- Code design and data flow table

### Project Two — App UI Design
Built the complete UI for the Weight-Tracking App in Android Studio using XML layout files. Screens created:
- Login / Register Screen
- Dashboard Screen (with progress bar, weight grid, bottom navigation)
- Add Weight Screen
- Set Goal Weight Screen (with SMS permission section)
- Stats Screen
- Profile Screen

### Project Three — Fully Functional App
Developed all Java code to make the app fully functional. Features implemented:
- SQLite database with three tables (users, daily_weights, goal_weight)
- Full login and account creation functionality
- CRUD operations (Create, Read, Update, Delete) for weight entries
- SMS permission request and goal reached notification
- Navigation between all screens with data passing via Intents

---

## Module Assignments

### Module Three — Android Studio Layout Editor
Created a simple Android Studio project with No Activity, built a layout with a Button, TextView, and EditText, and configured IDs and attributes using the Layout Editor.

### Module Four — Mobile App UI Redesign
Redesigned the Weight-Tracking App Dashboard screen with new features including a progress ring card, color-coded weight history, a 7-day trend chart, a Stats screen, and a bottom navigation bar. Justified all design decisions using Android Material Design 3 guidelines.

### Module Five — Android Studio Coding
Added Java functionality to the Module Three layout including a SayHello() function, input validation, and dynamic button enable/disable logic using a TextWatcher.

### Module Six — SensorManager
Built a separate SensorApp that uses SensorManager to read real-time accelerometer data (X, Y, Z values) from the Android Emulator. Tested using virtual sensor controls and debugger breakpoints.

---

## App Reflection

### App Summary
The Weight Tracker app helps users log their daily weight, set a personal goal weight, and receive an SMS notification when they reach that goal. It was designed for three user types: weight-loss users, maintenance users, and muscle-gain users.

### UI Design Decisions
Every screen was designed with the user in mind. The bottom navigation bar provides consistent and predictable navigation. The progress bar on the dashboard surfaces the most important information immediately. The color scheme (blue #2E75B6 and green #70AD47) was used consistently across all screens to create a cohesive visual identity.

### Coding Approach
Development followed a bottom-up approach — the DatabaseHelper class was built first to establish a solid data foundation before any UI logic was written. This separation of concerns kept each Activity class focused and readable.

### Testing
The app was tested continuously using the Android Emulator after each screen was completed. Both outcomes of the SMS permission request were tested. Debugger breakpoints were used in the SensorManager assignment to inspect live sensor values.

### Greatest Success
The DatabaseHelper class was the most successful component of the project. It supports all four CRUD operations across three tables, handles edge cases like duplicate usernames and existing goal weights, and maintains persistent data across sessions.

---

## Technologies Used
- Android Studio (Java)
- SQLite Database
- ConstraintLayout / LinearLayout
- RecyclerView with custom Adapter
- SensorManager (Accelerometer)
- SMS Manager
- Android Emulator (API 36.1)
