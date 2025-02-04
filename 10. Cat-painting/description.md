# Cat Painting

This project creates a simple cat painting using HTML and CSS. The cat's face is made up of various shapes and elements, including the head, ears, eyes, nose, mouth, and whiskers.

## **HTML Structure**

### 1. **Main Structure**
   - The `<main>` element wraps the content, with a class of `.cat-head` that represents the entire cat face.
   - Inside the cat head, there are separate divs for the cat's ears, eyes, nose, mouth, and whiskers.

### 2. **Cat Head:**
   - The `.cat-head` class represents the face, which is a rounded rectangle with a gradient background to give it a 3D effect.

### 3. **Ears:**
   - The ears are represented by the `.cat-left-ear` and `.cat-right-ear` divs, with inner elements (`.cat-left-inner-ear` and `.cat-right-inner-ear`) that create a layered effect using `border` properties.
   - The `rotate()` transform is applied to the ears to tilt them appropriately.

### 4. **Eyes:**
   - The eyes are created with the `.cat-left-eye` and `.cat-right-eye` divs, positioned symmetrically on the cat's face. Each eye has an inner part (`.cat-left-inner-eye` and `.cat-right-inner-eye`) that represents the pupil.

### 5. **Nose and Mouth:**
   - The cat's nose is created using the `.cat-nose` div with a triangular shape and a reddish-brown color.
   - The mouth is created using two divs (`.cat-mouth-line-left` and `.cat-mouth-line-right`), which are rotated to create a "V" shape.

### 6. **Whiskers:**
   - Whiskers are created using div elements inside `.cat-whiskers-left` and `.cat-whiskers-right` divs. Each whisker is a line (`width: 40px; height: 1px;`), positioned at different angles to give the appearance of a cat's whiskers.

## **CSS Styling**

### 1. **Body Styling:**
   - The `* { box-sizing: border-box; }` rule ensures all elements are sized based on their border-box model.
   - The background color of the body is set to `#c9d2fc`, giving it a light blue appearance.

### 2. **Cat Head Styling:**
   - The `.cat-head` class has a width of `205px` and height of `180px`, with a `border-radius` of `46%` to give it an oval shape.
   - The background of the cat's face is created using a `linear-gradient`, transitioning from a grey color at the top to a darker shade at the bottom.

### 3. **Cat Ears Styling:**
   - Each ear is styled with borders that form a triangle shape. The left and right ears have different rotations applied using the `transform: rotate()` property.
   - The inner ears are similarly shaped, with a darker shade to create the inner ear effect.

### 4. **Cat Eyes Styling:**
   - The eyes are made using `border-radius: 60%` to give them an oval shape, and the eyes are placed with the `position: absolute` property.
   - The inner eyes (pupils) are smaller circles, with white backgrounds, and are placed inside the eyes using absolute positioning.

### 5. **Nose Styling:**
   - The `.cat-nose` is a triangle-like shape created with borders. The top-left and top-right borders are transparent, while the bottom border is solid, forming the triangular nose shape.

### 6. **Mouth Styling:**
   - The mouth is made using two divs with rotated borders to form curved lines on either side of the nose.
   - The divs are rotated using `transform: rotate()` to position them into the desired "V" shape.

### 7. **Whiskers Styling:**
   - The whiskers are represented by thin divs with a width of `40px` and height of `1px`. The divs are rotated using `transform: rotate()` to position them at different angles.

## **Key Features**

- **Simplicity:** The cat face is made entirely with CSS shapes and transforms, with no images used.
- **Layered Structure:** The structure of the cat face is built by stacking and transforming basic shapes.
- **Interactive Animation:** While this example does not include animations, you could easily add CSS animations for more dynamic effects.