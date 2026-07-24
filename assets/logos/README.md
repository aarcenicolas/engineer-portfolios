# Logos

Square PNG or SVG, transparent background, 200×200 px or larger. SVG preferred.

Filenames the site already looks for:

- `lmu.png`         — Education, FAB Lab, Thermal Fluids Lab
- `asf.png`         — The American School Foundation (high school)
- `boeing.png`      — Materials Lab (Boeing-sponsored)
- `ruhrpumpen.png`  — Project Engineer Intern
- `vacamsa.png`     — Sales Associate
- `walltopia.png`   — Walltopia (entry still commented out in index.html)

Until a file exists the bubble shows a monogram instead — nothing breaks.

Dark logos vanish on the dark background. Each entry in `index.html` has an
`invert` flag: set `invert:true` for black-on-transparent artwork, `false` for
logos that are already white or brightly colored.
