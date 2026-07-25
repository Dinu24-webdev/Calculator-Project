# Calculator

A modern, responsive web-based calculator built with vanilla HTML, CSS, and JavaScript. Featuring a sleek dark theme with smooth animations and intuitive controls.

## Features

- **Basic Arithmetic Operations**: Addition, subtraction, multiplication, and division
- **Clear Display (CLR)**: Reset the calculator with one click
- **Backspace**: Delete the last entered character
- **Decimal Support**: Handle floating-point numbers
- **Error Handling**: Displays "Error" for invalid expressions
- **Smooth Animations**: Hover scale effects and active state transitions
- **Responsive Design**: Clean centered layout with grid-based button arrangement
- **Modern UI**: Dark gradient background with contrasting operator buttons

## Built With

- **HTML5** — Structure and semantic markup
- **CSS3** — Styling, animations, and responsive grid layout
- **JavaScript** — Calculator logic and DOM manipulation

## Getting Started

### Prerequisites

No build tools or dependencies required. All you need is a modern web browser.

### How to Run

1. Clone or download this repository
2. Navigate to the project directory
3. Open `index.html` in your browser

## Usage

| Button | Function |
|--------|----------|
| `0-9`  | Enter numbers |
| `+` `-` `*` `/` | Arithmetic operators |
| `.` | Decimal point |
| `=` | Calculate result |
| `CLR` | Clear the display |
| `⌫` | Delete the last character |

### Example

1. Click `2` `+` `3`
2. Click `=`
3. Display shows: `5`

## Project Structure

```
Calculator-Project/
├── index.html      # HTML structure and button layout
├── style.css       # Styling, theme, and animations
├── script.js       # Calculator logic and event handlers
└── README.md       # Project documentation
```

## Code Overview

### JavaScript Functions (script.js)

- `appendtodisplay(input)` — Appends a character or operator to the display
- `cleardisplay()` — Clears the entire display
- `calculate()` — Evaluates the expression and shows the result
- `backspace()` — Removes the last character from the display

### CSS Highlights (style.css)

- **Grid Layout**: 4-column button grid with `span 2` for the zero button
- **Color Scheme**: Dark body with `#ff9500` (orange) operator buttons, `#666` (gray) special buttons, and `#333` (dark gray) number buttons
- **Animations**: `scale(1.08)` on hover and `scale(0.95)` on click with 0.2s smooth transition
- **Display**: Large 3rem font, right-aligned, with rounded corners

