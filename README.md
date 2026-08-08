# BookHaven — E-Commerce Book Store Website

A fully responsive, front-end e-commerce website for an online book store, built entirely with **HTML**, **CSS**, and **vanilla JavaScript (DOM manipulation)**. No backend, frameworks, or external libraries are used (Google Fonts for typography only).

---

## Project Overview

BookHaven is an online bookstore offering a curated collection of 12 books across four categories: Self-Help, Finance, Fiction, and Technology. The website provides a complete shopping experience including product browsing, search, category filtering, a shopping cart with quantity management, and a checkout form — all powered by client-side JavaScript.

---

## Features

### Home Page (`index.html`)
- Website logo and title with navigation bar
- Hero/banner section with call-to-action buttons and statistics
- Features strip (free delivery, wide selection, secure checkout, easy returns)
- Featured products section (dynamically rendered via JavaScript)
- Newsletter subscription section
- Footer with quick links, categories, and contact information

### Products Page (`products.html`)
- 12 products displayed in responsive product cards
- Each card includes: product image, name, author, price (with old price), category, star rating, and "Add to Cart" button
- Live search by book title or author name
- Category filter buttons (All, Self-Help, Finance, Fiction, Technology)
- "No results" message when search/filter returns nothing

### Shopping Cart Page (`cart.html`)
- View all items added to the cart
- Increase/decrease product quantity (with automatic removal at 0)
- Remove items from the cart entirely
- Dynamic calculation of subtotal, shipping (free over £30), and total
- Checkout form with validation (name, email, address)
- Empty cart state with call-to-action
- Order confirmation screen on successful checkout
- Cart persists across pages using `localStorage`

### About Page (`about.html`)
- Company story with bookstore interior image
- Core values section (Curated Quality, Customer First, Lifelong Learning)
- Team member profiles with photos and descriptions

### Contact Page (`contact.html`)
- Contact information card (address, phone, email, live chat)
- Contact form with full JavaScript validation:
  - Name (minimum 2 characters)
  - Email (valid format check)
  - Phone (optional, validated if provided)
  - Subject (dropdown selection)
  - Message (minimum 10 characters)
- Real-time error clearing on input
- Success message on valid submission

---

## Design Highlights

- **Responsive design**: Mobile-first approach with breakpoints for tablet (992px) and mobile (768px, 480px)
- **Consistent colour theme**: Deep navy primary with warm gold/amber accents
- **Product card shadows**: Hover effects with lift animation and image zoom
- **Hover effects**: On buttons, navigation links, product cards, and social icons
- **Toast notifications**: Slide-in confirmation messages for user actions
- **Mobile navigation**: Hamburger menu with animated icon
- **Accessibility**: Semantic HTML, ARIA labels, alt text on all images, keyboard-friendly forms

---

## Project Structure

```
BookHaven/
├── index.html          # Home page
├── products.html       # Product listing page
├── cart.html           # Shopping cart page
├── about.html          # About page
├── contact.html        # Contact page
├── css/
│   └── style.css       # All styles (responsive, layout, components)
├── js/
│   └── script.js       # All JavaScript (cart logic, rendering, validation)
├── media/
│   └── images/         # Book covers, bookstore, team photos, contact image
└── README.md           # This file
```

---

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and semantic markup |
| CSS3 | Styling, responsive design, animations |
| JavaScript (ES5) | DOM manipulation, cart logic, form validation |
| localStorage | Cart persistence across page navigation |
| Google Fonts | Typography (Playfair Display + Inter) |

No frameworks (React, Vue, Angular, jQuery) or external JavaScript libraries are used.

---

## Book Collection

| # | Title | Author | Category | Price |
|---|---|---|---|---|
| 1 | Atomic Habits | James Clear | Self-Help | £14.99 |
| 2 | The Psychology of Money | Morgan Housel | Finance | £12.99 |
| 3 | Rich Dad Poor Dad | Robert T. Kiyosaki | Finance | £13.49 |
| 4 | Think and Grow Rich | Napoleon Hill | Self-Help | £11.99 |
| 5 | The Alchemist | Paulo Coelho | Fiction | £10.99 |
| 6 | Ikigai | Héctor García & Francesc Miralles | Self-Help | £12.49 |
| 7 | Deep Work | Cal Newport | Self-Help | £15.99 |
| 8 | Harry Potter and the Sorcerer's Stone | J.K. Rowling | Fiction | £16.99 |
| 9 | The 7 Habits of Highly Effective People | Stephen R. Covey | Self-Help | £14.49 |
| 10 | The Pragmatic Programmer | Andrew Hunt & David Thomas | Technology | £39.99 |
| 11 | Clean Code | Robert C. Martin | Technology | £34.99 |
| 12 | Introduction to Algorithms | Cormen, Leiserson, Rivest & Stein | Technology | £59.99 |

---

## How to Run

1. Download or clone the project folder
2. Open `index.html` in any modern web browser (Chrome, Firefox, Safari, Edge)
3. No server or build step required — it runs entirely in the browser

---

## Learning Outcomes Addressed

- **LO1**: Create web pages using HTML & CSS — All 5 pages built with semantic HTML and comprehensive CSS
- **LO2**: Implement basic client-side scripting (JavaScript) — Cart management, search, filter, form validation, DOM rendering
- **LO3**: Design responsive layouts and apply web design best practices — Mobile-first responsive design with breakpoints
- **LO4**: Apply accessibility, UX, basic SEO and web development principles — ARIA labels, semantic HTML, meta tags, alt text, keyboard navigation

---

© 2026 BookHaven. All Rights Reserved.
