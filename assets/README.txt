# Construction & Design - Landing Page Optimization

A modern, fully responsive landing page tailored for the **construction and architectural industry**. The primary focus of this project was to refactor raw, auto-generated code from a visual web builder into a clean, semantic, and high-performance production-ready website.

## 🚀 Optimization Result: W3C Validated
The website underwent manual code refactoring and rigorous verification.
* **W3C Validator Errors:** 0
* **W3C Validator Warnings:** 0
* The codebase is now fully accessible (a11y) and highly optimized for SEO.

## 🛠️ Implemented Improvements (Refactoring)
* **HTML5 Semantics:** Replaced generic, invalid sections created by the builder with appropriate structural tags (`<header>`, `<footer>`).
* **Accessibility (ARIA):** Implemented proper bindings for tab components (`role="tab"`, `aria-controls`, `role="tabpanel"`) to ensure smooth screen-reader navigation.
* **Heading Hierarchy:** Restructured heading tags (`<h1>` -> `<h2>` -> `<h3>`) to form a logical document outline without altering the visual design.
* **Code Cleanup:** Purged redundant and non-standard editor attributes (such as `once`, `data-bs-version`, and stray `</hr>` tags).

## 🧰 Tech Stack
* **HTML5** (Clean, semantic markup)
* **Bootstrap 5.1** (Responsive mobile-first CSS framework)
* **Custom CSS** (Layout styling and display classes)
* **JavaScript DOM** (Interactive components and event handling)

## 📸 Project Structure
```text
├── index.html          # Clean and fully validated main HTML file
├── assets/             # Project assets
│   ├── css/            # Style sheets and framework libraries
│   ├── js/             # JavaScript files (Bootstrap functionality)
│   └── images/         # Optimized graphics and images
└── README.txt           # Project documentation
```

## 📝 License & Inspiration
The UI layout is inspired by the industrial project from [360procent.com.pl](https://360procent.com.pl). The codebase has been completely overhauled, optimized, and tailored for portfolio purposes.