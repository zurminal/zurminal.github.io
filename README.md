# Personal Website (Academic Pages + Minimal Mistakes)

This repo scaffolds a personal site for `zurminal` using Jekyll, Minimal Mistakes, and Academic Pages conventions. It includes:

- About, Publications, Highlights, and CV sections
- BibTeX-driven publications via `jekyll-scholar`
- GitHub Pages deployment with Actions
- Social links: GitHub, LinkedIn, Google Scholar, ORCID (icons included)

## Quick Start

1) Create the repo on GitHub as `zurminal/zurminal.github.io`.

2) Push this code:

```bash
# from this project root
git init
git branch -m main
git add .
git commit -m "Scaffold site (Academic Pages baseline)"
git remote add origin git@github.com:zurminal/zurminal.github.io.git
git push -u origin main
```

3) Enable GitHub Pages
- Settings → Pages → Build and deployment → Source: GitHub Actions

4) Customize
- `_config.yml`: title, name, description, social links, etc.
- `_pages/about.md`: write your bio
- `_pages/publications.md` + `assets/bib/references.bib`: add BibTeX entries
- `_pages/highlights.md` + `_highlights/`: add highlight posts
- `_pages/cv.md`: drop a PDF at `assets/cv/your_name_cv.pdf`
- `index.md`: tune the splash hero and feature cards

5) Local development (optional)
- Install Ruby (>= 3.1), Bundler
- `bundle install`
- `bundle exec jekyll serve`
- Visit http://127.0.0.1:4000

## Notes
- Timezone is set to `America/Los_Angeles` (PST).
- Analytics are disabled.
- Icons: Academicons is included for Scholar and ORCID.
- No patents or provisional patents are included anywhere.
