# termite_colors

A simple bash script to change your termite profile on the go.

# How to use

- Place your color profiles in the configuration folder of termite (usually `~/.config/termite/`.
- Place the file `termite_colors` in a folder included in your path (like `/usr/bin`)
- Run `termite_colors` to list the available themes, `termite_colors NAME` to apply the theme `NAME`.
- Enjoy

# How to create color profile

A color profile is simply the `[color]` portion of your configuration file, saved in a file called like
your theme, ending with `.termite` (e.g. `dark.termite`, `light.termite`, `mine.termite`, ...) 
You can generate several configurations with https://terminal.sexy/, save the output of the website as `yourtheme.termite`
and copy it to your configuration folder.

# License

The code on this repository is licensed under the GNU Public License v3, see [LICENSE](LICENSE) for more informations.

