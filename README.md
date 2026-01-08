# 🛒 ShopCart – Android E-Commerce Application

ShopCart is a modern and scalable **Android e-commerce application** developed using **XML for UI design**, **Kotlin for application logic**, and **Firebase** as the backend service.  
The application focuses on providing a clean user interface, smooth user experience, and real-time data handling suitable for online shopping platforms.

---

## 📖 Project Overview

The goal of ShopCart is to simulate a real-world shopping application where users can browse products, view detailed product information, manage their cart, and see an order summary with calculated pricing.  
The project follows **industry-standard Android development practices**, including **MVVM architecture**, **Firebase integration**, and **separation of concerns**.

This project is ideal for learning and demonstrating:
- Android UI development using XML
- Kotlin-based application logic
- Firebase backend integration
- E-commerce application workflows

---

## ✨ Key Features

### 🔹 User Interface
- Attractive onboarding screen
- Home screen with featured products and recommendations
- Product detail screen with:
  - Product images
  - Color selection
  - Size selection
  - Quantity increment/decrement
- Cart and order summary screen
- Clean and modern UI inspired by real e-commerce apps

### 🔹 Shopping & Cart Management
- Add products to cart
- Update product quantity
- Automatic calculation of:
  - Subtotal
  - Delivery charges
  - Tax
  - Total payable amount

### 🔹 Backend (Firebase)
- Firebase Authentication for user management
- Firebase Firestore / Realtime Database for storing:
  - Product data
  - Cart data
  - User-related information
- Real-time data synchronization

---

## 📱 App Screenshots

> Screenshots are stored in the `screenshots/` directory.

### Onboarding Screen
![Onboarding](screenshots/onboarding.png)

### Home Screen
![Home](screenshots/home.png)

### Product Details Screen
![Product Details](screenshots/product_details.png)

### Order Details / Cart Screen
![Order Details](screenshots/order_details.png)

---

## 🛠 Technology Stack

### 🔹 Frontend
- **Language:** Kotlin
- **UI Design:** XML
  - ConstraintLayout
  - RecyclerView
  - Material Design Components

### 🔹 Architecture
- **MVVM (Model-View-ViewModel)**
- ViewModel for business logic
- LiveData / State handling
- Clear separation between UI and data layers

### 🔹 Backend
- **Firebase**
  - Firebase Authentication
  - Firebase Firestore / Realtime Database

### 🔹 Build System
- Gradle with Kotlin DSL (`.kts`)

---

