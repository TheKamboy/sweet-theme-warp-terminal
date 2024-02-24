# sweet-theme-warp-terminal

The Sweet theme for Warp Terminal

![screenshot](https://raw.githubusercontent.com/TheKamboy/sweet-theme-warp-terminal/master/assets/Screenshot_20240224_125151.png)

I made this since there was no readily available theme, since Warp just released to Linux.

# How to install

You will need a script from Warp that makes a preview for your theme, WHICH is required to be able to use it (annoying).

The easiest way to the clone their example themes directory to the warp terminal themes directory.
[More info on that here.](https://docs.warp.dev/appearance/custom-themes)

Clone the repository: `git clone https://github.com/TheKamboy/sweet-theme-warp-terminal ~/sweet-theme-warp-terminal`

Make a folder in the themes directory:

- For Linux: `mkdir -p ${XDG_DATA_HOME:-$HOME/.local/share}/warp-terminal/themes/Sweet`
- For MacOS: `mkdir -p ~/.warp/themes/Sweet`

Move Sweet.yaml into the folder:

- For Linux: `mv ~/sweet-theme-warp-terminal/Sweet.yaml ${XDG_DATA_HOME:-$HOME/.local/share}/warp-terminal/themes/Sweet/Sweet.yaml`
- For MacOS: `mv ~/sweet-theme-warp-terminal/Sweet.yaml ~/.warp/themes/Sweet/Sweet.yaml`

Make sure to enter the theme directory now.

Now, run the generation script:

- For Linux: `python3 ./scripts/gen_theme_previews.py Sweet`

It should appear now!
