# 🔐 Secure Login & Registration System (HTML, CSS, JS)

A modern **secure login and registration system** built with **HTML, CSS, and JavaScript**.  
It uses **AES encryption (CryptoJS)** for password storage in **localStorage** and manages user sessions with **sessionStorage**.  
The UI is animated with smooth transitions, a neon-glass effect, and responsive design.

---

## 🚀 Features

- **Login & Registration**
  - User can create an account with email & password.
  - AES-encrypted password storage in `localStorage`.
  - Validates matching password fields on registration.
  - Prevents duplicate email registrations.

- **Secure Login**
  - Compares input password with decrypted stored password.
  - Supports **"Remember Me"** using `localStorage`.

- **Session Management**
  - Uses `sessionStorage` to track logged-in user.
  - Welcome screen with user’s email after successful login.
  - Logout functionality with proper session reset.

- **UI/UX Enhancements**
  - Glassmorphism & neon glow effects.
  - Animated transitions between login, register, and welcome screens.
  - Shake animation on incorrect login.
  - Success & error toast messages.
  - Loading animations on button clicks.

- **Extras**
  - "Forgot Password" (placeholder for future implementation).
  - Responsive design for desktops & mobiles.

---

## 🛠️ Technologies Used

- **Frontend:**  
  - HTML5  
  - CSS3 (Neon + Glassmorphism effects, animations)  
  - JavaScript (ES6)  

- **Libraries:**  
  - [CryptoJS](https://cdnjs.com/libraries/crypto-js) – AES encryption/decryption  
  - [Ionicons](https://ionic.io/ionicons) – Icons  

---

## 📂 Project Structure

