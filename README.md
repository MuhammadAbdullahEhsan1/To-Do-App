# 📝 To-Do List App (Flutter)

This is a simple **To-Do List App** built with Flutter. It demonstrates the use of **state management** using `setState` and **persistent local storage** using `SharedPreferences`.

## 📚 Learning Objectives Covered

- ✅ Understand and implement basic state management using `setState`.
- ✅ Store and retrieve data locally using `SharedPreferences`.
- ✅ Build a basic user interface with interactive widgets.

---

## 🚀 Features

### 1. 🔢 Counter App
- Basic counter functionality to increase or decrease a value.
- Uses `setState` for state management.
- Saves counter value using `SharedPreferences` to persist data on app restart.

### 2. ✅ To-Do List App
- Add new tasks via a text field.
- View the list of tasks in a `ListView`.
- Tasks are saved locally and persist across app restarts using `SharedPreferences`.

---

## 🛠️ Tech Stack

- **Flutter**
- **Dart**
- **SharedPreferences Plugin**

---

## 🧩 How It Works

### Counter App:
- Initializes counter value from `SharedPreferences` on app launch.
- Updates and saves value every time it is increased or decreased.

### To-Do List:
- Adds new task to the list and updates the UI with `setState`.
- Saves task list in `SharedPreferences` as a JSON string.
- On launch, retrieves and decodes the task list.

---

## 🧪 Getting Started

### Prerequisites:
- Flutter installed on your machine
- Dart SDK

### Run the App:
```bash
flutter pub get
flutter run
