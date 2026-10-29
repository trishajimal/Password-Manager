# PassX - A Password Manager

PassX is a lightweight password-manager demo built with HTML, CSS, and vanilla JavaScript. It lets you save website credentials in your browser, view saved entries with passwords masked, and delete entries.

## Features

- Add a website, username, and password.
- View saved credentials in a table; passwords are displayed as asterisks.
- Delete a saved entry.
- Keep entries in browser `localStorage` so they remain available after reloading the page.
- Use a responsive layout on smaller screens.

## Run locally

No dependencies or build step are required.

1. Download or clone this project.
2. Open `index.html` in a modern web browser.

Alternatively, serve the project directory with any local static web server and open the URL it provides.

## Project files

- `index.html` — page structure and password-entry form.
- `style.css` — layout, styling, and responsive rules.
- `script.js` — password list rendering and `localStorage` operations.

## Storage and security

This is a learning/demo project, not a secure password vault. Credentials are stored in the browser's `localStorage` as readable JSON; they are not encrypted, and masking passwords in the table only changes how they are displayed. Anyone with access to the browser profile or page scripts may be able to read them.

Do not use this app to store real or sensitive passwords. A production password manager needs appropriately designed encryption, authentication, and secure key management.
