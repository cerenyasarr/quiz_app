# 📱 Flutter Quiz App

This is a simple and interactive Quiz application built with Flutter. Users can answer multiple-choice questions and see how many answers they got right or wrong at the end. The project is designed to practice and understand core Flutter concepts like `StatefulWidget`, `setState()`, page navigation, and user interaction.

---

## 🚀 Features

- Welcome screen to start the quiz
- Multiple-choice questions with shuffled answer options
- Tracks user's selected answers
- Result screen showing correct and incorrect answers
- Clean and colorful UI

---

## 🧠 What You’ll Learn

- Usage of `StatelessWidget` and `StatefulWidget`
- Updating UI with `setState()`
- Handling data with `List` and `Map`
- Page navigation using widget structure
- Custom fonts with `Google Fonts`
- Using local images via `Image.asset`
- Shuffling answers dynamically with `getShuffledAnswers()` method

---

## 📁 Project Structure

```

lib/
├── main.dart               \# Entry point of the app
├── quiz.dart               \# Root widget managing app state
├── start\_screen.dart       \# Welcome/start screen UI
├── questions\_screen.dart   \# Quiz screen with questions & options
├── results\_screen.dart     \# Result screen showing user's performance
├── questions\_summary.dart  \# Widget showing answer summary
├── data/
│   └── questions.dart      \# List of questions and answers
├── models/
│   └── quiz\_question.dart  \# Model class for a quiz question
├── answer\_button.dart      \# Reusable button widget for answers

```

---

## 🛠️ How to Run

1.  Make sure Flutter is installed on your machine.
2.  Open the project directory in your terminal or IDE.
3.  Run `flutter pub get` to install dependencies.
4.  Use `flutter run` to start the app on an emulator or device.

---

## 📸 Screenshots

| Start Screen                                                                                                                   | Question Screen                                                                                                                   | Result Screen                                                                                                                    | Result Screen (Scrolled)                                                                                                                   |
| :-----------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------: |
| <img width="200" alt="Simulator Screenshot - iPhone 16 Plus - 2025-10-26 at 17 31 10" src="https://github.com/user-attachments/assets/32f4adfc-e151-4a53-aa3c-ae56ccd4ac19" /> | <img width="200" alt="Simulator Screenshot - iPhone 16 Plus - 2025-10-26 at 17 32 45" src="https://github.com/user-attachments/assets/0c4f48b2-b91a-4fff-b054-8406fc523f02" /> | <img width="200" alt="Simulator Screenshot - iPhone 16 Plus - 2025-10-26 at 17 41 29" src="https://github.com/user-attachments/assets/7f1ff289-98f6-4abe-aafb-9014203992a7" /> | <img width="200" alt="Simulator Screenshot - iPhone 16 Plus - 2025-10-26 at 17 41 52" src="https://github.com/user-attachments/assets/94e4f02a-d896-454a-a1b1-5e7e51ab3914" /> |

---

## 📝 Notes

- All questions are stored in `lib/data/questions.dart`.
- The correct answer is always the **first** item in the `answers` list for each question object in `questions.dart`.
- The app is optimized for portrait mode on mobile devices.

---

## 🧑‍💻 Developer

**Ceren Yaşar – 2025**
This app was developed as part of my Flutter learning journey.

---
```
