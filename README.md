# Portfolio Landing Page

A clean, minimal landing page that links to all my analytics and data science project pages.

Built with plain HTML/CSS — no frameworks, no build step.

## Local Preview

Open `index.html` directly in your browser (this is the main portfolio page).

## Deploy to GitHub Pages

1. Create a new repo on GitHub (e.g., `portfolio` or `your-username.github.io`)
2. Push this project:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/your-username/your-repo-name.git
   git push -u origin main
   ```
3. In the repo on GitHub: **Settings → Pages → Source → Deploy from branch → main / (root)**
4. Your site will be live at `https://your-username.github.io/your-repo-name/`

## Adding a New Project

1. Add a new `<article class="project-card">` block inside `.projects-grid` in `index.html` (styles are embedded in the `<style>` tag in the same file)
2. Update the `href` on the "View Project" button to point to the project's live URL or GitHub Pages link
