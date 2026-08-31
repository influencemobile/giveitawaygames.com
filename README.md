# 25 Words or Less Daily Play Pitch

Private partnership concept site for a 25 Words or Less daily play and rewards experience powered by Influence Mobile.

## Project Status

This is a static HTML/CSS pitch site. There is no build step and no runtime dependency.

## Local Preview

```bash
npm run dev
```

Then open:

```text
http://localhost:4173
```

## GitHub Setup

Recommended repo visibility: private until the partner-facing version is approved.

After creating an empty GitHub repository, run:

```bash
git init
git add .
git commit -m "Initial 25 Words or Less pitch site"
git branch -M main
git remote add origin git@github.com:YOUR-ORG/25-words-less-daily-play-pitch.git
git push -u origin main
```

Replace `YOUR-ORG` with the GitHub user or organization that should own the repo.

## Vercel Setup

This is a static site. When importing the GitHub repo into Vercel, use:

- Framework Preset: Other
- Build Command: leave blank
- Output Directory: leave blank
- Install Command: leave blank

After the project is live, add the purchased domain in Vercel Project Settings > Domains and follow Vercel's DNS instructions.

The page and Vercel headers currently include `noindex, nofollow` protection for private pitch use.

## Notes

- The phone images are illustrative mockups from the existing Give It Away Games concept.
- Final partner branding, promotion mechanics, rules, prize language, and game catalog should be approved before external distribution.
