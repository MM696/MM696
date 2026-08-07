# Hi, I'm MacAnthony 👋

**Software Engineer (Web & Mobile)** focused on building scalable, production-ready applications — from intuitive frontend experiences to robust backend systems.

I specialize in translating product requirements into clean, maintainable architectures, delivering high-performance user interfaces, and developing reliable APIs that power real-world applications.

---

## 🛠 Tech Stack

### **Frontend (Web)**

* React, TypeScript, Next.js, Vue, Angular, Vite
* Tailwind CSS, Responsive & Mobile-First Design

### **Mobile**

* React Native (Expo)
* TypeScript
* React Navigation

### **Backend**

* Laravel, Node.js, Express, NestJS, AdonisJS
* REST APIs, Authentication & Authorization
* PostgreSQL, Supabase Redis, BullMQ, Docker

### **State, Data & Tools**

* Redux Toolkit, Axios
* Git, GitHub, Figma
* Deployment: Render, Vercel

---

## 🚀 Featured Projects

### 🐦 Chirp — Social Media Platform

A Twitter-like full-stack monorepo with a user app, admin moderation dashboard, and gRPC API — auth, feeds, follows, bookmarks, notifications, and content moderation.

* **Tech Stack:** Turborepo, pnpm, TanStack Start, React 19, TypeScript, gRPC, StyleX, SQLite (Drizzle), Vitest, Playwright, Biome, GitHub Actions

* **Key Contributions:**

  * Built a monorepo with separate user and admin clients plus a typed gRPC API
  * Implemented secure auth (bcrypt password hashing, API-issued session JWTs)
  * Optimized feed/bookmarks queries with batch loading to avoid N+1 database load
  * Added unified API error handling, request tracing, and structured logging
  * Set up CI (lint, typecheck, unit tests, affected builds) and pre-commit hooks

* **Repository:** https://github.com/MM696/A-full-stack-social-platform

---

## 🏫 School Payment & Transaction System (Laravel)

A fintech-style backend application built with Laravel, handling secure payments, transaction tracking, and audit logging.

* **Tech Stack:** Laravel, MySQL, Redis, Sanctum
* **Key Contributions:**

  * Developed secure RESTful APIs for payments and transaction management
  * Implemented idempotent payment processing to prevent duplicate charges
  * Built offline transaction handling to support network interruptions
  * Designed audit logging to track all transaction status changes
  * Integrated Paystack payment gateway with webhook handling
* **Repository:** https://github.com/MM696/My-Laravel-Project

---

### 🔗 Ezrah Webhook Relay (Fintech)

A production-oriented webhook relay system that ingests events via REST API, fans out to subscriber endpoints, and delivers signed HTTP payloads with retries, rate limiting, and observability.

* **Tech Stack:** AdonisJS 7, TypeScript, Vue 3, Vite, PostgreSQL, Redis, BullMQ, Docker

* **Key Contributions:**

  * Built REST APIs for endpoint registration, event ingestion, delivery monitoring, and metrics
  * Implemented asynchronous delivery with BullMQ workers and HTTP-aware retry backoff (5xx, 429, network errors)
  * Secured webhook payloads with HMAC-SHA256 signatures and encrypted endpoint secrets at rest (AES-256-GCM)
  * Designed at-least-once delivery semantics with `X-Ezrah-Delivery-Id` for subscriber deduplication
  * Added per-endpoint rate limiting, structured logging (Pino), and a Vue dashboard for endpoints, events, and deliveries
  * Containerized API, worker, PostgreSQL, and Redis with Docker Compose for production-like local runs
  * Wrote unit and functional tests with CI via GitHub Actions

* **Repository:** https://github.com/MM696/Fintech-Webhook-Relay

---
### 🚗 Car Rental Booking System

A full-stack platform for browsing, booking, and managing vehicle rentals.

* **Tech Stack:** React, TypeScript, Tailwind CSS, Node.js, Express

* **Key Contributions:**

  * Developed responsive UI for listings, search, and booking workflows
  * Designed and implemented backend APIs for vehicles, bookings, and users
  * Built authentication and protected route systems
  * Integrated frontend with live backend services and managed API state

* **Repository:** https://github.com/MM696/CarRental

* **Live Demo:** https://carrental-w1sy.onrender.com/

---

### 🤝 Cooperative Management System

A full-stack system for managing cooperative members, contributions, and administration.

* **Tech Stack:** Next.js 14, Tailwind CSS, Supabase, PostgreSQL

* **Key Contributions:**

  * Built dashboards, tables, and form-driven workflows
  * Integrated Supabase for authentication and real-time data handling
  * Designed relational data models for members and contributions
  * Implemented role-based access control for admins and users

* **Repository:** https://github.com/MM696/cooperative_website

* **Live Demo:** https://cooperative-website.vercel.app/

---

### 💜 Heartcord Landing Page

A cinematic marketing landing page for Heartcord, an AI developer workspace — full-bleed hero, animated network visuals, product sections, pricing, and FAQ.

* **Tech Stack:** Angular 19, TypeScript, SCSS

* **Key Contributions:**

  * Built a component-based Angular landing page (hero, features, tools, pricing, FAQ)
  * Designed a dark, high-impact visual system with custom SCSS and motion
  * Integrated full-bleed imagery with scroll-triggered and looping CSS animations
  * Structured reusable section components for a maintainable marketing site layout

* **Repository:** https://github.com/MM696/HEARTCORD-landing-page

* **Live Demo:** https://heartcord-landing-page.onrender.com/
  
---

### 🏥 InspectCare

A healthcare management platform for symptom tracking, medication management, and appointment scheduling.

* **Tech Stack:** React, Redux Toolkit, Tailwind CSS, Node.js

* **Key Contributions:**

  * Developed mobile-first dashboards and healthcare workflows
  * Managed complex global state using Redux Toolkit
  * Integrated backend APIs for appointments and emergency services
  * Optimized performance and API data handling

* **Repository:** https://github.com/MM696/inspectcare

* **Live Demo:** https://inspectcare-p1i7.onrender.com/

---

### 💳 Transaction App (React Native – Expo)

A FinTech-style mobile application showcasing scalable frontend architecture and structured state management.

* **Tech Stack:** React Native (Expo), TypeScript, Redux Toolkit, React Navigation

* **Key Contributions:**

  * Built transaction list with search, filtering, and pull-to-refresh
  * Implemented detailed transaction views with clean UI presentation
  * Developed validated add-transaction workflow with native inputs
  * Designed a dark-themed, responsive UI optimized for readability

* **Repository:** https://github.com/MM696/Expense-Tracker-Mini-App

---

## 📸 Screenshots

![List Screen](https://raw.githubusercontent.com/MM696/Expense-Tracker-Mini-App/main/assets/list.png)
![Detail Screen](https://raw.githubusercontent.com/MM696/Expense-Tracker-Mini-App/main/assets/detail.png)
![Add Screen](https://raw.githubusercontent.com/MM696/Expense-Tracker-Mini-App/main/assets/add.png)
![Search Screen](https://raw.githubusercontent.com/MM696/Expense-Tracker-Mini-App/main/assets/search.png)

---

### 📱 Expo Mobile App

A cross-platform mobile application built with Expo, demonstrating scalable mobile architecture and efficient development workflows.

* **Tech Stack:** React Native (Expo), TypeScript
* **Key Features:**

  * File-based routing for structured navigation
  * Cross-platform support (Android, iOS, Web)
  * Fast development workflow using Expo CLI
  * Clean and modular project structure
* **Getting Started:**

  ```bash
  npm install
  npx expo start
  ```
* **Repository:** https://github.com/MM696/Mobile-app-using-Expo

---

## 💡 Core Strengths

* Building end-to-end applications (frontend → backend → database)
* Designing scalable and maintainable system architectures
* Developing reusable UI components and modular backend services
* Translating business requirements into production-ready solutions

---

## 📫 Contact

* GitHub: https://github.com/MM696
* LinkedIn: https://www.linkedin.com/in/macanthony-eze-6aba23345
* Portfolio: https://mcanthonys-portfolio-u7ks.onrender.com/

---
