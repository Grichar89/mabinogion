# Mabinogion

A medieval Welsh storybook theme for Omarchy, inspired by all four branches of the Mabinogion. Its deep ink greens, aged vellum, tarnished gold, and Annwn blue-grey tie the terminal palette to four original illustrated scenes.

## Install

```sh
omarchy theme install https://github.com/Grichar89/mabinogion
omarchy theme set mabinogion
```

## Included art

- Annwn, the Otherworld
- The court of Branwen
- Pwyll and Rhiannon at the mound
- Blodeuwedd beneath the forest canopy

Each scene is provided as a 2560×1440 PNG wallpaper and a scalable SVG source.

## Animated ASCII screensaver

`screensaver/mabinogion.txt` is a Braille ASCII rendering of the dragon emblem from the book spine. Omarchy's built-in screensaver animates it with its TTE effects. To use it for idle screensaver sessions:

```sh
install -Dm644 screensaver/mabinogion.txt ~/.config/omarchy/branding/screensaver.txt
```

Run `omarchy screensaver` to start it manually. The old still images have been removed.
