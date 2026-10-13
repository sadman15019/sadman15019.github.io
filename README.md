# sadman15019.github.io

Personal academic website of Sadman Sakib. It is plain static HTML/CSS with no build step.

## Files
- `index.html`: all content (bio, interests, publications, research, experience, education, courses, projects)
- `style.css`: styling, including light/dark theme
- `assets/profile.jpg`: profile photo
- `assets/Sadman_Sakib_CV.pdf`: add a CV without the references section here

## Deploy on GitHub Pages
1. Create a **public** repository named exactly `sadman15019.github.io`.
2. Push these files to the `main` branch:
   ```bash
   git init
   git add .
   git commit -m "Initial academic website"
   git branch -M main
   git remote add origin https://github.com/sadman15019/sadman15019.github.io.git
   git push -u origin main
   ```
3. On GitHub, go to **Settings → Pages**, set Source to *Deploy from a branch*, choose `main` and `/ (root)`, then save.
4. The site goes live at **https://sadman15019.github.io** within about a minute.

## Updating
Edit `index.html` and push. Each section has a comment banner (`<!-- ===== COURSES ===== -->`, etc.) so it's easy to find.
