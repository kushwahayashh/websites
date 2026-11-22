# websites

A collection of small, hand-built websites. Each site lives in its own folder and is a self-contained static page: no build step, no dependencies. Open the `index.html` in a browser and it runs.

## Sites

| Site | Description | Preview |
| --- | --- | --- |
| [pixelmoss](./pixelmoss) | Pixel-art landing page for a tiny two-person game studio. Animated landscape with a Day/Night toggle, animated game windows, pixel cursor and a sleepy campfire footer. | <img src="pixelmoss/screenshots/hero-day.png" width="320"> |

## Structure

```
websites/
├── README.md
└── <site-name>/
    ├── index.html
    ├── README.md
    └── screenshots/
```

## Running a site locally

```bash
cd pixelmoss
python3 -m http.server 8000
# then open http://localhost:8000
```

Or just open `index.html` directly in a browser.

## Adding a new site

1. Create a folder named after the site.
2. Put the page in `index.html` (plus any assets next to it).
3. Add a `README.md` and a `screenshots/` folder.
4. Add a row to the table above.
