# Blender Application Templates
[![License](https://img.shields.io/github/license/Drakmyth/blender-app-templates)](https://github.com/Drakmyth/blender-app-templates/blob/master/LICENSE.md)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/Drakmyth/blender-app-templates)

Application Templates for Blender allowing quick startup configuration for different use cases.

> :warning: **Note:** These templates were created using Blender 3.1. Except where otherwise noted, they will likely work on any 3.x version.

## Installation

Pre-packaged versions of these templates are available from the [Releases](https://github.com/Drakmyth/blender-app-templates/releases) page. The templates can also be installed manually. Optionally, the built-in `General` template can be configured to refer instead to one of these templates. Instructions for doing that are included below.

### Packaged Install

1. Download the latest version of the desired template from the Releases page.
1. Open Blender
1. From the top menu select: (Blender icon) > Install Application Template...
1. Select the downloaded application template zip file

### Manual Install

1. Navigate to your Blender `USER` directory (See the [official documentation](https://docs.blender.org/manual/en/latest/advanced/blender_directory_layout.html#blender-directory-layout) for details)
1. Navigate to the `scripts/startup/bl_app_templates_user` directory
    1. Create this directory if it doesn't exist
1. Create a folder with the name of the template you want to install
    1. The name of this directory determines the name you will see on the startup screen
1. Download the files for the desired template into the newly created directory

### Install as `General`

1. Navigate to your Blender `USER` directory (See the [official documentation](https://docs.blender.org/manual/en/latest/advanced/blender_directory_layout.html#blender-directory-layout) for details)
1. Navigate to the `config` directory
1. Download the files for the desired template directly into this directory

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

## Issues

If you have identified a bug that seems to come from one of the scripts bundled with one of these templates, please report it here. Make sure to follow these guidelines to ensure your report isn't closed as "Invalid":

* Make sure you are using the latest version of the template. Old versions of templates are unsupported.
* Make sure you are using the latest version of Blender. Templates will not be backported to older versions.
* Search to see if someone else has already reported the bug. Duplicate reports just slow down getting things fixed.
* Include steps to reproduce the issue in your report. Screenshots or videos may also prove helpful.

## Contributions

These templates are open source! That means if you have an idea for how to improve them in some way, you can make those changes and submit a pull request! Because it is difficult to compare Blender files against each other, make sure to describe all of the changes you made and how they improve the template. If your changes require addons that do not come bundled with Blender, you should also provide a link to where the addons can be acquired.

## License

These templates are licensed under the GNU General Public License v3.0 or later (GPL-3.0-or-later). See [LICENSE](./LICENSE.md) for details.
