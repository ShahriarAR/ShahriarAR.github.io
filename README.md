# MD. Shahriar Ahamed Ridoy — Personal Website

A custom Hugo portfolio for a data and automation-focused software professional. The site includes project case studies, research, a web resume, contact options, and Data Science Notes.

## Local preview

```powershell
hugo server
```

Open `http://localhost:1313/`.

## Production build

```powershell
hugo --gc --minify
```

The generated website is written to `public/` and is intentionally excluded from Git.

## Updating content

- Project case studies live in `content/projects/`.
- Data Science Notes live in `content/notes/`.
- The About, Research, Resume, and Contact page content lives in `content/`.
- Contact details and global metadata live in `hugo.yaml`.
- The PDF resume is `static/cv/md-shahriar-ahamed-ridoy-cv.pdf`.
- The portrait and social card are in `static/images/`.

Each new project or note should be a Markdown file with YAML front matter matching the existing examples.

## Deployment

Pushes to the `main` branch trigger `.github/workflows/hugo.yaml`, which builds the site with Hugo and deploys the generated artifact to GitHub Pages.
