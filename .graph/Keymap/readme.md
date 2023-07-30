# Keymap
- https://wiki.archlinux.org/title/sway#Keymap
By default, sway starts with the US QWERTY keymap. To configure per-input:

```
~/.config/sway/config
input * {
    xkb_layout "us,de,ru"
    xkb_variant "colemak,,typewriter"
    xkb_options "grp:win_space_toggle"
}

input <identifier> xkb_model "pc101"
```