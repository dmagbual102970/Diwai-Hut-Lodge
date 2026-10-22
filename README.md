# Diwai Hut Lodge — demo website

**Demo only. Sample content. No backend.** Built to show what the lodge's website could look like.

- **Live:** https://dmagbual102970.github.io/Diwai-Hut-Lodge/
- **Theme:** forest green · Playfair Display + Inter
- **Hero:** photograph of the lodge
- **Contact:** +675 532 3840 · WhatsApp · Goroka, Eastern Highlands Province
- **Demo content:** sample rooms (Standard K450, Garden K550, Family K650), services with photos,
  "why book direct" section, sample policies, guest stories.
- **Demo booking:** the booking wizard, availability check and "find my booking" are answered locally
  (no Firebase) so the flow can be demonstrated end to end.

## Rebuilding

```bash
cd "Edgewood Hotel & Apartment/website"
VITE_DEMO_CONTENT=true node ./node_modules/vite/bin/vite.js build --base=/Diwai-Hut-Lodge/
```

Copy `dist/` here, copy `index.html` to `404.html`, keep `.nojekyll`.
