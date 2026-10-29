# Memory Game Dark Theme

A responsive, accessible Memory (Concentration) card game built with HTML, CSS, and JavaScript, with a dark mode toggle added for a better low-light experience.

## Features

- 4x4 and 6x6 grid options
- Smooth card flip animations
- Move counter and timer
- Star rating system
- Local storage for top scores
- Keyboard controls for accessibility
- Responsive layout for mobile and desktop
- Light and dark theme toggle
- No external dependencies

## How to Play

1. Open `memory-game.html` in a browser
2. Click or use keyboard controls (Tab + Enter/Space) to flip cards
3. Match all pairs to win
4. Try to finish with the fewest moves possible
5. Switch between 4x4 and 6x6 boards from the controls
6. Toggle the theme to switch between light and dark mode

## Project Structure

- `memory-game.html` — complete game logic, styling, and markup
- `README.md` — project overview and setup steps
- `context.md` — repository context summary
- `PRD_dark_theme.md` — product requirements for the dark mode change

## Run Locally

### Option 1: open directly
Open `memory-game.html` in a browser.

### Option 2: use a local server
```bash
python3 -m http.server 8000
```
Then visit:

```text
http://localhost:8000/memory-game.html
```

## GitHub Pages

This app is a static HTML project and can be published easily using GitHub Pages.

1. Go to your GitHub repository
2. Open Settings
3. Go to Pages
4. Select Deploy from a branch
5. Choose `main` and `/ (root)`
6. Save

Your game will be available at a URL like:

```text
https://<your-username>.github.io/Memory_Game_Dark_Theme/
```

## Technical Details

- Pure HTML, CSS, and JavaScript
- No external libraries or frameworks
- CSS custom properties for theme switching
- LocalStorage used for best-score persistence
- Fully responsive and keyboard accessible

## License

This project is available for personal and educational use.
