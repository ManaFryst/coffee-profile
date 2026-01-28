# Darren A | Digital Profile Page

## Project Overview
This project is a personal digital profile page for **Darren A**, a cybersecurity student and enthusiast. The page is designed with a **Neo-Brutalist** aesthetic using a **Pastel Coffee** color palette. It showcases Darren's background in cybersecurity, web development, home labbing, and tinkering.

### Key Features
- **Responsive Design**: Custom layouts for both mobile and desktop devices.
- **Neo-Brutalist UI**: High-contrast thick borders, hard solid shadows, and monospaced typography.
- **Dark Mode Support**: A "Dark Roast" theme toggle with persistence using `localStorage`.
- **Minimalist Aesthetic**: Clean, boxy design inspired by modern web design trends (as seen in `examples/`).

## Technology Stack
- **HTML5**: Structured semantic content.
- **CSS3**: Custom properties (variables), Grid, and Flexbox for responsive layouts.
- **Vanilla JavaScript**: Theme toggling logic and local storage persistence.
- **Google Fonts**: Uses 'Space Mono' for headings and 'Inter' for body text.

## File Structure
- `index.html`: Main structure and content.
- `style.css`: Comprehensive styling including light/dark themes and responsive breakpoints.
- `script.js`: Theme switching functionality.
- `examples/`: Reference images for design inspiration.

## How to Run
1.  Open `index.html` in any modern web browser.
2.  No build steps or dependencies are required.

## Development Conventions
- **Theming**: All colors are managed via CSS variables in `:root` and overridden in `body.dark-mode`.
- **Layout**: 
    - Mobile-first approach for basic stacking.
    - Media query at `768px` for desktop grid layout.
- **Shadows**: Hard shadows use `--shadow-offset` and are offset to the bottom-right.
- **Accessibility**: Use `aria-label` on the theme toggle button and maintain high contrast in both themes.

## Future TODOs
- [ ] Add links to social media/GitHub.
- [ ] Add a "Projects" section to showcase specific home lab or tinkering results.
- [ ] Integrate a contact form or email link.
