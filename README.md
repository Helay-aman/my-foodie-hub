Foodie Hub - Responsive Frontend
Project Overview
This repository contains the frontend UI for "Foodie Hub," a responsive public food ordering platform. This project was built using only HTML and CSS, leveraging Bootstrap 5 for rapid development and responsiveness. The goal was to create a single-page website that allows users to browse restaurants, view menus, and simulate placing orders, all without the use of JavaScript.

Features
Responsive Navbar: Bootstrap navbar that collapses into a hamburger menu on mobile.

Hero Section: Large banner with background image and overlay text, centered and responsive.

Restaurants List: A responsive grid displaying 6 sample restaurant cards with names, photos, descriptions, and "View Menu" buttons.

Layout: 4 cards/row (large screens), 2 cards/row (tablets), 1 card/row (mobile).

Hover effects on cards (shadow and scale).

Restaurant Menu Section: Displays distinct menu items for each restaurant. "View Menu" buttons on restaurant cards use anchor links to scroll to specific menu sections.

Menu items shown as Bootstrap cards with dish name, description, price, and availability badges.

Availability badges styled in green (available) or red (unavailable) using custom CSS.

Order Form: A form for users to enter customer name, phone number, and select a restaurant.

Responsive layout: two columns on large screens, stacks vertically on smaller screens.

No actual form submission logic (placeholder action #).

About Section: Two-column layout on desktop (image and descriptive text), stacks vertically on mobile.

Contact Section / Footer: Simple contact information and social media icons (Bootstrap Icons). Responsive text alignment.

Technical Details
HTML & CSS Only: No JavaScript or other frameworks were used, adhering strictly to the assignment requirements.

Bootstrap 5: Utilized for core UI components, grid system, and responsive utilities.

Custom CSS: A separate style.css file is included for custom styling, hover effects, and media queries that fine-tune Bootstrap's default behavior.

Responsive Design: Implemented using Bootstrap's grid system and custom CSS media queries to ensure optimal viewing on desktop, tablet, and mobile devices.

Semantic HTML: Structured with appropriate HTML5 semantic tags (<nav>, <section>, <footer>, etc.).

Clean Code: Code is well-structured, indented, and commented for readability.

How to Run Locally
Clone the repository:

git clone https://github.com/Helay-aman/my-foodie-hub.git

Navigate to the project directory:

cd my-foodie-hub

Open index.html: Simply open the index.html file in your web browser.

Live Demo
You can view the live demo of this project here:
https://helay-aman.github.io/my-foodie-hub/


Design Decisions
Color Palette: A clean and modern palette using Bootstrap's default primary blue for accents, complemented by shades of grey and white for backgrounds and text, ensuring readability and a professional look.

Typography: Relies on Bootstrap's default font stack, which provides good readability across devices.

Interactive Elements: Subtle hover effects (shadows, slight lifts, color changes) are applied to buttons and cards to provide visual feedback without JavaScript.

User Experience: Designed with clear navigation and intuitive layout to ensure users can easily browse restaurants and menus.

Challenges Faced

Initial GitHub Pages Setup: Getting the index.html file to be at the root level of the repository for GitHub Pages to correctly serve the site was a key learning curve.

Managing Anchor Links: Ensuring smooth scrolling and correct navigation between sections on a single-page site using only HTML/CSS anchor links required careful ID management.

Responsive Image Cropping: Achieving consistent cropping and responsiveness for images within Bootstrap cards while maintaining visual appeal across different screen sizes.

Customizing Bootstrap Components: Overriding Bootstrap's default styles with custom CSS for specific elements (like availability badges or detailed hover effects) while maintaining responsiveness.

No JavaScript Constraint: Designing interactive elements and form behavior without relying on JavaScript required creative use of HTML and CSS features.
