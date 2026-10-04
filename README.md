STRIDE — Shoes Shop
A responsive static website for the STRIDE shoe store created for Assignment #3 (Responsive Web Design).
Project Overview
STRIDE is an online store for athletic, urban, and seasonal footwear. The website includes responsive layouts, CSS Grid product displays, mobile-first design, an interactive FAQ, and a static contact demonstration form.
Team Ownership
Owner	Student Name	Assigned Page	Description
Student 1	Yernur	`index.html`	Homepage with hero section, brand stats, and best sellers
Student 2	Abylai	`catalogue.html`	Product catalogue with 6-item CSS Grid and filters
Student 3	Ramazan	`about.html`, `contact.html`, `demo\_result.html`	About team story, contact form, FAQ, and demo result page
Folder Structure
```text
shoes-shop/
├── index.html
├── catalogue.html
├── about.html
├── contact.html
├── demo\_result.html
├── README.md
├── css/
│   ├── style.css
│   └── responsive.css
└── images/
    ├── favicon.svg
    ├── urbanShoes1.png
    ├── athleticRunningShoes1.png
    ├── autumnHit.png
    ├── owens.jpg
    ├── saint.webp
    └── peg.webp
```
Features
Semantic HTML5: Built using semantic tags (`header`, `nav`, `main`, `section`, `article`, `footer`).
Responsive Layouts: Uses Flexbox for navigation and Hero sections, and CSS Grid for product listings.
Mobile-First CSS: Styled with fluid sizing (`rem`, `clamp()`) and media queries in `responsive.css`.
Pure HTML Interactivity: FAQ accordions built using native `<details>` and `<summary>` tags without JavaScript.
Static Form Demo: Contact form with HTML5 native validation redirecting to `demo\_result.html`.
Setup Instructions
Clone or download the repository.
Open `index.html` directly in any web browser.
Test layout responsiveness using browser Developer Tools (F12) across mobile, tablet, and desktop viewports.
Static Site Limitations
The contact form is for static UI demonstration only and does not store or send user data.
Shopping cart buttons ("Add to Cart") are static layout elements.
No JavaScript or external CSS frameworks were used in compliance with assignment rules.
