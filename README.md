# Flutter Firebase Authentication App

A production-style Flutter application demonstrating a complete, secure authentication flow using Firebase Authentication.

## Features
* **Secure Registration & Login:** Email and password authentication with validation.
* **Reactive Routing:** Utilizes `StreamBuilder` and `FirebaseAuth.instance.authStateChanges()` to automatically route users to the Profile screen upon login, completely eliminating manual `Navigator.push` state bugs.
* **Profile Management:** Displays the current user's email and provides a secure form to update the account password.
* **Clean Architecture:** Separates Firebase API logic into a dedicated `AuthService` class, keeping the UI widgets focused solely on presentation and validation.

## Tech Stack
* Flutter
* Firebase Authentication (Email/Password Provider)
* Firebase Core