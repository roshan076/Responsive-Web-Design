# Survey Form

This project creates a survey form for users to share their thoughts and experiences with the game **Clash of Clans**. The form includes several fields that allow users to provide personal details, game preferences, and feedback.

## Overview

The survey form asks users for the following information:
- **Name** (text input).
- **Email** (email input).
- **Age** (number input with a range from 10 to 70 years).
- **Town Hall Level** (dropdown select to choose from Town Hall 1 to Town Hall 17).
- **Frequency of Play** (radio buttons for daily, weekly, monthly, occasionally, or never).
- **Game Features Enjoyed** (checkboxes for different game features like Farming Resource, Trophy Pushing, etc.).
- **Feedback** (textarea for users to provide their feedback).
- **Submit Button** (to submit the form).

The form is designed with clear labels and placeholders to make the survey easy to complete. Additionally, fields like Name, Email, Age, and Feedback are required to ensure necessary information is collected.

## HTML Structure

The form includes:
1. **`<form>`**: This element encloses the input fields and the submit button.
2. **`<label>`**: Labels for each field provide descriptions for the user inputs.
3. **`<input>`**: Used for different types of data entry, including text, email, number, and submit.
4. **`<select>`**: Dropdown list for selecting the Town Hall Level.
5. **`<fieldset>`**: Groups related fields together, such as the frequency of play and game features.
6. **`<textarea>`**: A larger input field for the user's feedback.

## CSS Styling

The form is styled with a modern, clean design to ensure a good user experience:
- **Body**: The background color is a soft light blue (`rgb(215, 247, 247)`), providing a calm and pleasant environment for the form.
- **Form Layout**: The form is centered on the page with a background color of dark blue (`#1b1b32`) and rounded corners (`border-radius: 20px`), making it visually appealing. The form width is responsive and adapts to different screen sizes.
- **Input Fields**: The input fields (text, email, number, textarea, and dropdown) have a consistent look with white text on a dark background, maintaining good contrast for readability.
- **Buttons**: The submit button is green with azure text, and it changes to light green with dark text when hovered, making it interactive.
- **Form Elements Spacing**: Each input field has proper margins and padding for better alignment and readability.

## Features

- **Responsive Design**: The form adjusts its layout for different screen sizes, ensuring it looks great on mobile devices as well as desktops.
- **User-friendly Inputs**: The use of dropdowns, checkboxes, radio buttons, and a text area provides various ways to gather user preferences and feedback.
- **Hover Effects**: The submit button changes color when hovered over, providing visual feedback to the user.