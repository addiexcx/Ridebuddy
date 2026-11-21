# RideBuddy – Driver Register prototype

Clickable prototype of the RideBuddy fleet safety flow (Figma "6th Version"): Driver Overview, Driver Register (All, High Performing, High Risk, Flagged), expanded driver row, Take action modal, Driver Profile and Counselling log.

It is a single static page, `index.html`, with no build step.

## Run locally

Open `index.html` in a browser, or serve the folder:

```
npx serve .
```

## Deploy on Vercel

1. In Vercel, choose **Add New → Project** and import this repository.
2. Framework preset: **Other**. Build command: none. Output directory: repository root.
3. Deploy. Every push to `main` redeploys.

## Notes

- Screens are routed with the URL hash: `#overview`, `#all`, `#high-performing`, `#high-risk`, `#flagged`, `#profile`, `#counselling`.
- Data is sample data from the Figma file. Flags, filters and saved actions are kept in memory only and reset on reload.
