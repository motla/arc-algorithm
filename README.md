This is a JavaScript implementation of the Andres circle algorithm, adapted for arc drawings.

## Features
### :rocket: [See demo](https://motla.github.io/arc-algorithm/)
- No need for floating point numbers or trigonometric functions in fast approximation mode
- Sets each pixel only once
- Supports start/end angles, arc radius and trace width

## Quirks
- In fast approximation mode, the number of drawn pixels is approximated for a given angle, so the end of the arc can be noisy (visible only on large arc widths/radius for some angles). This is OK for an animated spinner for example.
