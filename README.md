# Emerald Key — public page

The recruitment/info page for the **Emerald Key** Arma 3 roleplay server.
One self-contained `index.html` — no build step, no dependencies, no external requests.

**Live:** https://tellisCMN.github.io/emerald-key/

---

## Hosting it

This is set up for **GitHub Pages**:

1. Push this repo to GitHub.
2. **Settings → Pages → Source: Deploy from a branch**, branch `main`, folder `/ (root)`.
3. It goes live at `https://<user>.github.io/emerald-key/` within a minute or two.

★A **custom domain** (e.g. `emeraldkey.gg`) works too: add it under Settings → Pages,
then point a `CNAME` record at `<user>.github.io`. Pages will issue the HTTPS certificate.

---

## Editing it

Everything is in `index.html`:

- **Colours** are CSS custom properties at the top of `<style>` — one place, and both
  light and dark themes are defined through the same tokens.
- **Copy** is plain HTML below the styles.
- The **Discord invite** appears twice: once in the masthead, once in the closing
  call-to-action. Change both.

★The page renders in the visitor's light or dark theme automatically. If you change a
colour, check both — the light theme is a parchment/chart treatment, not an inversion of
the dark one.

---

## Keeping it honest

The page has a **status section** that says plainly what works, what is in progress, and
what is only designed. ★Update it as things ship. A recruitment page that overstates the
server is worse than one that undersells it — players notice the gap on day one, and the
honesty is part of the pitch.
