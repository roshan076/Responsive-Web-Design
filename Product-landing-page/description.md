# Product Landing Page

## Overview

This is a **Product Landing Page** for "Himalayan Java Coffee." The page includes several key sections: 
- **Header** with the brand logo and navigation.
- **Main Section** which contains an email form, features of the product, a video section, and pricing.
- The layout is responsive, adapting to various screen sizes through media queries.

## HTML Structure

### Header Section
- **Logo Image**: Displays the Himalayan Java logo (`#header-img`).
- **Brand Name**: The text "Himalayan Java Coffee" is styled with the class `.header-text`.
- **Navigation Bar**: Provides links to different sections of the page:
  - Features
  - Stories From Java
  - Pricing

### Main Content Section
- **Main Heading**: The title "From the Himalayan peaks to your perfect cup."
- **Email Form**: A form to collect email addresses, which includes:
  - An email input field (`#email`)
  - A submit button (`#submit`)
  
- **Features Section**: A list of key product features:
  - Mountain-Grown Quality
  - Artisanal Crafting
  - Sustainably Sourced
  
- **Stories From Java**: Contains an embedded YouTube video that tells the story of the coffee.
  
- **Pricing Section**: Displays a product card for the "Roasted Bean" priced at $100, including its features and a "Select" button.

## CSS Breakdown

### Global Styles
- **Reset Styles**: All padding, margins, and box-sizing are reset for consistency.
- **Font Setup**: The root font size is set at `62.5%` to use rem units effectively for scalability.

### Header Styles
- **Fixed Header**: Positioned at the top of the page, with a logo, title, and navigation bar.
- **Logo**: The logo is displayed with a circular border and is positioned using `justify-self: end`.
- **Navigation Bar**: Links are displayed horizontally and styled with a hover effect (changes background and color).

### Main Section Styles
- **Layout**: Flexbox is used to structure the content, with centered elements and proper spacing.
- **Form**: Includes a styled email input field and a submit button, both with responsive properties.
  
### Features Section
- Each feature is displayed as a list with a heading and a description for better readability.

### Pricing Section
- Displays the "Roasted Bean" product using a card layout. The card includes:
  - Product name
  - Price
  - Features in a list
  - A styled button to select the product

### Responsive Design
- Media queries adjust the layout for smaller screens (e.g., under 400px wide) to make the header and content display in a row format.

## Interactive Features
- **Hover Effects**: Buttons and navigation links have hover effects that change colors.
- **Embedded Video**: A YouTube video is embedded in the "Stories From Java" section.
- **Responsive Layout**: The layout uses flexbox and media queries to adapt the page for various screen sizes.