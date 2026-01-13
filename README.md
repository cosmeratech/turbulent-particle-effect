# turbulent-particle-effect

A creative visual experiment featuring a dynamic "glitch" distortion effect. Hovering over the image triggers a chaotic, liquid-like turbulence loop that momentarily dissolves the visual into randomized static before smoothly reforming.

## Features

- **Interactive Hover Effects**: The animation activates seamlessly on mouse interaction.
- **Fractal Noise Generation**: Uses randomized seed values to create unique static patterns every time.
- **SVG Displacement Maps**: Maps the generated noise to the image pixels for a realistic distortion effect.
- **Fluid Animation**: Combines CSS scaling with JavaScript-controlled filter attributes to create a "breathing" artifact effect.

## How It Works

The core effect is built using SVG filters (`feTurbulence` and `feDisplacementMap`). 
- **Turbulence** creates a cloud of random noise.
- **Displacement Map** uses that noise to shift the pixels of the image.
- **JavaScript** rapidly updates the "seed" of the noise to make it fizz and pop like TV static, while simultaneously animating the intensity of the distortion.
