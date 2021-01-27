# blender-extended-industry-keymap
An improved version of blender industry standard keymap that adds many missing shorts cuts

Blender's initial [Industry Compatible Keymap](https://docs.blender.org/manual/en/latest/interface/keymap/industry_compatible.html) is a great start but lacks many short cuts that are important for my work with blender. After during this repeatedly on different machines, I decided it's time for a repository.

Tested with Blender v2.91



## Changes

### Disabled short cuts

After repeated mistakes I decided to change or remove the following short cuts

- ~~S, ALT+S, SHIT+ALT+S~~ Insert keyframing
- ~~SHIFT+W, SHIT+E, SHIFT+R~~ Keyframe Move, rotate scale
- Q - always switches to rect select does not cycle though selection modes



### Navigation

- **ALT+F** - Fly navigation
- **SHIFT+ALT+F** - Walk navigation
- **F** - Focus selection
- **SHIFT+F1** - Snap to view axis 

### Editing

- **SHIFT+G** - move selection blender style (with MMB for axis constrain)
- **G** - Repeat
- **SHIFT+1** - Toggle edit origin mode
- **SHIFT-I** - Toggle local view
- **SHIFT-Q** - always switches to circle select
- **ALT-Q** - always switches to lasso select

### Mesh Editing

- **F** - Make face (Like classic Blender)
- **I** - Inset faces (Like classic Blender)
- **SHIFT+E** - Extrude face (Like classic Blender)
- **ALT+E** - Extrude vertex (Like classic Blender)
- **ALT+C** - Edge Loop
- **SHIFT+C** - Edge slide
- **CTRL+B** - Bevel