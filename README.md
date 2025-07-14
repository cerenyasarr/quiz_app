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
- Shuffling answers dynamically with `shuffledAnswers()` method

---

## 📁 Project Structure

```
lib/
├── main.dart               # Entry point of the app
├── quiz.dart               # Root widget managing app state
├── start_screen.dart       # Welcome/start screen UI
├── questions_screen.dart   # Quiz screen with questions & options
├── results_screen.dart     # Result screen showing user's performance
├── questions_summary.dart  # Widget showing answer summary
├── data/
│   └── questions.dart      # List of questions and answers
├── models/
│   └── quiz_question.dart  # Model class for a quiz question
├── answer_button.dart      # Reusable button widget for answers
```

---

## 🛠️ How to Run

1. Make sure Flutter is installed on your machine.
2. Open the project directory in your terminal or IDE.
3. Run `flutter pub get` to install dependencies.
4. Use `flutter run` to start the app on an emulator or device.

---

## 📸 Screenshots

- Start Screen  
- Question Screen  
- Result Screen  

(*You can add actual screenshots here using Markdown syntax like `![Start](assets/screenshots/start.png)`*)

---

## 📝 Notes

- All questions are stored in `questions.dart`.
- The correct answer is always the **first** item in the `answers` list.
- The app is optimized for portrait mode on mobile devices.

---

## 🧑‍💻 Developer

**Ceren Yaşar – 2025**  
This app was developed as part of my Flutter learning journey.

---
