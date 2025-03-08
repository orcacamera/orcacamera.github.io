# CLAUDE.md - Guidance for Orca Camera Website

## Build Commands
- Start local server: `python -m http.server`
- Validate HTML: `npx html-validator-cli --file=index.html`
- Check for accessibility: `npx pa11y http://localhost:8000`

## Codebase Structure
- Single-page static website with HTML, CSS, and JavaScript
- All styles in `<style>` section of index.html
- All scripts in `<script>` section of index.html

## Code Style Guidelines
- CSS: Use CSS variables for colors and consistent spacing
- HTML: Semantic HTML5 elements with proper accessibility attributes
- JS: ES6 syntax, event listeners with function expressions
- Indentation: 4 spaces
- Naming: kebab-case for CSS classes, camelCase for JS variables
- Comments: Section headers in HTML, function descriptions in JS

## Design Pattern
- Mobile-first responsive design
- CSS Grid and Flexbox for layouts
- Custom CSS with no frameworks

## Error Handling
- Defensive coding in JS functions
- Validate user inputs where applicable
- Graceful degradation for older browsers