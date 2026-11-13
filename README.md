# Stateweave

**A visual finite state machine designer that runs entirely in your browser.**

<p align="center"><svg width="100%" viewBox="0 0 720 170" xmlns="http://www.w3.org/2000/svg"><rect width="720" height="170" rx="16" fill="#0b1020"/><g fill="#1c3152" stroke="#62e3c1" stroke-width="2"><rect x="60" y="60" width="112" height="48" rx="10"/><rect x="300" y="25" width="112" height="48" rx="10"/><rect x="540" y="90" width="112" height="48" rx="10"/></g><g stroke="#62e3c1" fill="none" stroke-width="2"><path d="M172 75Q235 30 300 48"><animate attributeName="stroke-dasharray" values="0 220;220 0" dur="3s" repeatCount="indefinite"/></path><path d="M412 52Q490 35 540 100"><animate attributeName="stroke-dashoffset" values="0;-80" dur="3s" repeatCount="indefinite"/></path></g><g fill="#edf3ff" font-family="monospace" font-size="11" text-anchor="middle"><text x="116" y="88">DRAFT</text><text x="356" y="53">REVIEW</text><text x="596" y="118">DONE</text></g></svg></p>

## Features
- Add named states and connect them with event-driven transitions.
- Automatically arranged SVG-style state graph.
- Export the model as portable JSON or copy it to the clipboard.
- Includes a small example workflow.
- No frameworks, dependencies, accounts, or network requests.

## Run
Open `index.html` in any modern browser. No installation or build step is required.

## Data format
The exported JSON contains a `states` array and a `transitions` array. Each transition has `from`, `to`, and `event` fields.

## License
MIT
