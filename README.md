# Haze Watch

Single-page static site. No build step.

- Haze (PSI, PM2.5, PM10): National Environment Agency via data.gov.sg, Singapore only.
- Weather: Open-Meteo, Singapore and 11 ASEAN cities.
- Both are a snapshot taken at 10:00 SGT on 1 Nov 2026, embedded in `index.html`
  (search for `var NEA` and `var CITIES` to update the values).

## Deploy to Vercel

CLI: run `vercel` in this folder (Framework Preset: Other, no build command,
output directory left blank), then `vercel --prod`.

Dashboard: drag this folder onto vercel.com/new, or import the Git repo that holds it.

`vercel.json` is optional. It only adds clean URLs and basic response headers.
