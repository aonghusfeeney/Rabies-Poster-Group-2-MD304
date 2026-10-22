# 100% Preventable, 100% Fatal

Companion site to an e-poster on rabies elimination, prepared for **MD304 Global Health and
Development**, School of Medicine, University of Galway.

| Page | File | What it is |
|---|---|---|
| Landing | `index.html` | Entry point — links to the three sections below |
| The poster | `poster.html` | The full argument, built for reading on a phone, with the search strategy and two interactive figures |
| Revision guide | `study-guide.html` | Short notes and twelve self-test questions on rabies and the neglected tropical diseases |
| Further reading | `resources.html` | WHO and Irish guidance, plus the ten primary sources with direct links |

Plain HTML and CSS with a little vanilla JavaScript. No build step, no dependencies, no analytics,
no cookies. Every page works without JavaScript, respects `prefers-reduced-motion`, and has a dark
mode that follows the device setting.

## Publishing with GitHub Pages

1. Create a repository and upload the contents of this folder to it.
2. **Settings → Pages → Build and deployment → Source: Deploy from a branch**, branch `main`,
   folder `/ (root)`. Save.
3. The site appears at `https://<username>.github.io/<repository>/` within a minute or two.

## Search engines are switched off deliberately

Every page carries `<meta name="robots" content="noindex, nofollow">` and `robots.txt` disallows
all crawlers. The site is reachable by anyone with the link or the QR code, but should not turn up
in search results. This is intentional: the poster text is also a submitted assessment, and having
it indexed invites a similarity-checking tool to match the submission against it.

To make the site publicly searchable later, delete `robots.txt` and remove the `robots` meta tag
from all four pages.

## Declaration

Screening, extraction and drafting for these pages and the accompanying e-poster were AI-assisted
(Claude, Anthropic). Figures were checked against their source publications by the authors, who are
responsible for the final content.
