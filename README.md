# Atul P. Pohane – QA Automation Engineer / SDET Portfolio

A static portfolio site for QA Engineer, Senior SDET, Automation Test Engineer and Senior Consultant roles.

**Highlights:** 5+ years in software testing · Selenium (Java, TestNG) · Playwright (TypeScript) · REST Assured · JMeter · Jenkins · e-commerce and healthcare projects.

## Contents

```
atul-pohane-portfolio/
├── index.html                    # the whole site (HTML + CSS + JS, no build step)
├── assets/
│   ├── atul-pohane.jpg           # profile photo
│   └── Atul_Pohane_Resume.pdf    # downloadable resume
├── .nojekyll                     # tells GitHub Pages to serve files as-is
└── README.md
```

## Publish on GitHub Pages

1. Create a new **public** repository on GitHub. For a clean URL, name it `<your-username>.github.io`
   (site URL: `https://<your-username>.github.io`). Any other name also works, e.g. `portfolio`
   (site URL: `https://<your-username>.github.io/portfolio`).
2. Unzip this package and upload everything inside `atul-pohane-portfolio/` to the repository root
   (GitHub: **Add file → Upload files**), or use Git:

   ```bash
   cd atul-pohane-portfolio
   git init
   git add .
   git commit -m "Add portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. In the repository, open **Settings → Pages**. Under **Build and deployment**, set **Source** to
   *Deploy from a branch*, choose branch **main** and folder **/ (root)**, then **Save**.
4. Wait about a minute. Your live URL appears at the top of the Pages settings screen.
5. Put that URL on your resume, LinkedIn and job applications.

## Customise

- Text, projects and links: edit `index.html`.
- Add your LinkedIn and GitHub links by adding two buttons next to the email button in the **Contact** section.
- Replace the resume: overwrite `assets/Atul_Pohane_Resume.pdf` with the same file name.
- Add a test-framework sample repo to the Projects section once you have one public; recruiters like to see code.
