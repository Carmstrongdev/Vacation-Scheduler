# 🌴 Vacation Scheduler

**Plan • Explore • Remember**

An Android vacation planning application designed to help travelers organize trips, manage excursions, schedule reminders, and preserve memories from their adventures.

Developed as part of the **D424 Software Engineering Capstone** at Western Governors University.

---

## 📲 Download Vacation Scheduler

### ⬇️ [DOWNLOAD THE ANDROID APP (.APK)](./vacation-scheduler.apk?raw=1)

**Get Vacation Scheduler for Android!**

No account registration is required. Download the APK, install it on a compatible Android device, and start planning your next adventure.

**Platform:** Android 8.0 or newer  
**Application:** Vacation Scheduler  
**File:** `vacation-scheduler.apk`  
**Cost:** Free

> **Important:** This application is distributed as an APK rather than through Google Play. Android may require you to authorize installation from the source used to download the file.

---

## ✨ Application Features

### 🗓️ Vacation Management

Create and organize vacations with important trip information.

- Create, edit, and delete vacation records.
- Record accommodation information.
- Schedule vacation start and end dates.
- Search vacations by title or accommodation.
- Validate dates and required information before saving.

### 🧭 Excursion Planning

Keep track of activities associated with your vacations.

- Add excursions to specific vacations.
- Edit and delete existing excursions.
- Schedule activities within vacation dates.
- Prevent excursions from being scheduled outside the vacation period.

### 🔔 Vacation Reminders

Stay informed about upcoming travel plans.

- Schedule vacation start reminders.
- Schedule vacation end reminders.
- Receive excursion date notifications.
- Restore scheduled notifications after supported device restart events.

### 📸 Vacation Photo Gallery

Preserve memories from your favorite trips.

- Select photos using Android's built-in Photo Picker.
- Associate photos with individual vacations.
- Display saved photos in a gallery.
- Tap photos to view enlarged previews.
- Remove photos from the application without deleting the original images.

### 📊 Vacation Reports

Generate reports showing your saved travel information.

Reports include vacation titles, accommodations, start dates, end dates, the total number of vacations, and a generation timestamp.

### 🔒 Security and Data Validation

Vacation Scheduler implements application security practices including:

- Input validation and sanitization.
- Parameterized Room database queries.
- Restricted Android component access.
- Controlled access to device photographs.
- Error handling for database operations.
- Restrictions on automatic backup and cleartext network traffic.

---

## 🚀 Installation Guide

**Step 1 — Download**

Select the download link at the top of this README to obtain the Android APK.

**Step 2 — Open the APK**

Locate `vacation-scheduler.apk` in your device's Downloads folder and open it.

**Step 3 — Authorize Installation**

If Android requests permission to install applications from this source, review the prompt and enable the necessary permission.

**Step 4 — Install**

Follow the Android installation prompts.

**Step 5 — Launch**

Open **Vacation Scheduler** from your device's application drawer.

**Step 6 — Start Planning**

Select *Plan a New Vacation* to create your first vacation, or *View My Vacations* to browse existing records.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Java | Application development |
| Android Studio | Development environment |
| Android SDK | Android application platform |
| Room Persistence Library | Database access |
| SQLite | Local relational database |
| XML | User interface layouts |
| Gradle | Build automation |
| JUnit | Automated unit testing |
| GitLab | Source control and development history |
| GitHub Pages | Public application download website |

---

## 🏗️ Software Architecture

Vacation Scheduler uses a modular architecture that separates user interface components, application logic, and database access.

The application uses Room entities representing three primary data models:

**Vacation:** Stores trip information, accommodations, and travel dates.

**Excursion:** Stores activities associated with individual vacations.

**VacationPhoto:** Stores references to photos associated with saved vacations.

Each vacation can have multiple excursions and photographs.

Database access objects (DAOs) provide reusable operations for creating, retrieving, updating, and deleting application data.

The application also includes database migrations, indexed relationships, asynchronous image loading, and thumbnail caching to support future expansion.

---

## 🧪 Software Testing

Vacation Scheduler uses JUnit to verify important input validation functionality.

Automated testing includes:

| Test | Expected Behavior |
|---|---|
| Vacation title validation | Reject blank titles and accept valid titles |
| Calendar date validation | Reject impossible dates |
| Vacation date-range validation | Reject invalid ranges and accept valid ranges |

**Test results:** All three local JUnit tests passed during the final reported test execution.

Testing was performed using Android Studio and Gradle.

---

## 📱 How to Use Vacation Scheduler

**Create a vacation:** Open the application, select *Plan a New Vacation*, enter the requested information, and save.

**Manage excursions:** Open a saved vacation and select *View Excursions* to create or manage its activities.

**Add vacation photos:** Open a saved vacation and select *View Vacation Photos* to access its gallery.

**Search vacations:** Enter a vacation title or accommodation in the search field on the vacation list screen.

**Generate a report:** Select *Generate Vacation Report* to display a summary of saved vacations.

**Schedule reminders:** Open a saved vacation or excursion and use the available notification controls.

---

## 🎓 About This Project

Vacation Scheduler was developed for the **D424 Software Engineering Capstone** at Western Governors University.

The application demonstrates Android development, object-oriented programming, relational database management, user input validation, application security, automated testing, reporting, and modular software design.

The official development repository and commit history are maintained separately in WGU GitLab.

---

**Vacation Scheduler**

*Your next adventure starts here.*

**[⬇️ DOWNLOAD VACATION SCHEDULER FOR ANDROID](./vacation-scheduler.apk?raw=1)**
