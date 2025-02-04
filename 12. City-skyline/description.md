# City Skyline

This code represents an HTML and CSS setup that creates a city skyline scene, with background and foreground buildings. The buildings are arranged into various layers using `div` elements, each with a specific class and corresponding CSS styles to create a visually pleasing structure. Here's a breakdown of the key elements in the code:

## HTML:

### Building Div Structure:
The HTML structure is organized into two main sections:
- **background-buildings**: Contains the buildings in the background, stacked on top of each other.
- **foreground-buildings**: Contains the buildings in the foreground, also stacked with varying heights.

### Building Wrapping:
- The buildings are wrapped in a `building-wrap` class, and within each wrap, specific elements represent parts of the building, such as windows or walls, with their own class names (e.g., `bb1a`, `bb2a`, `fb3b`, etc.).

## CSS:

### Color Variables:
At the top, there are CSS variables to define the colors for the buildings and windows.
- These variables include `--building-color1`, `--window-color1`, and so on.

### Building Styles:
- Different building elements (`bb1`, `bb2`, etc.) are styled with widths, heights, and colors defined by the CSS variables.
- The background buildings (e.g., `.bb1`, `.bb2`) are styled to look like tall buildings in the distance, using gradients and shapes to add depth.

### Window Styling:
- The windows within the buildings are created using the `window-wrap` class and individual `bb1-window`, `fb2-window`, etc., which are aligned in a grid pattern using Flexbox.

### Sky and Background:
- The sky is given a gradient effect using `radial-gradient` to create a sunset or sunrise feel. The gradient changes based on the time of day (yellow to blue for daytime and grayish tones for nighttime).

### Foreground Buildings:
- The foreground buildings are styled similarly to the background ones but with more prominent colors to create a sense of depth and perspective.

## Media Query:

### Responsive Design:
- There’s a media query at the end of the CSS that adjusts the colors and sky gradient for smaller screen sizes (under 1000px).
- The building colors are changed to darker tones (`#000`), and the sky becomes more muted with a darker gradient, simulating nighttime.

## How It Works:
- The layout uses `flex` to align the buildings in a row, both in the background and foreground. 
- The sky `div` is styled to create a nice gradient effect, simulating a sunset or sunrise.
- Each building (`bb1`, `bb2`, etc.) uses specific widths and heights, and elements within them (like windows) are carefully spaced using flex and gradients.
- When viewed in a browser, the buildings will appear stacked in the foreground and background, creating a layered, cityscape effect.