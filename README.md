# Werpsyn - Public Website Repository

This is the public GitHub Pages website repository for the [Werpsyn iOS app](https://apps.apple.com/app/werpsyn).

## Important

This repository contains **only** public website content, legal documents, and support information.

**Do NOT store in this repository:**
- iOS app source code
- Backend/API source code
- API keys, secrets, or tokens
- Private endpoints or internal documentation
- Database credentials
- Deployment configurations

The actual app code and backend services are stored in private repositories.

## Website Structure

The website is built using plain HTML and CSS (no frameworks or build tools) and is served via GitHub Pages.

### File Organization

```
docs/
├── index.html                  # Homepage
├── privacy-policy/
│   └── index.html             # Privacy Policy
├── support/
│   └── index.html             # Support page
├── app-info/
│   └── index.html             # App Information
├── donations/
│   └── index.html             # Support Development
└── assets/
    └── style.css              # Shared styles
```

## Enabling GitHub Pages

To enable GitHub Pages for this repository:

1. Go to repository **Settings**
2. Navigate to **Pages** (left sidebar)
3. Under "Build and deployment"
   - **Source:** Select "Deploy from a branch"
   - **Branch:** Select `main`
   - **Folder:** Select `/docs`
4. Click **Save**

GitHub will automatically deploy the site within a few moments.

## Public URLs

Once enabled, the website will be available at:

- **Homepage:** https://ontwerps.github.io/werpsyn/
- **Privacy Policy:** https://ontwerps.github.io/werpsyn/privacy-policy/
- **Support:** https://ontwerps.github.io/werpsyn/support/
- **App Information:** https://ontwerps.github.io/werpsyn/app-info/
- **Support Development:** https://ontwerps.github.io/werpsyn/donations/

## App Store Compliance

This website is configured for use in App Store Connect:
- Privacy Policy URL: `https://ontwerps.github.io/werpsyn/privacy-policy/`
- Support URL: `https://ontwerps.github.io/werpsyn/support/`
- Marketing URL: `https://ontwerps.github.io/werpsyn/`

## Security Notes

⚠️ **Before committing:**

- Never commit API keys, secrets, or tokens
- Never commit app source code or backend code
- Never commit private endpoints or credentials
- Use this repository for public-facing content only

If you accidentally commit sensitive data, revoke those credentials immediately and rotate all secrets.

## Development

All pages are standalone HTML files with inline styles or external CSS. To test locally:

```bash
# Python 3
python -m http.server 8000

# Or Node.js
npx http-server
```

Then visit `http://localhost:8000/werpsyn/` in your browser.

## License

This repository contains public information and legal documents for the Werpsyn app.
