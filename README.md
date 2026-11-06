# Wedding website service: landing page

Three files make up the page. Keep them all in the same folder.

| File | What it controls |
|------|------------------|
| `index.html` | All the words, links and page structure |
| `styles.css` | Colours, fonts, sizes and spacing |
| `sheet-to-site.html` | The "From a sheet to a site" animation, shown inside the page |

## Common edits

**Change text.** Open `index.html` and search for `EDIT:`. Each note sits right above something you will likely want to change (business name, headline, email, example links, footer name).

**Pricing.** The Pricing section is hidden for now. `pricing-backup.html` holds it, with the steps to bring it back. Do not upload that file.

**Change the business name or tagline.** The name (RSVP) is in the top bar, the tagline is the line above the big headline, and the name also appears in the footer and the page `<title>`.

**Change the email address.** Search for `mailto:` and replace the address after it.

**Add or remove a "How it works" step.** Each step is one `<li>...</li>`. Copy a whole `<li>` to add one, or delete one to remove it.

**Change colours.** In `styles.css`, edit the values in the `:root` block at the very top. For example, change `--mauve` and every button and italic heading updates.

**Change fonts.** Change `--serif` and `--sans` in `styles.css`, and swap the Google Fonts `<link>` near the top of `index.html`.

**Leave alone.** The block at the bottom of `index.html` called ART LIBRARY holds the garland, mandala, lotus and paisley drawings.

## Publishing on GitHub Pages

1. Upload `index.html`, `styles.css` and `sheet-to-site.html` to the root of your repository.
2. Go to Settings, then Pages, then Deploy from a branch, choose `main` and `/ (root)`, and save.
3. After each change, commit the file. The site updates within a minute or two.
