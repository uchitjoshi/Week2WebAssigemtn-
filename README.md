# 🌐 Uchit Joshi — Personal Portfolio

> **A simple, semantic, and accessible personal portfolio built using strictly HTML5.**

This project is a single-page personal portfolio created as part of my **Week 2 HTML5 assignment**. The website uses **semantic HTML5 elements** to organize the content without using CSS, JavaScript, or inline styling.

The main purpose of this project is to demonstrate my understanding of **HTML5 document structure, semantic elements, accessibility, navigation, forms, project sections, and basic web development practices**.

---

## 👨‍💻 About Me

Hello! I am **Uchit Joshi**, an Information Technology student from Nepal.

I am interested in:

* 💻 Web Development
* 🐍 Python Programming
* 🔐 Cybersecurity
* 🗄️ Databases
* 🌐 Web Technologies
* 🚀 Learning New Technologies

This portfolio provides a simple overview of my background, technical skills, projects, and contact information.

---

## ✨ Project Features

The portfolio includes:

| Section       | Description                                         |
| ------------- | --------------------------------------------------- |
| 🏠 Header     | Contains my name and primary navigation             |
| 🔗 Navigation | Internal links to different sections                |
| 👤 About Me   | Personal introduction and profile image             |
| 🛠️ Skills    | Technical skills presented using a description list |
| 📂 Projects   | Individual project modules using `<article>`        |
| 📧 Contact    | Accessible contact form with labels                 |
| 📌 Footer     | Copyright information                               |

---

## 🧱 HTML5 Semantic Structure

The website uses semantic HTML5 elements to provide a meaningful document structure.

```text
<body>
│
├── <header>
│   ├── <h1>
│   └── <nav>
│       └── <ul>
│
├── <main>
│   │
│   ├── <section> About Me
│   │   └── <img>
│   │
│   ├── <section> Skills
│   │   └── <dl>
│   │
│   ├── <section> Projects
│   │   ├── <article> Banking System
│   │   └── <article> Quiz Game
│   │
│   └── <section> Contact
│       └── <form>
│
└── <footer>
```

Using semantic elements makes the structure of the webpage easier for browsers, developers, and assistive technologies to understand.

---

## 🛠️ Technologies Used

* **HTML5**
* Semantic HTML elements
* HTML forms
* Internal page navigation
* Git & GitHub

### No CSS or JavaScript

This assignment intentionally does **not** use:

* ❌ CSS
* ❌ Inline styling
* ❌ JavaScript
* ❌ External UI frameworks

The webpage therefore uses the **browser's default HTML rendering**.

---

## 📁 Project Structure

```text
portfolio/
│
├── index.html
├── README.md
│
└── images/
    └── profile.jpg
```

### File Description

**`index.html`**
Contains the complete single-page personal portfolio.

**`images/profile.jpg`**
Contains the profile image displayed in the About Me section.

**`README.md`**
Provides information about the project, implementation, and structure.

---

## 📂 Projects

### 🏦 Banking System

A simple banking system developed using the **C programming language**.

The project demonstrates basic programming concepts and problem-solving skills.

🔗 [View Project](https://github.com/uchitjoshi)

---

### 🎮 Quiz Game

A simple quiz game created as a programming project.

The project demonstrates basic programming logic and interaction with users.

🔗 [View Project](https://github.com/uchitjoshi)

---

## ♿ Accessibility

Accessibility was considered during the development of this portfolio.

Examples include:

* The profile image contains descriptive `alt` text.
* Form fields have explicitly associated `<label>` elements.
* Semantic HTML5 elements are used to organize the page.
* Navigation links provide direct access to different sections.
* The document uses meaningful headings such as `<h1>`, `<h2>`, and `<h3>`.

Example:

```html
<label for="email">Email:</label>
<input type="email" id="email" name="email">
```

The `for` attribute of the label matches the `id` of the input field.

---

## ✅ HTML Validation

The HTML document was tested using the **W3C HTML Validator** to identify markup errors and confirm that the document follows HTML standards.

📸 A screenshot of the successful validation result is included in the project report as required by the assignment.

---

## 🖥️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/uchitjoshi/portfolio.git
```

### 2. Open the project folder

```bash
cd portfolio
```

### 3. Open `index.html`

Double-click `index.html` or open it using a web browser.

No server, framework, or additional software is required.

---

## 📸 Project Output

The portfolio is intentionally displayed using the browser's default HTML layout because the assignment requires **strictly semantic HTML5 without CSS or inline styling**.

The project report contains screenshots of:

1. HTML source code
2. Portfolio webpage output
3. W3C HTML Validator successful result

---

## 🎯 Learning Objectives

Through this project, I practiced:

* Understanding HTML5 document structure
* Using semantic HTML elements
* Creating internal navigation links
* Adding accessible images
* Creating description lists
* Organizing projects using `<article>`
* Creating accessible HTML forms
* Using labels with form controls
* Validating HTML documents
* Uploading source code to GitHub

---

## 📚 References

Meyer, J. (2022). *The essential guide to HTML5: Using games to learn HTML5 and JavaScript* (3rd ed.). Apress.

Shi, W., Moses, H., Yu, Q., Malachowsky, S., & Krutz, D. E. (2024). ALL: Supporting experiential accessibility education and inclusive software development. *ACM Transactions on Software Engineering and Methodology, 33*(2), Article 39. https://doi.org/10.1145/3625292

---

## 👨‍🎓 Author

**Uchit Joshi**

Information Technology Student
Nepal

---

### ⭐ Project Summary

> **Simple HTML. Semantic Structure. Accessible Design.**

This project demonstrates how a functional personal portfolio can be created using **HTML5 alone**, while following semantic structure and basic accessibility principles.
