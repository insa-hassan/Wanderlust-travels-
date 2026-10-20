 # Wanderlust Travel Agency - Web Technologies Assignment 2

## 1. What CSS Is and Its Benefits
Cascading Style Sheets (CSS) is a style sheet language used to describe the visual presentation and layout of HTML documents. By separating content from design, CSS provides clean code structure, central maintenance, and faster page loading through browser caching.

## 2. CSS Rule Breakdown
From `style.css`:
    css
label { margin-bottom: 6px; }

Selector (label): Targets every <label> element.
Property (margin-bottom): Controls space underneath the element.
Value (6px): The exact distance unit applied by the browser.


3. ## Inline, Embedded, and External CSS
Inline CSS (index.html): Applied directly inside HTML tags using the style attribute. Useful for single overrides, but causes duplication.
Embedded CSS (information.html): Defined within <style> tags in <head>. Useful for styling only that specific document.
External CSS (registration.html & style.css): Placed in a standalone file linked via <link rel="stylesheet">. Offers maximum reusability and production maintainability.

4.  ## Brief CSS Evolution
CSS1 (1996): Provided basic typography, font styling, colors, and margins.
CSS2 / CSS2.1 (1998–2011): Introduced positioning, z-index, and media types.
Modern Modular CSS (CSS3+): Adopted independent modules bringing Flexbox, Grid, animations, and responsive media queries.


5. ## Browser Testing & Compatibility
Cross-browser testing verifies that rendering engines render styles uniformly. I tested the site on Google Chrome and Mozilla Firefox. Chrome rendered date inputs with rounded native popups, while Firefox displayed input borders slightly bolder prior to explicit CSS normalization.

6. ##  Semantic vs Non-Semantic HTML
Semantic HTML: <article> and <nav> provide meaningful architectural context to browsers and assistive technologies.
Non-Semantic HTML: <div class="input-row"> acts solely as an unopinionated container for grouping and styling without semantic meaning.