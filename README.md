# Sandeep Chauhan 👋

#### Android Engineer

---

Android Engineer specializing in Modern Android Development (MAD). Proficient in crafting robust applications using Kotlin, Jetpack Compose, and Clean Architecture. Dedicated to continuous learning and building impactful mobile solutions—from enterprise inventory management to personalized AI assistants.

## 📧 Contact

-   **Email:** dn.sandeeep@gmail.com
-   **Phone:** +91 8878997534
-   **LinkedIn:** www.linkedin.com/in/dn-sandeeep
-   **GitHub:** https://github.com/dn-sandeeep
-   **Medium:** https://medium.com/@dn.sandeeep
-   **Resume**: [Notion Link](https://www.notion.so/Sandeep-Chauhan-24c4803a5d4080ac825de8e3c7093b8e)

---
## 💼 Work Experience
#### The Streamliners (Contract) (April 25 - Jan 26)
*The Streamliners builds MVPs to help startups launch and validate ideas quickly.*

### Madhav Stone
- Tech Stack: Kotlin, Jetpack Compose, MVVM, Firebase, Coroutines, StateFlow, Git/GitHub.
- Architected a production-grade inventory system using Firebase for backend services, implementing Role-Based Access Control (RBAC) for Admin, Managers, Liner, and Supervisors.
- Integrated Firebase Firestore for real-time data synchronization, ensuring instant updates of stone processing stages across multiple devices.
- Built a highly reactive UI system using Jetpack Compose and StateFlow to render dynamic data tables and live machine status dashboards.

### Veda Connect
- Tech Stack: Kotlin, Jetpack Compose, MVVM, Firebase, Coroutines, StateFlow, Git/GitHub,  Play Store.
- Designed and developed a feature-rich Android app providing users with Vedic knowledge.
- Built a modular navigation system using Bottom Navigation Bar, connecting multiple key sections such as Content, Gamified, and Awareness screens.
- Managed Play Store deployment, app signing, and version updates, ensuring smooth release management.
---

## Projects 
### 🍿 [TimePass](https://github.com/username/TimePass)
> A modern Android application delivering curated content recommendations with a seamless user experience.

- **📱 Fully Declarative UI & Custom Theming:** Built the entire user interface from scratch using **Jetpack Compose**. Avoided default themes by implementing a unified, custom design system (`Theme.kt`, `Color.kt`) for a personalized look.
- **🏗️ Robust Clean Architecture:** Implemented a strictly decoupled **MVVM (Model-View-ViewModel)** architecture, ensuring clear separation of presentation logic from UI components to maximize scalability.
- **🔐 Secure Authentication Flow:** Integrated a robust, end-to-end user authentication system managed by dedicated ViewModels (`AuthViewModel`), ensuring safe and stable onboarding.
- **🛣️ Advanced Compose Navigation:** Engineered a complex, type-safe navigation graph (`NavGraph`) facilitating fluid transitions and state-preserving navigation across multiple screens without XML.
- **⚙️ Modern Build System:** Migrated to centralized dependency management using **Kotlin DSL (`build.gradle.kts`)** and **Gradle Version Catalogs (`libs.versions.toml`)** for highly optimized, reproducible, and faster builds.


### 💰 [Track Spends  ](https://github.com/dn-sandeeep/Personal-Finance-Companion)
> Android finance app built with Jetpack Compose & Clean Architecture
- 📊 Dashboard with Budget Ring, Weekly Trend Charts (pure Canvas — no library)
- 🎯 Goal tracking with Saving Velocity Engine (14-day rolling average + ETA projection)
- 📅 No-Spend Challenge & Insights Pie Chart
- 🔔 WorkManager reminders, DataStore preferences, CSV Export via SAF
- 🏗️ MVVM + Clean Architecture | Hilt DI | Room DB | Coroutines + Flow
- 📱 Offline-first | Material 3 | Min SDK 24
[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?logo=jetpackcompose&logoColor=white)](https://developer.android.com/jetpack/compose)
[![Download](https://img.shields.io/badge/Download%20APK-2E7D32?logo=android&logoColor=white)](https://github.com/dn-sandeeep/Personal-Finance-Companion/releases/latest)

---

### 🤫 SilentZone — Intelligent Modes Automation

> An Android app that automatically silences your phone based on location, WiFi network, and calendar events.

**Key Highlights:**
- 📍 **Geofencing** — Triggers silent mode in the background using Google Play Services Location API
- 📶 **WiFi Zones** — Auto-silences when connected to a saved SSID; restores previous mode on disconnect
- 📞 **Emergency Whitelist** — Priority contacts can still ring through even in Silent mode
- 📅 **Meeting Mode** — Reads Google Calendar "Busy" events and silences automatically
- 🏗️ **Architecture** — MVVM + Clean Architecture · Hilt DI · Room DB · Jetpack Compose (Material 3)
- 🔒 **Privacy First** — All location, WiFi, and contact data processed fully on-device

[![View Project](https://img.shields.io/badge/GitHub-SilentZone-blue?style=flat&logo=github)](https://github.com/dn-sandeeep/Silent-Zone)

#### SpotifyAdMuter App (Personal Project)
Service-based Android app that runs in the background to auto-mute music ads in real time, with live stats on ads blocked, songs played, and restoring volume post-ad.

- Developed an intelligent background Android service that auto-mutes ads in music streaming platforms for uninterrupted playback.
- Leveraged NotificationListenerService for real-time ad detection and seamless, non-intrusive operation.
- Designed a minimal yet functional control interface to start and manage the service.
- Implemented MVVM architecture with Kotlin Coroutines to ensure smooth and efficient background processing.
- Gained deep expertise in Android Services, background task management, and system event handling.

---
#### MyAI App (Personal Project)
A mobile AI application built on the Gemini API, demonstrating proficiency in modern Android development and architectural patterns.

- Developed a complete native Android application ("MyAI") using Kotlin and Jetpack Compose for a modern, declarative UI.
- Implemented the Model-View-ViewModel (MVVM) architecture to ensure a clean separation of concerns, testability, and a maintainable codebase.
- Integrated the Gemini API to power the core functionality, enabling real-time, conversational AI interactions.
- Managed network communication with Ktor, utilizing its client to efficiently send API requests and process received responses.

---
#### Weather App (Personal Project)
*An Android app that provides real-time weather updates for any country, city, or town, featuring detailed climate metrics in a clean Jetpack Compose interface.*

- Built a real-time weather app allowing users to search by country, city, or town.
- Displayed key metrics including temperature, humidity, wind speed, precipitation, UV index, and “feels like” temperature.
- Implemented live updates with a last updated timestamp for accurate data display.
- Designed a clean, responsive UI using Jetpack Compose for optimal user experience.
- Integrated public weather APIs via Retrofit for reliable data fetching.

---
## 🛠️ Skills

|            |                   |          |                 |   |
| ----------------------------------------- | -------------------------- | -------------------------- | -------------------------- | --------------- |
| **Modern Android Development**            | **Coroutine**              | **Firebase**               | **Figma**                  | **Kotlin** |
| **UI/UX**                                 | **Postman**                | **OOPS**                   | **Functional Programming** | **Jet Compose** |
| **Rest APIs (Retrofit & Okhttp)**         | **Multi-Module**           | **Functional Programming** | **Clean Architecture**     | **Ktor**        |
| **Dependency Injection (Koin & Dagger/Hilt)** | **Room DB**            | **Analytics**                  | **MVVM**                       | **GitHub**          |

**Soft Skills:**
- Communication
- Logical & Critical
- Planning
- Entrepreneurship
- Punctual
- HardWorking
---
## 🏆 Achievements

• Solved 250+ Problems on DSA. </br>
• Participated in 10+ CP/DSA Contests. </br>
• 850+ Rating on CodeChef. </br>

---
<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://developer.android.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="android" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://firebase.google.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://kotlinlang.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/kotlinlang/kotlinlang-icon.svg" alt="kotlin" width="40" height="40"/> </a> <a href="https://postman.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=dn-sandeeep&show_icons=true&locale=en&layout=compact" alt="dn-sandeeep" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=dn-sandeeep&show_icons=true&locale=en" alt="dn-sandeeep" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=dn-sandeeep&" alt="dn-sandeeep" /></p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=dn-sandeeep" alt="dn-sandeeep" /></a> </p>
