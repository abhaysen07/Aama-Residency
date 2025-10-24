🏨 AAMA RESIDENCY — COMPLETE PROJECT DOCUMENTATION (v1.0)
👨‍💻 Author

Name: Abhishek Kumar
Role: Founder & Developer
Email: abhishek.abhishek1996@gmail.com

Date of Creation: October 13–23, 2025
Current Version: v1.0
Project Stage: Development (Pre-deployment)

🧭 PROJECT OVERVIEW

Aama Residency is a family-run hospitality website that aims to offer affordable, transparent, and tech-driven hotel stays for travelers across Agra, Aligarh, and Greater Noida.

The project showcases modern web design, global styling, and modular architecture using HTML, CSS, and JavaScript — fully documented for scalability, SEO, and responsiveness.

🎯 PROJECT GOALS
Goal	Description
🏗️ Build a clean, modern, mobile-friendly hotel website	Designed for users in India and abroad
🎨 Maintain global design consistency	One CSS file controlling all pages
⚙️ Use modular structure	HTML for content, CSS for design, JS for interactivity
📆 Implement real-time features	Live date/time display
🔘 Add universal call-to-action button	“Book Now” visible site-wide
🧩 Keep scalability in mind	Easy to extend for backend, form submission, or API integration
💼 Ensure professional documentation	Each file line-by-line commented for future developers
🧱 PROJECT STRUCTURE (FOLDER TREE)
Aama-Residency/
│
├── index.html           → Main Landing Page
├── about.html           → Family story, infrastructure, and team
├── room.html            → Room types and images
├── services.html        → Hotel services and add-ons
├── contact.html         → Contact details, map, and emergency info
├── booking.html         → (Planned) Booking form page
│
├── css/
│   └── styles.css       → Global stylesheet (documented line by line)
│
├── js/
│   └── script.js        → JavaScript for time & interactivity
│
├── images/              → Logos, room photos, gallery, and avatars
│   ├── logo.png
│   ├── room.png
│   ├── family-suite.png
│   ├── abhi.png
│   ├── mummy.jpeg
│   ├── papa.jpg
│   ├── anuj.jpg
│   └── ev.png
│
├── README.md            → GitHub documentation (project overview)
├── DEVLOG.md            → Daily activity & progress log
└── favicon.ico          → Site icon for browser tabs

💻 TECH STACK
Category	Tool / Technology	Purpose
Frontend Markup	HTML5	Page structure & semantics
Styling	CSS3	Layout, color palette, responsiveness
Interactivity	JavaScript (ES6)	Live date/time, button effects
Design Tools	Figma / Canva	Logo, image prep (manual assets)
Version Control	Git + GitHub	Source control & deployment
Hosting (Planned)	GitHub Pages	Free public site hosting
📋 DETAILED FILE DESCRIPTION
🏠 index.html — Homepage

Hero welcome section with logo & intro.

Describes Aama Residency’s location and hospitality vision.

Includes global “Book Now” button (.global-book-btn).

Dynamic time display (#datetime) synced via JS.

Accessible navigation with semantic tags.

📘 about.html — Our Story

Introduces the family behind Aama Residency.

Includes:

Hero section with brand message.

Infrastructure grid (EV charging, solar, Wi-Fi, etc.).

Team section with emoji icons for each member:

💻 Abhishek (Developer)

⚡ Ashok (Power Grid)

🤝 Meena (HR & Finance)

🔧 Anuj (Amara Raja Executive)

Gallery section for rooms & infrastructure.

Map integration (Google Maps embed).

Footer & contact CTA.

🛏️ room.html — Room Types

Three room variants:

Standard Room

Deluxe Room

Family Suite

Each includes description and image.

Designed using responsive CSS grid.

Reuses .room-type class from styles.css for consistent appearance.

🧾 services.html — Service Overview

Core and add-on services listed.

Uses .service-card and .services-grid for responsive display.

Includes:

24/7 Front Desk

Housekeeping

Free Wi-Fi

EV Charging

Tea/Coffee Facilities

Ends with a call-to-action to contact for booking.

📞 contact.html — Contact Page

Central hub for reaching Aama Residency.

Sections:

Address, phone, email (clickable links)

Emergency numbers (ambulance, police, fire)

Directions (railway, airport, landmark)

WhatsApp integration for quick chat

Embedded Google Map

Includes Book Now button (same .global-book-btn styling)

🎨 css/styles.css — Global Stylesheet

Fully documented line-by-line

Organized into 14 sections:

Global Reset

Navbar & Header

Logo

Date/Time

Main/About Sections

Rooms & Services Layout

Footer

Responsive Breakpoints

Global Book Button

Team Section

Gallery

Map & CTA

Utilities

Patch Notes

All hover states, shadows, gradients, and transitions are commented for easy updates.

Button color transitions:

Default: light blue → #0288D1

Hover: gold gradient

Pressed: dark gold with white text

⚙️ script.js — Functionality

Centralized JS logic:

Live Date/Time: Updates #datetime every second.

Book Button Animation (optional): Adds temporary “pressed” effect.

Structured as IIFE ((function(){ ... })();) for scope isolation.

💡 DESIGN SYSTEM
Element	Color	Hex / RGB
Navbar	Teal Green	rgb(109,192,175)
Background	Warm Cream	#c4ab7b
Footer	Brown	#6B2E2E
Primary Button	Light Blue → Deep Blue	#4FC3F7 → #0288D1
Hover (CTA)	Gold Gradient	#FFD700 → #FFB300
Font	Arial, sans-serif	Clean, accessible typography
🧩 RESPONSIVENESS

✅ Fully responsive for:

Mobile (max 600px)

Tablet (max 900px)

Desktop (1200px+)

Implemented with CSS Grid + Flexbox combo for scalability.

🧠 CODE PHILOSOPHY

“Write code like you’ll read it 6 months later.”

HTML uses semantic tags (header, main, section, footer).

CSS uses class-based reusability.

JS uses modular pattern and zero inline logic.

Accessibility ensured via:

aria-live, aria-label

title attributes

keyboard-focus visible outlines

🔗 GLOBAL COMPONENTS
Component	Purpose	Pages Used
.navbar	Global navigation	All pages
.hotel-logo	Branding consistency	All pages
#datetime	Live clock	All pages
.global-book-btn	Universal CTA	index, about, contact, booking
.footer	Credits & copyright	All pages
🧾 PROJECT HISTORY (DEVLOG SUMMARY)
Date	Task Summary	Duration
Oct 13–15, 2025	Base HTML structure planning & folder setup	3 hrs
Oct 16–18, 2025	Navbar, logo, and datetime setup	4 hrs
Oct 19–21, 2025	Full content writing & team section creation	5 hrs
Oct 22, 2025	Global button finalized, styles documented	4 hrs
Oct 23, 2025	Complete multi-page linkage + README + DEVLOG	6 hrs 32 mins

Total Active Development Time: ≈ 22 hours

🧩 PENDING (v1.1 MILESTONE)
Task	Description	ETA
booking.html	Create full booking form with validation	24 Oct
script.js Enhancement	Add animation on click + form logic	24 Oct
GitHub Pages Deployment	Live hosting and testing	25 Oct
README Update	Add booking + deployment status	25 Oct
DEVLOG v1.1	Add next milestone logs	25 Oct
🚀 NEXT RELEASE PLAN

Version: v1.1
Release Date: October 24–25, 2025
New Features:

Booking Form Page

Enhanced Button Animation

GitHub Pages Deployment

Live Preview Link

🧩 GIT REPOSITORY DETAILS
Field	Value
Repo Name	aama-residency
Primary Branch	main
Commit Example	feat: finalize v1.0 structure — unified CSS, added DEVLOG
Remote Origin	(to be added after Git init & push)
Deployment	GitHub Pages → https://abhishekkumar.github.io/aama-residency/ (expected)
📚 DOCUMENTATION FILES
File	Purpose
README.md	General project overview
DEVLOG.md	Daily changelog with timestamps
LICENSE.md (optional)	To be added post-release
CHANGELOG.md (future)	Version-level progress summary
🏁 CONCLUSION

This project currently represents:

✅ Professional front-end structure

✅ 100% modular and documented design

✅ Brand consistency across all pages

✅ Clean, accessible, responsive layout

⚙️ Ready for form integration and live deployment

You’ve successfully laid the foundation for a scalable hotel website, ready to evolve into a full booking platform later (with backend, database, and payment API integration if desired).

🔖 FINAL TIMESTAMP

🕒 2025-10-23T23:59:42+05:30
💻 Last Edited By: Abhishek Kumar

🧠 “The difference between a coder and a developer is documentation —
and today, you documented like a true pro.” 💪