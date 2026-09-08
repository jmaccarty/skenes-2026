# Skenes' Fall, Some Hypotheses Backed by Data

Statcast forensics on Paul Skenes' 2026 season. All 8,140 pitches of his career,
run through a blind changepoint hunt on pitch physics, then a second informed pass
with the results turned back on.

The page is built around one hypothesis chain — velocity dropped, so the slot came
up to tighten the tunnel, which cost spin and location, and the results followed —
with a tab per link and a verdict on each. Four hold up. Two do not.

`index.html` is fully self-contained: all data embedded, all charts hand-drawn SVG.
The only external request is Google Fonts, which degrades to a system stack if
blocked. No build step, no dependencies.

Deep links work per tab: `#overview`, `#velo`, `#slot`, `#tunnel`, `#spin`,
`#location`, `#results`, `#more`.

Data: Baseball Savant / MLB Statcast, retrieved 2026-09-05.
