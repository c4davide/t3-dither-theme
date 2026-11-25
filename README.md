# T3 Dither

A dark theme for [T3 Code](https://github.com/pingdotgg/t3code) drawn in dots.

- On an empty thread, a dotted night sky sits behind the prompt.
- When you send the first message, the view slides down to a dotted landscape where a bear walks along the bottom of the chat.
- The header shows the word "orso" in dots, with a dotted wave while the agent is working.
- The strip under the composer fades into the background instead of cutting the dots with a hard edge.
- Includes a light variant. With reduced motion turned on, the animations are off.

Everything is in one file, `t3-dither.json`: the color palette plus CSS with inline SVG images. It loads no external files.

## Install

Requires T3 Code v0.1.12 or later.

Download `t3-dither.json`, then either:

- run this in the folder where you saved it, which installs the theme and switches to it:

  ```sh
  npx t3 theme set ./t3-dither.json
  ```

- or copy it into your T3 themes folder, then pick **T3 Dither** in Settings → Appearance:
  - macOS / Linux: `~/.t3/userdata/themes/`
  - Windows: `%USERPROFILE%\.t3\userdata\themes\`

Themes apply to the web and desktop apps. The mobile app does not use them.

## License

MIT
