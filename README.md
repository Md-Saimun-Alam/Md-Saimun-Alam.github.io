# md-saimun-alam.github.io

Personal academic website of Md Saimun Alam (PhD student, Physics, University of Toledo).
Plain HTML/CSS, no build step. Edit `index.html`, commit, and GitHub Pages republishes.

## Add a photo to "Moments"
1. Resize/crop to about 960 x 720 px (JPG) and put it in `assets/photos/`.
2. In `index.html`, find `<div class="moments">` and copy one line, e.g.
   `<figure><img src="assets/photos/NEW.jpg" alt="what is in the photo" width="960" height="720" loading="lazy"><figcaption>Short caption</figcaption></figure>`

## Add a talk photo
Replace the `<div class="ph">…</div>` placeholder in that talk card with
`<img src="assets/photos/NEW.jpg" alt="..." width="960" height="720" loading="lazy">`.

## Update the CV
Replace `assets/Md_Saimun_Alam_CV.pdf` with the new PDF (same file name).
