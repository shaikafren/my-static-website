# Task 6 - Static Website

**Objective:** Deploy a simple HTML website using GitHub Pages.

**Files included:**
- `index.html` — main webpage
- `style.css` — styling
- Screenshots folder — shows live site

**Description:**  
This task demonstrates hosting a static website using GitHub Pages. The site includes basic HTML and CSS styling.
git init
git add .
git commit -m "Initial commit for Task 6"
git branch -M main
git remote add origin https://github.com/shaikafren/task-6-static-website.git
git push -u origin main
 INTERVIEW QUESTIONS
 1. What is GitHub Pages?

GitHub Pages is a free service by GitHub that lets you host static websites directly from a GitHub repository.

It’s ideal for personal sites, project pages, or documentation.

The site is built from files in a branch (usually main) of your repo.

2. Can you host dynamic apps here?

No, GitHub Pages only supports static content:

HTML, CSS, JavaScript, images, etc.

Server-side languages (like PHP, Python, Node.js) cannot run.

For dynamic apps, use platforms like Heroku, Vercel, Netlify, or AWS.

3. What are the limits of GitHub Pages?

File size: Individual files must be ≤ 100 MB.

Repo size: Recommended < 1 GB.

Bandwidth: Soft limit ~100 GB/month (GitHub may throttle heavy traffic).

No server-side processing. Only static content.

4. How do you update the website?

Make changes locally in your repo (HTML, CSS, JS).

Commit the changes with Git:

git add .
git commit -m "Update website"


Push to GitHub:

git push


GitHub Pages automatically rebuilds your site with the updates.

5. What happens when you delete the repo?

The GitHub Pages site stops working immediately.

The live URL (https://username.github.io/repo-name/) becomes 404 Not Found.

6. What is the default file that loads?

GitHub Pages looks for an index.html file in the root of the branch or folder you selected.

This file is loaded automatically when someone visits your site.

7. Can you use a custom domain?

Yes!

You can configure your GitHub Pages site to use your own domain instead of username.github.io.

Add your domain in Settings → Pages → Custom domain.

Update your DNS records to point to GitHub’s servers.

You can also enforce HTTPS for security.
