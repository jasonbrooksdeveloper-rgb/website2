# Website 2 (A.Shridhar — intro animation only)

Standalone starting experience of the old ashridhar.com — no full website.

Flow: loader → start screen ("Click here to begin the experience") →
title-to-lift film (auto-pauses at 15s, 8-sec Skip countdown) →
"Pick Your Choice" (4 categories) → category films pausing at each project
name with next-arrow → lift film loops back to choices.
"View Project Details" shows an end card (full site not included) + replay.

Run it: `python -m http.server 8001 --directory .` → http://127.0.0.1:8001/
(or just double-click `index.html` — works offline, no internet needed).

- `video/` — the 6 original films (same files + timings as the old site)
- `img/`, `gif/` — logo, category icons, arrows, loader

Large `*.mp4` files are stored with Git LFS.
