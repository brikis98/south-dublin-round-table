# Project Agent Rules

For any HTML/CSS changes in this project:

1. Never use inline styles (`style="..."`).
2. Use existing utility classes from BassCSS and AceCSS whenever fitting ones exist.
3. Prefer utility-style class names that describe behavior (what the class does), not page/component names (what it styles).
4. If no BassCSS or AceCSS class exists for the needed behavior, define an immutable class in `assets/css/main.css` and use that class in the HTML.
