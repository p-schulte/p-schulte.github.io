# Paul Schulte

Source for [p-schulte.github.io](https://p-schulte.github.io/), my personal academic website. It brings together my research interests, publications, projects, and CV.

The site is built with Jekyll and based on the al-folio theme. GitHub Actions builds and deploys it to GitHub Pages.

## Run locally

With Docker and Docker Compose installed, run:

```sh
docker compose up
```

Open <http://localhost:8080/>. Changes to the site files are watched and rebuilt automatically. Stop the server with `Ctrl+C`.

## Where to make changes

- `_pages/` contains the main pages, including the home page and publications page.
- `_projects/` contains project descriptions.
- `_bibliography/papers.bib` contains publication entries.
- `_data/` contains CV, social, and other structured data.
- `assets/` contains images, documents, and other static files.
- `_config.yml` contains site-wide settings.

## Formatting

Install the Node.js dependencies with `npm install`, then check formatting with `npx prettier . --check` or format files with `npx prettier . --write`.
