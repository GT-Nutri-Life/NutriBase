# NutriBase — Food Composition Table

NutriBase is a single-page web app that lets you explore a food composition table for Sri Lanka and India. It presents energy, macronutrients, vitamins, and minerals per 100g edible portion with fast search, filters, and detailed food views.

## Live site

https://gt-nutri-life.github.io/FoodCompositionTable/

## Features

- Search by English name, local name, scientific name, notes, or food ID.
- Filter by food group, form (raw or cooked), and source country.
- Toggle between table and card views with nutrient highlights.
- Open food details with references and notes.
- Optional per-food image URLs stored in localStorage.

## Data notes

- Each row represents values per 100g edible portion.
- Country and reference fields indicate the source of each entry.
- Data is embedded directly in `index.html` as a CSV string for a fully static deployment.

## Project structure

- `index.html` — single-page application with data, styling, and logic.
- `assets/og-image.png` — social sharing image for SEO metadata.

## Getting started

No build step is required. Open `index.html` in a browser, or serve it with any static HTTP server:

```bash
python -m http.server
```

## Deployment

This repository uses GitHub Pages via `.github/workflows/static.yml`. Pushes to `main` deploy automatically.

## Contributing

Suggestions and improvements are welcome. Please open an issue or submit a pull request with clear context and screenshots if UI changes are involved.

## License

No license file is currently provided. All rights reserved until a license is added. Add a `LICENSE` file if you intend to define reuse terms.
