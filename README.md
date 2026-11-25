# 🔐 Password Security System

A Python-based desktop application built using **Tkinter** that helps users analyze password strength and generate random passwords through a modern graphical user interface.

The application evaluates passwords based on multiple security criteria, provides improvement suggestions, and maintains a history of password analysis.

## ✨ Features

### 1. Password Strength Analyzer
- Evaluates password strength using 5 security criteria.
- Checks password length (minimum 8 characters).
- Detects uppercase and lowercase letters.
- Checks for numeric digits.
- Identifies special characters.
- Detects common weak passwords, predictable sequences, and years.

### 2. Password Generator
- Generates random passwords between 8 and 50 characters.
- Includes uppercase and lowercase letters.
- Includes numbers and special characters.
- Automatically ensures at least one character from each category.
- Automatically analyzes the generated password.

### 3. Strength Classification

Passwords are classified into four levels:

| Score | Strength | Description |
|---|---|---|
| 0–2 | Weak | Needs improvement |
| 3/5 | Medium | Moderate password complexity |
| 4/5 | Strong | Good password complexity |
| 5/5 | Very Strong | Meets all basic checks |

Common weak patterns can override the score and classify a password as Weak.

### 4. Analysis Suggestions
- Provides suggestions to improve password strength.
- Displays password length and security score.
- Shows a visual progress bar.
- Displays detailed analysis results.

### 5. Password History
- Automatically saves analysis history.
- Records the date and time.
- Stores password length and strength classification.
- Saves records in `password_history.txt`.

### 6. Modern Graphical Interface
- Dark-themed user interface.
- Blue, purple, and cyan accent colors.
- Interactive buttons.
- Visual password strength indicator.
- Built with Python Tkinter.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Tkinter | Graphical User Interface |
| Random | Random password generation |
| Datetime | Date and time tracking |

## 📁 Project Structure

```text
Password-Security-System/
│
├── password_security.py
├── password_history.txt    # Generated automatically
└── README.md
```

## 🚀 Installation & Setup

### Prerequisites

- Python 3.8 or above
- Windows, Linux, or macOS

### Step 1: Clone the Repository

```bash
git clone YOUR_REPOSITORY_URL
```

### Step 2: Open the Project Directory

```bash
cd Password-Security-System
```

### Step 3: Run the Application

```bash
python password_security.py
```

**Note:** Tkinter is included with most standard Python installations. On some Linux distributions, it may need to be installed separately.

## 📖 How to Use

1. Launch the application.
2. Enter an existing password in the password input field.
3. Click **ANALYZE** to evaluate its strength.
4. Review the security score and improvement suggestions.
5. Enter a desired password length between 8 and 50.
6. Click **GENERATE** to create a random password.
7. Click **CLEAR** to reset all fields and results.

## 🧠 Password Evaluation Criteria

The application evaluates five basic criteria:

- **Length:** At least 8 characters.
- **Uppercase:** Contains A–Z.
- **Lowercase:** Contains a–z.
- **Numbers:** Contains 0–9.
- **Special Characters:** Contains symbols such as @, #, $, and %.

It also checks against a predefined list of common weak passwords, predictable sequences, and years.

## 🔒 Security & Privacy
- Password analysis is performed locally.
- No external API or internet connection is required.
- Password history stores the password length and strength, not the actual password.
- Generated passwords use Python's standard `random` module.

**Security Note:** This project is intended for educational purposes. It is not a production-grade password security solution. For real-world password generation, use Python's `secrets` module instead of `random`. Password strength also depends on factors beyond these basic checks.

## 🎯 Project Objective

The main objective of this project is to demonstrate practical implementation of Python programming concepts, including:

- Functions and conditional statements.
- Loops and string operations.
- Lists and random selection.
- File handling.
- Exception handling.
- Date and time operations.
- GUI development using Tkinter.

## 👨‍💻 Author

**Jaswant Yadav**

B.Tech – Artificial Intelligence & Machine Learning

Bharati Vidyapeeth (Deemed to be University), College of Engineering, Pune

---

⭐ If you find this project useful, consider giving it a star!
