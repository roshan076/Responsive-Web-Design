# Quiz

This is an accessibility quiz practice project created to help users improve their knowledge of HTML and CSS accessibility standards. The quiz includes sections for personal information as well as questions regarding HTML and CSS concepts. It incorporates accessibility best practices to ensure usability for all users, including keyboard navigation and screen reader support.

## Features

- **Navigation**: The navigation bar provides quick access to different sections of the quiz with clear labels and keyboard shortcuts (using the `accesskey` attribute).
- **Student Info Section**: Includes fields for user details like name, email, and birth date, with proper labels and accessible input types.
- **HTML & CSS Quiz Sections**: Each section contains questions with multiple-choice and dropdown-style answers.
- **Form Accessibility**: Each question has been designed with accessible form elements, such as `fieldset`, `legend`, and clearly defined labels, improving screen reader compatibility.
- **Smooth Scrolling**: The page supports smooth scrolling for better navigation.

## CSS Styling

- **Responsive Design**: The layout adapts to different screen sizes using flexible widths, media queries, and the `max-width` property.
- **Header Styling**: The header is fixed at the top, ensuring that the navigation is always accessible, even when users scroll.
- **Form Elements**:
  - Input fields, dropdowns, and buttons are styled to be visually clear and user-friendly.
  - Labels are correctly associated with form elements using the `for` attribute, enhancing accessibility for screen readers.
- **Keyboard Navigation**: The `accesskey` attribute allows users to quickly navigate to specific sections (INFO, HTML, CSS) without using a mouse.
- **Hidden Content for Screen Readers**: The class `.sr-only` hides elements from visual users but keeps them accessible to screen readers. This is used for visually hiding the "Question #" label while still providing it for screen readers.

## Accessibility Features

1. **Keyboard Shortcuts**: 
   - Links in the navigation (`INFO`, `HTML`, and `CSS`) have `accesskey` attributes, which allow users to navigate the page using specific keyboard keys.
   
2. **Screen Reader Support**: 
   - The `legend` and `fieldset` elements are used in the quiz questions to group related elements together, improving the experience for screen readers.
   - The `.sr-only` class hides certain elements visually while keeping them accessible to screen readers. For example, the question numbers are hidden but still read aloud by screen readers.

3. **Input Fields**: 
   - Proper labeling of form elements ensures that users using screen readers can easily understand the input requirements.
   - The form includes appropriate input types like `email` and `date`, which provide built-in validation and help improve the overall accessibility.

## Conclusion

This quiz is designed with accessibility in mind, ensuring that all users, regardless of their abilities, can participate effectively. It integrates key accessibility practices, such as keyboard navigation, screen reader compatibility, and clear form labeling.
