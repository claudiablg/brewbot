# BrewBot — Kōban Coffee & Tea Customer Support Demo

A single-page customer support chatbot demo for a fictional specialty coffee & tea shop. The bot uses pre-written smart responses that match keywords in the user's message — no API, no backend, fully static.

## Demo

Open `index.html` in a browser. That's it.

## Tech

- Single HTML file with inline CSS and JS — no framework, no build step
- No API, no backend — fully static
- Deploy as a static site on Vercel, Netlify, or GitHub Pages

## How it works

1. Chat opens with a friendly welcome message
2. User types a question or clicks a quick-action button
3. The bot matches keywords (best seller, subscription, shipping, brew, matcha, etc.) and responds with a relevant pre-written answer
4. A typing indicator simulates AI "thinking" for 1–2 seconds before each reply
5. If no keyword matches, the bot falls back to a polite "contact us" message

## Deploy

Drop `index.html` into any static host.

```bash
# Vercel
vercel deploy

# Netlify
netlify deploy --dir=.
```

---

Portfolio demo by Claudia Bélanger.
