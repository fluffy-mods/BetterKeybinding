# Better Keybinding
A simple keybinding container.
- allows modifier keys, e.g.: <kbd>Alt</kbd> + <kbd>Ctrl</kbd> + <kbd>S</kbd> 
- allows mouse input, e.g.: <kbd>LMB</kbd>, <kbd>RMB</kbd>, <kbd>Shift</kbd> + <kbd>ScrollUp</kbd>
- includes a simple config widget.

# How to use
 - Grab the `.dll` from the `obj` folder, or build it yourself. 
 - Reference the dll: `using BetterKeybindings`
 - Instantiate a new `KeyBind`
    - set a label
    - set a default key/button/direction
    - set modifiers (optional)
 - `KeyBind.Draw( someRect )` draws a config widget
 - Don't forget to Scribe the result!

