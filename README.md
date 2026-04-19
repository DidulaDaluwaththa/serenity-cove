# 🌿 Serenity Cove | Luxury Cave Dining Web Experience

> A bespoke front-end web interface developed for a conceptual luxury waterfall cave dining restaurant in Ella, Sri Lanka. 

**Live Demo:** [View Serenity Cove Here](https://diduladaluwaththa.github.io/serenity-cove/)

## 📖 Overview
Serenity Cove is an immersive, high-end digital presence created to mirror a luxury restaurant's physical brand—blending nature, exclusivity, and a zero-waste philosophy. This project was commissioned by hospitality students at the **William Angliss Institute, Sri Lanka** for their final capstone hotel project. 

Moving away from standard templates, this project features a custom-engineered UI, utilizing a bespoke nature-inspired color palette, smooth scroll animations, and a premium typographic hierarchy.

## ✨ Key Features
* **Custom Design System:** Built with a fully customized **Tailwind CSS** configuration, mapping exact Pantone and Dulux shades to evoke the feeling of sandy beaches, deep caves, and rich forests.
* **Immersive Animations:** Utilizes **GSAP (GreenSock)** and **ScrollTrigger** for elegant parallax hero sections, custom text-glow effects, and synchronized content reveals.
* **Dynamic Navigation:** A responsive, glassmorphism-styled `navbar.html` that is dynamically fetched across all pages using Vanilla JavaScript and transitions cleanly on scroll.
* **Fully Responsive:** Fluid typography and flexible CSS Grid layouts ensure a flawless, premium experience across mobile, tablet, and desktop displays.

## 🛠️ Tech Stack
* **HTML5** (Semantic structure)
* **Tailwind CSS** (Via CDN with a custom inline theme configuration)
* **GSAP & ScrollTrigger** (High-performance scroll animations)
* **Vanilla JavaScript** (Component fetching and DOM manipulation)
* **Google Fonts** (*Cormorant Garamond* for luxury headings, *Inter* for clean UI copy)

## 🎨 Brand Color Palette
The UI abandons standard black and white in favor of a warm "Nature & Luxury" palette:
* `bg-sand` (#E3DACF) - Primary background (Dulux Sandy Beach)
* `text-darknight` (#454341) - Primary text & footers (Pantone Dark Night)
* `bg-treetop` (#4B5E40) - Primary Call-to-Action buttons & Vegan badges (Pantone Treetop Green)
* `text-buckthorn` (#9C6D33) - Accents, borders & Signature badges (Pantone Buckthorn Brown)
* `text-daphne` (#2A5C8A) - Subtle highlights & GF badges (Pantone Daphne Blue)

## 📂 Project Structure

```text
├── index.html          # Home / About Us page
├── experience.html     # Cave dining & philosophy showcase
├── menu.html           # A La Carte, Brunch, High Tea & Beverage menus
├── reserve.html        # Booking form & policies
├── navbar.html         # Reusable navigation component
└── images/             # Local image assets
    ├── herobg.jpg
    ├── exp-hero.jpg
    ├── menu-hero.jpg
    └── ...
```

## 🚀 How to Run Locally
Because this project uses the JavaScript `fetch()` API to load the `navbar.html` file globally across the site, it needs to be run through a local web server. Opening the HTML files directly in your browser (via `file://`) will cause a CORS error, and the navbar will not load.

1. Clone the repository:
   ```bash
   git clone [https://github.com/diduladaluwaththa/serenity-cove.git](https://github.com/diduladaluwaththa/serenity-cove.git)

2. Open the project folder in **VS Code**.
3. Install the **Live Server** extension.
4. Click **"Go Live"** at the bottom right of your editor to spin up a local server.

## 👨‍💻 Author
**Didula Daluwaththa**
* [LinkedIn](www.linkedin.com/in/diduladaluwaththa) 
* [Linktree](https://linktr.ee/didula.daluwaththa)


