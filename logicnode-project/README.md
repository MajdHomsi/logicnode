# LogicNode — Website

Your personal IT services website. Built with plain HTML, CSS, and JavaScript — no frameworks, no dependencies.

## Project Structure

```
logicnode-project/
├── index.html        ← Main website file
├── css/
│   └── style.css     ← All styles
├── js/
│   └── main.js       ← Scroll animations + nav behaviour
└── assets/           ← Drop images/favicon here when ready
```

## How to Run Locally

Just open `index.html` in your browser. Or in VS Code:
- Install the **Live Server** extension
- Right-click `index.html` → **Open with Live Server**

## Things to Update Before Going Live

1. **Email** — swap `majd.homsi.ca@gmail.com` with `majd@logicnode.ca` once domain is set up
2. **Footer year** — update `© 2025` to current year
3. **Favicon** — add a `favicon.ico` to the root folder
4. **Google Analytics** — add your GA tag in the `<head>` of `index.html`

## How to Deploy (Free, 2 minutes)

1. Go to [netlify.com](https://netlify.com) and sign up free
2. Drag and drop the entire `logicnode-project` folder onto the Netlify dashboard
3. Your site is live instantly at a Netlify URL
4. Go to **Domain Settings** → add `logicnode.ca`
5. In Namecheap, point your nameservers to Netlify's (they'll give you these)

Done. Your site is live on `logicnode.ca`.

## Customization Tips

- All colors are CSS variables in `css/style.css` under `:root` — change `--blue` to update the accent color everywhere
- Fonts are loaded from Google Fonts (Syne + DM Sans) — swap in `index.html` `<head>` if needed
- Pricing, services, and contact info are all plain HTML — easy to edit directly
