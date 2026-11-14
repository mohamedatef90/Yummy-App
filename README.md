# Yummy

A recipe browser built with HTML, CSS, Bootstrap, and jQuery. It loads meals from the public [TheMealDB](https://www.themealdb.com) API (`https://www.themealdb.com/api/json/v1/1/`) and has no backend and no build step.

## Features

- **Home:** a list of meals (the American cuisine list is loaded by default).
- **Search** by meal name or by first letter.
- **Categories, Areas, and Ingredients:** browse each list, then open the meals for the chosen item.
- **Meal details** view.
- **Contact form** with client-side validation (name, email, phone, age, and password fields). Nothing is submitted to a server.
- A slide-out side navigation and a loading screen (jQuery animations).

## Tech

- HTML, CSS (`css/style.css`), and JavaScript (`js/main.js`) with jQuery 3.6.3
- Bootstrap 5 and Font Awesome (bundled in `css/` and `js/`)
- Poppins from Google Fonts
- TheMealDB API over `fetch`

## Running

Open `index.html` in a browser. The app needs an internet connection for the API and Google Fonts.

## Project structure

```
index.html   Page
js/main.js   API calls, rendering, side navigation, and form validation
css/         Bootstrap, Font Awesome, and custom styles
Img/         Logo
```
