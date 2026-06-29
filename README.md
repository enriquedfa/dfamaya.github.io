# dfamaya.github.io

Static site for dfamaya's Wear OS apps — a landing page plus per-app privacy
policies and support.

Published at: <https://enriquedfa.github.io/dfamaya.github.io/>

## Pages

- `index.html` — landing page (lists all apps)
- `style.css` — shared styles

### Wear OS Watch Faces

- `privacy.html` — privacy policy (covers all watch faces by dfamaya)
- `support.html` — support / contact info

### Brief

- `brief/index.html` — app overview
- `brief/privacy.html` — privacy policy

## Play Store URLs

When submitting an app on Google Play, use:

**Wear OS Watch Faces**

- Privacy policy URL: `https://dfamaya.github.io/privacy.html`
- Support / website URL: `https://dfamaya.github.io/support.html` (or the root)

**Brief**

- Privacy policy URL: `https://dfamaya.github.io/brief/privacy.html`
- Support / website URL: `https://dfamaya.github.io/brief/` (or the root)

**Contact email:** `developerdfa@gmail.com`

## Adding another app

1. Create a folder for the app (e.g. `myapp/`).
2. Add `myapp/index.html` (overview) and `myapp/privacy.html` (policy),
   referencing `../style.css` for styles.
3. Add a card linking to it in the “Apps” section of `index.html`.
