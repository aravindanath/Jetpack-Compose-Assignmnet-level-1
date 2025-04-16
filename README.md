# 📱 Jetpack Compose UI Assignment – User Profile Screen

## 🧑‍💻 Level: Beginner to Intermediate (1–3 Years Experience)

### 🧩 Objective

Create a **User Profile screen** using **Jetpack Compose**. This screen should allow users to view and edit their name and email, with profile details displayed in a clean, material design-based UI.

---

## 📋 Requirements

Design a **single-screen Compose UI** that includes the following:

| Component           | Type         | Description                                         |
|---------------------|--------------|-----------------------------------------------------|
| 🖼️ Profile Image     | Static        | Circle avatar (use placeholder image)              |
| 📝 Name              | Editable      | `TextField` for user name                          |
| 📧 Email             | Editable      | `TextField` for email                              |
| 📱 Phone Number      | Display only  | Static text (non-editable)                         |
| 🆔 User ID           | Display only  | Static text (non-editable)                         |
| ✅ Save Button       | Button        | Shows `Snackbar` with success message              |
| ❌ Reset Button      | Button        | Resets name and email fields to original values    |

---

## 🖼️ UI Layout

|             [ Profile Image in Circle ]           |
|                                                  |
|   Name:      [ TextField ]                        |
|   Email:     [ TextField ]                        |
|   Phone:     9876543210                           |
|   User ID:   UID12345                             |
|                                                  |
| [Save Button]         [Reset Button]              |

---

## 🛠️ Technical Guidelines

- Use **Jetpack Compose** only – no XML
- Use `Scaffold` with `SnackbarHost`
- Use `remember` / `mutableStateOf` / `rememberSaveable` for state management
- Apply padding, spacing, alignment for a neat UI

---

## 🎯 Bonus Points (Optional)

- ✅ Validate email format before allowing save
- 🌀 Animate profile image on tap (e.g., bounce or scale)
- 💾 Store data using `rememberSaveable`
- 🔧 Break UI into smaller reusable composables

---

## 📦 Submission Guidelines

- Push your code to GitHub
- Share the repo link
- Optional: Include screenshots or a short Loom video demo

---

## 📚 Resources

- [Jetpack Compose Basics](https://developer.android.com/jetpack/compose/documentation)
- [Material 3 in Compose](https://developer.android.com/jetpack/compose/themes/material)
- [State in Compose](https://developer.android.com/jetpack/compose/state)

---

> 🧠 Tip: Focus on clean code, proper state handling, and user-friendly design. Make it modular and readable.
