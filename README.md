# 📱 Google Pay Clone Flutter Project

## 📌 Project Overview
This Flutter project follows a modular architecture with GetX for state management. It is structured in a way that ensures maintainability and scalability.

---

## 🏗 Project Architecture
```
lib/
├── core/
│   └── themes/
│       └── app_colors.dart         # Defines global app colors
│
├── features/
│   └── home/
│       ├── model/
│       │   ├── business_item.dart
│       │   ├── grid_item.dart
│       │   └── person.dart
│       │
│       ├── view/
│       │   └── home_screen.dart   # UI logic for Home screen
│       │
│       ├── view_modals/
│       │   ├── business_grid_provider.dart
│       │   ├── grid_provider.dart
│       │   └── recharge_grid_provider.dart
│       │
│       ├── widgets/
│       │   ├── business_tile.dart
│       │   ├── person_tile.dart
│       │   ├── recharge_tile.dart
│       │   └── transaction_list_tile.dart
│       │
│       ├── pagination.dart
│       └── pagination_provider.dart
│
└── main.dart                      # Entry point of the application
```

---

## 🚀 How to Run the Project

### Prerequisites
Ensure you have the following installed:
- **Flutter SDK**: [Install Flutter](https://flutter.dev/docs/get-started/install)
- **Dart SDK** (Included with Flutter)
- **Android Studio** or **Visual Studio Code**
- **An Android/iOS emulator** or a physical device

### Steps to Run
1. **Clone the repository**
   ```sh
   git clone https://github.com/prafulkorat/google_pay.git
   cd <your-project-folder>
   ```

2. **Install dependencies**
   ```sh
   flutter pub get
   ```

3. **Run the project**
   ```sh
   flutter run
   ```
    - If using an emulator, ensure it is running.
    - If using a physical device, enable USB debugging.

## 🎥 Demo Preview

<p align="center">
  <a href="https://raw.githubusercontent.com/prafulkorat/google_pay/main/assets/google_pay.gif" target="_blank">
    <img src="https://raw.githubusercontent.com/prafulkorat/google_pay/main/assets/google_pay.gif" width="300" alt="Google Pay Demo" />
  </a>
</p>

