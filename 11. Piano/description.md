# Piano

This project is a simple piano layout created with HTML and CSS. The piano keys are styled using `div` elements, and there are two types of keys: white keys and black keys.

## **HTML Structure**

### 1. **Main Structure**
   - The `<body>` contains a `div` with the id `#piano`, which serves as the main container for the piano.
   - Inside the `#piano` div, there's an image of the freeCodeCamp logo at the top.
   - The `.keys` div contains multiple `.key` divs, representing individual piano keys.
   - Each `.key` div can be either a white key (default) or a black key, which is styled using the `black--key` class.

### 2. **Piano Keys:**
   - The piano consists of 21 keys arranged in a traditional piano layout with both white and black keys.
   - White keys are represented by `.key`, while black keys are represented by `.key.black--key`.

### 3. **Logo:**
   - The `img` element with the class `logo` displays the freeCodeCamp logo. It's positioned at the top of the piano using absolute positioning.

## **CSS Styling**

### 1. **Body Styling:**
   - `html` and all elements use `box-sizing: border-box` to include padding and border in the element's total width and height.
   - The `#piano` container has a background color of `#00471b`, and it is styled with padding, margin, and rounded corners.

### 2. **Piano Styling:**
   - The `.keys` div serves as the background container for all the piano keys, styled with a dark color (`#040404`) to represent the piano body.
   - The `.key` divs represent the white keys of the piano. These are styled with a white background color, rounded corners at the bottom, and a margin between them to give the appearance of individual keys.

### 3. **Black Keys Styling:**
   - The black keys are created using `.key.black--key`. They are styled using the `::after` pseudo-element, which creates a black rectangle over the white key to simulate the appearance of the black keys.
   - The `::after` pseudo-element is absolutely positioned and has a width of `32px` and height of `100px`.

### 4. **Logo Styling:**
   - The logo image is given a fixed width of `200px` and is absolutely positioned at the top of the piano layout.

### 5. **Responsive Design:**
   - **Mobile View (max-width: 768px):**
     - The piano's width is reduced to `358px`, and the logo's width is reduced to `150px` to fit smaller screens.
     - The `.keys` div is resized to `318px` to ensure it stays proportionate on smaller devices.
   
   - **Tablet View (min-width: 769px and max-width: 1199px):**
     - The piano's width is set to `675px`, and the `.keys` div is resized accordingly to `633px` for medium-sized screens.

## **Key Features**

- **Basic Piano Layout:** The keys are created using simple `div` elements. The black keys are layered over the white keys using CSS pseudo-elements.
- **Logo:** The freeCodeCamp logo is displayed at the top of the piano, ensuring that it doesn't interfere with the piano keys.
- **Responsive Design:** The piano layout adjusts for different screen sizes, ensuring that it looks good on both mobile and desktop devices.