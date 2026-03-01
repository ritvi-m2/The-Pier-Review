# The Pier Review

## Newsletter behavior (no backend)

Newsletter signups are handled entirely in the browser.

- Each submission is appended to local browser storage.
- On every submit, a `subscribers.txt` file is downloaded with all saved entries in this format:

  `ISO_TIMESTAMP | email@example.com`

## How to run

Open `index.html` directly in your browser.