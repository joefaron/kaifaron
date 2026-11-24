# kaifaron.com

Kai's art portfolio. Plain HTML, no build step.

- Add a photo: put `name.jpg` (about 2000px) and `name-sm.jpg` (about 800px) in `photos/`, then add a line to `photos.json`.
- Change the look: the colors are at the top of `style.css`.
- Always strip location data from phone photos first (`magick in.jpg -auto-orient -strip ...`).
