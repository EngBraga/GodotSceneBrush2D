# GodotSceneBrush2D
A 2D scene brush plugin for Godot 3.1+

This plugin adds tools to help placing many scene instances in an 2D environment by "painting" over it, rather than dragging and dropping them manually from the file system dock.
It adds a new node `SceneBrush2D`.

## Install

This is a regular editor plugin.
Just Copy the `addons` folder to your Godot Project Folder and activate it in your project settings.

![scenebrush2D_plugin](https://gfycat.com/fairnaturalibex)

## Use

- Have any 2D scene
- Add a `SceneBrush2D` node to the scene, or select one already present
- Add scenes you wish to be able to paint into the list, and select the one you want to paint
- Start placing them by left-clicking in the scene. You can remove them using right-click.
  - This will create scene instances as child of the `SceneBrush2D` node.
