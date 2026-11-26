# StockSense – Inventory Dashboard

A responsive web dashboard that helps a small business see which products are running low on stock.

**Problem:** Stock-outs lose sales, and checking long product lists by hand is slow.
**Solution:** The dashboard loads product data from a REST API and shows summary cards, a stock-by-category chart, and product cards with colour-coded stock status (In stock / Low stock / Out of stock).

## Features
- Fetches product data from a REST API (DummyJSON) using `fetch` and async/await
- Search, category filter, sorting, and an adjustable low-stock limit
- Summary cards and a simple CSS bar chart
- Loading state, error handling with backup data
- Responsive layout (mobile and desktop) and light/dark theme

## Tech
HTML5, CSS3 (Grid, Flexbox, CSS variables), JavaScript (ES6), REST API

## Run
Open `index.html` in a browser, or host it free with GitHub Pages.
