> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

# mof_svg_char

A cute, fluffy character animation created with SVG and vanilla JavaScript. This project generates the animation dynamically in the browser, with no external libraries.

## Demo

View the live demo: **[https://code4fukui.github.io/mof_svg_char/](https://code4fukui.github.io/mof_svg_char/)**

## Features

The animation is procedurally generated frame-by-frame with the following dynamic effects:

- **Floating Motion:** The character gently floats up and down (±15px).
- **Squeeze Animation:** A subtle "squish and stretch" effect (±10% scale variation).
- **Blinking Eyes:** The character blinks periodically on a 15-frame cycle.
- **Fluffy Fur Wave:** The outer "fluff" circles pulsate and wave (±3px radius change).
- **Sparkling Particles:** Five decorative particles with animated opacity orbit the character.

## Usage

Simply open `index.html` in any modern web browser. The animation is rendered inside an `<svg>` element and updated every 50ms using `setInterval`.

## Credits

This project is a JavaScript implementation based on the original Python program by Tadataka Takahashi, detailed in this Qiita article:

- [SVGアニメーションで作る！かわいいもふもふキャラクターGIF #Python - Qiita](https://qiita.com/Tadataka_Takahashi/items/d91add8371d971f2e6ce)

## License

MIT License — see [LICENSE](LICENSE).