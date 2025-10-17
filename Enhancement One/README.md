# Enhancement One: Software Design and Engineering

## 📌 Overview

This enhancement reflects the transformation of a legacy Java-based inventory app into a modern, modular Kotlin application. It demonstrates my growth in software engineering, cloud integration, and maintainable architecture. The refactor focused on decomposing monolithic logic, centralizing input validation, and integrating Firebase Authentication and Firestore for secure, real-time data management.

---

## 🔧 Key Enhancements

- Migrated codebase from Java to Kotlin for improved readability and null safety
- Centralized input validation using a reusable `InputValidator` object
- Integrated Firebase Authentication for secure user registration and login
- Connected Firestore for real-time inventory storage and updates
- Added item-level editing and deletion with UI sync and async listeners
- Improved testability using modular design and coroutine support

---

## 🧠 Skills Demonstrated

- Modular architecture and separation of concerns  
- Cloud service integration (Firebase Auth + Firestore)  
- Asynchronous programming with coroutines  
- Input validation and error handling  
- UI synchronization and lifecycle-aware design

---

## 🎓 Course Outcomes Met

- Applied software engineering principles to refactor and modularize code  
- Designed scalable systems using cloud-based services  
- Communicated technical decisions through clean, maintainable code

---

## 📸 Code Snippet

The following screenshot shows the centralized input validation logic used across authentication and item management flows:

![InputValidator Kotlin Code Screenshot](../Snippet1.png)

This object-oriented approach promotes consistency, simplifies unit testing, and supports future enhancements like password strength indicators or localized error messages.

---

## 🔗 Related Files

- `InputValidator.kt` — reusable validation logic  
- `FirebaseRepository.kt` — handles authentication and Firestore operations  
- `MainActivity.kt` — orchestrates navigation and UI state  
- `ComposableScreens/` — modular UI components for login, registration, and inventory

---

## ✅ Why It Matters

This enhancement lays the foundation for a scalable, testable mobile app architecture. It demonstrates my ability to refactor legacy code, integrate cloud services, and enforce consistent validation across the application, all while aligning with professional software engineering standards.
