# DnDGMod: A Dungeons & Degenerate Gamblers Modloader
> ⚠️ Mods using this software are able to inject code into your *Dungeons & Degenerate Gamblers* executable!
> The DnDGMod team is **not** responsible for the contents of any mod not officially endorsed. Stay safe out there, 
> gamblers!
> ---
> 🏴‍☠️ The DnDGMod team does **not** condone piracy! Please **do not** distrubute compiled *Dungeons and 
> Degenerate Gamblers* executables (modded or unmodded) or decompiled source code. Thank you, gamblers!

## Installation
DnDGMod is available from [PyPI](https://pypi.org/project/dndgmod/) (Currently Windows-Only):
```
py -m pip install dndgmod
```

## Quickstart
### Initialization
Run this command to set up DnDGMod's `AppData` directory, install dependencies, and decompile your (locally stored) 
*Dungeons and Degenerate Gamblers* executable using [Godot RE Tools](https://github.com/bruvzg/gdsdecomp):
```
dndgmod init
```

### Using an Existing Mod
1. Open the directory where mods are stored:
      ```
      dndgmod open
      ```
2. Drag the mod's `.dndg` file into the opened `AppData` directory.
(NOTE TO FUTURE SETH: .dndg is just .zip with a different name)
3. [Recompile *Dungeons & Degenerate Gamblers*](#recompile-dungeons-degenerate-gamblers)

### Creating a New Mod
1. Create a mod skeleton:
      ```
      dndgmod create
      ```
2. Edit the mod files... (NOTE TO FUTURE SETH: ADD DOCS FOR THIS PART)
3. [Recompile *Dungeons & Degenerate Gamblers*](#recompile-dungeons-degenerate-gamblers)

### Recompile *Dungeons & Degenerate Gamblers*
Run this command to recompile *Dungeons & Degenerate Gamblers* using Godot (which is automatically installed during 
[Initialization](#initialization)):
```
dndgmod compile
```

### Credits
DnDGMod was created and developed by [TotallyNotSeth](https://github.com/TotallyNotSethP)

Playtesting provided by [Rando](https://github.com/rando-idiot), [Maple](https://github.com/Maple29234), and Monkeys

This project would not have been possible without the [Godot Engine](https://github.com/godotengine/godot/tree/master)
and its many contributors, as well as [Godot RE Tools](https://github.com/bruvzg/gdsdecomp/tree/master) by 
[bruvzg](https://github.com/bruvzg)