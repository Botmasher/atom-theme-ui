# Demo Atom UI Theme

A simple UI theme demonstrating how to extend interface theming on Atom. The development of this demo theme follows the steps in the [Atom Flight Manual](https://flight-manual.atom.io/hacking-atom/sections/creating-a-theme/#creating-a-ui-theme).

![Demo UI Theme screenshot]()

## Reproducing this theme

The steps for creating a UI theme are given in the manual linked above. Here are the modified steps I took to create this demo:

1. download a copy of the [template](https://github.com/atom-community/ui-theme-template)
2. move the template to the local Atom package directory
3. run Atom in dev mode from the local theme directory
  - command: `atom --dev .`
  - dev mode window has a little icon in the bottom left
4. change theme name in `package.json`
  - again, be sure the name ends in `-ui`
5. run `apm link --dev`
  - this symlinks repo to `~/.atom/dev/packages`
  - now you can always load atom normally to force Atom back to default theme
6. reload atom
7. enable the theme in Settings View
8. change the UI theme
  - test changing color and size variable values for base styles
