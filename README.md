# Adwaita-clean
A clean Gnome-shell theme based on Adwaita, with added transparency and sharper corners.

## Installing:
- Clone the repository into your `~/.themes` folder.
- Select Adwaita-transparent as your shell theme in gnome-tweaks.

## Changing:
This theme uses sass. Do not change the `gnome-shell/gnome-shell.css` file directly. 
Make your changes to the `*.scss` files in the `theme` folder, then run 
`sassc -a themes/gnome-shell.scss gnome-shell/gnome-shell` to update the theme.
