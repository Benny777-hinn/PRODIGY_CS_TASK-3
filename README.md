# PRODIGY_CS_TASK-3
# 🔐 Password Strength Analyzer

A responsive web-based Password Strength Analyzer built using HTML, CSS, and JavaScript.  
This tool evaluates password strength in real-time based on modern security standards and provides dynamic visual feedback to improve password hygiene.

---

## 📌 Features

- ✅ Real-time password strength evaluation
- ✅ Strength meter with dynamic progress bar
- ✅ Checks for:
  - Minimum length (12+ characters)
  - Lowercase letters
  - Uppercase letters
  - Numbers
  - Special characters
- ✅ Visual criteria validation checklist
- ✅ Show / Hide password toggle
- ✅ Responsive UI design
- ✅ Clean and modular JavaScript logic

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)

---

## 🧠 How It Works

The analyzer evaluates password strength using rule-based scoring:

| Criteria | Description |
|-----------|-------------|
| Length | Minimum 12 characters |
| Lowercase | At least one lowercase letter |
| Uppercase | At least one uppercase letter |
| Number | At least one digit |
| Special Character | At least one symbol |

Each satisfied condition increases the strength score.  
The total score determines the final classification:

- 🔴 Weak
- 🟠 Moderate
- 🟢 Strong

The strength meter updates dynamically as the user types.

---

## 📂 Project Structure

```
password-strength-analyzer/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/password-strength-analyzer.git
   ```

2. Open the project folder.

3. Open `index.html` in your browser.

No additional dependencies required.

---

## ⚠️ Limitations

- Rule-based evaluation (no entropy calculation)
- No dictionary attack detection
- No breached password database verification
- Equal weighting for all criteria

---

## 🔮 Future Improvements

- Implement entropy-based strength calculation
- Add estimated brute-force crack time
- Integrate breached password API
- Detect common patterns and keyboard sequences
- Convert into React or full-stack authentication module

---

## 📖 Academic Relevance

This project demonstrates:

- Client-side password validation
- Secure coding practices
- UX-driven cybersecurity awareness
- Modular JavaScript design

It can be extended into a broader Identity & Access Management (IAM) or Zero Trust security framework.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

Your Name  
Cybersecurity / Computer Science Student  

---

⭐ If you found this project helpful, consider giving it a star!
