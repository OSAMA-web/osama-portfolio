# Osama Ghufran — Portfolio

A responsive personal portfolio for **Osama Ghufran**, built as a single `index.html` file with embedded CSS and JavaScript. No framework, build step, or package installation is required.

## Features

- Responsive layout for mobile, tablet, and desktop
- About, skills, projects, experience, education, and contact sections
- Animated reveal effects and active navigation
- Mobile navigation menu
- Direct email, phone, GitHub, and résumé links
- Accessible focus states and reduced-motion support

## Files

```text
osama-portfolio/
├── index.html
├── README.md
└── Osama_Ghufran_Resume.pdf
```

## Run locally

1. Download or clone this repository.
2. Keep `index.html` and `Osama_Ghufran_Resume.pdf` in the same folder.
3. Open `index.html` in a browser.

No local server is required for this static website.

## Deploy with GitHub Pages

1. Create a new repository on GitHub, for example `osama-portfolio`.
2. Upload `index.html`, `README.md`, and `Osama_Ghufran_Resume.pdf` to the repository root.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/(root)` folder, then click **Save**.
6. Wait for GitHub Pages to publish the site. The URL will appear in the Pages settings and usually follows this format:

   `https://OSAMA-web.github.io/osama-portfolio/`

If you use a different repository name, the URL will use that name instead. A repository named `OSAMA-web.github.io` can publish at the root domain `https://OSAMA-web.github.io/`.

## Push using Git

Run these commands inside the extracted project folder after creating the empty GitHub repository:

```bash
git init
git add index.html README.md Osama_Ghufran_Resume.pdf
git commit -m "Add personal portfolio"
git branch -M main
git remote add origin https://github.com/OSAMA-web/osama-portfolio.git
git push -u origin main
```

If you named the repository differently, replace `osama-portfolio` in the remote URL. If GitHub CLI is already authenticated, you can use your existing `gh` workflow instead.

## Personalize before publishing

- Check all project links. The résumé supplied project descriptions, but did not include dedicated GitHub URLs for every project. Where a dedicated URL was unavailable, the portfolio links to the GitHub profile rather than inventing a repository URL.
- Confirm that the résumé PDF is the version you want public. Anyone who can access the website may be able to download it.
- Update the email, phone, project descriptions, or skill tags in `index.html` if needed.

## Technology

HTML5 · CSS3 · Vanilla JavaScript · GitHub Pages
