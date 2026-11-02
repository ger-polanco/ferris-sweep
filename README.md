# Ferris Sweep keymap

QMK keymap for the Ferris Sweep (34 keys, `LAYOUT_split_3x5_2`).
Layers: `BASE`, `NUM`, `SYM`, `NAV`. Thumbs: Tab/NUM, Space/NAV, Enter/SYM. Home-row mods tuned in `config.h`.

## Build & flash

```sh
qmk setup                                   # once
mkdir -p ~/qmk_firmware/keyboards/ferris/keymaps/geri
cp keymap.c config.h rules.mk ~/qmk_firmware/keyboards/ferris/keymaps/geri/
qmk flash -kb ferris/sweep -km geri         # repeat for each half if needed
```
