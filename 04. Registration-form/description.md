# Registration Form

This project creates a simple registration form, allowing users to provide personal details and create an account. The form consists of several sections, each gathering different types of information, such as personal details, account type, and preferences.

## Overview

The form includes the following fields:
- **First Name** and **Last Name** (text fields).
- **Email Address** (email field).
- **Password** (password field with a specific pattern for security).
- **Account Type** (radio buttons to choose between "Personal" or "Business").
- **Profile Picture** (file input to upload an image).
- **Age** (number input with a range between 13 and 120 years).
- **How did you hear about us?** (dropdown select field with several options).
- **Bio** (textarea to describe oneself).
- **Terms and Conditions** (checkbox to agree before submission).
- **Submit Button** (button to submit the form).

Each input field has a corresponding label, with some fields marked as required to ensure necessary data is provided.

## HTML Structure

The form is structured with the following elements:
1. **`<form>`**: Encloses all input elements and specifies the action URL and method for form submission.
2. **`<fieldset>`**: Grouping of related fields, such as personal details and account settings.
3. **`<label>`**: Provides a description for each input field.
4. **`<input>`**: Various types of inputs are used (text, email, password, file, number, checkbox, submit).
5. **`<select>`** and **`<textarea>`**: For selecting options and entering longer text, respectively.

## CSS Styling

The form is styled with modern design principles, ensuring it looks clean and user-friendly. Key points include:

- **Body**: The background is dark (#1b1b32), and the font color is light (#f5f6f7), creating a contrast that makes the text easy to read. The font family used is Tahoma, and the page is designed to fill the viewport height (`100vh`).
- **Form Layout**: The form is centered and has a maximum width of 500px, ensuring it is responsive. It adapts to different screen sizes by using relative units like `vw` and `em`.
- **Fieldset Styling**: Each fieldset is given padding and a bottom border, except the last one, to visually separate sections of the form.
- **Input Fields**: Input fields, including text boxes, radio buttons, and dropdowns, are styled with a dark background (#0a0a23) and white text for high contrast. The text areas and inputs span the full width of the form, with ample space between each.
- **Submit Button**: The submit button is styled with a background color of #3b3b4f and white text, making it stand out.
- **Links**: Links are styled to be light gray (#dfdfe2) to maintain the overall theme.

## Features

- **Responsive Design**: The form adjusts its layout based on the screen size, making it suitable for both desktop and mobile devices.
- **Interactive Elements**: The use of radio buttons, file uploads, and dropdown selections adds interactivity to the form.
- **Modern Look**: A clean and minimalistic design ensures that the focus remains on the form fields, with ample spacing and clear text.

