# Therapy+ Financial Performance Tool

Replace `build/index.html` in the repo and push; Netlify redeploys. Keep the
`netlify/` folder, `netlify.toml` and `package.json` in place, they are what make
"Load a month" save for everyone. Never drag-and-drop deploy.

v1.1 (2026-10-27): reads the new "COFK - IS by Dpt w EBITDA (Therapy+)" export
(office columns, no state grouping row; department from the report title; EBITDA
taken from the file's EBITDA row) as well as the older "COFK - Income Statement"
layout, and the review panel has a month picker so a Budget to Actual pack can
load a month that has no P&L files yet (revenue, GP, visits, hours only).
