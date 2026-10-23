# Transparent Dropdown Navigation Menu (HTML & CSS)

A horizontal navigation bar with dropdown sub-menus, built with **HTML & CSS only**. Semi-transparent black bars sit over a full-screen background image, and sub-menus appear on hover. **No JavaScript.**

🔗 **Live Demo:** https://muhammaduzairkhalid15.github.io/Transparent-Dropdown-Navigation-Menu-HTML-CSS-Uzi-Solutions/
💻 **Repository:** https://github.com/MuhammadUzairKhalid15/Transparent-Dropdown-Navigation-Menu-HTML-CSS-Uzi-Solutions

> ⭐ If this helped you, a star on the repo means a lot!

## ✨ Features

- 🧭 Horizontal menu with five items: Home, About, Things to do, Contact, News
- 🔽 Dropdown sub-menus that appear on hover (About, Things to do, Contact)
- 🪟 Semi-transparent dark bars over a full-screen background image
- 🟢 Green highlight on hover
- 🚫 No JavaScript

> Note: the dropdowns work on hover, so this version is designed for desktop and mouse use. Keyboard and touch support are listed under Next Steps.

## 🔧 Built With

- **HTML5**: nested lists
- **CSS3**: floats, descendant selectors, `:hover`, background-size cover

## 📂 Project Structure

```
Transparent-Dropdown-Navigation-Menu-HTML-CSS-Uzi-Solutions/
├── index.html
├── style.css
└── images/
    └── bg.jpg
```

## 🚀 Getting Started

1. Clone the repository
   ```
   git clone https://github.com/MuhammadUzairKhalid15/Transparent-Dropdown-Navigation-Menu-HTML-CSS-Uzi-Solutions.git
   ```
2. Open `index.html` in your browser and hover over the menu items.

## 🧠 How the Dropdown Works

```css
ul li ul li {
    display: none;
}

ul li:hover ul li {
    display: block;
}
```

Sub-menu items are hidden by default. When you hover a parent item, its nested items switch to `display: block`.

## 💡 What I Practiced

- Nesting lists to build multi-level menus
- Showing and hiding elements with `:hover` and descendant selectors
- Building a horizontal menu with floats
- Full-screen backgrounds with `background-size: cover`
- Creating a transparent look over an image

## 🔜 Next Steps

- Use `rgba()` backgrounds instead of `opacity` so the text stays fully opaque
- Add `:focus-within` for keyboard users
- Make the menu work on touch screens and small screens

## 📬 Feedback

Suggestions are welcome. Open an issue or reach out on LinkedIn!
