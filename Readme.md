# NexCart - E-Commerce Shopping Cart

## Project Overview

NexCart is a modern, responsive e-commerce shopping cart application built with vanilla HTML, CSS, and JavaScript. It features a dark-themed UI with a clean, professional design that provides users with an intuitive shopping experience.

## Features

- **Product Catalog**: Display of products with images, descriptions, and prices
- **Shopping Cart**: Sidebar cart that slides in/out with full functionality
- **Cart Management**: Add/remove items, adjust quantities
- **Persistent Storage**: Cart data saved to localStorage
- **Responsive Design**: Works on desktop and mobile devices
- **Modern UI**: Dark theme with attractive card designs and smooth animations

## Technical Implementation

### Technologies Used
- HTML5
- CSS3 (Flexbox, CSS Grid, CSS Variables)
- Vanilla JavaScript (ES6+)
- Font Awesome Icons
- LocalStorage API

### Key JavaScript Features
- ES6 Class implementation for cart functionality
- Event delegation for dynamic elements
- LocalStorage integration for data persistence
- DOM manipulation for dynamic content rendering

### Project Structure

├── HTML Structure
│   ├── Header with logo and cart icon
│   ├── Product grid section
│   └── Cart sidebar
├── CSS Architecture
│   ├── CSS Custom Properties for theming
│   ├── Responsive design with media queries
│   └── Smooth animations and transitions
└── JavaScript Modules
    ├── Product data management
    ├── Cart class with methods
    ├── DOM rendering functions
    └── Event handling system


## Setup Instructions

1. Download or clone the project files
2. Open `index.html` in a web browser
3. No additional dependencies or build process required

## Usage

1. Browse products in the main grid
2. Click "Add to Cart" to add items to your cart
3. Click the cart icon to view your shopping cart
4. Adjust quantities using +/- buttons
5. Remove items using the trash icon
6. Click "Proceed to Checkout" to complete your purchase

## Browser Compatibility

Works on all modern browsers including:
- Chrome (recommended)
- Firefox
- Safari
- Edge

## Customization

The application can be easily customized by modifying the CSS variables in the `:root` selector:

```css
:root {
  --dark-bg: #121212;
  --darker-bg: #0a0a0a;
  --card-bg: #1e1e1e;
  --accent: #8a2be2; /* Purple theme color */
  --accent-hover: #9932cc;
  --text: #f8f8f8;
  --text-secondary: #a0a0a0;
  --success: #00cc66;
  --danger: #ff4d4d;
}
```

## Future Enhancements

- Product categories and filtering
- Search functionality
- User authentication
- Order history
- Payment integration
- Product reviews and ratings
- Wishlist functionality
- Admin panel for product management

## Developer

Developed by Daniru Perera


*Note: This is a frontend demonstration project. For a complete e-commerce solution, backend integration would be required for product management, user accounts, and payment processing.*