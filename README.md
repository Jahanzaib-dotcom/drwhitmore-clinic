# Dr. Sarah Whitmore — Clinic Site

This is a single-file static website for "Dr. Sarah Whitmore" (a demo clinic landing page).

What's included

- `index.html` — main site (copy of `drwhitmore-clinic.html`)

Quick steps to deploy

1. Initialize git, commit, and push to GitHub (replace <your-remote> with your repo URL):

```bash
cd /Users/JahanzaibDev/Downloads/healthcare
git init
git add .
git commit -m "Initial commit — clinic landing page"
git branch -M main
git remote add origin <your-remote>
git push -u origin main
```

2. Deploy on Vercel

- Visit https://vercel.com and sign in (GitHub/GitLab/Bitbucket).
- Create a new project and import your repository.
- Use the default settings for a static site (Framework Preset: Other) and set the output directory to `/` (root).
- Deploy — Vercel will publish your site and provide a URL.

Notes

- If you want automatic form handling, connect a serverless function or a third-party form provider (Formspree, Netlify Forms, etc.)
- Update phone numbers, copy, and any PHI before going live.

If you want, I can:
- Initialize the Git repo here and push to GitHub (you'll need to provide a remote or grant access)
- Set up a Vercel project via the Vercel CLI and deploy (requires you to authenticate)
