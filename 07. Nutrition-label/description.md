# Nutrition Label

This project showcases a **nutrition label design**, mimicking the layout and style of a typical food product's nutritional information. The design is clean, with a modern and professional appearance, utilizing **CSS** for layout and styling, and **Google Fonts** for typography.

## Overview

The label displays essential nutritional information, including serving size, calories per serving, and a breakdown of key nutrients such as fat, cholesterol, carbohydrates, and proteins. It uses dividers to separate different sections for clarity, and applies different font sizes and weights to differentiate important details.

### Structure

1. **Header**: Contains the product's name "Nutrition Facts" with a small divider, followed by serving information.
2. **Calories Information**: Displays the amount of calories per serving in a large font for visibility.
3. **Nutrient Breakdown**: Lists various nutrients (fat, cholesterol, sodium, etc.) with their respective daily value percentages.
4. **Footer Note**: A small note explaining the *% Daily Value* (DV) to help users understand the nutritional context.


## CSS Styling

- **Global Styles**:
  - **`box-sizing: border-box;`** ensures that padding and borders are included in the element’s total width and height.
  - The body font is set to **Open Sans** (imported from Google Fonts) for a clean, modern look.

- **Label Container**:
  - The `.label` container has a black border and padding, giving it the appearance of a physical nutrition label. The width is set to **270px** to match a typical label size.

- **Text Styling**:
  - The **header title** (`h1`) is centered with a letter-spacing of 0.15px for a refined look.
  - **Bold text**: The `.bold` class is used for important elements like nutrient names and daily values.
  - **Font Sizes**: Various text sizes are set for clarity, including larger font sizes for calories and bold text for important nutrients.

- **Dividers**:
  - `.divider` is used to create horizontal lines that separate sections visually. There are different sizes (e.g., **`medium`** and **`large`**) to differentiate section breaks.

- **Nutrient Information**:
  - Nutrients are displayed in a **flexbox layout**, with amounts and daily values spaced apart. The `.calories-info` and `.daily-value` classes are used to position these items.
  - Nutrient items are formatted with indentations for sub-categories (like Saturated Fat, Sugars, etc.).

- **Footer Note**:
  - The **note** at the bottom explains the *% Daily Value* concept. It's styled with a smaller font size and a slight text-indent for a cleaner look.

## Features

- **Responsive Layout**: The label is compact and designed to fit a specific width, mimicking the look of an actual product label.
- **Typography**: Proper use of font sizes, bolding, and font weights highlights key nutritional details.
- **Dividers**: Horizontal dividers provide a clean and organized structure, making the label easy to read.
- **Clean Design**: A minimalist approach is used, with a focus on clarity and readability.