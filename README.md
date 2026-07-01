# KidSafe Play — story book images

Static page images for the Stories section of https://genai.io.vn, served via the
jsDelivr CDN (so they don't sit on the app host). Layout:

```
story/books/<slug>/cover.jpg
story/books/<slug>/page01.jpg … pageNN.jpg
```

CDN URL for a file:
`https://cdn.jsdelivr.net/gh/linhnnmt/kidsafe-assets@main/story/books/<slug>/<file>`

## Licensing & attribution

All books are openly licensed (**Creative Commons CC BY 4.0**) and re-hosted here
**with attribution**, per each source's terms. Nothing here is original to this repo.

**Book Dash** (https://bookdash.org) — CC BY 4.0, re-use allowed. Books:
the-window-seat, khaya-wants-to-row, little-goat, dudus-hat, sindi-and-the-moon,
little-ants-big-plan, maddy-moonas-menagerie. Each is shown in the app with the
Book Dash logo, a link to www.bookdash.org, its four creatives (author,
illustrator, designer, editor) and an adaptation note, as Book Dash requires.

**Global Digital Library** (https://digitallibrary.io) — CC BY 4.0 (Room to Read /
The Asia Foundation "Let's Read"). Books: i-love-my-mom, animal-hide-and-seek,
mom-says-we-can, how-hen-got-her-cluck. Shown with source + creators + CC BY 4.0.

Full per-book credit lines live in the app's story manifests (app/stories/*.php).
