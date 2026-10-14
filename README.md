# Spotigruv

A [Gruvbox](https://github.com/morhetz/gruvbox) dark theme for [Spotifast](https://github.com/crmne/spotifast).

## Install

Copy the theme into your Spotifast themes folder:

```sh
cp "Gruvbox Dark.json" ~/.config/spotifast/themes/
```

Restart Spotifast, then pick **Gruvbox Dark** in the theme settings.

Tip: turn off **accent from album art** if you want the Gruvbox orange accent to stay put.

## Palette

| Role            | Colour    | Gruvbox name |
| --------------- | --------- | ------------ |
| window          | `#282828` | bg0          |
| panel           | `#32302f` | bg0_s        |
| surface         | `#3c3836` | bg1          |
| surface_hover   | `#45403d` | bg1/bg2      |
| surface_active  | `#504945` | bg2          |
| outline         | `#504945` | bg2          |
| text            | `#ebdbb2` | fg1          |
| secondary       | `#a89984` | fg4          |
| dim             | `#928374` | gray         |
| accent          | `#fe8019` | orange       |
| accent_hover    | `#fe9a4a` | orange (lighter) |
| on_accent       | `#282828` | bg0          |
| danger          | `#fb4934` | red          |
| warning         | `#fabd2f` | yellow       |

Want a different accent? Swap `accent` for aqua `#8ec07c`, green `#b8bb26` or yellow `#fabd2f`, and set `accent_hover` to a slightly lighter shade.
