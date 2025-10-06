# Flutter Quiz App 🧠✨

An interactive Flutter quiz application with dynamic styling and restart functionality. This app demonstrates core Flutter and Dart concepts including state management, widget composition, and user interaction.

## 📱 Features

- **Interactive Quiz Interface**: Clean, user-friendly design with gradient backgrounds
- **Dynamic Question Navigation**: Progress through questions with visual feedback
- **Smart Answer Validation**: Real-time answer checking and scoring
- **Results Summary**: Detailed results screen showing:
  - Total score and percentage
  - Question-by-question breakdown
  - Visual indicators for correct/incorrect answers
- **Restart Functionality**: Complete quiz reset to retake the quiz
- **Responsive Design**: Works on various screen sizes and orientations

## 🎨 Visual Features

- **Color-coded Results**: 
  - 🟢 Green circles for correct answers
  - 🟣 Pink circles for incorrect answers
- **Gradient Backgrounds**: Beautiful purple gradient throughout the app
- **Centered Layout**: Professional alignment and spacing
- **Custom Styling**: Google Fonts integration for enhanced typography

## 🛠️ Technical Implementation

### Core Flutter Concepts Used:
- **StatefulWidget & StatelessWidget**: Proper state management
- **Navigation**: Screen switching without traditional routing
- **Layout Widgets**: Column, Row, Center, Expanded for responsive design
- **Styling**: Container, BoxDecoration, TextStyle customization
- **Lists & Maps**: Data handling for questions and answers
- **Callbacks**: Parent-child widget communication

### Key Components:
- `Quiz` - Main app controller with state management
- `StartScreen` - Welcome screen with quiz initiation
- `QuestionScreen` - Interactive question display with answer buttons
- `ResultScreen` - Score summary with restart functionality
- `QuestionSummary` - Detailed breakdown of answers
- `AnswerButton` - Reusable button component

## 🚀 Getting Started

### Prerequisites
- Flutter SDK (latest stable version)
- Dart SDK
- Android Studio / VS Code with Flutter extensions
- iOS Simulator / Android Emulator

### Installation

1. **Clone the repository**
   ```bash
   git clone <your-repository-url>
   cd adv_basics
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Run the app**
   ```bash
   flutter run
   ```

### Project Structure
```
lib/
├── main.dart                 # App entry point
├── quiz.dart                 # Main quiz controller
├── start_screen.dart         # Welcome screen
├── question_screen.dart      # Question display
├── result_screen.dart        # Results summary
├── question_summary.dart     # Answer breakdown
├── answer_button.dart        # Reusable button
├── data/
│   └── questions.dart        # Quiz questions data
└── models/
    └── quiz_question.dart    # Question model
```

## 🎯 How to Use

1. **Start**: Launch the app and tap "Start Quiz" on the welcome screen
2. **Answer**: Select answers for each question using the provided buttons
3. **Review**: View your results with detailed breakdown of correct/incorrect answers
4. **Restart**: Use the "Restart Quiz!" button to take the quiz again

## 🔧 Customization

### Adding New Questions
Edit `lib/data/questions.dart` to add or modify quiz questions:

```dart
final questions = [
  QuizQuestion(
    'Your question here?',
    ['Correct answer', 'Wrong answer 1', 'Wrong answer 2', 'Wrong answer 3'],
  ),
  // Add more questions...
];
```

### Styling Customization
- Modify colors in individual screen files
- Update gradient colors in `quiz.dart`
- Change fonts by updating GoogleFonts usage

## 🧪 Testing

Run the included widget tests:
```bash
flutter test
```

## 📋 Assignment Reflection

### Challenges Faced:
1. **Visual Feedback Implementation**: Creating dynamic color coding for answer correctness
2. **Layout Alignment**: Ensuring proper text alignment and spacing
3. **State Management**: Implementing restart functionality with proper state reset

### Solutions Applied:
1. **Conditional Styling**: Used boolean logic and ternary operators for dynamic colors
2. **Layout Widgets**: Applied CrossAxisAlignment and proper widget composition
3. **Function Callbacks**: Implemented parent-child communication for restart functionality

### Flutter & Dart Concepts Used:
- State management with setState()
- Widget composition and layout
- Conditional rendering and styling
- Function callbacks and parameters
- List operations and data handling
- Boolean logic and comparisons

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is created for educational purposes as part of a Flutter development course.

## 🙏 Acknowledgments

- Flutter team for the amazing framework
- Google Fonts for typography enhancement
- Udemy Flutter course for guidance and structure

---

*Built with ❤️ using Flutter & Dart*
