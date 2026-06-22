#Static Website For Developer's Portfolio

📋 Internship Details
INTERN ID: CITS1650

FULL NAME: Jayant Kumar Yadav

NO. OF WEEKS: 1 week

PROJECT NAME: Static Website For Developer's Portfolio

PROJECT SCOPE: To design, develop, and deploy a responsive static web application that effectively showcases a professional's skills, education, and technical projects to potential employers or clients.

🚀 Overview
This repository contains the source code for a fully responsive, accessible, static developer portfolio website built from scratch using HTML5, CSS3, and vanilla JavaScript. The project demonstrates semantic markup, keyboard accessibility, and mobile-first responsive design without relying on Node.js or external UI frameworks. It is ready to preview locally and deploy to GitHub Pages.

The site includes the following sections: Hero / Intro, Skills, Projects, About, and Contact. Interactivity is intentionally minimal and focused on usability: a keyboard-accessible skip link, an ARIA-enabled mobile navigation toggle, and a small script to handle the mobile menu and dynamic year.

🛠️ Technologies Used
HTML5 — Semantic structure and accessible content.

CSS3 — Custom properties, Flexbox and Grid layouts, responsive media queries.

JavaScript (Vanilla) — Small DOM interactions: mobile nav toggle and dynamic footer year.

No build tools — The site is pure static files; Node.js is not required.

Optional: VS Code Live Server for local preview (not required for the site to work).

📂 Project Structure
text
static-website-for-developer's-portfolio/
├── index.html          # Main HTML structure and content
├── css/
│   └── styles.css      # Styling and responsive rules
├── js/
│   └── script.js       # Small interactive behaviors
├── assets/
│   ├── avatar.jpg      # Replace with your portrait
│   └── project1.png    # Replace with project screenshots
├── .gitignore
└── README.md
✅ Features
Single-page layout with anchor navigation for smooth, simple browsing

Responsive design using CSS Grid and Flexbox for mobile → desktop layouts

Accessibility: skip link, semantic headings, ARIA attributes, visible focus states

Lightweight: no frameworks, minimal JS, fast load times

Easy deployment: ready for GitHub Pages (no build step)

🔧 How to Use (No Node.js Required)
Download or clone this repository to your machine.

Open the project folder in Visual Studio Code (or your editor of choice).

Preview locally:

Recommended: Install the Live Server extension in VS Code and click Go Live.

Alternative: Open index.html directly in your browser by double-clicking the file.

Edit content:

Replace assets/avatar.jpg and assets/project1.png with your optimized images.

Update name, email, bio, skills, and project descriptions in index.html.

Test keyboard navigation (Tab key), mobile layout (browser devtools), and link targets.

📦 Git and Deployment (GitHub Pages)
Create a new repository on GitHub named static-website-for-developer's-portfolio.

From your project folder run:

bash
git init
git add .
git commit -m "Initial commit: static portfolio"
git remote add origin https://github.com/<USERNAME>/static-website-for-developer's-portfolio.git
git branch -M main
git push -u origin main
On GitHub: go to Settings → Pages, choose Deploy from a branch, select main and folder / (root), then save.

After a short delay your site will be available at:

Code
https://<USERNAME>.github.io/static-website-for-developer's-portfolio/
✍️ Personalization Checklist
Before publishing, update these items to make the portfolio your own:

Contact: Replace youremail@example.com in index.html with your real email.

Name & Title: Update displayed name and role.

Bio: Write a concise About section highlighting your strengths and goals.

Skills: Replace placeholder skills with your actual technologies and proficiency levels.

Projects: Add real project cards with screenshots, short descriptions, tech stack, and links to live demos and repositories.

Images: Optimize images (aim for under 200–300 KB each) using tools like TinyPNG or Squoosh.

Accessibility: Verify focus states, color contrast, and keyboard navigation.

🧩 Example Snippets (copy-paste)
Email link (replace email):

html
<a class="btn primary" href="mailto:youremail@example.com">Email me</a>
Project card (replace content and links):

html
<article class="project-card">
  <img src="assets/project1.png" alt="Project One screenshot" />
  <div class="project-body">
    <h3>Project One</h3>
    <p class="project-desc">Short description of the project and its purpose.</p>
    <p class="tech">HTML; CSS; JavaScript</p>
    <p class="project-links">
      <a href="https://live-demo.example" target="_blank" rel="noopener">Live</a>
      <a href="https://github.com/username/project-one" target="_blank" rel="noopener">Repo</a>
    </p>
  </div>
</article>
📌 Notes & Tips
No Node.js or package managers are required — the site is pure static files.

Use the Live Server extension for a convenient local development experience.

Keep images small and use modern formats (WebP where supported) for best performance.

Run Lighthouse in Chrome DevTools to check accessibility and performance before publishing.

🔗 Website Link 
