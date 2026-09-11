# Photography

Drop approved photographs of Irini here, named after the slot they fill.
Nothing else needs to change — the pages pick them up at build time and the
stand-in film stills step aside.

Until then each slot shows a still from one of her performances, which plays
when clicked. Real photography will look better, but nothing is ever empty.

| File name                | Where it appears        | Shape          |
| ------------------------ | ----------------------- | -------------- |
| `hero.jpg`               | Home page, full bleed   | any; 3:2 or 4:5 both work |
| `portrait.jpg`           | About                   | 4:5 portrait   |
| `press-primary.jpg`      | Press kit               | 4:5 portrait   |
| `press-secondary.jpg`    | Press kit               | 3:2 landscape  |
| `partnerships.jpg`       | Partnerships            | 4:5 portrait   |

`.jpg`, `.jpeg`, `.png`, `.webp` and `.avif` all work. Supply the largest
version available — around 2400px on the long edge is ample. Next.js generates
the responsive AVIF and WebP variants at build time.

Update the alt text in `src/lib/photography.ts` to describe the actual
photograph once one is in place.

Only use photography that is cleared for this use, with the photographer
credited where required.
