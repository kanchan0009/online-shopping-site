 Online Shopping Website
A modern, fully responsive e-commerce platform built with HTML, CSS, and JavaScript, featuring seamless Google authentication for user sign-up and login.

✨ Features
🛒 Core Shopping Features
Product Catalog: Browse products with category filtering

Product Details: View detailed product information, images, and reviews

Shopping Cart: Add/remove items, update quantities, and view totals

Checkout Process: Secure and intuitive checkout flow

Order History: Track previous orders and current order status

Responsive Design: Works perfectly on desktop, tablet, and mobile

🔐 Authentication & Security
Google Sign-In: One-click authentication using Google accounts

Secure Sessions: Protected user sessions and data privacy

User Profiles: Personalized accounts with order history and preferences

No Password Hassle: Eliminates traditional sign-up forms

🎨 User Experience
Modern UI/UX: Clean, intuitive interface with smooth animations

Search Functionality: Find products quickly with instant search

Wishlist: Save favorite items for later

Product Reviews: Read and submit customer reviews

Shipping Calculator: Real-time shipping cost estimation

🚀 Technologies Used
Frontend
HTML5: Semantic markup for accessibility

CSS3: Flexbox, Grid, and custom properties for styling

JavaScript (ES6+): Dynamic functionality and DOM manipulation

Authentication
Google Identity Services: Secure OAuth 2.0 authentication

Local Storage: Session management for logged-in users

Firebase Authentication (optional): For extended user management
 Setup & Installation
Clone the repository

bash
git clone https://github.com/kanchan0009/online-shopping-site
cd online-shopping
Set up Google Authentication

Go to Google Cloud Console

Create a new project

Enable Google Identity API

Create OAuth 2.0 credentials

Add your domain to authorized origins

Copy your Client ID

Configure authentication

Open js/auth.js

Replace YOUR_GOOGLE_CLIENT_ID with your actual Client ID

Update redirect URIs as needed

Run the website

Open index.html in a modern web browser

Or use a local server (recommended):

bash
# Using Python
python -m http.server 8000

🎯 Key JavaScript Features
Authentication Module
javascript

}
Shopping Cart System
javascript

function addToCart(productId, quantity) {
 
}
Product Management
javascript

async function loadProducts(category) {

}
📱 Responsive Breakpoints
Mobile: < 768px

Tablet: 768px - 1024px

Desktop: > 1024px

🌟 Future Enhancements
Payment gateway integration (Stripe/PayPal)

Admin dashboard for product management

Advanced search with filters

Email notifications

Social sharing features

Multi-language support

Progressive Web App (PWA) capabilities

📝 Browser Support
Chrome 60+

Firefox 55+

Safari 11+

Edge 79+

🤝 Contributing
Fork the repository

Create a feature branch

Commit your changes

Push to the branch

Open a Pull Request

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments
Google Identity Services for authentication

Unsplash for placeholder images

FontAwesome for icons

All contributors and testers
