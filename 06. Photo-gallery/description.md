# Photo Gallery

This project is a simple **responsive photo gallery** built using **CSS Flexbox**. It showcases a collection of images, all organized neatly in a grid-like layout that adjusts seamlessly to different screen sizes.

## Overview

The gallery is centered on the page with a **header** at the top that introduces the gallery, followed by a collection of images displayed using a flexible layout. The design adapts well to various screen sizes by utilizing Flexbox for layout management, making it responsive and user-friendly.

### Structure

- **Header**: A simple header section at the top of the page with the title "CSS Flexbox Photo Gallery."
- **Gallery**: The main body of the page contains images of cats, arranged using Flexbox properties to ensure they are spaced and aligned properly. The gallery is responsive, automatically adjusting the number of images per row based on screen width.

## CSS Styling

The layout and style of the gallery are achieved using Flexbox and CSS properties:

- **Global Styles**: 
  - The `box-sizing` property is set to `border-box` for all elements to make box model calculations more predictable.
  - The body background is set to a light color (`#f5f6f7`), and the text font is set to **sans-serif** for a clean and modern look.
  
- **Header**:
  - The header has a dark background (`#0a0a23`) and white text. It also has uppercase text styling and padding for spacing. A border (`#fdb347`) runs along the bottom to add emphasis.

- **Gallery**:
  - The gallery uses **Flexbox** to display images in a responsive row, with **wrap** functionality enabled to allow the items to wrap onto the next line when the container's width is too small.
  - **Gap** is used between images to ensure that they don’t touch each other.
  - The images themselves are styled to be **responsive**, with a `max-width` of 350px and a `height` of 300px. **`object-fit: cover`** ensures that the images fill their space properly without stretching.

- **Responsive Layout**:
  - The gallery is centered using `margin: 0 auto`, and the `max-width` of the gallery container is set to **1400px** to maintain a reasonable width for large screens.
  - Flexbox properties like **justify-content** and **align-items** help center the images both horizontally and vertically.

## Features

- **Responsive Design**: The gallery adapts to different screen sizes using Flexbox, ensuring the layout is both mobile-friendly and desktop-ready.
- **Image Styling**: Each image has a rounded border radius and is contained within a flexible grid that adjusts based on available space.
- **Centered Layout**: The gallery is centered on the page, with proper padding and margins to keep everything spaced appropriately.

