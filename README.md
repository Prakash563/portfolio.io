# Prakash Dora — Data Science & AI/ML Engineer Portfolio

An interactive single-page portfolio for Prakash Dora, built from the supplied resume and public GitHub profile. The design direction is **Signal / Notebook**: an editorial research log with graphite backgrounds, warm paper panels, IBM Plex Mono metadata, Cormorant Garamond display type, and an electric chartreuse signal color.

## Included experience

The portfolio includes a responsive desktop/mobile navigation system, scroll progress, active section tracking, animated entry states, GitHub and LinkedIn links, live project filtering, expandable project method notes, a copy-email action, generated hero artwork, and a generated signal mark used throughout the brand system.

All project descriptions are grounded in the provided resume and the public GitHub profile at [github.com/Prakash563](https://github.com/Prakash563). The featured repositories link directly to GitHub so visitors can inspect the source.

## Local development

```bash
pnpm install
pnpm run dev
```

The production checks used for this project are:

```bash
pnpm run check
pnpm run build
```

## Push this project to GitHub

Create an empty repository under the GitHub account that should own the site, then run the following from the project root. Replace the placeholder remote URL with the repository URL you created.

```bash
git init
git add .
git commit -m "Create Prakash Dora data science portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
git push -u origin main
```

The project is frontend-only and does not require a database or secret keys. The generated visual assets are referenced through the managed project asset URLs, so there is no large local media folder to commit.

## Content source

The copy is based on `Prakashdora.pdf` and public repository/profile information visible at the time of build. Update project cards in `client/src/pages/Home.tsx` when a new repository, metric, or role becomes verified.
