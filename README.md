# wezterm-sequoia-moonlight

Sequoia-Moonlight theme for Wezterm.

<img width="768" alt="wezterm screenshot" src="https://user-images.githubusercontent.com/43127622/185772845-30d29765-04dd-4df0-b192-c40aa96ea51e.png">

## Sequoia-Theme

Sequoia theme created by [Michael Andreuzza](https://github.com/michael-andreuzza).

- [Official Website/Color Palettes](https://sequoiatheme.com/)
- [Sequoia for iTerm](https://github.com/Sequoia-Theme/iTerm)

## Installation for POSIX

Place `sequoia-moonlight.toml` in a directory named `$HOME/.config/wezterm/colors`.

Define `color_scheme_dirs` and `color-scheme` in `wezterm.lua`.

```lua
-- wezterm.lua
return {
    color_scheme_dirs = { "$HOME/.config/wezterm/colors/" },
    color_scheme = "sequoia-moonlight",
}
```

For a detailed description of custom schemas, please refer to the [wezterm documentation](https://wezfurlong.org/wezterm/config/appearance.html#defining-a-color-scheme-in-a-separate-file).
