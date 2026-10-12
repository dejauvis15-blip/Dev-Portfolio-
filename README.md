# jauvis dozier — dev portfolio

My developer portfolio: a minimal, monospace one-pager with falling snow along the bottom.
It links to my UX design portfolio at [jauvis-dozier-portfolio.vercel.app](https://jauvis-dozier-portfolio.vercel.app/).

## Built with

- Plain **HTML, CSS and JavaScript**, with no framework or build step
- **Fira Code** for the name and **JetBrains Mono** for everything else
- **`<canvas>`** for the snow

## Features

- **Falling snow:** flakes in three depth layers, blown by gusting wind, settling onto a drift that builds up where they land
- **Reduced motion:** the animation stays still for visitors who ask their device to reduce motion

## Palette

| Color        | Hex       | Used for                     |
| ------------ | --------- | ---------------------------- |
| Smoky Black  | `#11120D` | Background                   |
| Olive Drab   | `#565449` | Hover states, dividers       |
| Bone         | `#D8CFBC` | Headings, secondary text     |
| Floral White | `#FFFBF4` | Main text, snow              |

All four are CSS variables at the top of `styles.css`, and `main.js` reads the snow colors from them.

## Files

| File         | What it does                                  |
| ------------ | --------------------------------------------- |
| `index.html` | Page content: intro, experience, links        |
| `styles.css` | Layout, colors and type                       |
| `main.js`    | Snow animation                                |
| `brook.webp` | Animated avatar (transparent)                |
| `favicon.gif` | Animated Brook browser-tab icon             |
| `apple-touch-icon.png` | Home-screen icon for phones        |
| `tombras.png`, `utk.png` | Company logos in the experience list |

## Run it locally

Open `index.html` in a browser, or use the VS Code **Live Server** extension so the page reloads on save.

## Deploy

Import this repo on [Vercel](https://vercel.com/new). No settings are needed.
