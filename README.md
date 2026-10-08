# arnedt.github.io

Personal website of Arne De Temmerman, PhD researcher at DTAI, KU Leuven Campus Bruges.
Live at <https://arnedt.github.io>.

Built with [Jekyll](https://jekyllrb.com/) and the [al-folio](https://github.com/alshedivat/al-folio) theme.

## Editing content

| What               | Where                       |
| ------------------ | --------------------------- |
| Bio, profile photo | `_pages/about.md`, `assets/img/prof_pic.jpg` |
| Publications       | `_bibliography/papers.bib`  |
| CV                 | `_data/cv.yml`              |
| Projects           | `_projects/*.md`            |
| Social links       | `_data/socials.yml`         |
| Site settings      | `_config.yml`               |

## Local preview

```bash
docker compose up
```

Then open <http://localhost:8080>.

## Deployment

Pushing to `main` triggers `.github/workflows/deploy.yml`, which builds the site and publishes it to the `gh-pages` branch.
