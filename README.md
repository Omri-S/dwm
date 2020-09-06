# Omri's build of dwm (forked)

## Patches and features

- New layouts: bstack, fibonacci, deck, centered master and more. All bound to keys `super+(shift+)t/y/u/i`.
- True fullscreen (`super+f`) and prevents focus shifting.
- Windows can be made sticky (`super+s`).
- stacker: Move windows up the stack manually (`super-K/J`).
- shiftview: Cycle through tags (`super+g/;`).
- vanitygaps: Gaps allowed across all layouts.
- swallow patch: if a program run from a terminal would make it inoperable, it temporarily takes its place to save space.

## Please install `ttf-font-awesome`!

This build of dwm does not block color emoji in the status/info bar, so you must install [libxft-bgra](https://www.archlinux.org/packages/community/any/ttf-font-awesome/) from the AUR, which fixes a libxft color emoji rendering problem, otherwise dwm will crash upon trying to render one. Hopefully this fix will be in all libxft soon enough.
