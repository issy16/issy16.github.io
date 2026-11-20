# issy16.github.io

Personal site of Isabel Chen, software developer (UC Riverside CS '25).
Live at **https://issy16.github.io**.

## What's here

| Path | What it is |
|---|---|
| [`/`](https://issy16.github.io) | Resume and portfolio: about, skills, experience, projects, awards |
| [`/mindsea/`](https://issy16.github.io/mindsea/) | **Mindsea**, a deep-sea mind map app (beta). Sync via Supabase. |
| [`/tutorme/guest/`](https://issy16.github.io/tutorme/guest/) | **TutorMe** demo with sample data. The real lesson log keeps its records encrypted in a private repo. |

Related projects in their own repos:

- [System Design Lab](https://github.com/issy16/systemdesignlab): learn system design by breaking a simulated ticket app
- [Meowdoku Solver](https://github.com/issy16/meowdoku): constraint-satisfaction puzzle solver

## Structure

Static site, no build step. Push to `main` and GitHub Pages republishes.

```
index.html       resume page
css/pixel.css    pink pixel "music software" theme
js/eq-data.js    audio levels for the header equalizer
img/  video/     portrait, gallery images, music video
mindsea/         Mindsea app (single file)
tutorme/         TutorMe app; guest/ is the same page in demo mode
```
