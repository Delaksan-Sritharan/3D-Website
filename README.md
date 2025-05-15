# Dela Landing Page - Frontend

This README provides an overview of the frontend codebase for the Dela landing page. It outlines the project structure, technologies used, and how to get started.

## Overview

This frontend implements a modern and engaging landing page for Dela, a product focused on email solutions for developers. The design features a dark theme with gradient and blur effects, a clear navigation, a compelling main content section with animated elements, and a 3D robot model. The layout is responsive, adapting to different screen sizes.

## Website

<img width="1440" alt="Screenshot 2025-05-15 at 10 28 48 AM" src="https://github.com/user-attachments/assets/b9ea05c7-0132-41c8-affa-881e1f228152" />

## Technologies Used

* **HTML:** Provides the structural foundation of the webpage.
* **CSS:** Styles the HTML elements, including layout, colors, typography, animations, and responsiveness.
* **JavaScript:**
    * **Spline Viewer:** Used to embed and interact with the 3D robot model.
    * **AOS (Animate On Scroll):** A library to create subtle scroll-triggered animations for various elements.

## Project Structure

The main files for this frontend are:

* `index.html`: The primary HTML file containing the structure and content of the landing page.
* `style.css`: The stylesheet containing all the CSS rules for styling the page.
* `gradient.png`: An image file used for the background gradient effect.

## Getting Started

To view this frontend:

1.  **Save the Code:** Save the provided HTML and CSS code into two separate files named `index.html` and `style.css` in the same directory. Also, ensure you have the `gradient.png` file in the same directory.
2.  **Open in Browser:** Open the `index.html` file in any modern web browser (Chrome, Firefox, Safari, etc.).

## Key Features

* **Visually Appealing Design:** A dark background with a subtle gradient and a layered blur effect creates a modern and engaging aesthetic.
* **Animated Elements:** The tag box in the main content features a subtle gradient animation, drawing attention to the key message.
* **3D Integration:** A 3D robot model embedded using Spline adds a unique and interactive element to the page.
* **Scroll Animations:** The AOS library is used to animate elements as the user scrolls, enhancing the user experience.
* **Responsive Layout:** The design adapts seamlessly to different screen sizes (desktop, tablet, and mobile) using CSS media queries.
* **Clear Navigation:** A straightforward header includes a logo, navigation links, and a prominent sign-up button.
* **Compelling Main Content:** The main section features a highlighted tag, a clear and concise headline, a descriptive paragraph, and call-to-action buttons.

## CSS Structure

The `style.css` file is organized with comments to delineate different sections:

* **General Reset:** Basic reset for margin, padding, and box-sizing.
* **Body Styles:** Global styles for font, background color, text color, minimum height, and line height.
* **Gradient and Layer Blur Effect:** Styles for the background gradient image and the white blur layer.
* **Container:** Styles for the main container that centers the content.
* **Header:** Styles for the header section, including the logo and navigation.
* **Navigation:** Styles for the navigation links.
* **Main Content:** Styles for the main content area.
* **Tag Box:** Styles for the animated tag element.
* **Main Content Heading:** Styles for the main headline.
* **Description:** Styles for the descriptive text.
* **Buttons:** Styles for the call-to-action buttons.
* **3D Robot:** Styles for positioning the Spline viewer.
* **Tablet Responsive:** Media queries for tablet-sized screens.
* **Mobile Responsive:** Media queries for mobile-sized screens.

## Libraries and Assets

* **Spline Viewer:** Loaded via CDN in the `index.html` to display the 3D model.
* **AOS (Animate On Scroll):** Loaded via CDN in the `index.html` for scroll-triggered animations. The initialization script is included at the end of the `index.html` body.
* **gradient.png:** A local image file for the background gradient.

## Further Development

Potential areas for further development include:

* Adding more content sections.
* Implementing interactive elements beyond the 3D model.
* Integrating a backend for form submissions (if any).
* Optimizing assets for better performance.
* Adding unit and integration tests.
