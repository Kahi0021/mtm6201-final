# mtm6201-final
# The Green Plate – Final Project

**Live site:** https://kahi0021.github.io/mtm6201-final/

## Figma Designs
https://www.figma.com/board/4IhGvsoULgvgRSBw79Jw1G/Untitled?node-id=0-1&p=f



## My Process, Challenges & What I Learned

### Process
I started from my Figma mockups for The Green Plate, a vegetarian restaurant concept. 
I built three pages — Home, About Us, and Menu — using Bootstrap 5 as the core framework. 
I used CSS custom properties to override Bootstrap's default colour scheme with my brand 
green and red palette. I chose Caveat for headings to give the brand a handwritten, organic 
feel, paired with Lato for readable body copy. Animate.css was added for entrance animations 
on the hero and section headings.

### Challenges
The biggest challenge was getting the responsive image `<picture>` and `srcset` setup right — 
I had to export two sizes of every image and make sure the correct file was served at each 
breakpoint. Renaming all image files to follow lowercase no-space conventions was also tricky but important for cross-platform compatibility. Styling the Bootstrap hamburger icon to match the brand colour required overriding the default SVG background-image in CSS.

### What I Learned
- How to use CSS variables to systematically theme Bootstrap from a single ":root" block.
- The correct use of <picture>, "srcset", and "media" for responsive images.
- Why semantic HTML, ARIA labels, and keyboard accessibility matter beyond just validators.
- How Schema.org structured data helps search engines understand restaurant content.

