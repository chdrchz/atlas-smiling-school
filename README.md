# Atlas Smiling School

## Project Overview

In this project, you will create three web pages using Bootstrap. The goal is to apply your knowledge of HTML, CSS, Accessibility, Responsive Design, and Bootstrap to create fully functional web pages that match the provided design files. You have creative freedom in your approach, but the final pages must closely resemble the designer's mockups.

## Requirements

- **Framework**: Use Bootstrap for layout and styling.
- **CSS**: Minimize custom CSS by leveraging Bootstrap classes as much as possible.
- **Responsiveness**: The web pages should adjust to different screen sizes with specific breakpoints for tablet and mobile versions.
- **Button Styling**: Implement hover and active states for buttons with `opacity: 0.9`.

## Breakpoints

- **Tablet**: At a screen width of 768px, the web pages should switch to the tablet version.
- **Mobile**: At a screen width of 576px, the web pages should switch to the mobile version.

## Usage

1. **Clone the Repository**: Clone the project repository to your local machine.

    ```bash
    git clone https://github.com/chdrchz/atlas-smiling-school
    ```

2. **Navigate to Project Directory**: Change into the project directory.

    ```bash
    cd atlas-smiling-school
    ```

3. **Open in Browser**: Open `landing.html` in your preferred browser to view the main page.

4. **Inspect Responsive Design**: Use the browser's developer tools to test the responsiveness of the web pages by resizing the window to the specified breakpoints.

## Development

- **HTML**: Write semantic HTML to ensure the pages are accessible and follow best practices.
- **CSS**: Minimize the custom `styles.css` by utilizing Bootstrap classes wherever possible.
- **Bootstrap**: Use Bootstrap’s grid system, components, and utilities to create a responsive layout and styling.

## Custom CSS

- Only add custom CSS rules to `styles.css` when necessary to achieve the exact look of the design.
- For buttons, implement the following styles:

    ```css
    .btn-custom:hover,
    .btn-custom:active {
        opacity: 0.9;
    }
    ```

## Best Practices

- **Accessibility**: Ensure all web pages are accessible, including using proper HTML semantics, alt text for images, and sufficient color contrast.
- **Responsive Design**: Use Bootstrap's grid and responsive utilities to create a fluid layout that adapts to different screen sizes.
- **Code Quality**: Maintain clean, readable, and maintainable code. Use comments where necessary to explain your code.