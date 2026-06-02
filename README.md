# 🍽️ Foodie's Restaurant Website

A multi-page, responsive restaurant website built with HTML, CSS, and Bootstrap 5.

## 📋 Overview

Foodie's is a static front-end website for a fictional restaurant based in Mumbai, India. It showcases the restaurant's offerings through multiple pages including a home landing page, menu, gallery, about section, and contact/reservation pages.

## 🗂️ Project Structure

```
restaurant-project/
├── index.html          # Home page (hero carousel, featured dishes, stats, testimonials)
├── about.html          # About page (story, stats, chef profiles)
├── menu.html           # Menu page (tabbed: Pizza, Burger, Dessert + modals)
├── gallery.html        # Food photo gallery
├── contact.html        # Contact info + form + embedded Google Map
├── reservation.html    # Table reservation page (linked but not included in zip)
├── css/
│   └── style.css       # Custom styles
├── images/
│   └── burger.jpg      # Local burger image
└── logo.png            # Restaurant logo
```

## ✨ Features

- **Responsive Design** — fully mobile-friendly using Bootstrap 5 grid and utilities
- **Hero Carousel** — auto-sliding full-viewport image carousel with captions on the home page
- **Featured Dishes** — card-based dish showcase with hover lift animation
- **Tabbed Menu** — Pizza, Burger, and Dessert categories using Bootstrap Pills + Tab Panes
- **Item Modals** — "View Details" popups for menu items with descriptions
- **Stats Section** — highlights (10K+ customers, 15 chefs, 50+ dishes, 12 years)
- **Customer Reviews** — testimonial cards
- **CTA Section** — prominent "Reserve Your Table" call-to-action with orange background
- **Chef Profiles** — team cards on the About page
- **Food Gallery** — responsive image grid with hover zoom effect
- **Contact Form** — name, email, and message fields
- **Embedded Map** — Google Maps iframe showing restaurant location (Mumbai)
- **Consistent Footer** — opening hours, social icons (Facebook, Instagram, Twitter)
- **Sticky Navbar** — dark navbar that stays at the top on scroll

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure |
| CSS3 | Custom styles (`css/style.css`) |
| Bootstrap 5.3.3 | Responsive layout, components, utilities |
| Bootstrap Icons 1.11.3 | Social media and UI icons |
| Unsplash | External food/restaurant images |

## 🚀 Getting Started

No build tools or dependencies to install — this is a pure static website.

1. **Clone or download** the project folder.
2. Open `index.html` in any modern web browser.
3. Navigate between pages using the top navbar.

> **Note:** Images are loaded from Unsplash CDN, so an internet connection is required for them to display correctly.

## 📄 Pages

| Page | File | Description |
|---|---|---|
| Home | `index.html` | Hero carousel, about preview, featured dishes, stats, testimonials, CTA |
| About | `about.html` | Restaurant story, stats, chef team profiles |
| Menu | `menu.html` | Tabbed menu (Pizza · Burger · Dessert) with detail modals |
| Gallery | `gallery.html` | Responsive food photo grid |
| Contact | `contact.html` | Address, phone, email, contact form, Google Map embed |
| Reservation | `reservation.html` | Table booking page *(linked in navbar; file not included in this zip)* |

## 📱 Responsive Breakpoints

- **Mobile (< 768px):** Hero image height reduces to 70vh; carousel caption font size scales down.
- **Tablet / Desktop (≥ 768px):** Full 90vh hero, multi-column card grids, side-by-side layouts.

## 🎨 Custom Styles (`css/style.css`)

- `.hero-img` — full-height hero with 50% brightness dimming
- `.card:hover` — smooth upward lift (`translateY(-10px)`)
- `.cta-section` — burnt-orange background (`#d35400`)
- `.page-banner` — 300px dark-overlay banner used on inner pages
- `.gallery-img` — fixed 300px height with zoom-on-hover (`scale(1.05)`)
- `footer i` — large social icons with hover opacity

## 📞 Restaurant Info (Demo Data)

- **Location:** Mumbai, India
- **Phone:** +91 9876543210
- **Email:** info@foodies.com
- **Hours:** Mon–Sun, 10 AM – 11 PM

## 📝 License

This is a demo/practice project. All food images are sourced from [Unsplash](https://unsplash.com) and are subject to the Unsplash License.
