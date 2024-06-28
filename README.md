# Footer Component

This project provides a simple, responsive footer component built with HTML and CSS. The footer is structured into three columns: "Company", "Get Help", and "Follow Us". It includes links for navigation and social media icons.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Responsive Design](#responsive-design)
- [Credits](#credits)

## Installation

1. **Download the files:**
    - `index.html`
    - `style.css`

2. **Include the Font Awesome library for icons:**
    ```html
    <link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css">
    ```

3. **Link the CSS file in your HTML:**
    ```html
    <link rel="stylesheet" href="style.css">
    ```

## Usage

To use the footer project, open the index.html file in your web browser. You will see the structure of the template.

## Customization

1. **Changing Text:**
    - Edit the text within the `<h4>` tags and `<a>` tags to suit your needs.

2. **Updating Links:**
    - Update the `href` attribute in each `<a>` tag to point to the correct URL.

3. **Company Name:**
    - Replace `[Company Name]` in the copyright section with your actual company name.

4. **Social Media Icons:**
    - Add or remove social media icons by adding/removing `<a>` tags within the `.social-links` div. Use Font Awesome classes to change the icons.

## Responsive Design

The footer is designed to be responsive. The columns will adjust as the screen size changes:
- On screens wider than 767px, the footer displays four columns.
- On screens between 767px and 574px, the footer displays two columns.
- On screens smaller than 574px, the footer displays a single column.

## Credits

- Font Awesome for the social media icons: [Font Awesome](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css)
- Google Fonts for the 'Poppins' font: [Google Fonts](https://fonts.google.com/)
