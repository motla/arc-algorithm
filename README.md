This is a JavaScript implementation of the Andres circle alorithm, adapted for arc drawings.

## Features
### :rocket: [See demo](https://motla.github.io/arc-algorithm/)
- No need for floating point numbers
- No trigonometric functions
- Sets each pixel only once
- Supports start/end angles, arc radius and trace width

## Quirks
- The number of drawn pixels is approximated for a given angle, so the end of the arc can be noisy (visible only on large arc widths/radius for some angles). But for an animated spinner this is fine.
