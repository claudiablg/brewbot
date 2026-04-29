# BrewBot — Kōban Coffee & Tea Customer Support Demo

A single-page customer support chatbot demo for a fictional specialty coffee & tea shop. The bot uses pre-written smart responses that match keywords in the user's message — no API, no backend, fully static.

## Demo

Open `index.html` in a browser. That's it.

## Tech

- Single HTML file with inline CSS and JS — no framework, no build step
- No API, no backend — fully static
- Deployed as a static site on Netlify

## How it works

1. Chat opens with a friendly welcome message
2. User types a question or clicks a quick-action button
3. The bot matches keywords (best seller, subscription, shipping, brew, matcha, etc.) and responds with a relevant pre-written answer
4. A typing indicator simulates AI "thinking" for 1–2 seconds before each reply
5. If no keyword matches, the bot falls back to a polite "contact us" message

## Deploy on Netlify

Option A — drag-and-drop:

1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the `brewbot` folder onto the page
3. Done — Netlify gives you a live URL

Option B — Git integration:

1. In Netlify, click **Add new site → Import from Git**
2. Connect this repo (`claudiablg/brewbot`)
3. Leave **Build command** empty and set **Publish directory** to `.`
4. Click **Deploy**

Option C — CLI:

```bash
npm install -g netlify-cli
netlify deploy --dir=. --prod
```

---

Portfolio demo by Claudia Bélanger.
