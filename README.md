# Claude Opus 5.5 · 100 HTML Files

A collection of **100 self-contained HTML pages** made with **Claude Opus 5.5**: generative art, physics
simulations, playable instruments and games, editorial layouts, dashboards and small tools. Every page is a
single HTML file with all CSS and JavaScript inline (no external fonts, images, libraries or network
requests), and ships with the exact prompt that produced it.

**Browse the gallery:** https://miaai-lab.github.io/Claude-Opus-5.5-100-HTML-Files/

## Structure

```
├── index.html     ← gallery index (screenshot, description and prompt for every page)
├── thumbs/        ← first-frame screenshots, 001–100 (1200×750 JPEG)
├── NNN-*.html     ← the 100 standalone pages
└── NNN-*.txt      ← exact prompt, description, visual techniques and interaction model
```

## Gallery features

- One card per page: screenshot, number, title, description
- **Open** loads the page in a new tab
- **Prompt** expands the exact prompt and links its `.txt` file
- Search across numbers, titles, descriptions and prompt text, with a live result count (press `/`)
- The shared requirements given with every prompt are listed once at the top

## How it was made

Each page had its own creative brief, and each was written individually as a hand-authored file, with no
templates or generators. The work was split across 20 parallel Claude Opus 5.5 agents, five pages each. Every
page was then rendered in headless Chromium at 1440×900 and at 390×844 (phone) and reviewed from its
screenshots before it was accepted.

The final automated pass over all 100 pages checked:

- no JavaScript exceptions or console errors on load or on a basic interaction
- no network requests beyond the page itself
- no horizontal overflow on a 390px phone screen
- structurally valid HTML5: balanced tags, unique ids, correct nesting in buttons, links and lists, labels
  pointing at real controls (a stdlib-based structural checker, not the W3C Nu validator)
- each `.txt` carries its prompt verbatim

## The pages

Among others: an aurora glassmorphism landing page, a cyberpunk night market, a Swiss poster machine, a brass
orrery, a stable-fluids sumi ink study, a neo-brutalist zine, a neumorphic synthesizer, a lighthouse long read,
a knitted Game of Life, a Mandelbrot and Julia explorer, a full legal chess board, a periodic table, a
Jansen-linkage walking machine, a harmonograph, an infinite Droste room and a final organic wave lab.
Fictional brands, people and data are marked as fictional on the pages.
