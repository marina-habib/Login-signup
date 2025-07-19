# Flutter Auth UI (Login & Signup)

This Flutter project implements a beautiful **Login** and **Signup** screen with:

- ✅ Modern UI inspired by Facebook-style design
- ✅ Form validation (username, email, password match)
- ✅ Navigation between Login and Signup
- ✅ Ready for Firebase or backend integration

---

## 📱 Screens Included

### 🔐 Login Screen

- Username + Password fields
- Form validation for empty inputs
- Navigation to the Signup screen
- Placeholder for "Forgot Password"

### 📝 Signup Screen

- Username, Email, Password, Confirm Password
- Validation for:
  - Empty fields
  - Email format
  - Password length
  - Matching password & confirmation
- Google Sign-In button (UI only)
- Navigation to Login screen

---

## 🛠️ Project Structure

```bash
lib/
├── login_screen.dart        # Login screen with validation & navigation
├── signup_screen.dart       # Signup screen with validation & navigation
└── main.dart                # App entry point with routing
