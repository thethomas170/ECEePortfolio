# ECE ePortfolio — Thomas Nguyen

Personal ePortfolio for ECE 1100 at the Georgia Institute of Technology.
Static HTML/CSS, no build step, hosted with GitHub Pages.

**Live site:** https://thethomas170.github.io/ECEePortfolio/

## Pages

| File | Required component |
|---|---|
| `index.html` | Welcome / summary statement |
| `about.html` | Biography / About Me |
| `resume.html` | Resume — viewable and downloadable |
| `career-goals.html` | Career goals / ECE Roadmap |
| `projects.html` | Technical project samples (scalable) |
| `discovery-project.html` | **Discovery Project Feature** |
| `contact.html` | Additional section — contact |

## Still to add

- [ ] `assets/img/portrait.jpg` — replace placeholder with a real portrait
- [ ] `assets/img/about-hero.jpg` — replace placeholder
- [ ] `assets/img/project-build.jpg` — **own photo of the Discovery Project (required)**
- [ ] `assets/files/Thomas-Nguyen-Resume.pdf` — resume PDF for the download button
- [ ] Real email address and LinkedIn URL (currently placeholders)
- [ ] Discovery Project results section + showcase video embed
- [ ] Delete every `callout--todo` block before submitting

## Editing

Plain HTML. Each page carries its own header and footer; if you change the nav,
change it in all seven files. All styling lives in `assets/css/style.css`.

Run locally with:

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.
