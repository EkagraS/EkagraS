<div align="center">

# Ekagra Shandilya
### Android Development • Jetpack Compose • Clean Architecture • MVVM • HILT • Unit testing
</div>

I am an Android Developer specializing in building, mobile applications using Kotlin and Jetpack Compose. I use Modern Android Architecture, like MVVM and Clean Architecture to ensure that my codebases are scalable, testable, and easy to maintain. My experience ranges from engineering real-time IoT controllers that bridge the gap between mobile software and hardware for hundreds of live users to developing productivity systems that utilize background services to automate complex daily routines.

On the engineering side, I work with in building responsive user interfaces with Material 3 to managing complex asynchronous logic using Kotlin Coroutines and reactive data streams like StateFlow and SharedFlow. I utilize Hilt for dependency injection and use Room for local data storage, Retrofit for REST API integration, and Firebase. To ensure application reliability, I implement automated background tasks through WorkManager and AlarmManager, while maintaining code quality through rigorous unit testing with JUnit and Mockito, memory leak detection with LeakCanary, and performance monitoring via the Android Profiler.

## Tech Stack

📱 **Android Development**
* **Jetpack Compose** (Modern UI)
* **XML** (Legacy UI & View System)
* **Material 3** (Design Standards)
* **Lottie** (Vector Animations)

⚙️ **Core Engineering**
* **Clean Architecture** (Modular Layering)
* **MVVM Architecture** (UI & Logic Separation)
* **Dependency Injection** (Hilt)
* **Kotlin Coroutines** (Structured Concurrency)
* **Flow** (Reactive State Handling)

🔥 **Backend & Data Services**
* **REST API Integration** (Retrofit & OkHttp)
* **Firebase Authentication**
* **Firebase Realtime Database** & **Firestore**
* **Room Database** (Local Persistence)

🧪 **Testing & Reliability**
* **JUnit & Mockito** (Unit Testing ViewModels)
* **WorkManager** (Background Task Reliability)
* **LeakCanary** (Memory Leak Detection)
* **Android Profiler** (Performance Monitoring)

## 🚀 Projects

### 🔹 UniTrack  
Android application designed to automate daily student workflows.

#### What it does:
- **Automates Attendance:** Tracks and organizes student attendance records with daily updates  
- **Routine Management:** Manages study sessions and tasks using background scheduling  
- **Data Sync:** Syncs user profiles and task data using Firebase Realtime Database  
- **Background Automation:** Ensures reminders and cleanup tasks run even when the app is closed  

#### Technical Highlights:
- Implemented structured state handling in Jetpack Compose for UI consistency  
- Used WorkManager and AlarmManager for reliable background execution  
- Optimized Firebase data fetching to reduce latency  

#### Tech Stack:
- Jetpack Compose
-  Kotlin
-  Firebase
-  WorkManager
-  AlarmManager
-  MVVM
  
--

### 🔹 IoT WiFi Controller  
Android application used to control NodeMCU-based devices over a local WiFi network.

#### What it does:
- **Real-time Control:** Sends commands from the phone to the device over WiFi  
- **Custom Mapping:** Allows configurable input-to-command mapping  
- **Local Communication:** Works over a local network without requiring internet  

#### Technical Highlights:
- Implemented HTTP-based communication for sending commands to NodeMCU  
- Handled unstable network conditions for smoother real-time control  
- Designed a simple and responsive control interface for live usage  

#### Tech Stack:
- Kotlin  
- XML  
- NodeMCU (ESP8266)  
- WiFi (Local Network Communication)  

--

### 🔹 Trip Companion  
Android application for managing trips with basic location tracking features.

#### What it does:
- **Location Tracking:** Tracks and updates user location using Google Maps  
- **Data Storage:** Stores trip and location data using Firebase  
- **Trip Management:** Allows basic organization of trip-related information  

#### Technical Highlights:
- Integrated Google Maps API for location-based features  
- Used Firebase Realtime Database for storing and syncing data  
- Built using MVVM architecture for better code structure  

#### Tech Stack:
- Kotlin  
- Jetpack Compose  
- Firebase  
- Google Maps API  
- MVVM  
