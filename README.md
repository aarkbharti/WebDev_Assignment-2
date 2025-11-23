# Personal Portfolio Webpage (Lab 2)

## Project Overview
This project is a personal portfolio website styled using an **External CSS stylesheet**. It demonstrates the fundamental concepts of CSS including the Box Model, Positioning, Selectors, and Table styling.

## Features Implemented

### 1. Styling & Theme
- **External CSS:** All styles are defined in `style.css`.
- **Color Theme:** Used a consistent palette (Dark Blue `#2c3e50` for headers/footer, Gold `#f39c12` for highlights).
- **Typography:** Imported 'Poppins' font from Google Fonts.

### 2. Layout & Box Model
- Used `margin`, `padding`, and `border` to separate sections clearly.
- Used `<hr>` tags with custom styling as visual separators between the About, Skills, and Projects sections.
- Centered content using `margin: 0 auto`.

### 3. Specific Lab Requirements
- **Navigation:** Styled `<nav>` bar with hover effects on links (no underline, color change).
- **Skills Table:** Technical skills are displayed in a formatted `<table>` with alternating row colors (`nth-child`) and borders.
- **Positioning:** Implemented a **"Back to Top"** button using `position: fixed` so it stays visible while scrolling.
- **Sticky Header:** The navigation bar uses `position: sticky` to stay at the top.

## File Structure
- `index.html` - The HTML structure containing the Table, Form, and Sections.
- `style.css` - The styling rules.
- `profile.jpg` - Profile image asset.

## How to Run
1. Download the files.
2. Ensure `profile.jpg` is in the same folder.
3. Open `index.html` in a web browser.