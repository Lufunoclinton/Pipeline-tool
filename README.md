# Pipeline-tool
Here's a README file for your Blender add-on, "Pipeline Tools":

---

# Pipeline Tools Add-on for Blender

## Overview

The Pipeline Tools add-on provides a set of tools to streamline the animation pipeline in Blender. It allows users to import assets, set up scenes, clear scenes, import textures, rig characters, animate characters, and render/export animations easily.

## Features

- **Import Asset:** Import 3D models (FBX, OBJ) or images (PNG, JPG, BMP, TIFF, EXR).
- **Setup Scene:** Automatically set up a scene with cameras, lights, and environment textures.
- **Clear Scene:** Clear all existing objects in the scene.
- **Import Texture:** Import texture images.
- **Rig Character:** Rig characters using the Rigify add-on.
- **Keyframe Animation:** Apply keyframe animations to selected objects.
- **Render and Export:** Render the final animation and export it in various formats.

## Installation

1. **Download the Add-on:**
   - Save the script as `pipeline_tools.py`.

2. **Install the Add-on in Blender:**
   - Open Blender.
   - Go to `Edit > Preferences`.
   - In the Preferences window, go to the `Add-ons` tab.
   - Click `Install...` at the top and select the `pipeline_tools.py` file.
   - Enable the add-on by checking the checkbox next to "Pipeline Tools".

## Usage

1. **Accessing the Tools:**
   - The Pipeline Tools panel is located in the 3D Viewport's Sidebar under the "Pipeline" tab.

2. **Import Asset:**
   - Click the "Import Asset" button to import 3D models or images. Supported formats: FBX, OBJ, PNG, JPG, BMP, TIFF, EXR.

3. **Setup Scene:**
   - Click the "Setup Scene" button to automatically set up a scene with a camera, light, and environment texture.

4. **Clear Scene:**
   - Click the "Clear Scene" button to remove all existing objects from the scene.

5. **Import Texture:**
   - Click the "Import Texture" button to import texture images.

6. **Rig Character:**
   - Click the "Rig Character" button to rig a character using the Rigify add-on.

7. **Keyframe Animation:**
   - Click the "Keyframe Animation" button to apply keyframe animations to selected objects.

8. **Render and Export:**
   - Set the output path and file format in the "Render and Export" section.
   - Click the "Render and Export" button to render the animation and export it.

## Operators

- `ImportAssetOperator`: Handles the import of 3D models and images.
- `SetupSceneOperator`: Sets up the scene with cameras, lights, and environment textures.
- `ClearSceneOperator`: Clears all existing objects in the scene.
- `ImportTextureOperator`: Imports texture images.
- `RigCharacterOperator`: Rigs characters using the Rigify add-on.
- `WalkCycleAnimationOperator`: Animates characters with a walking cycle.
- `KeyframeAnimationOperator`: Applies keyframe animations to selected objects.
- `RenderAndExportOperator`: Renders and exports the final animation.

## Panels

- `PipelineToolsPanel`: The main panel in the 3D Viewport's Sidebar for accessing all pipeline tools.

## Development

To contribute or make modifications, you can extend the classes and operators defined in the script.

1. **Register New Operators and Panels:**
   - Define your custom operators and panels.
   - Register them in the `register` function.
   - Unregister them in the `unregister` function.

2. **Test Your Changes:**
   - Save the script and reload it in Blender to test your changes.

## License

This add-on is licensed under the MIT License.

---

This README file provides a detailed overview of the Pipeline Tools add-on, including installation, usage, features, and development instructions.
