# Muhammed Abdu Rahman C — Portfolio

A single-page personal portfolio built with plain HTML/CSS/JS, styled as a code editor / terminal interface.

## Live preview

Open `index.html` in any browser — no build step required.

## Structure

```
.
├── index.html            # the whole site
├── 69646760473.jpg.jpeg  # profile photo (referenced in the hero section)
└── resume.pdf            # downloadable resume (linked from the "Download Resume" button)
```

## Sections

| Tab            | Content                                  |
|----------------|-------------------------------------------|
| `about.md`     | Short bio                                 |
| `skills.json`  | Frontend, programming, and tools skills   |
| `projects.js`  | Featured projects                         |
| `education.yml`| Degree info + currently-learning git log  |
| `contact.sh`   | Email, GitHub, LinkedIn                   |

## To do before publishing

- [ ] Replace `YOUR_GITHUB_LINK` (appears twice) with your actual GitHub URL
- [ ] Replace `YOUR_LINKEDIN_LINK` with your actual LinkedIn URL
- [ ] Make sure `69646760473.jpg.jpeg` and `resume.pdf` are in the same folder as `index.html`
- [ ] Update project descriptions/stack as new projects are added

## Tech

- HTML5 / CSS3 (custom properties, no framework)
- Vanilla JS (scroll-based active-tab highlighting)
- Fonts: [JetBrains Mono](https://www.jetbrains.com/lp/mono/) + [Inter](https://rsms.me/inter/), via Google Fonts

## Deploying

Works as a static site — drag the folder into any static host (GitHub Pages, Netlify, Vercel) or push it to a `username.github.io` repo for a free GitHub Pages deploy.
