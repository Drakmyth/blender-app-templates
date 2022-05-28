## Template Descriptions
### [Default](./Default/)

An alternative to the default Blender startup scene. These changes are also applied to all of the other templates in this repository unless otherwise specified.

#### Changes
- Enable viewport `Show Cavity` option
- Increase `Undo Steps` to 256 (up from 32)
- Enable `Object: Bool Tool` addon
- Open `Context` Panel

### [3D Printing](./3D%20Printing/)

> :warning: Requires Addon: [CAD Sketcher](https://github.com/hlorus/CAD_Sketcher)

Facilitates CAD sketching and optimized for STL export to 3D printing slicing software.

#### Changes
- Change scene `Unit Scale` to 0.001
- Change scene `Length` to millimeters
- Increase viewport `Clip End` to 100000 millimeters (up from 1000)
- Change viewport overlay `Scale` to 0.001
- Enable `3D View: CAD Sketcher` addon
- Change CAD Sketcher `Entity Default` color to cyan
- Remove all workspaces except `Layout`
- Rename `Layout` workspace to `Modeling`
