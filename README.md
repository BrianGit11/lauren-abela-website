# laurenabela.com — Website Source

Static HTML/CSS website for Lauren Abela — public speaker and inclusion advocate.

## Structure

```
website/
├── .github/workflows/deploy.yml   ← GitHub Actions FTP auto-deploy
├── css/style.css                  ← All styles
├── index.html                     ← Home page
├── about.html                     ← About page
├── speaking.html                  ← Speaking/talks page
├── contact.html                   ← Booking inquiry form
└── images/                        ← Add photos here (not yet created)
```

## Deploying

Push to `main` → GitHub Actions automatically deploys to laurenabela.com via FTP.

```bash
git add .
git commit -m "Your message here"
git push origin main
```

## First-time setup (run once)

```bash
git init
git remote add origin https://github.com/BrianGit11/lauren-abela-website.git
git branch -M main
git add .
git commit -m "Initial website build"
git push -u origin main
```

## Contacts / Form

The contact form uses Formspree. Sign up at formspree.io and replace `YOUR_FORM_ID` in `contact.html` with your endpoint ID.
