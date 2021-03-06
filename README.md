## Karabiner Elements keybindings for Sketch.app and Razer Tartarus
This is a pretty niche thing, but I bought a Razer Tartarus (Pro) gaming keypad specifically for mapping shortcuts to design programs like Sketch, Axure, etc. to increase my speed. Unfortunately, Razer's config program (Synapse 3) is only for Windows at this point—but Karabiner Elements for macos to the rescue!

Once you've [installed Karabiner](https://pqrs.org/osx/karabiner/), copy and paste this link  (that Github markdown does not like) into your browser:

`karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/0xafaebabe/karabiner-sketch-razer/master/razersketch.json`

Alternatively, you can download the json file and copy it to ~/.config/karabiner/assets/complex_modifications.

After installing the keybindings, simply open Karabiner prefs, go to complex modifications and hit "add rule." You can then pick and choose particular bindings, or just enable all! 

Happy Sketching :) 

### Contents
This repository is pretty simple. It contains:
* A ruleset for importing into Karabiner
* A printable key reference
* The Sketch source file for the reference in case you want to make layout changes.

![Image of key layout](https://raw.githubusercontent.com/0xafaebabe/karabiner-sketch-razer/master/Sketch-Razer%20Keybindings%402x.png)

### Notes
* Round to Pixel: Sketch does not have a built-in shortcut for this. In order for this to work, you'll need to go to Preferences -> Keyboard -> Shortcuts and add an application specific shortcut for Sketch to map Control-Command-R to the Round to Nearest Pixel menu item.
* The scroll wheel button/click is mapped to command. This serves two purposes:
  1. Hold and scroll to zoom
  2. Sometimes the 20 key mapped to command is a bit of a reach, and this can save your fingers a bit
