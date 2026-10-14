# VidyaSpace — Student Workspace

Responsive frontend prototype for the Canvas 2 Code Tech Fest 2026.

## Run in VS Code
1. Extract this ZIP.
2. Open the extracted folder in VS Code.
3. Right-click `index.html` and select **Open with Live Server**.
4. The login page opens first. Enter any demo student ID/email and a password of at least 4 characters.
5. Click **Sign in to VidyaSpace** to open `dashboard.html`.

## Main files
- `index.html`: login page and website entry point.
- `login.css`, `login.js`: login page styling and demo form behavior.
- `dashboard.html`: main student dashboard.
- `style.css`, `script.js`: dashboard styling and interactions.
- `assets/vidya-logo.png`: supplied Vidya logo with near-black background made transparent.

## Important security note
This is only a frontend demo. The login form validates inputs in the browser but does not verify an account. Anyone can open `dashboard.html` directly or inspect the code. For real protected accounts, connect a backend or authentication provider and enforce access checks on the server. Do not use real passwords.
