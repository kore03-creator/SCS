# SCS Lab research photo refresh (2026-10-14)

## Selection and layout
- **Hero**: `assets/hero-experiment.jpg`, selected from the second user-provided high-resolution large-scale structural test photograph.
- **Research image set**: `assets/research-sprite.jpg`, composed of nine separately supplied research photographs and figures. Each displayed region is a 540 × 330 px tile, not an enlarged preview thumbnail.
- The original director portrait `assets/professor-lee.jpg` is unchanged.

## Photo panels (3 × 3 image)
The nine panels in the composite are indexed from 0 to 8:

| Index | Contents | Placement |
|---|---|---|
| 0 | Steel member and connection test | Home: Steel Structures; Research: Steel |
| 1 | Large-scale beam test | Home: Composite Structures; Research: Composite |
| 2 | Damaged/protected structural specimen | Home: Fire & Resilience; Research: Fire |
| 3 | Masonry specimen with observation markers | Research: Vision-based Monitoring |
| 4 | Frame analysis model | Research: Seismic Performance |
| 5 | Test apparatus / beam specimen | Home + Research gallery |
| 6 | Structural member test setup | Research gallery |
| 7 | Finite-element stress contour visualization | Research gallery |
| 8 | Another beam experimental setup | Home + Research gallery |

## Changed repository files
- `index.html`: hero photo; main 3 research cards; 3 featured gallery panels
- `research.html`: five focus-area images; 6 gallery panels; accurate general captions
- `assets/styles.css`: image composition and responsive layouts
- `assets/hero-experiment.jpg`: new, optimized hero JPEG
- `assets/research-sprite.jpg`: new, optimized nine-photo composite JPEG
- `PHOTO_UPDATE.md`: this guide

## Safeguards
- Before editing, the `main` branch was backed up at `backup-before-2026-10-14-photo-refresh`.
- Other pages (Professor, Publications, Members, Contact), their bibliography and lab contact data were not overwritten.
- Research photos represent the laboratory's research directions. Publication-to-photo provenance and detailed test conditions should be confirmed before asserting exact experiment IDs.
