# Product Data

This folder contains the product data for the DearPlayers website.

## Product Data Structure

Each product has a folder named after the product slug.

The folder contains the following files:

- `page.default.html`: The default template for the product page.
- `faq.default.md`: The default template for the FAQ section.

- `en-my`, `en-sg`, `en-ph`, `en-th`: The product page content for each channel.
- `en-my/faq.md`, `en-sg/faq.md`, `en-ph/faq.md`, `en-th/faq.md`: The FAQ section for each channel.


## Page

The page is a HTML file that contains the product page content, class names are used for styling, can use Tailwind CSS classes.

## FAQ

The FAQ is a markdown file that contains the frequently asked questions for the product.


## Variables

- `{{channel}}`: The channel slug.
- `{{country}}`: The country name.