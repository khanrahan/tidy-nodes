# Tidy Nodes

Plugin for [Autodesk Flame software](http://www.autodesk.com/products/flame).

Align, distribute, tidy (align & distribute), or scale nodes in the Batch or Action schematic.

![screen capture demonstration](tidy_nodes_demo.gif)

## Compatibility
|Release Version|Flame Version|
|---|---|
|v2.X.X|Flame 2025 and up|
|v1.X.X|Flame 2021 up to 2024.2|

## Installation

### Flame 2025 and newer
To make available to all users on the workstation, copy `tidy_nodes.py` to `/opt/Autodesk/shared/python/`

For specific users, copy `tidy_nodes.py` to the appropriate path below...
|Platform|Path|
|---|---|
|Linux|`/home/<user_name>/flame/python/`|
|Mac|`/Users/<user_name>/Library/Preferences/Autodesk/flame/python/`|

### Flame 2021 up to 2024.2
To make available to all users on the workstation, copy `tidy_nodes.py` to `/opt/Autodesk/shared/python/`

For specific users, copy `tidy_nodes.py` to `/opt/Autodesk/user/<user name>/python/`

## Menus
- Right-click selected nodes in the Action schematic `->` Tidy Nodes... `->`
  - Align Vertically
  - Distribute Horizontally
  - Distribute Vertically
  - Scale
  - Tidy Horizontally
  - Tidy Vertically
- Right-click selected nodes in the Batch schematic `->` Tidy Nodes... `->`
  - Align Vertically
  - Distribute Horizontally
  - Distribute Vertically
  - Scale
  - Tidy Horizontally
  - Tidy Vertically

## Acknowledgements
UI Templates courtesy of [pyflame.com](http://www.pyflame.com)
