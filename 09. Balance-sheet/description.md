# Balance Sheet

This webpage showcases a **Balance Sheet** for AcmeWidgetCorp, displaying financial data for the years **2019**, **2020**, and **2021**. It includes sections for **Assets**, **Liabilities**, and **Net Worth**, with a clean and visually appealing design. Below is an explanation of the key features:

## **HTML Structure**

### 1. **Main Structure:**
   - The page content is wrapped inside the `<main>` element, with all balance sheet-related information residing within a `<section>`.

### 2. **Header:**
   - The `<h1>` element contains the company name (`AcmeWidgetCorp`) and the title (`Balance Sheet`), organized within a flex container for layout.
   
### 3. **Years Section:**
   - The `<div id="years">` contains the years for which financial data is provided (2019, 2020, 2021) and uses `aria-hidden="true"` for accessibility, making it hidden for visual users but still accessible for screen readers.

### 4. **Tables:**
   - Three separate tables display financial data for **Assets**, **Liabilities**, and **Net Worth**. Each table:
     - Has a caption for the table.
     - Contains a header row with the years (2019, 2020, 2021).
     - Includes data rows for financial values.
     - Has a final total row for each table that sums up assets, liabilities, or net worth.

### 5. **Accessibility:**
   - The `span` elements with the class `sr-only` hide text from the visual display but keep it accessible to screen readers (for example, year labels).
   - Descriptions for each financial item are embedded inside the `<th>` elements with a `description` class, providing additional context.

## **CSS Styling**

### 1. **Font and Layout:**
   - The page uses a **sans-serif** font and a simple color scheme of dark text on a light background for clarity.
   - Flexbox is used in the header to align the title and display the sections vertically.

### 2. **Sticky Years Section:**
   - The `#years` section is sticky (`position: sticky`), ensuring that it stays visible at the top of the page while scrolling, which helps users easily track the years associated with the data.

### 3. **Table Design:**
   - The tables use `border-collapse: collapse` to remove extra spaces between cells, creating a neat presentation.
   - Each table has a **caption** positioned absolutely above the table using `position: absolute`.

### 4. **Total Rows:**
   - The total rows (`tr.total`) are styled with bold text and a double border at the bottom to differentiate them from other rows. They also feature a hover effect, changing the background color when the user hovers over them (`background-color: #99c9ff`).

### 5. **Responsive Design:**
   - The table has flexible width settings for the `<td>` elements, and it adjusts for smaller screen sizes. However, there could be more adjustments made for extremely small viewports (e.g., stacking rows or hiding unnecessary data on mobile devices).

## **Key Features**

- **Responsive and Accessible:** The use of the `sr-only` class ensures that critical information is accessible via screen readers, improving the page's accessibility.
- **Sticky Year Headers:** The years at the top of the page remain visible when scrolling, making it easier to follow financial data over the years.
- **Interactive Hover Effect on Total Rows:** The hover effect on total rows (`background-color: #99c9ff`) enhances user interactivity and engagement.
