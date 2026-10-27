# youngkyungkim93.github.io

Personal research website for Young Kyung Kim. It is a single static page (`index.html`) plus the CV (`cv.pdf`), so it needs no build step.

## Publish on GitHub Pages

1. On GitHub, create a new public repository named exactly `youngkyungkim93.github.io`.
2. Upload `index.html`, `cv.pdf` and this `README.md` to the repository root and commit.
3. Open **Settings → Pages**. Under "Build and deployment", set the source to **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. After a minute or two the site is live at https://youngkyungkim93.github.io.

## Common edits

- **Add a news item:** in `index.html`, find the comment `Recent updates` and add a new `<li>` at the top of that list.
- **Add a paper:** copy an existing `<li class="pub">` block in the Publications section, change the text and links, and give it a unique `id` (for example `pub-3dgen`) so other parts of the page can link to it.
- **Add a photo:** put `photo.jpg` in the repository root, then find the comment "To add a photo" in `index.html` and remove the comment marks around the `<img>` line. A portrait (taller than wide) works best.
- **Update the CV:** replace `cv.pdf` with the new file, keeping the same name.
- **Update the date:** change "Updated October 2026" in the footer.

## Custom domain (optional)

If you buy a domain, add it under **Settings → Pages → Custom domain** and follow GitHub's DNS instructions.
