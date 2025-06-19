
# Singleton Pattern in C#

This project demonstrates the **Singleton Design Pattern** in C#, using a simple `Logger` class.

## 🔍 Problem Scenario

In many real-world applications, you often need only one instance of a class to coordinate actions across the system. For example, a logging utility should use the same logger object globally for consistent logging behavior. The Singleton pattern ensures that only one instance of the class is created and provides a global access point to it.

---

## 🏗️ Project Structure

- `Logger.cs` — Contains the singleton `Logger` class.
- `Program.cs` — Demonstrates how multiple calls to `Logger.GetInstance()` return the same object.

---

## 📂 How It Works

- `Logger` is a class with:
  - A **private static field** `instance` holding the single object.
  - A **private constructor** to prevent external instantiation.
  - A **public static method** `GetInstance()` to control object creation and return the same instance every time.

---


