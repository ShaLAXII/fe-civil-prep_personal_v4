# FE Civil Prep — Compact GitHub Pages Edition

This replaces the earlier 81 MB base64-image edition with a smaller original-PDF-backed website. **No nested ZIPs, no Mac server, no infinite-scroll or nested PDF viewer.** Each question opens a single rasterized original source page with Previous/Next controls; solutions open the corresponding source page.

## Publish
1. Download and extract the ONE website ZIP.
2. Make a new GitHub repository (or delete old files from a previous FE website before replacing them).
3. Upload the extracted files **not the ZIP itself** with GitHub's `Add file > Upload files`. You can select all files at once. Keep `index.html`, `app.js`, and the six PDFs together at repository root.
4. In `Settings > Pages`, set `Deploy from a branch > main > /(root)`.
5. Wait for GitHub to show your published URL, then test question 1, an Islam question, and a companion-exam problem.

## How this works
The website uses Mozilla PDF.js (Apache 2.0), loaded from cdnjs over the internet, to render original PDF pages into **images on demand**. There is no scrolling PDF widget; one book page is displayed at a time with page navigation. The page content can be taller than the screen, so the ordinary webpage may still scroll.

The site needs an internet connection to load the PDF.js library and GitHub Pages PDFs. If the renderer fails to load, check network/CDN access. The PDFs are hosted publicly on GitHub Pages along with the website. Publishing requires actual redistribution permission from the copyright holders. User says permission is available; that has not been independently verified.

## Integrity and verification
Includes the same index of 2,294 source positions and 65 redrawn diagrams as the previous visual release. This is **not** a full independent solution audit: many questions are review-only, and source answers can contain errors. The publisher exam questions may overlap with the main bank. There are no new verified engineering solutions in this version.

GitHub browser upload currently allows 25 MiB per individual file; **all files here are below that size**. This edition is a smaller download and fewer uploads than the 81 MB package.
