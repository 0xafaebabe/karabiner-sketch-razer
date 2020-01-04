## Karabiner Elements keybindings for Sketch.app and Razer Tartarus
This is a pretty niche thing, but I bought a Razer Tartarus (Pro) gaming keypad specifically for mapping shortcuts to design programs like Sketch, Axure, etc. to increase my speed. Unfortunately, Razer's config program (Synapse 3) is only for Windows at this point—but Karabiner Elements for macos to the rescue!

### Contents
This repository is pretty simple. It contains:
* A ruleset for importing into Karabiner
* A printable key reference
* The Sketch source file for the reference in case you want to make layout changes.

### Notes
* Round to Pixel: Sketch does not have a built-in shortcut for this. In order for this to work, you'll need to go to Preferences -> Keyboard -> Shortcuts and add an application specific shortcut for Sketch to map Control-Command-R to the Round to Nearest Pixel menu item.
* The default Razer d-pad seems weird to me: it is rotated counter-clockwise from what I'd expect. The button pointing up is actually left, the button pointing forward is up, etc. I've remapped this so up is up, down is down, pointing forward is right, and point back towards you is left.

### TODO
* I have no use for the scroll wheel to scroll; I just want it to zoom by default. However I don't think it's possible (yet?) to automatically add a modifier to mouse events in Karabiner.
* I might swap the Escape/Delete and Tab/Select-All bindings, idk.
