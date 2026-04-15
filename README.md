# Nice Gadgets — Product Catalog

A responsive e-commerce product catalog for Apple-style gadgets. Browse phones, tablets, and accessories, save favorites, and manage your shopping cart — all with persistent state via localStorage.

## Live Preview

[Live Demo](https://eg598.github.io/nice-gadgets__landing-page/)

## Design Reference

The UI follows an Apple-inspired design with clean product cards, smooth sliders, and a minimal color palette.

## Technologies Used

**Core**
- React (v18.3.1) — UI framework
- TypeScript (v5.2.2) — Type safety
- SCSS/Sass (v1.77.8) — Styling

**Routing & State**
- React Router DOM (v6.25.1) — Client-side navigation with HashRouter
- React Context API — Global state for products, cart, and favorites
- localStorage — Persistent cart and favorites between sessions

**Development & Build**
- Vite (v5.3.1) — Build tool
- classnames — Conditional class handling

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/eg598/nice-gadgets__landing-page.git
cd nice-gadgets__landing-page
```

2. Install dependencies:

```bash
npm install
```

3. Run the project locally:

```bash
npm start
```

## Features

- **Product Catalog** — Browse phones, tablets, and accessories fetched from a local JSON API
- **Product Details** — Dedicated detail page per product with specs and image gallery
- **Shopping Cart** — Add/remove items, adjust quantities, see total price; persisted in localStorage
- **Favorites** — Toggle favorite products; count shown in header; persisted in localStorage
- **Homepage Sliders** — Auto-playing banner slider and scrollable "Brand New" / "Discounted" product carousels
- **Shop by Category** — Category cards on the homepage with live model counts
- **Responsive Design** — Optimized for mobile, tablet, and desktop with a collapsible burger menu
- **Navigation badges** — Live cart and favorites counters displayed in the header
