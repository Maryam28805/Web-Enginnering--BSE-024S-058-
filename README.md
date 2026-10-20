# ByteBazaar - Tech Store Website

Web Engineering - Assignment 1 (HTML and CSS only, no JavaScript)

## Architecture note

**Pages (9):** Home, All Products, Laptops, Phones, Accessories, Deals, About, FAQ, Contact.

**Navigation:** Every page has the same header with links to all 9 pages. The current page is highlighted with the `active` class. The footer has extra links. Product buttons lead to the Contact page to place an order. The nav wraps on small screens, so no JavaScript menu is needed.

**Images:** All pictures are in the `images/` folder and are added with the `<img>` tag. File names are listed in `images/README.txt`.

**CSS:** One shared file, `style.css`, is linked in every page. It uses CSS variables for colors, Flexbox for the header, Grid for product cards and page layouts, hover and focus styles, and a media query for mobile screens. The FAQ uses the HTML `<details>` tag, so it opens and closes without JavaScript.

## Run locally
Open `index.html` in a browser.
