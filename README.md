# Musical Journey — Simple Calculator

A clean, responsive calculator that runs entirely in your browser. Built as a single self-contained HTML page—no frameworks, dependencies, build step, or installation required.

## Try it

**[Open the calculator](https://bumpers80.github.io/musical-journey/)**

> GitHub Pages must be enabled for the link to work. To run it locally, download or clone this repository and open `index.html` in any modern browser.

## Features

- **Everyday arithmetic:** addition, subtraction, multiplication, and division.
- **Keyboard or click:** enter numbers and operators without leaving the keyboard.
- **Helpful controls:** clear the calculation, delete the last digit, or evaluate the result.
- **Responsive layout:** a compact interface that adapts to smaller screens.
- **Accessible details:** labeled controls, a live-updating result display, visible keyboard focus, and reduced-motion support.
- **No dependencies:** HTML, CSS, and JavaScript are all included in one file.

## Keyboard shortcuts

| Key | Action |
| --- | --- |
| `0`–`9` | Enter a digit |
| `.` | Enter a decimal point |
| `+`, `-`, `*`, `/` | Choose an operation |
| `Enter` or `=` | Show the result |
| `Backspace` | Delete the last digit |
| `Escape` | Clear the calculator |

## Run locally

1. Clone or download this repository.
2. Open `index.html` in a modern web browser.
3. Start calculating—there is no setup or build command.

## Project structure

```text
.
├── index.html   # Calculator markup, styles, and behavior
└── README.md    # Project guide
```

## Implementation notes

The calculator evaluates chained operations as they are entered (left to right), rather than applying conventional operator precedence. Results are formatted to a maximum of 10 significant digits; division by zero and other non-finite results display `Error`.

## Contributing

Ideas and improvements are welcome. For a change, open an issue to discuss it or submit a pull request with a clear description of what you changed and how you tested it.

## License

No license is currently specified. Unless a license is added, all rights are reserved by the repository owner.
