# Student Upload App

A simple student registration web app built with plain HTML, CSS, and JavaScript.

## Features
- Add a student with a form for name, matric number, level, and department.
- Validate each field with inline error messages.
- Prevent duplicate matric numbers.
- Show the student register list with the most recent entry highlighted.
- Toggle a names-only panel for all registered students.
- Remove the most recently added student with a dedicated button.
- Add 3 sample students when the register is empty.

## How to run
1. Open `index.html` in your browser.
2. Use the form to add students, remove the last one, or show the names list.

## File structure
- `index.html` — app layout and form structure
- `style.css` — styling, colors, layout, and dark mode support
- `script.js` — validation, rendering, and student list logic
- `README.md` — project notes and instructions

## Matric number format
Matric numbers must follow this pattern: `23/024145123`
- two digits
- a slash
- nine digits
- example regex: `/^\d{2}\/\d{9}$/`

## Color note
The app uses a deep jade green for the primary actions and success states, with garnet red for removal and the `Last added` highlight. The page background uses a soft green-grey tone and the color palette also includes a dark theme using `prefers-color-scheme`.
