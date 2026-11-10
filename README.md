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

- [x] ~~portrait~~ (professional headshot)
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

## How to edit the text yourself

Easiest way, no software needed:

1. Open the repo on github.com and click the page you want to change
   (e.g. `about.html`).
2. Click the **pencil icon** (top right of the file view).
3. Find the sentence you want and edit it. The words sit between the tags —
   change the text, leave the `<p>` and `</p>` alone.
4. Scroll down, click **Commit changes**.
5. GitHub Pages rebuilds in about a minute.

Which file holds what:

- Home page text → `index.html`
- Your biography → `about.html`
- Discovery Project write-up → `discovery-project.html`
- PC building project → `pc-building.html`
- Career goals / roadmap → `career-goals.html`
- Resume text on the page → `resume.html`
- Contact details → `contact.html`

Tip: `&mdash;` is a dash, `&middot;` is a dot separator, and `&amp;` is an
ampersand. Leave those as they are.
