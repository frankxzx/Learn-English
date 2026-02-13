# Learn-English Template Grind

A mobile-friendly English template trainer with spaced repetition (SRS), speech playback, and mastery tracking.

## Run locally

```bash
python3 -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000).

## GitHub Pages deployment

This repo includes a workflow at `.github/workflows/deploy-pages.yml`.

1. Push to `main`.
2. In GitHub: `Settings -> Pages -> Build and deployment -> Source: GitHub Actions`.
3. Wait for the `Deploy to GitHub Pages` workflow to finish.

Your site URL will be:

`https://<your-username>.github.io/<repo-name>/`

## Notes

- Learning history is stored in browser `localStorage`.
- Progress does not sync across devices unless you add backend sync.
