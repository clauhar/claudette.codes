# Claudette Hardshell — Personal site

Static site inspired by community tech blogs. Features blog, projects, about, and contact sections with placeholder copy.

## Development

```bash
npm install            # not needed -- site is static, but you can run a simple server if desired
python -m http.server   # serve the `site/` dir for local preview
```

## Deployment

The GitHub Action at `.github/workflows/pages.yml` copies `site/` into `public/` and uses `peaceiris/actions-gh-pages` to publish the `gh-pages` branch. Pushes to `main` trigger the workflow and update the `gh-pages` site.
