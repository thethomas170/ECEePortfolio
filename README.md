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
| `pc-building.html` | Additional project feature |
| `contact.html` | Additional section — contact |

## Still to add

- [x] ~~portrait~~ (cropped from campus photo — a solo headshot would be better)
- [x] ~~about hero~~ (campus photo)
- [ ] `assets/img/project-build.jpg` — **own photo of the Discovery Project (required)**
- [x] ~~resume PDF~~
- [x] ~~email and LinkedIn~~
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
