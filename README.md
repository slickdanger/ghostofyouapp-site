# ghostofyouapp-site

The marketing website for **Ghost of You** — one self-contained page, hosted on GitHub Pages.

This repository is **separate from the app's code repository on purpose**. Nothing from the app
repo is copied here, and nothing here contains secrets, keys, analytics, trackers or forms.

## What is here

| file | what it is |
|---|---|
| `index.html` | the whole website — one page |
| `images/` | the page's images as real files |
| `dns-before-2026-09-19.txt` | a dated record of the domain's DNS settings *before* any change |

## Where it is published

GitHub Pages, at the project's temporary address. **No custom domain is set**, and there is
deliberately **no `CNAME` file** — adding one would point the real domain here before it is meant
to move.

## The live domain

`ghostofyouapp.com` still serves the previous site on Carrd. It moves only when Tyler changes the
DNS records at Namecheap himself, as a separate step.

⛔ **`privacy.ghostofyouapp.com` and `terms.ghostofyouapp.com` stay on Carrd permanently** and are
not affected by anything in this repository. They are separate DNS records.
