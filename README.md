# 🔢 Minimum Beam Depth Calculator (ACI 318-19)

A lightweight, browser-based web app that calculates the **minimum required depth of nonprestressed reinforced concrete beams** in accordance with **ACI 318-19 Section 9.3.2.1**. Ideal for civil and structural engineers needing quick, code-compliant checks during design.

🌐 **Live Demo:**  
[https://rodranchez.github.io/minimum-d-beam-aci318/](https://rodranchez.github.io/minimum-d-beam-aci318/)

---

## 📌 Features

- 📐 Calculates minimum depth based on **ACI 318-19 Sec. 9.3.1.1**
- 🔁 Toggle between **SI units (meters)** and **Imperial units (feet)**
- 🔄 Automatically converts input values when units are switched
- 💻 Desktop layout: input (left) + results (right)
- 📱 Responsive layout: stacked inputs and results on smaller screens
- ⬇️ Scroll-to-results button appears on mobile for smooth navigation
- ⚡ No installation needed — runs entirely in the browser

---

## 🧰 Tech Stack

- **HTML5** — Page structure  
- **CSS3** — Styling and responsive design  
- **JavaScript (Vanilla)** — Calculation logic and unit conversion  

---

## 🗂️ Folder Structure

- `index.html` — Main HTML structure
- `styles/`
  - `styles.css` — Styling and responsive layout rules
- `scripts/`
  - `main.js` — Beam depth calculation & unit toggle logic
- `images/`
  - `logo.png` — Logo used in the navbar

---

## 🧪 How to Use

1. **Toggle the unit system** (SI or Imperial)
2. **Enter the beam’s clear span length**
3. **Select the beam support condition** (e.g., simply supported, cantilevered)
4. **Toggle the unit system again if you just want to convert units** (SI or Imperial)
5. **View the calculated minimum required beam depth**

---

## 📱 Responsive Behavior

- **Desktop View:**
  - Navbar with logo
  - Two-column layout: inputs on the left, results on the right

- **Mobile View:**
  - Inputs and results stack vertically
  - A scroll button appears below the last input to bring users to the result section

---

## 📖 ACI Code Reference

> Based on **ACI 318-19 Section 9.3.1.1**: Minimum thickness for nonprestressed beams, depending on span and support conditions.

---

## 🙌 Support This Project

If you found this project helpful and want to support future tools like this, consider donating via PayPal:

👉 [paypal.me/rodjrranchez](https://paypal.me/rodjrranchez)

Your support is appreciated! 🙏

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

