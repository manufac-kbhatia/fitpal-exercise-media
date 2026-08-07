# FitPal Exercise Media

Self-hosted mirror of exercise demonstration videos, posters, and images used
by the FitPal app's built-in exercise library. Media is organized by type
(matching the source API's own foldering):

- `videos/` — front and lateral demonstration clips (.mp4)
- `posters/` — poster/thumbnail images for each video (.jpg)
- `images/` — a small number of animated demonstration images (.gif)

Served to the app via jsDelivr's CDN (`cdn.jsdelivr.net/gh/manufac-kbhatia/fitpal-exercise-media@...`).
No API calls happen at runtime — this repo *is* the data source.
