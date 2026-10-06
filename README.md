# Mousse Patisserie

Midterm project for Web Technologies I. It is a website for a small patisserie in Astana.

Link: https://winux125.github.io/midterm-web/

## Topic

Mousse sells cakes, cupcakes and pastries and also makes custom cakes. On the website people can look at the catalog with prices and send a request for a custom cake.

## Pages

- Home (index.html)
- Catalog (catalog.html)
- Custom cakes (custom-cakes.html)
- About us (about.html)
- Contact (contact.html)

The structure is the same as in Task 5 of Assignment 1.

## What is used

- Navigation bar and footer on every page
- Semantic HTML (header, nav, main, section, article, footer)
- A table with cake sizes and prices
- Two forms: custom cake request and contact
- Flexbox for the header and steps, Grid for product cards and gallery
- Position: sticky header, absolute text on the hero image and badges on products
- Media queries for tablet (992px) and mobile (576px)
- Bootstrap 5 grid and utility classes

## Local assets and offline use

Open `index.html` directly in a browser. All photos are stored in `images/`, and Bootstrap 5.3.3 is stored in `css/bootstrap.min.css`. The pages do not download styles or photos from external servers.

The Contact page uses `map.html` to display a local, static map of Astana IT University at EXPO, Block C1. The image is rendered from downloaded OpenStreetMap building footprints, roads and green areas, with the marker at the university's OpenStreetMap point. The source data is stored in `images/location-map.osm`. The map does not support zooming or panning. OpenStreetMap attribution is displayed inside the frame.

Original photo URLs and map coordinates are recorded in `images/sources.json`. Social links and the map attribution link require internet only when followed. The forms still require a backend to send messages.

## Authors

- Baubek Serikbay (winux125)
- Mardan Khalilov (Mardan7)
