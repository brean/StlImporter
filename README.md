# STL Importer
STL import plugin for Godot.

## Downloading and activating the Plugin
1. Download the Plugin using AssetLib.
1. Click on Project / Project Settings to open the Project Settings Menu.
1. Click on Plugins and make sure "STL Importer" is activated.
1. Close the Project Settings Menu and click on Project / Reload Current Project

That's it, while reloading Godot should find your STL-files and import them automatically.

You can then just drag-and-drop your STL to your scene. Note that most STLs are Z-up by and in mm by default for mechanics, robotics and 3D-printing. This means you probably want to rotate the STL by **-90°** degree and scale it down to **0.001**.

<img width="1920" height="1080" alt="Screenshot From 2026-02-21 22-06-40" src="https://github.com/user-attachments/assets/614f0f77-8087-4e78-bd9e-e9b7f62a58a1" />
