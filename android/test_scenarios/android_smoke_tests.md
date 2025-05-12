# 📱 Android Smoke Test Scenarios

## Test App: Sample Android App
> Device: Android Emulator (Pixel 4, API 33)

---

### ✅ Smoke Test: Launch App
- **Precondition:** Android emulator is running
- **Steps:**
  1. Open the Android app
- **Expected Result:** App loads without crashing and reaches home screen

---

### ✅ Smoke Test: Navigate to Login
- **Steps:**
  1. Tap the "Login" button
- **Expected Result:** Login screen appears with username and password fields

---

### ✅ Smoke Test: Submit Empty Login
- **Steps:**
  1. Tap Login with empty fields
- **Expected Result:** Error message appears: "Username required"

---

### ✅ Smoke Test: View Settings
- **Steps:**
  1. Tap hamburger menu > Settings
- **Expected Result:** Settings screen loads with options

- 
