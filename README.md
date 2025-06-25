# 🔐 Password Strength Checker (Python + Tkinter)

A simple desktop application built with Python and Tkinter to evaluate the strength of a password in real time. The app provides visual feedback using a progress bar, color-coded results, improvement tips, and a show/hide password toggle.

---

## 🧰 Features

- Real-time password strength detection
- Visual feedback with color and progress bar
- Tips for creating stronger passwords
- Show/hide password button (👁️ / 🙈)
- Clean and modern-looking GUI using `ttk`

---

🧠 How It Works
The app analyzes the password based on five criteria:

- Minimum length (8 characters)

- Contains uppercase letters

- Contains lowercase letters

- Contains numbers

- Contains special characters (e.g. !@#%)

Each criterion increases the strength score. Based on the score, it displays:

- Weak (red)

- Medium (orange)

- Strong (green)

Improvement tips are shown dynamically if the password is weak or medium.

---

🛡️ Why It Matters
This is a beginner-friendly project with real-world value. It introduces key concepts in cybersecurity and user input validation, helping raise awareness of safe password creation — aligned with best practices from OWASP and NIST.
