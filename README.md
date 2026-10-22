# Paint Mixing Bench

A single-page web app for experimenting with artist paint mixes and checking them against colours in a reference photo.

Use it on the web: https://jlauko.github.io/paint-mixing-bench/

## Features

- **Palette builder**: choose from about 40 common artist paints grouped by family, start from a preset (Studio, Zorn, Primary triad, Split primary, Landscape earths), or add your own paint colours.
- **Pigment-style mixing**: add parts of each paint and see the result. Mixing is simulated with [Mixbox](https://scrtwpns.com/mixbox), so blue and yellow make green rather than grey.
- **Photo comparison**: upload, drop or paste a photo, then click it to pick a target colour. The app shows the ΔE 2000 colour difference, advice on value, intensity and hue, a value (greyscale) check, and a suggested next step.
- **Recipe finder**: searches combinations of up to three paints from your palette for the closest match to the target.
- **Colour charts per painting**: name and save each colour you mix, with its recipe and the photo colour it was matched to. You can copy a chart as text or download it.

## Running it

Visit the GitHub Pages site above, or open `index.html` in a modern browser. It loads Mixbox and Google Fonts from CDNs, so it needs an internet connection.

On GitHub Pages or a local copy, colour charts are saved in that browser's local storage, so they stay on that device and browser. (When the page runs as a Claude artifact with a signed-in viewer, charts are saved to the Claude account instead.)

## Licensing

The Mixbox library is © Secret Weapons, licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/), which allows non-commercial use only. Paint swatch colours are approximations of typical masstones; real tubes vary by brand.
