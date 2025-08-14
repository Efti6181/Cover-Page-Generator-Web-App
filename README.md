# 📄 Cover Page Generator Web App

** A modern, customizable, and user-friendly platform** designed to help students, professionals, and organizations quickly create **professional cover pages** for assignments, proposals, reports, and more.

🚀 **Live Demo:** [covgene.netlify.app](https://covgene.netlify.app) *(Database-dependent features currently disabled on live site due to Netlify hosting limitations)*

---

## 🌟 Overview

This project was developed as part of my **Internet Programming** course at **Premier University, Chittagong**. The goal was to create a **full-stack web application** that combines a clean interface, smart automation, and flexible customization to produce high-quality cover pages in minutes.

With **multiple ready-to-use templates**, **automatic profile information integration**, and **PDF download support**, the app is suitable for:

* 🎓 **Students** – Assignments, lab reports, project reports
* 🏢 **Professionals** – Business proposals, annual reports, presentations
* 📚 **Researchers** – Academic papers, conference submissions

---

## 🛠 Tech Stack

| Layer        | Technology                |
| ------------ | ------------------------- |
| **Frontend** | HTML, CSS, JavaScript     |
| **Backend**  | PHP                       |
| **Database** | MySQL                     |
| **Hosting**  | Netlify *(Frontend only)* |

⚠ **Note:** Due to Netlify's PHP and MySQL limitations, **login, profile management, and database-driven features** are not active in the live version. A full deployment will be made on a PHP/MySQL-supported host in the future.

---

## ✨ Key Features

### 👤 User Management

* **Registration & Login** – Create an account with name, email, and password.
* **Profile Management** – Update varsity name, department, student ID, section, and profile picture.

### ⚡ Smart Automation

* **Auto-Fill Details** – Profile information is automatically inserted when creating a new cover page, saving time and effort.

### 🎨 Customization Options

* Rich text editing: **bold**, *italic*, **font size adjustments**, text color changes, and more.
* Multiple **professional cover page templates** for different needs.

### 📄 Output Options

* **Instant PDF download** or **direct printing**.

### 🎓 Premier University Chittagong Special Templates

* Assignment cover pages
* Lab report covers
* Index pages tailored to PUC formatting standards

---

## 📌 Future Plans

* ✅ **Full-stack deployment** with all features enabled
* ✅ Enhanced template gallery with more customization options
* ✅ Cloud-based template storage for user convenience
* ✅ Advanced typography and layout controls

---

## 🚧 Current Limitations

Since the project is currently hosted on **Netlify**:

* PHP code cannot execute server-side
* MySQL database connection is disabled
* Login, search, and profile updates are not functional in the live demo

These features work in a local environment or when hosted on a PHP-supported server (e.g., XAMPP, WAMP, or cPanel hosting).

---

## 📂 Installation & Setup

If you want to run this project locally with **full functionality**:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/cover-page-generator.git
   cd cover-page-generator
   ```

2. **Set up PHP & MySQL environment:**

   * Install [XAMPP](https://www.apachefriends.org/) or [WAMP](https://www.wampserver.com/).
   * Start **Apache** and **MySQL** services.

3. **Import the database:**

   * Open `phpMyAdmin`
   * Create a new database (e.g., `coverpage_db`)
   * Import the provided `.sql` file from the `database` folder.

4. **Configure database connection:**

   * Update `config.php` with your database credentials.

5. **Run the application:**

   * Place project files inside the `htdocs` folder (for XAMPP)
   * Open in browser:

     ```
     http://localhost/cover-page-generator
     ```

---

## 📸 Screenshots

*(Add screenshots of your UI here — template selection, editor interface, PDF output preview, etc.)*

---

## 🤝 Contributing

Contributions, suggestions, and bug reports are welcome!
If you’d like to contribute:

1. Fork this repository
2. Create a new branch (`feature/new-feature`)
3. Commit changes and push
4. Submit a pull request

---

## 📜 License

This project is licensed under the **MIT License** – feel free to use, modify, and distribute it for personal or educational purposes.

---

## 👨‍💻 Author

**Najmul Alam Efti**
🎓 Premier University, Chittagong
📧 \[[your.email@example.com](mailto:your.email@example.com)]
🌐 [Live Demo](https://covgene.netlify.app)

---

I can also make this **visually attractive** with GitHub README badges (tech stack badges, Netlify badge, license badge, etc.) so your repo looks more professional and appealing.

Do you want me to make that styled, badge-rich version next? That will make your GitHub project page look much more polished.
