Bloom & Brew Café Website

A responsive, single-page website for Bloom & Brew, a neighbourhood café. Built with plain HTML, CSS, and JavaScript.

## Features

- Home hero with café photography and menu call to action
- Our Story section with rotating café captions
- Six photo menu cards with hover and glow effects
- Café photo gallery
- Contact section with call, WhatsApp, and Google Maps links
- Responsive navigation for mobile screens
- Sticky header, smooth scrolling, and scroll reveal effects
- Basic search and social sharing metadata
- Security response headers in `_headers` for Cloudflare Pages

## Project files

```text
bloom-and-brew/
├── index.html   # Page content and metadata
├── style.css    # Layout, colors, responsive styles, and animations
├── script.js    # Mobile menu, rotating story captions, and scroll effects
├── _headers     # Cloudflare Pages response headers
└── README.md   # Project notes
```

## Preview locally

1. Open the `bloom-and-brew` folder in Visual Studio Code.
2. Open `index.html` in a web browser, or use the Live Server extension in VS Code.

The page uses external images from Unsplash, fonts from Google Fonts, and an embedded Google Map, so those features need an internet connection.

## Publish

Push the project files to a GitHub repository and connect that repository to your Cloudflare deployment. With Git integration enabled, Cloudflare can publish new commits automatically.

For a static Cloudflare Pages deployment, keep `_headers` in the published output directory beside `index.html`. Cloudflare Pages applies the response headers in that file to static asset responses.

## Before publishing

Replace the sample café address, phone number, opening hours, and map location in `index.html` with Bloom & Brew's real details. Update the phone number in the `tel:` and `wa.me` links as well as the structured data block.

The website is a static front end. Do not put passwords, private API keys, or other secrets in its HTML, CSS, or JavaScript files.
