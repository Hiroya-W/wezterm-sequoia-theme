# wezterm-sequoia-theme

Sequoia theme for Wezterm.

<img width="768" alt="wezterm screenshot" src="https://user-images.githubusercontent.com/43127622/185772845-30d29765-04dd-4df0-b192-c40aa96ea51e.png">

## Sequoia-Theme

Sequoia theme created by [Michael Andreuzza](https://github.com/michael-andreuzza).

- [Official Website/Color Palettes](https://sequoiatheme.com/)
- [Sequoia for iTerm](https://github.com/Sequoia-Theme/iTerm)

This Sequoia theme for wezterm created and maintained by [Hiroya-W](https://github.com/Hiroya-W)

## Installation for POSIX

Place `sequoia-moonlight.toml` and `sequoia-monochrome.toml` in a directory named `$HOME/.config/wezterm/colors`.

Define `color_scheme_dirs` and `color-scheme` in `wezterm.lua`.

```lua
-- wezterm.lua
return {
    color_scheme_dirs = { "$HOME/.config/wezterm/colors/" },
    color_scheme = "sequoia-moonlight",
}
```

For a detailed description of custom schemas, please refer to the [wezterm documentation](https://wezfurlong.org/wezterm/config/appearance.html#defining-a-color-scheme-in-a-separate-file).

## Installation with nightly build

If you are using the nightly version, the Sequoia theme is included in wezterm. You can use it in the following:

```lua
return {
    color_scheme = "Sequoia Moonlight",
}
```

Please check the color schemes documentation for details.

- [Color Schemes#sequoia-monochrome](https://wezfurlong.org/wezterm/colorschemes/s/index.html#sequoia-monochrome)
- [Color Schemes#sequoia-moonlight](https://wezfurlong.org/wezterm/colorschemes/s/index.html#sequoia-moonlight)

## Author

[Hiroya-W](https://github.com/Hiroya-W)
