# SelfContainedFlashCards
Self Contained HTML Flashcard Program

## Overview
A single-file, self-contained HTML flashcard application for studying terms and definitions. Everything you need is in one file - no external dependencies, no installation required!

## Features
- ✅ **Single File** - Everything in one HTML file (17KB)
- ✅ **Two Study Modes**:
  - Study Terms: See terms, provide definitions
  - Study Definitions: See definitions, provide terms
- ✅ **Interactive Learning** - Type your answer, see the correct answer, self-grade
- ✅ **Progress Tracking** - Shows which card you're on (e.g., "Card 3 of 10")
- ✅ **Score Tracking** - Final score with percentage at completion
- ✅ **Card Shuffling** - Cards appear in random order each session
- ✅ **Keyboard Support** - Press Enter to submit answers
- ✅ **Fully Accessible** - ARIA labels and screen reader support
- ✅ **Modern UI** - Beautiful gradient design with smooth animations

## Usage
1. Open `flashcards.html` in any web browser
2. Choose your study mode (Terms or Definitions)
3. Type your answer in the input field
4. Press Enter or click "Submit Answer"
5. Review the correct answer
6. Click "I Was Correct" or "I Was Incorrect"
7. Repeat until all cards are complete
8. View your final score and start a new session!

## Adding Your Own Flashcards
Edit the `flashcards` array in the JavaScript section of `flashcards.html`:

```javascript
const flashcards = [
    {
        "term": "Your Term",
        "definition": "Your Definition"
    },
    {
        "term": "Another Term",
        "definition": "Another Definition"
    }
    // Add as many cards as you want!
];
```

## Technical Details
- **No Dependencies** - Pure HTML, CSS, and JavaScript
- **Self-Contained** - All code in one file
- **Responsive** - Works on desktop and mobile
- **Accessible** - WCAG compliant with proper ARIA attributes
- **Modern Browser Support** - Works in all modern browsers

## Sample Flashcards
The application comes with 10 sample flashcards covering basic programming concepts:
- HTML, CSS, JavaScript
- API, JSON, DOM, HTTP
- Variable, Function, Array

## Screenshots
See the beautiful, intuitive interface with gradient backgrounds, smooth animations, and clear visual feedback for each step of the learning process.

## License
Free to use and modify for educational purposes.
