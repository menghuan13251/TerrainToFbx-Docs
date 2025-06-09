# TerrainToFbx

**Version**: 1.0.0  
**Unity Version**: 2021.3+  
**Author**: Huan Meng  
**Email**: m18266322300@gmail.com  
**Repository**: [GitHub](https://github.com/yourusername/terraintofbx)  

## Overview
TerrainToFbx is a powerful tool designed to convert Unity's native terrain into exportable FBX models while preserving key details such as heightmaps, vegetation, and textures.

## Features
- Convert Unity terrain to FBX format
- Preserve terrain heightmap, textures, and vegetation details
- Visual editor window with one-click export functionality
- Customizable parameters for mesh precision and coordinate system conversion

## Installation
1. Open your Unity project (2021.3 or later)
2. Navigate to `Window > Package Manager`
3. Click the `+` button and select `Add package from git URL...`
4. Enter `https://github.com/yourusername/terraintofbx.git`
5. The package and its dependencies will be automatically installed

## Usage
1. Open the tool: `Tools > TerrainToFbx`
2. Select a terrain object in your scene
3. Configure export parameters:
   - **Export Path**: Destination folder for the FBX file (recommended: within project)
   - **Mesh Resolution**: Grid density (lower values = higher detail)
   - **Include Vegetation**: Toggle to export terrain vegetation
   - **Coordinate System**: Choose target application (Unity/Blender/Maya)
4. Click `Export to FBX` to generate the model

## Dependencies
- Unity FBX Exporter: `com.unity.formats.fbx@4.1.3` (automatically installed)

## Limitations
- Does not support terrains with Streaming enabled
- Vegetation export is limited to Unity's native system (third-party plugins not supported)
- Exporting very large terrains may take significant time

## Feedback
For issues or suggestions, please contact:
- Email: m18266322300@gmail.com
- [GitHub](https://menghuan13251.github.io/)  

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Changelog
### v1.0.0 (2025-05-31)
- Initial release
- Support for terrain export with heightmap and texture preservation
- Vegetation synchronization with native Unity system
- FBX format conversion with configurable parameters
