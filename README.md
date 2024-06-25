# Myntra Functional Clone - README

## Overview

This project is a functional clone of the Myntra website, featuring a home page with product listings and a shopping bag page. The clone is built using HTML, CSS, and JavaScript, and incorporates a design inspired by Myntra's actual website. 

## Table of Contents
1. [Project Structure](#project-structure)
2. [Dependencies](#dependencies)
3. [Installation](#installation)
4. [Usage](#usage)
5. [File Descriptions](#file-descriptions)
6. [Customization](#customization)
7. [Known Issues](#known-issues)
8. [Future Enhancements](#future-enhancements)

## Project Structure

The project directory is structured as follows:

```
myntra-clone/
│
├── css/
│   ├── index.css
│   ├── bag.css
│
├── data/
│   └── items.js
│
├── images/
│   ├── myntra_logo.webp
│   ├── 1.jpg
│   ├── 2.jpg
│   ├── 3.jpg
│   ├── 4.jpg
│   ├── 5.jpg
│   ├── 6.jpg
│   ├── 7.jpg
│   ├── 8.jpg
│
├── pages/
│   └── bag.html
│
├── scripts/
│   ├── index.js
│   ├── bag.js
│
├── index.html
├── README.md
```

## Dependencies

- Google Fonts (Material Symbols Outlined): For icons used in the navigation bar and other sections of the page.
- CSS Flexbox: For layout and positioning.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/myntra-clone.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd myntra-clone
   ```

3. **Open `index.html` in your browser to view the home page:**
   ```bash
   open index.html
   ```

4. **Open `pages/bag.html` in your browser to view the shopping bag page:**
   ```bash
   open pages/bag.html
   ```

## Usage

- **Home Page:**
  - The home page displays a navigation bar, a search bar, and various product listings.
  - Products are dynamically loaded from the `items.js` file.

- **Shopping Bag Page:**
  - The shopping bag page displays the items added to the bag.
  - Users can view the summary of the items in the bag, including price details and total cost.

## File Descriptions

### HTML Files
- **index.html:** The main landing page containing the navigation bar, search bar, product listings, and footer.
- **bag.html:** The shopping bag page displaying items added to the cart.

### CSS Files
- **index.css:** Contains styles for the home page, including the header, navigation bar, product listings, and footer.
- **bag.css:** Contains styles for the shopping bag page, including item details, price summary, and order button.

### JavaScript Files
- **index.js:** Handles the dynamic loading of products on the home page from the `items.js` data file.
- **bag.js:** Manages the functionality of adding items to the bag, updating the bag count, and displaying the bag summary.

### Data Files
- **items.js:** Contains the product data in a JSON-like array format. Each product object includes details such as `id`, `image`, `company`, `item_name`, `original_price`, `current_price`, `discount_percentage`, `return_period`, `delivery_date`, and `rating`.

### Images
- Contains logo and product images used in the project.

## Customization

- **Adding New Products:**
  - Edit `items.js` to add new product objects.
  - Each product object should follow the existing structure.

- **Modifying Styles:**
  - Update the CSS files (`index.css`, `bag.css`) to change the look and feel of the pages.

- **Updating Icons:**
  - The icons are sourced from Google Fonts (Material Symbols Outlined). Modify the `link` tag in the HTML files to include different icons if needed.

## Known Issues

- The current implementation does not persist the shopping bag items between page reloads.
- There is no backend integration; all data is static and stored in the `items.js` file.
- Responsive design adjustments are minimal and may not provide an optimal user experience on all device sizes.

## Future Enhancements

- **Local Storage:** Implement local storage to persist shopping bag items between sessions.
- **Responsive Design:** Improve responsiveness for better compatibility with different screen sizes.
- **Backend Integration:** Connect to a backend service to fetch and manage product data dynamically.
- **User Authentication:** Add user login and profile management functionalities.

## Conclusion

This project is a simple yet functional clone of the Myntra website, focusing on the essential features like product listing and shopping bag management. It serves as a great starting point for learning web development and can be expanded with additional features and enhancements.

Feel free to contribute to this project by submitting issues and pull requests on the GitHub repository. Enjoy coding!
