# mini-apps

Small, single-file web apps, hosted on GitHub Pages at **https://rshiva.com/apps/**.

## Layout

```
index.html                  → redirects rshiva.com/ to /apps/
apps/index.html             → the listing page (rshiva.com/apps/)
apps/<slug>/index.html      → each app (rshiva.com/apps/<slug>/)
CNAME                       → custom domain for GitHub Pages
```

## Adding an app

1. Put the HTML file at `apps/<slug>/index.html`.
2. Add an entry to the `APPS` array in `apps/index.html`.
3. Commit and push to `main`. Pages redeploys automatically in about a minute.
