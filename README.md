# GnoMenu for GNOME 51

[GnoMenu](https://github.com/nilsonpmjr/GnoMenu) 0.1.0 alpha 9 (a global menu in the top bar,
application name first), enabled for GNOME Shell 51.

GnoMenu itself declares GNOME 50 only. Its code uses no API that changed in GNOME 51, so the only
change here is the supported version in `metadata.json`. Tested on GNOME Shell 51.1: Files shows
its full menus, other apps their exported menus or a partial menu, and the extension disables and
re-enables cleanly.

## Installation

```bash
cp -r . ~/.local/share/gnome-shell/extensions/gnomenu@nilsonpmjr.github.io
```

Log out and back in, then enable it in Extensions.

## License

GPL-3.0-or-later, like GnoMenu (see `COPYING`).
