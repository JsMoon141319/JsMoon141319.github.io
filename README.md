# JsMoon Portfolio
Dark, bilingual, modular portfolio for Technical Art, 3D Art and 2D Art.

## Edit projects
Edit `data/projects.json` on GitHub. Each JSON array entry is a project.
- `id`: unique slug
- `category`: `Technical Art`, `3D Art`, or `2D Art`
- `title`, `description`, `content`: bilingual objects with `zh` and `en` fields
- `tools`: list of tags
- `thumbnail`: image URL or relative path such as `images/my-work.jpg`
- `images`: array of image URLs/paths for the detail view
- `link`: optional external URL
- `visible`: false to hide a project

The initial entries are placeholders. Replace them with real work.

## Publish
In Settings → Pages set Source to GitHub Actions. Every push to main deploys the site.
