# Niyantri Coffee – Website Package

This repository includes a five-page static website for a coffee shop named "Niyantri Coffee" with a warm, coffee-color theme and PayPal integration on the cart page.

Pages:
- index.html   (Home)
- menu.html    (Menu)
- cart.html    (Cart + PayPal checkout)
- about.html   (About)
- contact.html (Contact)

Notes and design decisions:
- Fully responsive layout with a fluid full-width design; no max-width containers on main content.
- Tailwind CSS is used via CDN for styling; all styling is done with Tailwind utility classes.
- Page load fade-in effect applied on the body via the classes and a small script.
- Mobile navigation with a hamburger menu (JS toggles the dropdown).
- Menu items are static HTML blocks. A simple localStorage cart is implemented to allow adding items to a cart that persists in the browser.
- PayPal integration uses the sandbox setup (client-id=sb) for the cart page. The total is calculated from cart items and passed to PayPal.
- Placeholder location used for contact page (Hyderabad, India) as there was no location specified.

Files overview:
- index.html: Hero section with a background image placeholder, quick intro, and two CTA buttons. Includes a testimonials section and quotes.
- menu.html: Grid of coffee items with images, descriptions, prices, and Add to Cart buttons.
- cart.html: Cart overview, total calculation, and PayPal button for checkout.
- about.html: Company background and values.
- contact.html: Contact form and placeholder address with a map placeholder image.

If you need any adjustments (colors, additional items, or real PayPal credentials), tell me and I’ll update the build accordingly.