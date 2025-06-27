## Tudee App
> A personal task management app built with Kotlin and modern Android practices, supporting offline use, dynamic theming, and bilingual UI.

---

## 🚀 Features

- ✅ Onboarding screen (only first launch)
- ✅ Home screen with task statistics
- ✅ Create task with title, description, priority, and category
- ✅ Filter tasks by date
- ✅ View task details
- ✅ Change task status: `To Do` → `In Progress` → `Done`
- ✅ Delete tasks
- ✅ Manage predefined & custom categories (with image support)
- ✅ Light & Dark theme
- ✅ Auto language switch (English / Arabic)

---

## 🧱 Architecture & Design

| Layer | Description |
|-------|-------------|
| **Presentation** | Jetpack Compose + ViewModels scoped per screen |
| **Domain** | Abstractions (e.g. `TasksServices`) and entities |
| **Data** | Room DAOs and mappers |
| **DI** | Powered by **Koin** |
| **Navigation** | Jetpack Navigation Component |
| **Design System** | Centralized theme, spacing, typography |

📌 Follows **SOLID** principles.  
📌 No over-engineering – only essential components are included.  
📌 All styles, colors, dimensions are extracted into a custom **Design System**.

---

## 📱 Demo Video

Watch the full app walkthrough on Google Drive:  
(https://drive.google.com/file/d/1t1yTi6EaSRsK7hkdBsbpviy1CUSOgmMW/view?usp=drive_link)

---

## 🛠 Tech Stack

- **Kotlin**
- **Room** – Local database
- **Koin** – Dependency Injection
- **Jetpack Compose** – UI
- **ViewModel + StateFlow**
- **Navigation Component**
- **Design System** – Custom UI styling

---

## ✅ Unit Testing

- ViewModel & business logic are covered.
- Code coverage goal: **≥ 70%**

```bash
./gradlew testDebugUnitTestCoverage
