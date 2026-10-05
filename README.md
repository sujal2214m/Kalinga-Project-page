# Kalinga University Practical / Assignment Cover Page Generator

A modern, browser-based **Practical & Assignment Cover Page Generator** designed for Kalinga University students.

The tool lets students enter academic details, customize the cover page, preview it instantly, and generate a print-ready A4 document.

🔗 **Live Demo:**  
https://sujal2214m.github.io/Kalinga-Project-page/

---

## ✨ Features

- 📘 Practical cover page generation
- 📝 Assignment cover page generation
- 🎨 Multiple cover page themes
- 🔤 Multiple font styles
- 👀 Real-time canvas preview
- 📄 A4 print-ready output
- 🧑‍🎓 Student information fields
- 📚 Academic and course information
- 👨‍🏫 Faculty / teacher information
- 🖼️ University branding
- 🧹 Clear entered details
- 💾 Saves selected preferences in the browser
- 📱 Responsive interface
- ♿ Keyboard-friendly focus states
- 🎞️ Reduced-motion support
- ⚡ Client-side application
- 🚫 No account or login required

---

## 🎓 Cover Page Types

The generator supports:

### Practical

```text
PRACTICAL ON
[Subject Name]
```

### Assignment

```text
ASSIGNMENT ON
[Subject Name]
```

A segmented selector lets users switch between the two formats.

---

## 📋 Details Supported

### Academic Details

- Session
- Semester
- Subject
- Program
- Course Code
- Faculty / Teacher

### Student Details

- Student Name
- Roll Number
- Enrollment Number

The form includes validation and inline error messaging for invalid or incomplete fields.

---

## 🎨 Cover Page Themes

The project provides selectable visual themes with thumbnail previews.

Current themes include:

- Circuit
- Ocean
- Hexagon
- Blueprint
- Sunrise
- Confetti
- Classic

Each theme is previewed using a canvas thumbnail before selection.

---

## 🔤 Font Selection

The cover page supports multiple font choices, including:

- Handwritten
- Times New Roman
- Georgia
- Garamond
- Arial
- Calibri

The interface also loads several web fonts for the application UI and cover rendering.

---

## 🖥️ Modern Glass-Style UI

The latest interface uses a modern glass-inspired design with:

- Glassmorphism panels
- Backdrop blur
- Rounded cards
- Gradient background
- Navy and gold visual branding
- Responsive layout
- Interactive controls
- Soft shadows
- Sticky preview area on desktop

The header also contains university branding and a creator profile section.

---

## 👀 Live A4 Preview

The cover is rendered using the **HTML Canvas API**.

The canvas uses an A4 proportion:

```text
2480 × 3508
```

The preview scales responsively while maintaining the same aspect ratio.

The desktop layout displays the form and preview side-by-side, while smaller screens switch to a single-column layout.

---

## 📄 Print / PDF Workflow

The project is designed around a simple workflow:

```text
Enter Details
      ↓
Select Practical / Assignment
      ↓
Choose Theme
      ↓
Choose Font
      ↓
Preview Cover
      ↓
Generate / Download
      ↓
Print
```

The cover is rendered in the browser, so the core generation experience does not require a backend server.

---

## 💾 Saved Preferences

The application stores selected interface preferences locally in the browser.

This allows preferences such as the selected:

- Cover type
- Font
- Theme

to remain available when the user returns to the tool.

---

## 📱 Responsive Design

The application adapts to different screen sizes.

### Desktop

```text
┌────────────────────┬──────────────────────┐
│     Input Form     │     A4 Preview       │
│                    │                      │
└────────────────────┴──────────────────────┘
```

### Mobile

```text
┌──────────────────────┐
│      Input Form      │
├──────────────────────┤
│      A4 Preview      │
└──────────────────────┘
```

At smaller widths, the preview moves below the form and the desktop sticky behavior is removed.

---

## ♿ Accessibility & UX

The interface includes:

- Visible keyboard focus states
- Form labels
- Inline validation messages
- Responsive controls
- Reduced-motion support using `prefers-reduced-motion`
- Large clickable controls
- Clear visual selection states

---

## 🛠️ Technologies Used

### Frontend

- HTML5
- CSS3
- JavaScript

### Browser APIs / Features

- HTML Canvas API
- LocalStorage API
- File input
- Responsive CSS
- CSS backdrop filters

### Fonts

- Google Fonts
- System fallback fonts

---

## 🏗️ Application Architecture

The application is primarily client-side:

```text
                ┌─────────────────┐
                │   User Input    │
                └────────┬────────┘
                         ↓
                ┌─────────────────┐
                │ Form Validation │
                └────────┬────────┘
                         ↓
                ┌─────────────────┐
                │ Theme + Font    │
                │ Selection       │
                └────────┬────────┘
                         ↓
                ┌─────────────────┐
                │ Canvas Renderer │
                └────────┬────────┘
                         ↓
                ┌─────────────────┐
                │ Live A4 Preview │
                └────────┬────────┘
                         ↓
                ┌─────────────────┐
                │ Final Output    │
                └─────────────────┘
```

---

## 📁 Project Structure

```text
Kalinga-Project-page/
│
├── index.html
└── README.md
```

The main application is contained in the HTML file, including the interface, styling, canvas rendering logic, and client-side functionality.

---

## 🚀 Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/sujal2214m/Kalinga-Project-page.git
```

### 2. Enter the project directory

```bash
cd Kalinga-Project-page
```

### 3. Open the project

Open `index.html` in a modern browser.

For development, you can also use the **Live Server** extension in VS Code.

---

## 🌐 Live Demo

Try the generator online:

**https://sujal2214m.github.io/Kalinga-Project-page/**

---

## 🎯 Project Objective

Creating practical and assignment cover pages manually can become repetitive for students.

This project simplifies the process by providing a ready-to-use interface where students can:

```text
Enter Information
       ↓
Customize Design
       ↓
Preview
       ↓
Generate
       ↓
Print
```

The goal is to reduce repetitive formatting work while providing a consistent and professional-looking cover page.

---

## ⚡ Why Use It?

Instead of repeatedly editing a document template, students can use the generator to quickly create a cover page.

### Traditional Workflow

```text
Find Template
     ↓
Open Document
     ↓
Edit Details
     ↓
Fix Alignment
     ↓
Export
     ↓
Print
```

### With This Generator

```text
Enter Details
     ↓
Select Design
     ↓
Preview
     ↓
Generate
     ↓
Print
```

---



## 🤝 Contributing

Contributions and suggestions are welcome.

### Create a branch

```bash
git checkout -b feature/new-feature
```

### Commit your changes

```bash
git add .
git commit -m "Add new feature"
```

### Push the branch

```bash
git push origin feature/new-feature
```

Then open a Pull Request.

---

## 🐛 Bug Reports & Suggestions

If you find a bug or have an idea for improving the project, open an issue in the GitHub repository.

**Repository:**  
https://github.com/sujal2214m/Kalinga-Project-page/

---

## 👨‍💻 Developer

### Sujal Kumar Chandravanshi

**B.Tech CSE (AI & ML)**  
**Kalinga University, Raipur**

GitHub:  
https://github.com/sujal2214m

LinkedIn:  
https://www.linkedin.com/in/sujal2214m/

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

---

## 📄 License

This project is created for educational and personal use.

For commercial use, redistribution, or major modifications, please contact the developer.

---

## ❤️ Made for Students

Made with ❤️ for **Kalinga University students**.

**Enter → Customize → Preview → Generate → Print**
