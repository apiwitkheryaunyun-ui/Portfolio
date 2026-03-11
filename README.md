# Apiwit Kheryaunyun — Portfolio

A clean, responsive static portfolio website showcasing my projects, skills, and contact information.

---

## 📋 Project Overview

This is a personal portfolio website built with plain HTML, CSS, and JavaScript — no frameworks or build tools required. It is designed to be fast, lightweight, and easy to deploy anywhere that serves static files.

---

## ✨ Features

- Responsive design that works on desktop, tablet, and mobile
- Projects showcase section
- Skills & technologies section
- About me section
- Contact section
- Clean, modern UI

---

## 📁 Folder Structure

```
Portfolio/
├── index.html          # Main entry point
├── css/
│   └── style.css       # Main stylesheet
├── js/
│   └── main.js         # JavaScript interactions
├── images/             # Images and icons
├── .gitignore          # Files excluded from version control
├── LICENSE             # MIT License
└── README.md           # Project documentation
```

---

## 🚀 Local Run Instructions

No build step is required. Simply open the project in your browser:

### Option 1 — Open directly

```bash
# Clone the repository
git clone https://github.com/apiwitkheryaunyun-ui/Portfolio.git
cd Portfolio

# Open index.html in your default browser
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

### Option 2 — Use a local development server (recommended)

Using Python (built-in):

```bash
# Python 3
python -m http.server 8080
```

Then visit [http://localhost:8080](http://localhost:8080) in your browser.

Using Node.js (`npx`):

```bash
npx serve .
```

Then follow the URL printed in the terminal.

---

## 🌐 Deployment — GitHub Pages

This site is deployed via **GitHub Pages** from the `main` branch.

### Steps to deploy your own fork

1. Fork or clone this repository to your GitHub account.
2. Go to **Settings → Pages** in your repository.
3. Under **Source**, select the `main` branch and the `/ (root)` folder.
4. Click **Save**.
5. GitHub Pages will publish the site at:

```
https://<your-username>.github.io/Portfolio/
```

> **Tip:** If you rename the repository to `<your-username>.github.io`, the site will be available at `https://<your-username>.github.io` (no sub-path needed).

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
