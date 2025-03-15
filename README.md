# Gobo_It Pro

## Overview
Gobo_It Pro is a professional-grade Blender addon that provides a comprehensive gobo lighting system with advanced features and presets. It allows users to easily create and manipulate gobo effects for spot lights in Blender, making it perfect for architectural visualization, stage lighting, and creative lighting design.

![Screenshot 2025-03-15 213421](https://github.com/user-attachments/assets/fdab85c8-6cb7-43a3-8064-7303a9a23ccb)

## Features
- Easy-to-use gobo setup for spot lights
- Advanced node-based gobo system
- Real-world light units support
- Automatic tracking target setup
- Comprehensive preset system
- Bulk image loading
- Interactive parameter controls
- Advanced customization options

## Installation
1. Download the `Gobo_It_Pro.py` file
2. Open Blender and go to Edit > Preferences > Add-ons
3. Click "Install" and select the downloaded file
4. Enable the addon by checking the checkbox next to "Lighting: Gobo_It Pro"

## Requirements
- Blender 3.0 or newer
- Supported image formats: PNG, JPG, JPEG, TIFF, BMP, TGA

## Usage

### Basic Setup
1. Add a spot light to your scene
2. Select the spot light
3. Open the Gobo It panel in the sidebar (N-panel)
4. Click "Setup Gobo" to initialize the gobo system
5. Load a gobo image using the image selector
6. Adjust parameters as needed

### Controls
- **Scale**: Adjust the size of the gobo pattern
- **Rotation**: Rotate the gobo pattern
- **Opacity**: Control the strength of the gobo effect
- **Position X/Y**: Adjust the pattern position
- **Spot Size**: Control the light beam width
- **Spot Blend**: Adjust the edge softness

### Working with Presets
1. **Save Preset**:
   - Adjust gobo parameters as desired
   - Click the "+" button in the presets section
   - Enter a name for your preset
   - Click "OK" to save

2. **Apply Preset**:
   - Select a preset from the list
   - Click the checkmark button to apply

3. **Delete Preset**:
   - Select a preset from the list
   - Click the "-" button to remove it

### Advanced Features
- **Bulk Loading**: Load multiple gobo images at once using the folder icon
- **Category Filtering**: Filter gobos by category (Patterns, Textures, Effects, Custom)
- **Target Control**: Use the automatically created empty target to aim the gobo
- **Node Customization**: Access the underlying node setup for advanced customization

## Preferences
Access addon preferences through Edit > Preferences > Add-ons > Gobo_It Pro

### Basic Settings
- Default Gobo Folder
- Auto Preview
- Preview Size

### Advanced Settings
- Default Light Settings
  - Energy
  - Spot Size
  - Shadow Softness
- Custom Default Color
- UI Display Options

## Tips & Best Practices
1. Use high-contrast black and white images for best gobo effects
2. Adjust the spot size before fine-tuning gobo parameters
3. Use the tracking target for precise gobo placement
4. Save commonly used setups as presets
5. Organize gobos into categories for easier management

## Troubleshooting
1. **Gobo not visible**:
   - Ensure the spot light is properly set up
   - Check if the gobo image is loaded
   - Verify the light is pointing at a surface

2. **Preset not applying**:
   - Make sure a spot light is selected
   - Check if the preset file exists
   - Verify the preset data is valid

3. **Image loading issues**:
   - Ensure image format is supported
   - Check file permissions
   - Verify file path is accessible

## Known Limitations
- Works only with spot lights
- Some features require Blender 3.0 or newer
- Real-time preview performance depends on scene complexity

## Support
For bug reports and feature requests, please visit:
[[GitHub Repository URL](https://github.com/Dream-Pixels-Forge/Gobo-It-Pro)]

## Credits
- Created by: Dimona Patrick
- Version: 2.0.0
- License: GPL

## Changelog
### Version 2.0.0
- Added preset system
- Improved UI organization
- Added advanced preferences
- Added bulk loading feature
- Added category filtering
- Improved error handling
- Added tracking target system

### Version 1.0.0
- Initial release
- Basic gobo functionality
- Simple parameter controls
