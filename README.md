# GageMate Documentation

Public documentation website for GageMate, built with MkDocs Material and deployed to GitHub Pages.

## Setup

1. Replace `YOUR-USERNAME` in `mkdocs.yml` with your GitHub username or organization.
2. Add your verified GitHub Releases and support URLs in the documentation.
3. Add real screenshots to `docs/images/` and link them from the installation guide.
4. Push this repository to GitHub as `main`.
5. In GitHub **Settings → Pages → Build and deployment**, select **GitHub Actions**.
6. Open **Actions** and confirm the deployment workflow completes.

## Preview locally

```powershell
py -m pip install -r requirements.txt
py -m mkdocs serve
```

Visit `http://127.0.0.1:8000/`.

## Build

```powershell
py -m mkdocs build --strict
```

Review placeholders and verify all security, system-requirement, and support claims before making the site public.
