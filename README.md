# Documented Portfolio — Jekyll (Minimal Mistakes)

This is a ready-to-deploy starter for a personal **documented portfolio** using Jekyll + Minimal Mistakes.

## Quick Start (GitHub Pages)

1. Create a new **public** repo on GitHub (e.g., `username.github.io` or any name).
2. Upload all files from this folder (or push via Git).
3. Go to **Settings → Pages**:
   - Build and deployment = **GitHub Actions**
4. The provided workflow (`.github/workflows/jekyll.yml`) builds `main` and deploys to Pages.
5. Edit `_config.yml` (title, url, links), and start adding content in `_pages/` and `_posts/`.

## Local Preview (optional)
- Install Ruby 3.3+
- `bundle install`
- `bundle exec jekyll serve --livereload`
- Open http://127.0.0.1:4000/

## Structure
- `index.md` — homepage
- `_pages/` — about, story, portfolio, blog, contact
- `_posts/` — blog posts
- `assets/images/` — images
- `.github/workflows/jekyll.yml` — GitHub Pages deployment

## License
MIT for this starter. Minimal Mistakes theme under its own license.