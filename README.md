# iqrarwaqas.github.io

Personal site of Waqas Iqrar: https://iqrarwaqas.github.io/

Plain HTML, CSS and a few lines of JavaScript. No build step. GitHub Pages serves the `main` branch as is.

## Files

| File | What it is |
| --- | --- |
| `index.html` | Home: intro, research, experience, projects, selected publications |
| `publications.html` | Full publication list with DOI links and BibTeX |
| `cv.html` | CV as a web page, with a link to the PDF |
| `404.html` | Not-found page |
| `assets/css/style.css` | All styles. Colours and fonts are tokens at the top of the file |
| `assets/js/main.js` | Theme toggle and the Copy BibTeX buttons |
| `assets/WaqasIqrar_CV.pdf` | The PDF behind the Download button. Replace it to update the CV |

## Common edits

- **Add a publication:** copy an `<article class="row">` block in `publications.html`, and add a short version to the list in `index.html` and `cv.html`.
- **Add a project:** copy an `<article class="project">` block in `index.html`.
- **Change colours or fonts:** edit the `:root` block in `assets/css/style.css`. The dark theme values sit right below it, in two places that must match.

## Preview locally

```
python -m http.server 8000
```

Then open http://localhost:8000.
