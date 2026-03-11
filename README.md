# Isobe Lab website starter files

This is a simple GitHub Pages + Jekyll starter website modeled after a research group website.

## 1. Create a GitHub repository
Recommended repository name:
`isobe-lab-website`

## 2. Upload these files
Upload the full folder contents to the repository.

## 3. Turn on GitHub Pages
In your repository:
- Settings
- Pages
- Build and deployment
- Source: **Deploy from a branch**
- Branch: **main** / **root**

## 4. Edit `_config.yml`
Replace:
- `YOUR-GITHUB-USERNAME`
- repository name if different

Example:
- url: `https://kazuo-isobe.github.io`
- baseurl: `/isobe-lab-website`

## 5. Edit the page contents
Main pages:
- `index.md`
- `research.md`
- `members.md`
- `publications.md`
- `teaching.md`
- `join.md`
- `japanese.md`

## 6. Replace the top image
Replace:
`assets/images/top-placeholder.svg`

You can also rename it, but then update the image path in `index.md`.

## Optional: Run locally
If you have Ruby/Jekyll installed:
```bash
bundle install
bundle exec jekyll serve
```

Then open:
`http://127.0.0.1:4000/isobe-lab-website/`

## Quick customization ideas
- Add a `News` section on the home page
- Add member photos in `assets/images/`
- Add Google Scholar / ORCID links
- Add a bilingual Japanese/English page structure
