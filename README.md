                	Serenity Cove | Cave Dining Website
A luxury, immersive restaurant website built for a unique waterfall cave dining 				experience in Ella, Sri Lanka.


	📖 Overview
	------------
Serenity Cove is a conceptual luxury dining destination. This repository contains the front-end code for their official website, designed to reflect the restaurant's blend of nature, exclusivity, and modern fusion cuisine. The UI features a bespoke earthy color palette, smooth scroll animations, and a premium typographic hierarchy.


	✨ Key Features
- Immersive Animations: Utilizes GSAP & ScrollTrigger for elegant fade-ins, parallax hero sections, and synchronized content reveals.

- Custom Design System: Built with Tailwind CSS, featuring a meticulously injected custom color configuration based on Pantone and Dulux nature-inspired tones.

- Dynamic Navigation: A responsive, glassmorphism-styled navbar.html that is dynamically fetched across all pages and transitions on scroll.

- Fully Responsive: Fluid typography and flexible grid layouts ensure a flawless experience across mobile, tablet, and desktop displays.

- Modern Form Handling: A beautifully styled reservation system ready for backend integration.


	🛠️ Tech Stack
	-------------

  HTML5 (Semantic structure)

- Tailwind CSS (Via CDN for rapid, utility-first styling)

- GSAP / ScrollTrigger (High-performance scroll animations)

- Vanilla JavaScript (Component fetching and DOM manipulation)

- Google Fonts (Cormorant Garamond for luxury headings, Inter for clean UI copy)

 	🎨 Color Palette
	----------------
- The UI completely abandons standard black and white in favor of a custom "Nature & Luxury" palette:

- bg-sand (#E3DACF) - Primary background (Dulux Sandy Beach)

- text-darknight (#454341) - Primary text (Pantone Dark Night)

- bg-treetop (#4B5E40) - Primary Call-to-Action buttons (Pantone Treetop Green)

- text-buckthorn (#9C6D33) - Accents & borders (Pantone Buckthorn Brown)

- text-daphne (#2A5C8A) - Subtle highlights (Pantone Daphne Blue)

	📂 Project Structure
	--------------------

├── index.html          # Home / About Us page
├── experience.html     # Cave dining & philosophy showcase
├── menu.html           # A La Carte, Brunch, High Tea & Beverage menus
├── reserve.html        # Booking form & policies
├── navbar.html         # Reusable navigation component
├── herobg.jpg		# Local image asset
├── exp-hero.jpg	# Local image asset
├── menu-hero.jpg	# Local image asset
└── ...


Take a look at the live project here: https://diduladaluwaththa.github.io/serenity-cove/

	🚀 How to Run Locally
	---------------------
Because this project uses the Javascript fetch() API to load the navbar.html file into the other pages, it needs to be run through a local web server (opening the files directly via file:// in your browser will cause a CORS error for the navbar).


👨‍💻 Designed & Developed By Didula Daluwaththa



