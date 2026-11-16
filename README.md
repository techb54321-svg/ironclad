# Ironclad

Gym accountability with teeth: GPS-verified check-ins, a friend holding your deposit, and a log that shows tampering.

Live at **https://ironclad.coach**.

| Path | What |
| --- | --- |
| `/` (`index.html`) | Landing page |
| `/app/` | The app: a single-file, installable web app. See `app/README.md`. |
| `/app/privacy.html` | Plain-language explanation of what is stored and where |
| `/app/server/` | The shared Ironclad alerts server (a Cloudflare Worker) and its setup guide |

There is no build step. `.github/workflows/pages.yml` publishes the repository to GitHub Pages on every push to `main`, and `CNAME` holds the custom domain.
