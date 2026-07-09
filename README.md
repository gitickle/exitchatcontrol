# exitchatcontrol

A bilingual guide (English / French) to escape **Chat Control** and reclaim digital sovereignty: encrypted messaging, email, VPN, DNS, 2FA, Linux, GrapheneOS, self-hosting, and more. Each tool is presented with "what it's for", "why it matters", and "how to install it".

## Contents

- **`index.html`**: the complete guide, a self-contained website (no dependencies, opens directly in a browser).
- **`images/`**: screenshots to be inserted into the guide.
- **`article-presse.md`**: an actionable press article, ready to publish on a blog, a newsletter, or as an X Article.

## A trilingual site

The static site supports three languages, switchable from the top bar:

- 🇬🇧 English (default fallback)
- 🇫🇷 French
- 🇳🇱 Dutch

The visitor's browser language is detected on first load (English → English, French → French, Dutch → Dutch, anything else → English). The choice is remembered in `localStorage`.

## Publishing

Static site: drop the folder on a static host (Netlify, Vercel, Cloudflare Pages) or serve `index.html` with Caddy on a VPS.

Domain: https://exitchatcontrol.org

## License

See the `LICENSE` file.
