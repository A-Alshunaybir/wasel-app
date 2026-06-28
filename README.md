# Wasel - Smart Event Discovery App

> **Note**
>
> This repository contains the **Flutter frontend**.
> The AI recommendation engine and FastAPI backend can be found here:
> https://github.com/A-Alannoud/wasel-ai-engine

## Overview

**Wasel** is a cross-platform mobile application designed to help users discover, explore, and book local cultural events in Riyadh. It connects to a robust AI backend to deliver personalized recommendations, smart tour planning, and live chatbot assistance.

---

## Frontend Architecture & Technologies

The client-side application utilizes a clean, layered architecture that separates the UI, application logic, domain models, and data sources for maintainability and scalability.

| Technology           | Description                                                       |
| -------------------- | ----------------------------------------------------------------- |
| **Framework**        | Flutter & Dart                                                    |
| **State Management** | Provider                                                          |
| **Authentication**   | Firebase Authentication for secure login and signup               |
| **Database**         | Cloud Firestore for persistent user data, bookings, and favorites |
| **Caching**          | SharedPreferences for offline-friendly API response caching       |

---

## Key Features

### Bilingual Experience

* Full Arabic-English localization
* Custom Arabic fonts
* Dynamic language switching
* Localized content handling

### Location-Based Services

* Integrated geolocation and map libraries
* Nearby event discovery
* Route suggestions
* Personalized tour mapping

### Seamless Booking Flow

* End-to-end event discovery and booking
* Form validation
* Card-style payment inputs
* Secure Firestore booking persistence

### Dynamic User Interface

* Trending events section
* Smart search suggestions
* Category filtering
* Profile management
* Interactive AI chatbot screens

---

## Project Architecture

The application follows a clean layered architecture:

```text
Presentation Layer (UI)
        |
Application Layer (State Management)
        |
Domain Layer (Models & Business Logic)
        |
Data Layer (Firebase & External APIs)
```

This architecture improves maintainability, scalability, and separation of concerns.

---

## The Team & Contributions

The Wasel mobile application was developed as a graduation project by Alanoud Alshunaybir, Wjoud Albahli, Norah Almoajil, and Yara Alkhalifah.

The team collaboratively worked on the Flutter application, including UI/UX development, state management, testing, and documentation.

Alanoud Alshunaybir additionally contributed to database integration, backend API integration, testing, and coordination between the mobile application and the AI backend services.

---

## Backend Repository

The FastAPI backend and AI services can be found here:

https://github.com/A-Alannoud/wasel-ai-engine
