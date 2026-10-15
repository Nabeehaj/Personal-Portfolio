# Nabeeha Jahir | Personal Portfolio

> I wasn't born knowing. I was born asking.

A personal portfolio site for **Nabeeha Jahir**, a Computer Science student (CS Honors, expected May 2028) at Stony Brook University. It shows my projects, experience, and a little bit of who I am, and it has a small game hidden inside.

**Live site:** https://nabeehaj.github.io/YOUR-REPO-NAME/
*(replace with your real GitHub Pages link)*

---

## What's on the site

- **Hero:** a short intro, my photo in an arch frame, and a dot grid that reacts to your mouse. Click empty space and the dots ripple.
- **Skills bar:** a moving bar of languages and tools that speeds up as you scroll.
- **Projects:** a carousel of what I've built. The images stay dark and maroon until you hover over them.
- **About:** my story (with a "Read more" arrow), plus education, honors, coursework, languages, and tools.
- **Experience:** a timeline whose line and dots fill in as you scroll.
- **Play:** **Alien Reflex**, a small reaction game. Tap the aliens, avoid the astronauts, and don't lose all your lives.
- **Contact:** a message box that opens your email app with the note already written, plus links to my email, LinkedIn, and GitHub.
- **Resume:** a download button in the top bar.
- **Theme toggle:** dark maroon and black by default, with a lighter blush theme (the ◐ button).

## Projects featured

| Project | Link |
| --- | --- |
| Zakat Calculator | [Live site](https://nabeehaj.github.io/Zakaat-Calculator/) |
| Alien Reflex Game | [Code](https://github.com/Nabeehaj/alien-reflex-game) |
| RoyaltGold Storefront | [Repo](https://github.com/Nabeehaj/RoyalTGold) |

## Built with

- **HTML, CSS, and JavaScript only.** No frameworks and no build step, so it runs straight on GitHub Pages.
- Fonts: [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) and [Jost](https://fonts.google.com/specimen/Jost) from Google Fonts.
- Animations use the Canvas API, SVG, CSS, and `requestAnimationFrame`.
- Respects `prefers-reduced-motion` and works on phones.

## Files

```
.
├── index.html                  # the whole site (HTML, CSS, JS, and my photo)
├── Nabeeha_Jahir_Resume.pdf    # linked from the Resume buttons
└── README.md
```

My photo is embedded inside `index.html`, so there is no separate image file to upload.

## Run it locally

No install needed. Just open `index.html` in your browser.

To use a local server instead:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy with GitHub Pages

1. Put `index.html` and `Nabeeha_Jahir_Resume.pdf` in the root of the repo.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder, then save.
5. Wait a minute or two. Your site will be at `https://<username>.github.io/<repo-name>/`.

If the repo is named `<username>.github.io`, the site is served at `https://<username>.github.io/`.

## Make it yours

- **Photo:** search `index.html` for the `<img src="data:image/jpeg;base64,...` inside `id="arch"` and swap it for `<img src="me.jpg" alt="...">` if you'd rather use a separate file.
- **Resume:** replace `Nabeeha_Jahir_Resume.pdf` and keep the same file name, or update the three links that point to it.
- **Colors:** the theme colors are CSS variables at the top of the `<style>` block (`:root` for the dark theme, `[data-theme="blush"]` for the light one).
- **Game:** the Alien Reflex code is in the `<script>` block under the comment `Alien Reflex`.

## A note on how it was made

I wrote my own story and the text on this site. AI helped me build the ambience, meaning the design, animations, and code, because I cared most about the impression the site gives and wanted help getting there. It took many tries and themes (even an ocean one) before I landed on something that felt like me.

## Contact

- Email: [nabj.ny21@gmail.com](mailto:nabj.ny21@gmail.com)
- LinkedIn: [linkedin.com/in/nabeehaj](https://www.linkedin.com/in/nabeehaj/)
- GitHub: [github.com/Nabeehaj](https://github.com/Nabeehaj)

© Nabeeha Jahir
