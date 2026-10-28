# Muhammed Abdu Rahman C | Developer Portfolio

A responsive, single-page personal portfolio for a Computer Science Engineering student. It has a terminal / code-editor style design and works on phones and desktops.

## Features

- Light and dark theme: follows the device setting, with a toggle button (the choice is remembered)
- Sections for About, Skills, Projects, Education and Contact
- Five project cards linking to GitHub
- One-tap "copy email" button in the Contact section
- Responsive layout with a mobile-friendly scrolling nav bar
- Smooth scroll reveal animations, with a fallback if JavaScript is off
- Link preview tags (Open Graph / Twitter card) and structured data for search engines
- No frameworks, no build step, no dependencies

## Projects

| # | Project | Tech |
|---|---------|------|
| 01 | Personal Portfolio Website (this site) | HTML, CSS, JavaScript |
| 02 | Calculator | C |
| 03 | College Git Workshop | Git, GitHub |
| 04 | Programming Project | C / Python |
| 05 | StudyShare: Student Notes Platform | Node.js, SQLite, REST API, Docker |

## Project structure

```
portfolio/
├── index.html      # the whole site (HTML + CSS + JS)
├── profile.jpg     # profile photo
├── og-image.png    # 1200x630 link preview image
└── README.md
```

## Run locally

No installation needed. Open `index.html` in any browser.

Or serve it locally:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy on GitHub Pages

1. Push these files to the root of your repository.
2. Go to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Your site will be live at `https://<username>.github.io/<repository>/` after a minute or two.

## Customize

- **Text and projects:** edit the sections in `index.html`. Each project is an `<article class="project">` block; copy one to add another.
- **Colors:** change the theme variables in the `:root` blocks near the top of the `<style>` section (one set for light, one for dark).
- **Photo:** replace `profile.jpg`, keeping the same file name.
- **Link preview:** after deploying, update the `og:url`, `og:image` and `twitter:image` addresses in the `<head>` to match your live site address, so shared links show `og-image.png`.

## Fonts

Loaded from Google Fonts: [Inter](https://fonts.google.com/specimen/Inter) and [JetBrains Mono](https://www.jetbrains.com/lp/mono/). Without internet access the site falls back to system fonts.

## Contact

- Email: muhammedabdurahmanc01052006@gmail.com
- GitHub: [muhammedabdurahmanc076-commits](https://github.com/muhammedabdurahmanc076-commits)
- LinkedIn: [Muhammed Abdurahman C](https://www.linkedin.com/in/muhammed-abdurahman-c-70b28537a)

## License

This is a personal portfolio. Please don't copy the personal content (text, photo, projects); feel free to take inspiration from the layout.
