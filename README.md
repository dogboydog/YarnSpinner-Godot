# YarnSpinner-Godot
WIP non functional port of [YarnSpinner-Unity](https://github.com/YarnSpinnerTool/YarnSpinner-Unity) integration to the Godot Mono engine v3.5


| ![](./addons/YarnSpinnerGodot/Editor/Icons/YarnSpinnerLogo.png) | ![](./Godot_icon.png) |
|-----------------------------------------------------------------|-----------------------|

The YarnSpinner logo was made by [Cecile Richard](https://www.cecile-richard.com/).
Godot logo by Andrea CalabrĂ³

## Demo

Clone this project and open it as a godot project. Build the project solution, and then go to project settings,
and enable this YarnSpinner plugin

## Installation

Copy addons/ to your project. Add the package references from [this project's csproj file](./YarnSpinner-Godot.csproj) to your Godot Mono project's `.csproj` file.

Build your Godot project's solution, and then enable the plugin in the project settings

Working:
* Create a Yarn Project, Yarn Script, or Yarn Localization through the Tools > YarnSpinner menu
* Manage your Yarn Project with a custom inspector which provides buttons similar to the YarnSpinner-Unity inspector
* Yarn scripts will re-import on change, triggering a compilation of all yarn scripts in the associated project
* Storing a compiled yarn program, a list of errors, and string tables.
* Dialogue runners, commands, and functions are working
* Example line view and option view 

TODO:
* Generate Godot localization CSV files from yarn Localization resources
* Support localized resources in Localization
* Bug fixes

### Thanks

Thanks to the YarnSpinner team for answering questions as this plugin was developed, and to KXI and fmoo for giving feedback.