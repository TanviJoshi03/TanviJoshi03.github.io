# TanviJoshi03.github.io

Personal portfolio site — live at **https://TanviJoshi03.github.io**

## Deploy (one-time setup)

1. Create a new repo on GitHub named exactly `TanviJoshi03.github.io`
2. From this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio site"
   git branch -M main
   git remote add origin https://github.com/TanviJoshi03/TanviJoshi03.github.io.git
   git push -u origin main
   ```
3. GitHub Pages activates automatically — site is live in ~1 minute.

## Add your resume

Drop your PDF as `resume.pdf` in this folder, then:
```bash
git add resume.pdf
git commit -m "Add resume"
git push
```

The Resume button in the nav will link to it automatically.

## Update projects

All content is in `index.html`. Each project card is a self-contained `<div class="project-card">` block — easy to edit or add new ones.
