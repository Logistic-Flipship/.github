<p align="center">
  <img width="200" height="200" alt="Flipship Logo" src="https://github.com/user-attachments/assets/4994a64a-5b7d-4263-9db7-b9b110086051" />
</p>

# 🚛 FlipShip — Intercity Cargo Shipping Platform

**FlipShip** is a logistics platform that turns spare seats and cargo space on intercity passenger buses into a fast, affordable, and reliable shipping network. This organization hosts the source code for FlipShip's landing page, web management platform, and mobile application.

---

## 📦 Repositories

| Repository | Description | Stack |
| --- | --- | --- |
| [Logistic-LandingPage](https://github.com/Logistic-Flipship/Logistic-LandingPage) | Public marketing landing page introducing FlipShip's services, with pages for Home, About, Services, Contact, and App Download | Astro, React, Tailwind CSS |
| [Logistic-Web](https://github.com/Logistic-Flipship/Logistic-Web) | Web management platform for Admins and Transport Companies — dashboards, route/vehicle/order management, applications, payments | Next.js, TypeScript, Redux Toolkit |
| [Logistic-Mobile](https://github.com/Logistic-Flipship/Logistic-Mobile) | Mobile app for Customers, Drivers, and Companies — order placement, tracking, chat, ratings, payments | Expo, React Native, Redux Toolkit |

---

## 🏗 System Overview

The three repositories form a single ecosystem:

- **Landing Page** — the public-facing entry point where users learn about FlipShip and download the mobile app.
- **Web Platform** — the back-office for admins (approving company applications, overseeing the system) and companies (managing routes, vehicles, drivers, and orders).
- **Mobile App** — the primary touchpoint for end users: customers send packages, drivers handle deliveries, and companies can monitor their operations on the go.

All apps share core domains such as accounts, routes, trips, orders, payments, and notifications, communicating with a common backend API.

---

## 🛠 Shared Technologies

- **TypeScript** across all three projects
- **Redux Toolkit** for state management (Web & Mobile)
- **Tailwind CSS** for styling (via NativeWind on Mobile)
- **Goong Maps** for route mapping and geolocation
- **Firebase / Socket.IO** for real-time notifications and chat
- **Zod + React Hook Form** for form handling and validation

---

## 🚀 Getting Started

Each repository has its own setup instructions in its respective README:

1. [Landing Page setup](https://github.com/Logistic-Flipship/Logistic-LandingPage#-getting-started)
2. [Web Platform setup](https://github.com/Logistic-Flipship/Logistic-Web#-getting-started)
3. [Mobile App setup](https://github.com/Logistic-Flipship/Logistic-Mobile#-getting-started)

---

## 📄 License

All projects in this organization belong to **FlipShip / Logistic-Flipship**.
