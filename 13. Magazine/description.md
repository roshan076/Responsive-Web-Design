# Magazine

This code represents an HTML and CSS layout for a magazine-style page that displays an article with headings, images, and various sections. The page is designed to be responsive, with specific styling for mobile and tablet devices.

## HTML Structure:

### Main Sections:
- **Heading Section**: Contains the header with a hero image, title, subtitle, author information, and social media icons.
  - The hero image and text are central to the design.
  - The author information includes the name of the author (linked to freeCodeCamp) and the publish date.
  - Social media icons are displayed to encourage sharing.

- **Text Section**: Contains the main content of the article. The text is organized with headings, paragraphs, and a blockquote.
  - The first paragraph is styled to have a large first letter.
  - The quote is highlighted with specific styling to stand out.

- **Text with Images Section**: Includes a brief history list of the curriculum and images related to freeCodeCamp projects.
  - The images are displayed in a responsive grid layout.
  - A blockquote is also included with a related quote.

### Elements in the HTML:
- **Social Media Icons**: Uses FontAwesome icons for Facebook, Twitter, Instagram, LinkedIn, and YouTube.
- **Images**: Included are three images related to freeCodeCamp projects, with lazy loading applied.
- **Lists**: A brief history of the curriculum is displayed using an unordered list with specific classes for each version.

## CSS Styling:

### General Styles:
- **Reset Styles**: `*, ::before, ::after` rule resets padding, margin, and box-sizing to ensure consistency across browsers.
- **Fonts**: The page uses custom fonts from Google Fonts (`Anton`, `Baskervville`, and `Raleway`).
  - `Anton` is used for the main title, `Raleway` for subheadings and text, and `Baskervville` for the body text.
- **Font Size and Layout**: The font size is set to `62.5%` for easier scaling based on rem units.
  - The layout uses a grid system for organizing content.

### Hero Section:
- **Hero Image**: The hero section spans the full width of the container, with the title and subtitle centered above it.
  - The hero title has a large font size and an orangered color.
  - The subtitle is styled with a smaller font size and orangered color.

### Author and Date Section:
- The author name is linked to freeCodeCamp and changes color on hover.
- The publish date is styled with a lighter color to differentiate it from the rest of the content.

### Social Media Icons:
- The social icons are displayed in a grid layout and styled to align with the content.
- Each icon links to a freeCodeCamp social media page.

### Text Section:
- The text section is designed with a column layout to provide a clean and readable reading experience.
- **First Paragraph**: The first letter of the first paragraph is enlarged and colored orangered.
- **Quote**: The quote is styled with a distinct color and is surrounded by quotation marks.

### Text with Images Section:
- The section containing text and images is also laid out using a grid system.
  - The images are responsive and adjust their layout based on the screen size.
  - The brief history of the curriculum is organized in an unordered list with versioned items.

### Media Queries:
- **Responsive Design**: Multiple media queries are included to ensure the page adapts to various screen sizes, such as mobile and tablet devices.
  - **Max-width 720px**: The layout of the images is adjusted to fit smaller screens.
  - **Max-width 600px**: The text section switches to a single column layout.
  - **Max-width 550px**: Adjusts the font size for smaller screens, making the content more readable.
  - **Max-width 420px**: Further reduces the font size of the hero title to fit smaller screens.

### Specific Styling for Different Devices:
- **Mobile Optimization**: Font sizes for titles and text are reduced for mobile devices, making the layout cleaner and easier to read on smaller screens.
- **Grid Layouts**: The grid system used throughout the layout adjusts automatically based on screen size, making the design responsive and adaptable.