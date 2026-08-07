# 100 Notes Studio — support and privacy site

Static GitHub Pages site for the iOS/iPadOS app **100 Notes Studio: Pen & Paper**.
No framework, no build step, no third-party tracking, analytics or advertising,
and no external resources of any kind.

## Files

| File | Purpose |
|---|---|
| `index.html` | What the app is, its features, the free tier and the unlock, privacy summary, contact |
| `support.html` | FAQ: free tier, restoring a purchase, Apple Pencil, PDFs, audio, search, backups, contacting us |
| `privacy.html` | Privacy policy matching what the app actually does |
| `styles.css` | Shared stylesheet |

## Deploy

Push to `main` and enable GitHub Pages (Settings, Pages, Deploy from a branch, `main`, `/root`).

## App Store Connect fields

| ASC field | Value |
|---|---|
| Support URL | `https://alice51849.github.io/100notes-support/support.html` |
| Privacy Policy URL | `https://alice51849.github.io/100notes-support/privacy.html` |
| Marketing URL | `https://alice51849.github.io/100notes-support/` (optional) |

## Changing the contact address

The address `hourstag.app@gmail.com` appears in `index.html`, `support.html`
and `privacy.html`. Update all three together.

## Before publishing an app update

If a release changes what data the app touches, edit `privacy.html` and its
`Last updated` date first, then ship the app.
