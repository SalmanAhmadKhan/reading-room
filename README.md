# The Reading Room

> A calm, free app for revisiting your Kindle and Goodreads highlights — one passage at a time.

**[Open the app →](https://reading-room-ci8.pages.dev/app.html)**

---

## What it is

You've underlined hundreds of passages. You never see them again. The Reading Room changes that — surfacing one highlight at a time, randomly, whenever you have a quiet moment. The opposite of doomscrolling. A finite shelf, not an endless feed.

## Features

- **Import from anywhere** — Kindle's `My Clippings.txt`, Goodreads notes pages, PDFs, plain text
- **Random review** — one passage at a time, at random
- **Filter by book or theme** — tag highlights with `#GrowthMindset`, `#Stoicism`, `#Money` and filter across books
- **Add notes** — write why a passage stuck with you, shown alongside it in review
- **Search** — find any passage across your entire shelf instantly
- **Deprioritize** — mark passages to appear less often
- **Export / Import** — back up your shelf to a JSON file, restore on any device
- **Optional sync** — highlights live on your device by default; set up free [Supabase](https://supabase.com) sync for cross-device access
- **Works offline** — full Progressive Web App, installable on Android and iPhone

## Install (no app store needed)

**Android:** Open in Chrome → ⋮ menu → Add to Home screen

**iPhone:** Open in Safari → Share button → Add to Home Screen

## Import your Kindle highlights

The fastest way to fill your shelf:

1. Plug your Kindle into your laptop via USB
2. Find `My Clippings.txt` on the device (in the `documents` folder)
3. Open the app → Shelf → Import → select the file
4. Review and confirm — all your highlights from every book, in one step

## Sync across devices

Create a free account in the app's **Account tab** — sign up with email and password. Your highlights sync automatically between any device you sign into. No Supabase setup required for users.

## Deploy your own

Everything is in this repo. To host it yourself:

1. Fork this repo or download the files
2. Go to [pages.cloudflare.com](https://pages.cloudflare.com) → Create → Pages → Upload assets
3. Upload the files — you get a free `yourname.pages.dev` URL instantly
4. No build step, no configuration — it just works

## Tech

- Vanilla HTML, CSS, JavaScript — no frameworks, no build tools
- [Supabase](https://supabase.com) for optional sync (free tier)
- [Cloudflare Pages](https://pages.cloudflare.com) for hosting (free, unlimited bandwidth)
- All data stored locally in browser `localStorage` by default

## License

MIT — free to use, modify, and share.

---

*Built by a reader, for readers. Free forever.*
