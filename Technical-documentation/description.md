# Technical Documentation

This page provides a technical overview of Python, covering essential topics such as variables, data types, control flow, and more. The page has a fixed navigation bar on the left and a content area to the right that contains the documentation sections.

## **HTML Structure**

### 1. **Navigation Bar (Navbar)**
   - The navbar is fixed on the left side of the page, providing links to different sections of the Python documentation.
   - Each list item (`<li>`) contains an anchor (`<a>`) tag that links to a specific section, such as "Introduction," "Variables," and "Data Types."

### 2. **Content Area**
   - The `<main>` element contains various sections (`<section>`), each representing a topic in Python. Each section has a header and an article with detailed content.

### 3. **Sections**
   - **Introduction:** Overview of Python's characteristics, such as being high-level, interpreted, and general-purpose.
   - **What you should already know:** Assumes basic knowledge of programming concepts and experience with other programming languages.
   - **Python and Other Languages:** Comparison of Python with other languages like Java and C++.
   - **Hello World:** Introduction to the "Hello World" program in Python.
   - **Variables:** Explanation of variable rules and identifiers in Python.
   - **Declaring Variables:** Syntax for declaring variables in Python using dynamic typing.
   - **Variable Scope:** Explanation of global and local variable scope.
   - **Constants:** Python's convention for constants using uppercase variable names.
   - **Data Types:** Overview of Python's built-in data types like int, float, str, list, etc.
   - **if...else Statement:** Example of conditional statements in Python.
   - **While Statement:** Example of a while loop in Python.
   - **Function Declarations:** Syntax for defining functions in Python.
   - **Reference:** Source reference for the content (Python's official documentation).

## **CSS Styling**

### 1. **General Styling**
   - **Font:** The page uses `Open Sans`, with fallback fonts `Arial` and `sans-serif`. The line height is set to 1.5 for better readability.
   - **Body Styling:** The background color is white, and the text color is a dark gray (#4d4e53).

### 2. **Navbar Styling**
   - **Fixed Position:** The navbar is fixed on the left side of the page and takes up the full height (`100%`) of the screen.
   - **Width and Border:** The navbar has a width of `300px` and a border on the right side with a slight transparency (`rgba(0,22,22,0.4)`).
   - **List Items:** Each navigation item (`<li>`) has a border on top and a padding of `10px` for the links.
   - **Hover Effect:** The `a` tags inside the navbar have padding and are displayed as blocks to improve the clickable area.

### 3. **Main Content Area**
   - The main content is shifted to the right of the navbar using a left margin of `310px` to create space.
   - The text is styled with a margin of `15px`, and code blocks are given a background color of light gray (`#f7f7f7`) for clarity.
   - **Section Styling:** Each section has a header (`<header>`) aligned to the left and provides clear margins for better readability.

### 4. **Code Blocks**
   - Code blocks are styled with a background of light gray (`#f7f7f7`), padding of `15px`, and a border-radius of `5px` to visually separate them from other content.
   - The code inside the blocks is left-aligned and the line-height is increased for better readability.

### 5. **Responsive Design**

#### **Mobile View (max-width: 815px):**
   - On smaller screens, the navbar becomes horizontal and takes up the full width of the page (`100%`).
   - The main content adjusts to fit the screen width and moves to the top below the navbar, allowing for better accessibility on mobile devices.
   - The navbar also reduces in height to fit the smaller screen size.

#### **Extra Small Devices (max-width: 400px):**
   - Further adjustment is made to ensure the main content area and code blocks fit within the screen without overflow.
   - Margins and padding are reduced for better space utilization.

## **Key Features**

- **Navigation Bar:** A fixed sidebar allows users to navigate through different sections of the documentation easily.
- **Responsive Layout:** The layout adjusts for various screen sizes, ensuring usability on both large and small devices.
- **Content Formatting:** Sections and code blocks are styled for readability, with clear margins and padding.
- **Syntax Highlighting:** Code blocks are highlighted with distinct backgrounds to set them apart from regular text, improving visual hierarchy.