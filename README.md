# Chao-Kai Chiang academic website

This is a static academic / researcher website designed for GitHub Pages. The current version includes a Research Vision section, Google Scholar citation highlights, DBLP link, selected publications, linked publication titles, and an updated CV PDF.

## Files

- `index.html` — main one-page website
- `assets/style.css` — responsive styling
- `assets/script.js` — mobile menu and publication filters
- `assets/img/profile.jpg` — optimized profile image
- `assets/docs/` — updated CV and publication list PDFs
- `.nojekyll` — prevents GitHub Pages from running Jekyll processing

## Deploy to GitHub Pages

1. Create a public GitHub repository named `<username>.github.io`.
2. Unzip this folder and upload all files to the repository root.
3. Commit and push to the `main` branch.
4. Open `https://<username>.github.io` after GitHub Pages finishes publishing.

Command-line version:

```bash
git init
git add .
git commit -m "Initial academic website"
git branch -M main
git remote add origin https://github.com/<username>/<username>.github.io.git
git push -u origin main
```

## Items to confirm

- The site currently uses `https://github.com/chaokai` for GitHub and `chaokai.utokyo@gmail.com` for contact email. Replace either value in `index.html` if needed.
- The uploaded CV PDF still shows the University of Tokyo affiliation. The homepage has been updated to National Yang Ming Chiao Tung University based on the information provided in the chat. Replace `assets/docs/CV_ckchiang.pdf` when a new CV is ready.
