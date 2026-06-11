# timmybeckmann.com

Hand-coded portfolio site. Brand Motion Designer. Static HTML/CSS/JS, no build step.

## Stack
- Plain HTML + one shared stylesheet (`case-study.css`)
- General Sans via the Fontshare CDN
- Vimeo for all video, GitHub for code, Netlify for hosting

## Pages
- `index.html` — landing (reel only)
- `work.html` — six case studies grid
- `01`–`06` — case study pages
- `gallery.html` — breadth grid + Vimeo lightbox
- `about.html` — bio, games, contact

## Design tokens
All in `:root` at the top of `case-study.css`. Change one line, every page updates.
Accent red `#CA413A` is the only color.

## To finish wiring it up
- [ ] Reel: drop the Vimeo ID into the commented `<iframe>` in `index.html`
- [ ] Case studies: replace the play-button `<div class="video">` block with the Vimeo embed in each `01`–`06` (commented example is in each file)
- [ ] Work tiles: add short muted MP4 loops to `/clips` named `01.mp4` … `06.mp4` (+ optional `01-poster.jpg` …)
- [ ] Gallery: set `data-vimeo="VIDEO_ID"` on each `.gitem` / `.chip-link`, add square thumbs to `/thumbs`
- [ ] Approach + output images: swap the `.ph` placeholders for real stills
- [ ] Resume: drop `Timmy-Beckmann-Resume.pdf` into `/assets`
- [ ] Confirm social URLs in the footer (YouTube handle, Instagram)

## Local preview
Open `index.html` in a browser, or `python3 -m http.server` from this folder.
