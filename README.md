# Student_Management

# 🎓 Student Management System — Modern, Responsive & Feature-Rich

A **full-featured Student Management System** developed using **PHP**, **MySQL**, and **Bootstrap**, redesigned with a **modern dark UI**, **glassmorphism design**, and enhanced interactivity. Ideal for managing academic records, departments, courses, and users with role-based access.

---

## ✨ Features

- 🔐 **Role-based Login**: Admin & Staff access with secure authentication.
- 🎓 **Student Management**: Add, edit, view, delete student profiles with image upload (avatar & cover).
- 🧾 **Course & Department Module**: Fully manageable course and department database with status control.
- 🌐 **Modern UI**:
  - Dark theme with glassmorphism cards
  - Smooth animations, hover effects
  - Mobile-responsive layout
- 🖼️ **Image Preview**: Real-time avatar & cover preview using FileReader.
- ⚡ **AJAX-enabled Forms**: No page reloads on save/update.
- 📄 **Rich Text Support**: Summernote for dynamic content editing.
- 📊 **User List View**: With dropdown actions for edit, delete, verify.

---

## 🛠️ Tech Stack

| Layer     | Technologies                    |
|-----------|----------------------------------|
| Frontend  | HTML5, CSS3, Bootstrap 4/5, JS (jQuery), Select2, Summernote |
| Backend   | PHP (Procedural + OOP), AJAX     |
| Database  | MySQL                            |
| UX Enhancers | Font Awesome, Custom Animations, Toast Notifications |

---

## 🚀 How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/student-management-system.git
   ```

2. **Import Database**
   - Open `phpMyAdmin`
   - Import `student_management.sql` from the repo

3. **Configure Database**
   - Open `config.php`
   - Update your DB credentials:
     ```php
     $conn = new mysqli("localhost", "root", "", "student_management");
     ```

4. **Run the App**
   - Open browser and go to:
     ```
     http://localhost/student-management-system/
     ```

## 🤝 Contributions

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is open-source and available under the MIT License.

---
