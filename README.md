# Terminal Profile

A terminal-style **single HTML file** personal profile webpage with multi-tab support, command-based interaction, autocomplete, configurable commands, and a clean Ubuntu-inspired UI.

## Usage

1. Download `index.html`
2. Revise content in `CONFIG` and `commandConfig`
3. Revise other content if you like
4. Upload to static hosting
5. GO!

## Features

- Terminal-style personal homepage
- Multi-terminal tabs with rename and close support
- Click anywhere in the terminal to focus the command input
- Text selection still works normally
- Floating autocomplete popup above the current command line
- Hidden scrollbars for a cleaner terminal look
- Command history navigation with arrow keys
- Config-driven command system
- Table-based formatted outputs for structured commands
- BibTeX reference parsing and rendering, especially useful for high school students, university teachers and researchers.

## Demo Commands

Available commands include:

- `help` — show all commands with descriptions
- `list` — list all available commands
- `name` — show name
- `about` — show short introduction
- `contact` — show contact information
- `projects` — show selected projects
- `education` — show education background
- `ref` — parse and render references
- `clear` — clear terminal output

You can also use:

- `command --help`
- `command -h`

## Project Structure

This project is intentionally kept lightweight and self-contained.

```text
.
├── index.html
└── README.md