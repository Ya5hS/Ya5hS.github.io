# Portfolio Starter (Jekyll + GitHub Pages)

## What's in here

- `_config.yml` — site settings (title, nav, your GitHub/LinkedIn usernames)
- `index.md` — home/about page
- `projects.md` — auto-generated list of everything in `_projects/`
- `_projects/pipe-rack.md` — example project page (edit this, then copy it for each new project)
- `_layouts/project.html` — the template every project page uses
- `resume.md` — embeds a PDF resume from `assets/files/resume.pdf`

## First-time setup

1. Create a GitHub repo named `your-github-username.github.io`
2. Copy all these files into it
3. In `_config.yml`, replace `your-github-username` and `your-linkedin-username` with your actual usernames, and update the email in `index.md`
4. Export your resume to PDF and save it as `assets/files/resume.pdf`
5. Commit and push to the `main` branch
6. In the repo's Settings > Pages, confirm the source is set to the `main` branch (usually automatic for a `username.github.io` repo)
7. Your site goes live at `https://your-github-username.github.io` within a few minutes

## Adding a new project

1. Copy `_projects/pipe-rack.md` to a new file in `_projects/`, e.g. `_projects/formula-sae-brakes.md`
2. Update the `title`, `summary`, and `tags` in the front matter
3. Write the body using the same sections (Problem/Goal, Approach, Standards, Visuals, Outcome)
4. It'll automatically show up on `/projects.html` — no other file needs editing

## Testing locally (optional)

If you have Ruby installed:

```
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000`. Not required — you can also just push to GitHub and let Pages build it for you.
