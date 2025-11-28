# Ice Cream Website

A responsive ice cream e-commerce website built with HTML, CSS, and JavaScript. This project features a modern shopping interface with product browsing, cart management, and user authentication.

## Features

- **Responsive Design**: Mobile-friendly layout that adapts to all screen sizes
- **Interactive Navigation**: Smooth navigation menu with hamburger toggle for mobile
- **Product Browsing**: Browse and view ice cream products with images and descriptions
- **Shopping Cart**: Add/remove items from shopping cart with real-time updates
- **Search Functionality**: Search for products using the built-in search feature
- **User Login**: User authentication system via login form
- **Product Categories**: Browse ice cream by different categories
- **Customer Reviews**: View and read customer reviews for products
- **Font Awesome Icons**: Professional icons for better UI/UX

## Project Structure

```
ICE CREAM/
├── index.html          # Main website page
├── login.html          # User login page
├── script.js           # JavaScript functionality and interactivity
├── style.css           # Main stylesheet
├── images/             # Product and UI images
│   └── img1.jpeg       # Sample product image
└── README.md           # Project documentation
```

## Technologies Used

- **HTML5**: Semantic markup for page structure
- **CSS3**: Modern styling with CSS variables and responsive design
- **JavaScript (Vanilla)**: Interactive features without external dependencies
- **Font Awesome 6.5.0**: Icon library via CDN
- **Swiper 12**: Touch slider library for product carousels

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server installation required for basic functionality

### Installation

1. Clone the repository:
```bash
git clone https://github.com/sandhyaamethi2002-beep/icecream_website.git
cd icecream_website
```

2. Open the project:
   - Simply open `index.html` in your web browser
   - Or use a local server for better development experience

### Using a Local Server (Optional)

For development, you can use Python's built-in server:

```bash
# Python 3.x
python -m http.server 8000

# Python 2.x
python -m SimpleHTTPServer 8000
```

Then visit `http://localhost:8000` in your browser.

## Features Overview

### Header Navigation
- Logo and navigation links (Home, Features, Products, Categories, Reviews)
- Search bar for quick product lookup
- Shopping cart icon for cart management
- User login button

### Shopping Cart
- View selected items with images and prices
- Remove items from cart
- Real-time cart updates

### Login Form
- User authentication interface
- Accessible from main navigation

### Responsive Behavior
- Hamburger menu for mobile devices
- Touch-friendly interface
- Optimized layouts for all screen sizes

## CSS Customization

The project uses CSS variables for easy theming. Customize colors in `style.css`:

```css
--orange: #ff7800;      /* Primary accent color */
--black: #130f40;       /* Text and dark elements */
--light-color: #666;    /* Secondary text */
```

## JavaScript Functionality

The `script.js` file handles:
- Menu toggle functionality
- Search form activation
- Shopping cart management
- Login form display
- Element state management with event listeners

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Future Enhancements

- Backend integration for product database
- Payment gateway integration
- User account management
- Order history tracking
- Admin panel for product management
- Product filtering and sorting

## License

This project is licensed under the MIL License - see the LICENSE file for details.




