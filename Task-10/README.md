# Interactive Multi-Page Website Simulator (CSS Only)

##  Objective
This project demonstrates how to create a fully functional, multi-section website that simulates page navigation without using JavaScript. It relies purely on CSS techniques such as the `:target` pseudo-class, transitions, and responsive design.

##  Features
- **CSS-only page transitions** using the `:target` pseudo-class.
- **Smooth animations** for page visibility changes.
- **Responsive design** using Flexbox, Grid, and media queries.
- **Accessible navigation menu** that adapts to different screen sizes.

##  How It Works
1. **Navigation via Fragment Identifiers**  
   - Clicking on a navigation link (e.g., `#home`, `#about`) updates the URL with a fragment identifier (`#section-name`).
   - Example: Clicking "Gallery" changes the URL to `index.html#gallery`.

2. **CSS `:target` Selector**  
   - When a section is targeted (`#home:target`), it becomes visible by changing its `opacity` and making other sections invisible.

3. **Smooth Transitions**  
   - The `opacity` property is animated using `transition: opacity 1s ease-in-out;` to create a fade effect when switching pages.

4. **Responsive Design**  
   - Flexbox and Grid are used for layout management.
   - Media queries adjust the layout for different screen sizes.