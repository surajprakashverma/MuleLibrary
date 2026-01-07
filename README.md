# MuleLibrary – MuleSoft MCQ Practice Portal

## Overview
MuleLibrary is a web-based portal designed to help learners master MuleSoft concepts through 5000+ multiple-choice questions (MCQs) organized into chapters and topics. It provides an interactive interface for practicing questions, viewing explanations, and tracking progress.

## Features
- 16 Chapters covering all MuleSoft topics:
  - API-led connectivity
  - DataWeave fundamentals
  - Anypoint Studio
  - Deployment & CI/CD
  - Security, Testing, and more
- Difficulty Filters: Easy, Medium, Hard
- Dynamic Question Loading from JSON files
- Progress Tracking using local storage
- Responsive UI with modern design
- Explanation Panel for correct and incorrect answers
- Navigation Controls: Previous, Next, Show Answer, Reset
- Modals for About, Contact, Privacy, and Terms

## Tech Stack
- HTML5, CSS3, JavaScript
- Font Awesome for icons
- Local Storage for progress persistence
- JSON for question data

## Folder Structure
MuleLibrary/
│
├── index.html        # Main HTML file
├── Designer.png      # Favicon/logo
├── data/             # JSON files for chapters
│   ├── CH01.json
│   ├── CH02.json
│   └── ...
└── README.txt        # Documentation

## How It Works
1. Load Chapters: Sidebar displays chapters with MCQ counts.
2. Select Chapter: Loads questions dynamically from JSON.
3. Filter by Difficulty: Choose All, Easy, Medium, or Hard.
4. Answer Questions:
   - Select an option
   - Click Show Answer to reveal correct/incorrect answers and explanations
5. Track Progress: Progress bars update as you complete questions.

## JSON Question Format
Each chapter file (e.g., CH01.json) contains an array of questions:
[
  {
    "id": "CH01-0001",
    "question": "What is API-led connectivity?",
    "options": {
      "A": "A design approach for APIs",
      "B": "A MuleSoft runtime feature",
      "C": "A database integration method",
      "D": "None of the above"
    },
    "correctAnswer": "A",
    "difficulty": "Easy",
    "explanation": {
      "correct": "API-led connectivity organizes APIs into layers.",
      "incorrect": {
        "B": "Not a runtime feature.",
        "C": "Not related to databases.",
        "D": "Incorrect."
      }
    }
  }
]

## How to Run
1. Clone the repository:
   git clone https://github.com/yourusername/MuleLibrary.git
2. Open index.html in a browser.
3. Ensure JSON files are in the data/ folder.

## Future Enhancements
- Add search functionality for questions.
- Enable bookmarking questions.
- Add timer for practice sessions.
- Export progress as PDF.

## Author
Designed and developed by Suraj Prakash Verma
Email: surajprakashverma995@gmail.com
LinkedIn: https://www.linkedin.com/in/surajprakashverma
