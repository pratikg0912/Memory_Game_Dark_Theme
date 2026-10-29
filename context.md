# Repo Context

## Project name
The repository is named `memory-game-GHCP`.

There is no explicit acronym defined in the codebase itself. Based on the project contents and naming pattern, this appears to be a simple GitHub Copilot-related project label rather than a formal product acronym. The actual project is clearly a memory game application.

## What this repo does
This project is a browser-based Memory / Concentration card game built with plain HTML, CSS, and JavaScript.

Players flip cards to find matching pairs. The game includes:
- 4x4 and 6x6 board options
- move counter
- timer
- star rating based on performance
- local high-score tracking using browser storage
- keyboard accessibility
- responsive layout for desktop and mobile screens

## What it stands for
The repository name is best understood as:
- `memory-game` = the actual game type and purpose
- `GHCP` = likely a repository or environment tag, most likely referencing GitHub Copilot or a GitHub Copilot-assisted project context

The repo does not appear to define a deeper business or technical acronym beyond that.

## Project structure
- [README.md](README.md): project overview and usage instructions
- [memory-game.html](memory-game.html): complete app implementation including styles, markup, and JavaScript logic

## How it works
The app creates a shuffled set of matching emoji cards, renders them into a grid, and lets the player click or keyboard-select cards to reveal them. When two matching cards are selected, they stay flipped and count as a match; if they do not match, they flip back after a short delay. The game tracks moves, time, rating, and stores the best results in localStorage.

## How to run it
Open [memory-game.html](memory-game.html) directly in a web browser, or serve the folder with a local HTTP server:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000/memory-game.html
```

## Summary
This repository is a lightweight, dependency-free web game project focused on learning, entertainment, and front-end interaction design. It demonstrates JavaScript DOM manipulation, CSS animations, accessibility, and local browser persistence in a compact single-file implementation.
