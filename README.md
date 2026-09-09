# Stretch and Squeeze

A single-page tactics board for our 3–4–1 (9v9). It walks all eighteen shapes —
three thirds × three lanes, with the ball and without it — and every zone is a
draggable board you can adjust and rename.

Cloned from a Claude artifact and rebuilt as a plain static site so it works in
any phone or desktop browser.

## Live site

<https://bresch20.github.io/stretch-and-squeeze/>

Add it to your phone's home screen ("Add to Home Screen") to open it full-screen
like an app.

## How it works

- **We have it / They have it** — switch between the in- and out-of-possession shape.
- **Back / Next** — step through the eighteen zones one at a time.
- **Pause / Play tour** — auto-walk the grid on a timer; any drag pauses it.
- **Edit shapes** — drag any player or the ball within the current square. Also
  reveals the name fields, *Mirror to other side*, and the reset buttons.

Edits, ball positions and names are saved in the browser's `localStorage`, so
they persist per-device. They are not synced between devices, and clearing site
data resets to the shipped eighteen.

## Editing

Everything lives in `index.html` (HTML, CSS and JS in one file). Push to `main`
and GitHub Pages redeploys automatically.
