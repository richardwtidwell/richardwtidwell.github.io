# CS 499 Portfolio – GitHub Pages

This repository backs the GitHub Pages site for Richard Tidwell’s CS 499 capstone portfolio. The site highlights three enhanced artifacts (software engineering, algorithms/data structures, databases), links to milestone narratives, and provides contact information.

## Structure

- `index.html` – landing page content
- `styles.css` – dark theme styling
- `assets/` – HTML exports of milestone narratives and evidence snippets

## Local Preview

```bash
python3 -m http.server 4000
# then open http://localhost:4000
```

## Updating content

1. Drop new artifacts (PDF/DOCX/PNG) into the main repo (`CS-465`) and update any links in `index.html`.
2. If you export narratives to HTML, place them under `assets/` and add “Read in browser” links.
3. Run `git status`, commit, and push to publish the latest page.

## Notes

- The code-review video is included in the final submission bundle alongside the repository archive.
- Update screenshots or narratives by editing `assets/screenshots/` and the accordion content in `index.html`.
