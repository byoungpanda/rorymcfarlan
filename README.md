# Rory McFarlan · rorymcfarlan.com

Author site for Rory McFarlan, hosted free on GitHub Pages. Plain HTML, CSS, and a little JavaScript. No frameworks, no build step: edit a file on GitHub, commit, and it's live in about a minute.

## Files

| File | What it is |
|---|---|
| `index.html` | Home page: hero, awards strip, both books, themes, about, contact |
| `trials-of-patience.html` | Book page for *Trials of Patience* |
| `nephis-courage.html` | Book page for *Nephi's Courage: Story of a Bad Mormon* |
| `404.html` | Friendly "page not found" page |
| `style.css` | All styling (colors and fonts are variables at the top) |
| `script.js` | Mobile menu, header background on scroll, gentle scroll fade-ins |
| `trials-of-patience.jpg`, `nephis-courage.jpg` | Book covers |
| `og-image.jpg` | The preview image shown when the site is shared on social media or in texts |
| `favicon.svg`, `favicon.png`, `apple-touch-icon.png` | Browser tab and home-screen icons |
| `CNAME` | Tells GitHub Pages the custom domain is rorymcfarlan.com |
| `robots.txt`, `sitemap.xml` | Help search engines find every page |

## Hosting

GitHub Pages deploys from the `main` branch root. The domain is registered at GoDaddy, with DNS pointing at GitHub Pages:

| Type | Name | Value |
|---|---|---|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | byoungpanda.github.io |

HTTPS is enforced in Settings → Pages.

Before the switch (October 2026), GoDaddy forwarded the domain to the old Wix site (`rorymcfarlan.wixsite.com/website`) using its forwarding A records 15.197.225.128 and 3.33.251.168, with `www` as a CNAME to `@`. The domain had no MX or TXT records.

## Common updates

- **Book descriptions:** each book page has the description between `<!-- BLURB:START -->` and `<!-- BLURB:END -->`. The short teasers on the home page are in `index.html` under "BOOKS".
- **Buy links:** search for `amazon.com/dp/` in the HTML files.
- **A new book:** copy one of the book pages, swap the text, cover, and links, then add it to the nav, the home page "BOOKS" section, the footer, and `sitemap.xml`.
- **Swapping a cover:** upload a new file with the same name (Add file → Upload files replaces it). Covers look best at 2:3, about 800 × 1200 pixels.
- **Changing CSS or JS:** bump the `?v=1` after `style.css` or `script.js` in every HTML file so browsers fetch the new version.

## Copy style

American spelling, no em-dashes in visitor-facing text.
