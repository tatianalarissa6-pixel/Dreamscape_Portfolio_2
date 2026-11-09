# Dreamscape — Larissa De Souza

Interactive interior design portfolio, hosted on GitHub Pages. No server, no paid services.

## The journey
Sketch intro → the mind (void) → **World 1: Ledger Residence** → glass doors → **World 2: Live/Work Studio** → vase →
**World 3: HALO** → flames → **The Gear Room** (4 gears) → page flip → **The Professional** (Continue after 30 s) →
lights out (5 s) → green exit sign → **Thank you**.
**Express** (the button on the first screen) shows the portfolio PDF one page at a time.

## Folder structure
```
index.html                      the whole site
assets/
  professional/01-about-me.png
  w3-halo/02-halo-board-concept.png
  w3-halo/03-halo-board-technical.png
  w3-halo/04-halo-background-rooftop.png
  w2-live-work/05-kitchen-east-elevation.png
  w2-live-work/06-kitchen-south-elevation.png
  w2-live-work/07-studio-elevation.png
  w2-live-work/08-railing-plan-elevation.png
  w2-live-work/09-floor-plan.png
  w2-live-work/10-background-watercolour.png
  w1-ledger/11-background-living-room.png
  w1-ledger/12-kitchen-render.png
  w1-ledger/13-rear-exterior.png
  w1-ledger/14-front-exterior.png
  w1-ledger/15-south-section.png
  w1-ledger/16-axonometric-palette.png
  w1-ledger/17-preliminary-floor-plan.png
  w1-ledger/18-bubble-diagram.png
  w1-ledger/19-concept-sketch-high-ceilings.png
  w1-ledger/20-concept-sketch-seating.png
  express/page-01.jpg … page-18.jpg   (Express mode: the portfolio PDF pages)
```
The number at the start of each file name is the image number (1–20).

## Replacing the files on GitHub
1. Unzip the download on your computer.
2. Open your repository on GitHub. If it still has the old `assets/w1`, `assets/w2` or `assets/w3` folders, you can leave them (they are no longer used) or delete them.
3. Click **Add file → Upload files**. Drag in everything *inside* the unzipped folder (`index.html`, `README.md` and the `assets` folder). Files with the same name are replaced automatically.
4. Click **Commit changes**. The live site updates within a minute or two (refresh with Ctrl+F5 if you still see the old version).

## Changing things later
- **Board order, titles and captions:** in `index.html`, search for `boards: [` — each world lists its boards in order.
- **Swapping an image:** upload a new file with the *exact same name* (lower-case, same folder) and it replaces the old one.
- **Gear room text:** search for `const PROCESS`.
- **Testing tip:** add `?fast` to the end of the site address to skip the 30-second and 5-second waits.
