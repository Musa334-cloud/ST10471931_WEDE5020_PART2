# POE README

# ScentSymphony Website

## Overview
ScentSymphony is a luxury organic fragrance brand website created as part of the Web Development module (WEDE5020).  
The website showcases the brand story, products, contact details, and allows users to send enquiries.  

The project demonstrates semantic HTML5 structure, external CSS styling, responsive design, and accessibility best practices.

---

## Part 1 Summary
- Created the base structure of the website using semantic HTML5.
- Implemented navigation between pages: Home, About, Products, Enquiry, and Contact.
- Integrated a simple form for business enquiries.
- Added images with alt text for accessibility.
- Established a consistent structure across all pages.

---

## Part 2 Updates
Part 2 focuses on **visual appeal, responsiveness, and user experience**:

1. **External Stylesheet**  
   - All pages now link to `css/style.css`.  
   - Base reset and variables defined at the top.  

2. **Base Styles & Typography**  
   - Root variables for colors, font families, and spacing.  
   - Scalable typography using `rem` and `em`.  
   - Heading hierarchy and responsive text sizes added.  

3. **Layout**  
   - Desktop layout uses CSS Grid and Flexbox for two-column structures.  
   - Mobile layout collapses into a single column.  
   - Semantic placement of header, nav, main, and footer.  

4. **Visual Styles**  
   - Consistent color palette across all pages.  
   - Styled buttons with hover and focus states.  
   - Box shadows, borders, and consistent spacing implemented.  

5. **Navigation Adjustments**  
   - Navigation adapts for mobile screens.  
   - Stacked layout for small screens.  

6. **Responsive Images**  
   - Images styled to scale proportionally across devices.  
   - All images include descriptive alt text.  

7. **Testing & Screenshots**  
   - Responsive design tested using Chrome DevTools.  
   - Breakpoints tested:  
     - **Desktop:** 1440px  
     - **Tablet:** 768px  
     - **Mobile:** 375px
  ---
  
## Part 3 – JavaScript Enhancements & Interactivity
- Added accessible mobile nav toggle with `aria-expanded`
- Implemented lightbox gallery for product images
- Built real-time search filters for services and products
- Enhanced enquiry form with dynamic quote generation
- Integrated contact form with Formspree endpoint (`https://formspree.io/f/xpwbqqvd`)
- Moved all JavaScript into external file `js/scripts.js`
- Tested across Chrome, Firefox, and Edge for consistent behavior

---

## Screenshots

### Desktop View
![Desktop Home](screenshots/desktop-home.png)

### Tablet View
![Tablet Home](screenshots/tablet-home.png)

### Mobile View
![Mobile Home](screenshots/mobile-home.png)

---

## Changelog
See the [changelog.md](changelog.md) file for detailed entries of edits and improvements.

Example entries:
- **2025-09-15** — Part 2: Added external stylesheet (css/style.css) and linked to all pages.  
- **2025-09-15** — Typography: Added scale, responsive font sizes, and heading styles.  
- **2025-09-21** — Layout: Implemented CSS Grid two-column desktop layout and stacked mobile layout.  
- **2025-09-24/25** — Added responsive design breakpoints, tested across devices, and included screenshot evidence.  

---

## References
- MDN Web Docs: [https://developer.mozilla.org/](https://developer.mozilla.org/)  
- W3Schools CSS Guide: [https://www.w3schools.com/css/](https://www.w3schools.com/css/)  
- FreeCodeCamp Responsive Web Design: [https://www.freecodecamp.org/](https://www.freecodecamp.org/)  

---

## Author
**Andiswa Phewa**  
ST10471931  
ScentSymphony Website — Web Development (WEDE5020) Part 2
