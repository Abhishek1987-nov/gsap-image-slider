# GSAP Image Slider

A simple image slider built with plain HTML, CSS and [GSAP](https://gsap.com/). Slides animate sideways, and each caption fades in after the slide settles.

**Live demo:** https://abhishek1987-nov.github.io/gsap-image-slider/

## Features

- Previous and next buttons
- Clickable dots
- Left and right arrow key support
- Autoplay every 4 seconds
- Respects the "reduce motion" system setting

## Run locally

1. Download or clone the repository:
   ```bash
   git clone https://github.com/Abhishek1987-nov/gsap-image-slider.git
   ```
2. Open `index.html` in your browser.

You need an internet connection because GSAP and the sample images load from the web.

## Customize

- **Images and captions:** edit the `.slide` blocks in `index.html`.
- **Autoplay speed:** change `4000` (milliseconds) in the `restartAutoplay` function.
- **Animation speed:** change the `0.8` duration in the `goTo` function.

## Built with

- HTML and CSS
- [GSAP 3](https://gsap.com/) (loaded from cdnjs)
- Sample photos from [Lorem Picsum](https://picsum.photos/)
