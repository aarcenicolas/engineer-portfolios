# Images

Export around 1600 px on the long edge. JPG for photos, PNG for anything with
transparency. Images are cropped to fill, so keep the subject centered.

Aspect ratios in use:

- Portrait (About)   4:5
- Project card       4:3
- Project modal      21:9
- Hobby card         16:11

Suggested names: `portrait.jpg`, `rocket-launch.jpg`, `igvc-vehicle.jpg`,
`climbing.jpg`, `kitesurf.jpg`.

Wire one up by adding to the relevant entry in `index.html`:

    media: { type:"image", src:"assets/images/rocket-launch.jpg" }
