# Personal Portfolio

My personal portfolio website, built to show who I am, what I have learned and the projects I have worked on as an Information Technology student.

- **Live site:** [perstportfolio.vercel.app](https://perstportfolio.vercel.app/)
- **Repository:** https://github.com/bigron-turon/portfolio

## Sections

| # | Section | What it shows |
|---|---------|---------------|
| 1 | Home | Name, year level and tagline |
| 2 | About Me | A short introduction and my educational background |
| 3 | Skills | Technical skills and ways I like to work |
| 4 | Certificates | Microsoft certifications plus recognition and participation certificates |
| 5 | Projects | Brewffe, SariTrack, Cafe Rencontre, SmartEvent and two simple games |
| 6 | Contact | Email, GitHub and LinkedIn |

## Features

- A capybara mascot that opens a quick menu to jump to any section
- Dark and light mode toggle (sun/moon icon) that remembers the visitor's choice
- Responsive layout that works on phones, tablets and desktops
- Click any certificate or project screenshot to view it larger

## Built with

- **HTML5**: semantic, single-page layout
- **CSS3**: custom properties, Grid and Flexbox, no framework
- **JavaScript**: mascot menu, certificate and screenshot viewer, dark/light mode toggle
- **Google Fonts**: Bricolage Grotesque (headings), DM Sans (text)
- **Vercel**: hosting and deployment

## Project structure

```
personal-portfolio/
├── index.html            # all page content
├── style.css             # colors, layout and both themes
├── images/
│   ├── profile.jpg       # profile photo
│   ├── certificates/     # certificate images
│   └── projects/         # project screenshots
└── README.md
```

## Run it locally

No build step. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 4173
```

Then visit http://localhost:4173.

## Deployment

1. Push this folder to a public GitHub repository.
2. On [Vercel](https://vercel.com), log in with GitHub and import the repository.
3. Keep the defaults (Framework Preset: **Other**, no build command) and click **Deploy**.

Every push to `main` redeploys the site automatically.

## Author

**Rohn Monrhey Bañares**, 4th Year Information Technology Student, La Consolacion University Philippines

[GitHub](https://github.com/bigron-turon) · [LinkedIn](https://www.linkedin.com/in/rohn-monrhey-ba%C3%B1ares-69855a44a/)
