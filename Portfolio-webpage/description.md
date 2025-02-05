# Portfolio Webpage

## Overview
This project is a personal portfolio webpage designed to showcase a professional profile with sections like an introduction, projects, and contact details. It uses HTML for structure and CSS for styling and layout. The portfolio is responsive and includes smooth animations and interactions, such as hover effects and scaling buttons. The design incorporates modern fonts, a color palette, and a clean, minimalistic layout.

## Structure

### HTML
The HTML defines the structure of the portfolio. It includes:

- **Navbar**: A fixed navigation bar with links to different sections of the page, such as "About", "Projects", and "Contact".
- **Welcome Section**: A section displaying the name, profession, and a brief introduction.
- **Projects Section**: A section to display some projects with images and titles. Each project links to an external URL (e.g., GitHub).
- **Profile and Contact Section**: A section offering different contact options with clickable links for social media (Facebook, Twitter, LinkedIn, GitHub), email, and phone.

### CSS
The CSS provides styling for the layout, colors, typography, and animations:

- **Variables**: Custom properties (CSS variables) define the primary color palette for easy management and consistency across the site.
- **Typography**: Google Fonts are used for the page text. 'Poppins' and 'Raleway' are the main fonts applied for the body text and headings, respectively.
- **Navigation Bar**: The navbar is fixed to the top with a red background and links styled with padding. The links change color on hover.
- **Welcome Section**: This section covers the entire viewport height and uses a gradient background to create a dark theme with a welcoming message.
- **Projects Section**: A grid layout showcases the projects. Each project tile has an image, title, and hover effect. The section has a blue background with a header and a button linking to more projects.
- **Contact Section**: Displays clickable social media and contact options, with an emphasis on interactivity via hover effects.
- **Responsive Design**: A media query ensures that the design remains functional and visually appealing on mobile devices, including adjustments to font sizes and navigation alignment.

### Key Features
- **Hover Effects**: Interactive hover effects on project tiles, buttons, and contact links to improve user experience.
- **Responsive Layout**: The design adapts to different screen sizes, especially mobile devices (using media queries).
- **Smooth Scrolling**: The `scroll-behavior: smooth;` property enables smooth scrolling when navigating between sections.
- **Fixed Navbar**: The navigation bar stays at the top of the screen while scrolling through the page.
- **Minimalist Design**: The layout emphasizes simplicity, with clean fonts and a straightforward color scheme to maintain focus on the content.

## Custom Properties
- `--main-white`: Defines the main background color (light color).
- `--main-red`: The primary red color used for the navbar and interactive elements.
- `--main-blue`: A blue color used for the projects section background.
- `--main-gray`: A gray color used for the footer and background elements.

## Animations and Interactions
- **Scaling Effect**: The project tiles scale up slightly when hovered over, providing a visual cue to the user.
- **Button Hover Effect**: The buttons change background color and the icon inside shifts slightly when hovered.
- **Contact Link Hover**: The contact links shift vertically when hovered, providing interactivity.

## Media Queries
- Adjustments are made for screens with a width of 28.75em or less (mobile devices). This includes:
  - Centering the navbar items.
  - Adjusting font sizes for the projects header and profile header for better readability on small screens.