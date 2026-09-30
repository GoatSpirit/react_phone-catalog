# Nice Gadgets Product Catalog

Nice Gadgets is a responsive e-commerce product catalog for phones, tablets, and accessories. The app lets users browse products, open detailed product pages, search and sort catalog items, add products to favorites, manage a shopping cart, and keep cart/favorites state between page reloads.

<<<<<<< HEAD
## Demo

[DEMO LINK](https://GoatSpirit.github.io/react_phone-catalog/)
=======
#DEMO LINK

https://GoatSpirit.github.io/react_phone-catalog/

>>>>>>> d2d268b29f5226ce0fb348b255260df68a70616b

## Design Reference

The project is based on the dark version of the Phone Catalog design:

[Phone Catalog V2 Original Dark](https://www.figma.com/design/WMdJ24eHk4EkSr25mrt7Y2/Phone-catalog--V2--Original-Dark)

## Technologies Used


- React - UI library
- TypeScript - type safety
- SCSS Modules - component-scoped styling
- Vite - development and build tooling

### Routing and State

- React Router - client-side routing
- React Context - cart and favorites state management
- LocalStorage - persistent cart and favorites data

### UI and Assets

- Font Awesome - interface icons
- Responsive CSS Grid and Flexbox layouts
- Public JSON API and product images from the project assets

## Getting Started

Follow these steps to run the project locally.

### 1. Clone the repository

```bash
git clone https://github.com/GoatSpirit/react_phone-catalog.git
cd react_phone-catalog
```

### 2. Install dependencies

```bash
npm install
```

### 3. Run the project locally

```bash
npm start
```

The app will be available in the browser at the local URL printed in the terminal.

### 4. Build for production

```bash
npm run build
```

### 5. Deploy

```bash
npm run deploy
```

## Features

### Catalog

- Product pages for phones, tablets, and accessories.
- URL-based search, sorting, pagination, and items-per-page selection.
- Loading, error, empty, not-found, and product-not-found states.

### Product Details

- Product image gallery with selectable pictures.
- Color and capacity selectors for available product variants.
- Breadcrumbs, tech specs, product description, and suggested products.

### Cart and Favorites

- Shopping cart with quantity controls, item removal, and total price calculation.
- Favorites page with saved favorite products.
- Cart and favorites data are persisted in LocalStorage.

### UI and Navigation

- Responsive layout for desktop, tablet, and mobile screens.
- Sticky header with navigation, search, favorites, and cart indicators.
- Home page with an auto-changing image slider, category links, brand new products, and hot price products.
- GitHub Pages fallback for refreshing nested product routes.

## Repository

[GitHub Repository](https://github.com/GoatSpirit/react_phone-catalog)
