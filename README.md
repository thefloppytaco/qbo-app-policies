# QBO App Policy Pages

Two HTML files needed for Intuit Developer production app submission:

- `eula.html` — End-User License Agreement
- `privacy.html` — Privacy Policy

## Before publishing, edit both files and replace:

- `[YOUR NAME OR BUSINESS NAME]` — your name or the business name (e.g. "Moshe Baum" or "Baum Bookkeeping LLC")
- `[YOUR EMAIL]` — a contact email Intuit can use if there's an issue

The effective date (2026-05-07) is fine to leave as-is.

## Hosting options

### Option 1: Your existing website (simplest)
Upload `eula.html` and `privacy.html` to your web host. The final URLs you'll paste into Intuit will be something like:
- `https://yourdomain.com/eula.html`
- `https://yourdomain.com/privacy.html`

### Option 2: GitHub Pages
1. Create a public GitHub repo (e.g. `qbo-app-policies`).
2. Push these files to the `main` branch.
3. Repo Settings → Pages → Source: `main` branch, root folder → Save.
4. URLs will be `https://<username>.github.io/qbo-app-policies/eula.html` etc.

Either works. Test the URLs in an incognito window before pasting them into Intuit's portal — they must load without authentication.
