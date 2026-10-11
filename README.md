# Discord bot legal pages (GitHub Pages)

## Files
- `index.html` — landing page
- `terms.html` — Terms of Service
- `privacy.html` — Privacy Policy
- `style.css` — styling
- `.github/workflows/pages.yml` — automatic GitHub Pages deployment

## Before publishing
1. Search all files for `[BOT NAME]`, `[YOUR NAME OR ORGANISATION]`, `[CONTACT EMAIL OR SUPPORT SERVER URL]`, `[HOSTING / DATABASE PROVIDERS]`, and other bracketed placeholders.
2. Edit the policy to match what your bot actually stores and shares. Do not publish placeholders or inaccurate promises.
3. Create a public GitHub repository, e.g. `bot-legal-pages`, and upload these files at the repository root (including the `.github/workflows/pages.yml` file).
4. In GitHub, open **Settings → Pages**. Set **Build and deployment → Source** to **GitHub Actions**.
5. Push to the `main` branch or run the workflow under **Actions**. Wait for deployment.
6. Your pages will be available at:
   - `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/terms.html`
   - `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/privacy.html`
   - Home: `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`

## Discord Developer Portal
Paste the published `terms.html` URL into **Terms of Service URL** and the published `privacy.html` URL into **Privacy Policy URL**.

These are starter templates, not legal advice. Replace placeholders and verify the text against your actual implementation before publishing.
