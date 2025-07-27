# Camion – MVP Microservices Backend 🚛

This project represents the **Camion MVP** backend system using a **Microservices architecture** powered by [NestJS](https://nestjs.com/). The platform is designed for managing user authentication, product listing, search features (voice, image, QR), real-time notifications, payments, and much more—following scalable and modular microservices patterns.

---

![Camion Architecture](/Camion.png)

---

## 📜 Table of Contents

- [Overview](#overview)
- [MVP Features](#mvp-features)
- [Microservices Structure](#microservices-structure)
  - [User Service](#user-service)
  - [Product Service](#product-service)
  - [Backend Gateway](#backend-gateway)
  - [Notification Service](#notification-service)
  - [Payment Service](#payment-service)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Video Explanation](#video-explanation)
- [License](#license)

---

## 📝 Overview

Camion is a logistics & transport management platform aiming to simplify product discovery, customer engagement, and operational scalability. This MVP implements core modules using NestJS and microservices to ensure that each part of the system is loosely coupled and can scale independently.

---

## 🚀 MVP Features

![Camion Architecture](/board.png)

### ✅ Authentication

- Phone authentication (OTP via SMS)
- Social logins: Google, Facebook, Apple

### ✅ Search & Filtering

- Keyword search
- QR Code scanner
- Image-based search
- Voice-based search

### ✅ User Features

- Wishlist / Favorites
- Wallet for each user
- Order tracking and cart logic

### ✅ Admin/Manager Features

- Upload story (video link from the manager)
- Add categories with ratings
- View and manage comments per product

### ✅ Product & Category Management

- Pagination for category listing
- Stock / inventory management
- Rating system for each category

### ✅ Partner Onboarding

- Join Us form for suppliers
- Auto-code generation for validation

### ✅ Payments

- Integration with Stripe

### ✅ Notifications

- Push notifications using Firebase Cloud Messaging (FCM)

---

## ⚙️ Microservices Structure

### 🧑‍💼 User Service

Handles:

- User Registration & Login
- OTP SMS Verification
- Profile Management
- Wishlist & Wallet

### 📦 Product Service

Handles:

- Product Creation
- Listing with Pagination
- Ratings, Comments & Inventory

### 🌐 Backend Gateway

Acts as the main API gateway:

- Auth Guard & JWT
- Routes to all internal services

### 🔔 Notification Service

- Push Notifications via FCM
- Real-time communication hooks

### 💳 Payment Service

- Stripe payment integration
- Handles checkout flow

---

## 📦 Installation

### Prerequisites

- Node.js (>=14.x)
- NestJS CLI
- Docker (optional)

### Setup

```bash
git clone https://github.com/kareimakl/CamionAppBackend
cd CamionAppBackend
npm install
```
