# Bass Lake Association website

Draft public site, built with [Hugo](https://gohugo.io/) and published to GitHub Pages.

## Privacy rule

**This repo is public, and anything committed stays visible in Git history even if it's deleted later.** Never commit member data, officer contact details, association documents, meeting minutes, or passwords. Private content will live outside this repo.

## Preview

Install the Hugo version listed in `.github/workflows/deploy.yml`, then run:

```sh
hugo server
```

Open http://localhost:1313/ to see the site. Changes appear as you save.

## Edit

- **Pages:** `content/`
- **Navigation:** `hugo.toml`
- **Styles:** `assets/css/main.css`
- **Logos:** `static/images/`

The draft banner and the `noindex` tag are in `layouts/baseof.html`. Remove both at launch.

## Publish

Push to `main`. GitHub Actions builds the site and deploys it.

In the repo's settings, **Pages > Source** must be set to **GitHub Actions**.
