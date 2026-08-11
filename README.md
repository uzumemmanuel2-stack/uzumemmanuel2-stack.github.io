# Portfolio site

Plain HTML/CSS, no build step, no framework.

## Structure
```
index.html                          — homepage, hero + case list
case-studies/
  crop-disease-detection.html       — first case study
assets/
  styles.css                        — shared stylesheet
```

Adding a new case study later (e.g. the fish classifier) means:
1. Duplicate `case-studies/crop-disease-detection.html` as a template.
2. Replace the content inside `.decision-log` (Problem / Decision / Outcome).
3. Add a new `.case-card` block in `index.html` linking to it.
No restructuring needed.

## Deploy to GitHub Pages

1. Push this folder to a GitHub repo (e.g. `your-username.github.io`, or any repo name).
2. In the repo: **Settings → Pages → Source** → select the branch (usually `main`) and root folder (`/`).
3. Save. GitHub will give you a live URL, typically:
   - `https://your-username.github.io/repo-name/` (if repo isn't named `your-username.github.io`)
   - `https://your-username.github.io/` (if it is)
4. Wait 1–2 minutes for the first deploy, then visit the URL.

Any time you edit an HTML or CSS file and push, the live site updates automatically — no build step.

## Before publishing
- Read every line on both pages out loud. Cut anything that doesn't sound like you.
- Double check the email link works: `mailto:uzumemmanuel2@gmail.com`
- Once the fish classifier case study is ready, follow the steps above to add it — don't publish it early.
