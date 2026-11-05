# Ghostty Fleury theme

Ghostty ports of Ryan Fleury's [4coder theme](https://github.com/4coder-archive/4coder_fleury/blob/master/theme-fleury.4coder).
Dark, with gold and brown text.

| Theme | Background | Notes |
| --- | --- | --- |
| `fleury` | `#050505` | Softened for long sessions. Near black. |
| `fleury-warm` | `#151311` | Same as `fleury`, with a lighter warm black. |
| `fleury-4coder` | `#020202` | Faithful 4coder colors, no changes. |

## What the softened themes change

- The background is a little lighter than 4coder, which reduces halation.
- The foreground is `#c4a279`, between the faithful and the earlier softened value.
- The neon greens, cyans, and blues have 45 to 60 percent of their saturation.
- Dark red has a contrast ratio of at least 4.5:1.
- Cyan is closer to teal, so it reads apart from green.
- Bold text is gold (`bold-color`).
- Selection is the cool slate of the 4coder highlight color.

Palette slot 0 stays dark on purpose. Some tools, such as Claude Code with the dark-ansi theme, paint bands with bright black.

## Install

Copy the files into the Ghostty themes folder:

```sh
mkdir -p ~/.config/ghostty/themes
cp themes/* ~/.config/ghostty/themes/
```

Then set the theme in your Ghostty config:

```
theme = fleury
```

## Credit

The colors come from Ryan Fleury's 4coder theme. A VS Code port is in [fleury-vscode-theme](https://github.com/jonesnc/fleury-vscode-theme).

## License

MIT. See `LICENSE`.
