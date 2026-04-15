# Rawan Zahreddine — Portfolio

## Deploy to Netlify (recommended)

1. Go to [netlify.com](https://netlify.com) and sign up / log in
2. Click **"Add new site" → "Deploy manually"**
3. Drag the entire `portfolio/` folder onto the drop zone
4. Done — Netlify gives you a live URL immediately

To use a custom domain: Netlify → Site settings → Domain management → Add custom domain.

## Deploy to GitHub Pages

1. Create a new GitHub repo (e.g. `portfolio`)
2. Push the contents of this folder to the `main` branch
3. Repo settings → Pages → Source: Deploy from branch → `main` → `/ (root)`
4. Live at `https://<your-username>.github.io/portfolio`

## Updating content

All content is in `index.html`. Search for the relevant text and edit directly.
All styles are in `styles.css`.

## Adding a headshot later

In `index.html`, find `<section id="hero">`. Add an `<img>` tag inside the section
alongside `.hero-body` and position it on the right with CSS:

```css
.hero-photo {
  position: absolute;
  right: 56px; bottom: 0;
  height: 80vh;
  object-fit: cover;
}
```
