# s8117288_Assignment2

This Android application demonstrates **MVVM architecture**, **SOLID principles**, and **Dependency Injection (Hilt)**.  
Developed as part of the **NIT3213 Final Assignment** to showcase clean architecture and modular Android app design using **Kotlin** and **Android Studio**.

---

## 👨‍🎓 Student Information
- **Name:** Dipen Limbu  
- **Student ID:** s8117288  
- **Course Code:** NIT3213 – Mobile Application Development  
- **Assignment:** Final Android Development Project  

---

## 🎯 Features
- Implements **MVVM (Model–View–ViewModel)** architecture  
- Follows **SOLID principles** for maintainable, modular code  
- Uses **Hilt (Dependency Injection)** to inject repositories and ViewModels  
- **Login Screen:** validates user credentials  
- **Dashboard Screen:** displays dynamic data using RecyclerView  
- **Details Screen:** shows full details of a selected dashboard item  
- Navigation via **Intents** between Activities  
- UI designed with **XML layouts** and Material principles  

---

## 🧩 Project Structure
```
com.example.s8117288_assignment2
 ├── data/              # Data sources and repositories
 ├── di/                # Hilt dependency-injection modules
 ├── domain/            # (Reserved for future use cases)
 ├── presentation/
 │     ├── login/       # LoginActivity + LoginViewModel
 │     ├── dashboard/   # DashboardActivity + DashboardAdapter + DashboardViewModel
 │     └── details/     # DetailsActivity for item details
 └── utils/             # Shared helper utilities
```

---

## ⚙️ How to Build and Run the Application

### 🪜 Setup Instructions
1. **Clone the repository**
   ```bash
   git clone https://github.com/dipen879/s8117288_Assignment2.git
   ```
2. **Open the project in Android Studio**
   - Go to *File → Open → Select the project folder (`s8117288_Assignment2`)*  
   - Allow Gradle to sync automatically  
   - Ensure your SDK version is **Android 14 (API level 34)** or higher  

3. **Build the project**
   - Click **Build → Make Project**
   - Ensure you see `BUILD SUCCESSFUL` at the bottom

4. **Run the application**
   - Click the green **Run ▶️** button
   - Choose an emulator or connected device
   - Wait for the app to install and launch

---

## 🔑 Login Credentials
- **Username:** any value  
- **Password:** `8117288`

### 🧭 Navigation Flow
1. Enter credentials → **Login Screen**  
2. View list of items → **Dashboard Screen**  
3. Tap an item → **Details Screen** (shows title and description)

---

## 🧰 Dependencies
The following key libraries are required (already included in Gradle files):

| Library | Version | Purpose |
|----------|----------|----------|
| `androidx.lifecycle:lifecycle-viewmodel-ktx` | 2.8.3 | MVVM ViewModel support |
| `com.google.dagger:hilt-android` | 2.52 | Dependency Injection |
| `com.squareup.retrofit2:retrofit` | 2.11.0 | Networking (demo) |
| `com.squareup.okhttp3:logging-interceptor` | 4.12.0 | API call logging |
| `org.jetbrains.kotlinx:kotlinx-coroutines-android` | 1.8.1 | Background threading |
| `androidx.recyclerview:recyclerview` | Built-in | Dashboard list display |

All dependencies are already defined in `app/build.gradle.kts`.

---

## 🧠 Technologies Used
- **Language:** Kotlin  
- **Framework:** Android SDK  
- **Architecture:** MVVM  
- **Dependency Injection:** Hilt (Dagger 2)  
- **UI Components:** RecyclerView, XML Layouts  
- **Build System:** Gradle (Kotlin DSL)  
- **Version Control:** Git + GitHub  

---

## 🏆 Project Outcome
This project fulfills all NIT3213 assignment requirements:
- Clean architecture (MVVM + SOLID)  
- Dependency injection with Hilt  
- Functional Login → Dashboard → Details workflow  
- Well-documented build and setup instructions  

**Expected Grade:** 🎯 *High Distinction (HD)*  

---

## 🏁 Acknowledgement
Developed by **Dipen Limbu (s8117288)**  
As part of **NIT3213 – Mobile Application Development (Final Assignment)**  
Semester 2, 2025
