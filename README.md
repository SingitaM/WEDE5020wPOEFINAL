# Kei Mouth Hardware Website

## Project Information

**Student Name:** Singita Mushwana  
**Student Number:** ST10465147  
**Module Code:** WEDE5020  
**Module Name:** Web Development (Introduction)  
**Assignment:** Portfolio of Evidence (POE) - Part 2: CSS Styling & Responsive Design

---

## Project Overview

This project is a comprehensive website for **Kei Mouth Hardware**, a local hardware store located in the Eastern Cape, South Africa. The website serves as an online presence for the retail store, showcasing products, services, special offers, and providing contact information for customers.

The website was developed as part of a three-part Portfolio of Evidence (POE) assignment:

- **Part 1:** HTML Foundation (Completed)
- **Part 2:** CSS Styling & Responsive Design (Current - 100 marks)
- **Part 3:** JavaScript Functionality & SEO (Upcoming - 100 marks)

---

## Website Goals and Objectives

### Primary Goals

1. **Establish Online Presence:** Provide a professional online presence for Kei Mouth Hardware
2. **Product Showcase:** Display the comprehensive range of hardware products available
3. **Customer Engagement:** Enable customers to easily find information and contact the store
4. **Promote Special Offers:** Highlight current specials and promotions
5. **Build Trust:** Provide information about the company's history, values, and commitment to quality

### Objectives

- Create a user-friendly, accessible website that works seamlessly across all devices
- Implement responsive design that adapts to desktop, tablet, and mobile screens
- Use modern CSS techniques (Flexbox, Grid) for flexible layouts
- Ensure fast loading times with optimized images and efficient CSS
- Maintain consistent branding and visual identity throughout the site

---

## Key Features and Functionality

### Part 1: HTML Foundation

- Semantic HTML5 structure with proper document hierarchy
- Five main pages: Home, Products, Specials, About Us, and Contact
- Accessible navigation menu with proper list structure
- Contact form with validation-ready structure
- Comprehensive product categories and descriptions
- Company information and store hours

### Part 2: CSS Styling & Responsive Design

- **External Stylesheet:** Organized CSS in `/css/style.css` folder structure
- **CSS Variables:** Consistent theming using CSS custom properties
- **Base/Default Styling:** Comprehensive CSS reset and global styles
- **Typography:** Clear hierarchy with proper font sizing, weights, and spacing
- **Layout Structure:** CSS Grid and Flexbox for responsive layouts
- **Visual Styling:** Consistent color scheme, gradients, shadows, and borders
- **Pseudo-classes:** Comprehensive :hover, :focus, :active states on all interactive elements
- **Media Queries:** Responsive breakpoints for desktop, tablet, and mobile
- **Responsive Navigation:** Hamburger menu for mobile devices
- **Responsive Images:** Optimized images with lazy loading
- **Responsive Typography:** Fluid typography that scales appropriately

---

## Technologies Used

- **HTML5:** Semantic markup structure
- **CSS3:** 
  - Flexbox for flexible layouts
  - CSS Grid for complex layouts
  - CSS Variables for consistent theming
  - Media queries for responsive design
  - Pseudo-classes for interactive states
- **JavaScript (ES6):**
  - Interactive elements (accordions, gallery, lightbox)
  - Dynamic content generation
  - Real-time search and filtering
  - Form validation and processing
  - Map integration
  - Shopping cart functionality
- **Libraries:**
  - Leaflet.js for interactive maps
  - OpenStreetMap for map tiles
  - Font Awesome 6.4.0 for icons (via Cloudflare CDN)

---

## Part 2 Specifics

### Responsive Design Approach

The website uses a **mobile-first responsive design** approach, ensuring optimal viewing experience across all devices.

### Breakpoints Implemented

- **Desktop:** 1200px and above
- **Large Tablet:** 992px to 1199px
- **Tablet:** 768px to 991px
- **Mobile:** up to 767px
- **Small Mobile:** up to 575px

### Layout Techniques

- **CSS Grid:** Used for product grids, specials grid, values grid, and mission/vision layout
- **Flexbox:** Used for header navigation, form layouts, button containers, and flexible component layouts
- **Flexible Units:** Used rem and em units for scalable typography and spacing

### Responsive Features

1. **Navigation Menu:**
   - Desktop: Horizontal navigation bar
   - Mobile: Hamburger menu with slide-out drawer

2. **Layout Adjustments:**
   - Desktop: Multi-column layouts (3 columns for products)
   - Tablet: 2-column layouts
   - Mobile: Single column, stacked elements

3. **Typography:**
   - Scales from 18px (desktop) to 14px (small mobile)
   - Heading sizes adjust proportionally

4. **Images:**
   - Max-width: 100% with height: auto
   - Lazy loading for performance
   - Responsive grid layouts

---

## File Structure
Student Name: Singita Mushwana  
Student Number: ST10465147  
Module Code: WEDE5020  
Module Name: Web Development (Introduction)  
Assignment: Portfolio of Evidence (POE) - Part 2: CSS Styling & Responsive Design

/
├── index.html          # Home page
├── about.html         # About Us page
├── products.html      # Products page
├── specials.html     # Specials page
├── contact.html      # Contact page
├── css/
│   └── style.css     # External stylesheet
├── Images/           # Image assets
│   ├── logo.png
│   ├── brick-1.webp
│   ├── brick-3.webp
│   ├── cement-1.webp
│   ├── cement-2.webp
│   ├── Pine 2.jpg
│   ├── pine wood.jpg
│   ├── gradening tools 1.webp
│   ├── gardening tools 2.jpg
│   ├── grinder.png
│   ├── power tool 1.webp
│   ├── Paint.jpg
│   ├── paint brush.jpg
│   ├── plumbing pipes.jpg
│   ├── Plumbing fittings.jpg
│   ├── Wires.avif
│   └── light bulb.avif
├── README.md         # This file
└── CHANGELOG.md     # Development changelog
```

---

## Sitemap

```
Home (index.html)
├── Specials (specials.html)
├── Products (products.html)
│   ├── Bricks & Building Materials
│   ├── Cement & Concrete
│   ├── Timber & Wood Products
│   ├── Gardening Tools & Supplies
│   ├── Power Tools
│   ├── Paint & Decorating
│   ├── Plumbing Supplies
│   └── Electrical Supplies
├── About Us (about.html)
│   ├── Our Story
│   ├── Mission & Vision
│   ├── Why Choose Us
│   ├── Our Values
│   └── Visit Us / Store Hours
└── Contact (contact.html)
    ├── Contact Information
    ├── Contact Form
    └── Map & Directions
```

---

## Testing Evidence

### Browser Compatibility

Tested and verified in the following browsers:
- Google Chrome (Latest)
- Mozilla Firefox (Latest)
- Safari (Latest)
- Microsoft Edge (Latest)

### Responsive Testing

The website has been tested at the following viewport sizes:

**Desktop Views:**
- 1920px × 1080px
- 1440px × 900px
- 1280px × 720px

**Tablet Views:**
- 1024px × 768px (iPad)
- 768px × 1024px (iPad Portrait)

**Mobile Views:**
- 414px × 896px (iPhone 11 Pro Max)
- 375px × 667px (iPhone SE)

### Testing Notes

**Part 2 Testing:**
- All navigation links function correctly
- Hamburger menu works smoothly on mobile devices
- Images load properly and scale responsively
- Forms display correctly across all screen sizes
- Typography remains readable at all breakpoints
- No horizontal scrolling issues
- Touch targets are appropriately sized for mobile

**Part 3 Testing:**
- All JavaScript functionality operational
- Interactive accordions work smoothly
- Map displays correctly with both locations
- Gallery and lightbox function perfectly
- Product search filters accurately
- Form validation prevents invalid submissions
- Form processing generates correct responses
- Email compilation works correctly
- SEO elements complete on all pages
- Cross-browser compatibility confirmed (Chrome, Firefox, Safari, Edge)
- Mobile responsiveness verified for all features

---

## Timeline and Milestones

### Part 1: HTML Foundation
- HTML structure completed
- All pages created
- Content added
- Navigation implemented

### Part 2: CSS Styling & Responsive Design
- External stylesheet created
- CSS variables implemented
- Typography styles completed
- Layout structure implemented
- Visual styling applied
- Pseudo-classes added
- Media queries implemented
- Responsive navigation menu created
- Responsive images configured
- Cross-browser testing completed

### Part 3: JavaScript Functionality & SEO (Completed)
- **Interactive Elements:** Accordions on About page with smooth animations
- **Interactive Map:** Leaflet.js map with 2 store locations and detailed popups
- **Gallery with Lightbox:** Product image gallery with full-screen lightbox functionality
- **Dynamic Content:** 15+ products loaded dynamically from JavaScript array
- **Real-time Search:** Product search and filtering with instant results
- **Form Validation:** Comprehensive validation for enquiry and contact forms
- **Form Processing:** Enquiry form response generation and contact form email handling
- **SEO Optimization:** Complete SEO including titles, meta tags, alt text, robots.txt, sitemap.xml
- **Cross-browser testing:** All JavaScript features tested and working

---

## Part 3 Features

### Interactive Elements
- **Accordions:** Collapsible FAQ sections on About page
  - Smooth open/close animations
  - One section open at a time
  - Fully responsive on all devices

### Interactive Map
- **Leaflet Map Integration:** Contact page features interactive map
  - Two store locations displayed
  - Clickable markers with store information popups
  - Full zoom and pan functionality
  - Responsive design for all screen sizes

### Gallery with Lightbox
- **Product Image Gallery:** Responsive grid of 6-8 product images
  - Click thumbnail to view full-size in lightbox
  - Navigation arrows and image counter
  - Close with X button, backdrop click, or Escape key
  - Smooth animations and transitions
  - Touch-friendly for mobile devices

### Dynamic Content & Search
- **Dynamic Product Loading:** Products stored in JavaScript and dynamically displayed
  - 15+ products across 8 categories
  - Real-time search filtering
  - Category filter buttons
  - "No results found" messaging
  - Result count display

### Form Functionality

**Enquiry Form:**
- Comprehensive validation (HTML5 + JavaScript)
- Real-time error feedback
- Processes enquiry and shows response based on type
- Calculates pricing and availability
- Displays next steps and contact information

**Contact Form:**
- Full validation for all fields
- Email compilation with formatted output
- Success confirmation messages
- Professional user experience

### SEO Implementation

**Title Tags:**
- Unique, optimized titles for all 6 pages
- Length: 50-60 characters
- Format: Primary Keyword - Secondary Keyword | Brand Name

**Meta Tags:**
- Unique meta descriptions (150-160 characters) on all pages
- Comprehensive meta keywords (5-10 per page)
- Location-specific keywords included

**Image Optimization:**
- Descriptive filenames for all images
- Comprehensive alt text on all images
- Keywords naturally included

**Additional SEO:**
- robots.txt file for search engine guidance
- sitemap.xml with all pages and proper priorities
- Proper header tag hierarchy (H1-H6)
- Internal linking throughout site

---

## Recent Updates

### UI/UX Improvements - About Page & Specials (November 2025)
- **About Page Section Headings:** Centered all section headings and removed vertical border lines
  - Icons added to sections: Our Mission (fa-bullseye), Our Vision (fa-eye), Visit Us (fa-map-marker-alt), and various icons in Our Values section
  - Cleaner, centered presentation with consistent heading design
- **Our Vision Color Correction:** Changed Our Vision section from red to green to match site theme
- **Border Styling Updates:** Replaced left borders with full green borders on:
  - Our Values containers (Quality, Integrity, Community, Service)
  - Store Hours container
  - More balanced visual design with borders on all sides
- **Specials Page:** Reorganized Paint Supplies flip card content
  - "Click to flip back" text moved below terms section
  - Improved content hierarchy and readability

### Index Page Enhancements (November 2025)
- **Product Category Buttons:** Added "Shop Now" buttons alongside "Request Quote" buttons in all product category sections
  - Buttons displayed side-by-side with consistent styling
  - "Shop Now" provides direct link to products page
  - "Request Quote" links to contact page for custom quotes
  - Enhanced user experience with multiple action options

### Products Page Updates (November 2025)
- **Product Listing Optimization:** Removed "Circuit Breaker" product from Electrical category
  - Streamlined product listings for better clarity
  - Electrical section now focuses on core electrical supplies

---

## Changelog

For comprehensive details on all updates, enhancements, and bug fixes implemented during development, please see [CHANGELOG.md](CHANGELOG.md).

---

## References

- Font Awesome, 2025. Font Awesome Icons. [Online] Available at: <https://fontawesome.com/> [Accessed 4 November 2025]. Icon library loaded via Cloudflare CDN: <https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css>
- Font Awesome License, 2025. Font Awesome Free License. [Online] Available at: <https://fontawesome.com/license/free> [Accessed 4 November 2025].
- Freepik, 2025. Freepik - Free Vectors, Stock Photos & PSD Downloads. [Online] Available at: <https://www.freepik.com/> [Accessed 31 October 2025].
- Leaflet, 2025. Leaflet - an Open Source JavaScript Library for Mobile-Friendly Interactive Maps. [Online] Available at: <https://leafletjs.com/> [Accessed 31 October 2025].
- Mozilla Developer Network, 2025. MDN Web Docs. [Online] Available at: <https://developer.mozilla.org/> [Accessed 31 October 2025].
- OpenStreetMap Foundation, 2025. OpenStreetMap - The Free Wiki World Map. [Online] Available at: <https://www.openstreetmap.org/> [Accessed 31 October 2025].
- W3C, 2014. HTML5 Specification. [Online] Available at: <https://www.w3.org/TR/html5/> [Accessed 31 October 2025].
- W3C, 2025. CSS3 Specification. [Online] Available at: <https://www.w3.org/Style/CSS/> [Accessed 31 October 2025].

Design Principles

- Mobile-First Responsive Design
- Progressive Enhancement
- Accessibility Guidelines (WCAG)
- Semantic HTML5 Structure

---

## Contact Information

**Kei Mouth Hardware**  
14 Main Road  
Kei Mouth  
Eastern Cape  
South Africa  
5260

**Phone:** 043 841 1454  
**Email:** info@kmhardware.co.za

---

## Copyright

© 2025 Kei Mouth Hardware. All rights reserved.
