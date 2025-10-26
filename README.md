# Area Limiter - QGIS Plugin

A QGIS plugin for creating and editing polygons with precise area constraints. Perfect for land allocation, parcel design, and spatial planning tasks where specific area requirements must be met.

![Area Limiter Icon](icon.png)

## Features

✨ **Create New Polygons with Area Limits**
- Draw polygons while staying within a specified target area
- Real-time area feedback as you digitize
- Automatic prevention of exceeding target area

✨ **Edit Existing Polygons**
- Move existing vertices with area constraints
- Add new vertices by clicking on polygon edges
- Visual feedback with color-coded vertex markers

✨ **Flexible Units**
- Support for square meters (m²) and hectares (ha)
- Easy unit conversion with dropdown selector

## Installation

### From QGIS Plugin Repository (Recommended)
1. Open QGIS
2. Go to `Plugins` → `Manage and Install Plugins`
3. Search for "Area Limiter"
4. Click `Install Plugin`

### Manual Installation
1. Download the latest release from [Releases](https://github.com/Jessie42/arealimiter/releases)
2. Extract the ZIP file to your QGIS plugins directory:
   - **Windows**: `C:\Users\YourName\AppData\Roaming\QGIS\QGIS3\profiles\default\python\plugins\`
   - **Mac**: `~/Library/Application Support/QGIS/QGIS3/profiles/default/python/plugins/`
   - **Linux**: `~/.local/share/QGIS/QGIS3/profiles/default/python/plugins/`
3. Restart QGIS
4. Enable the plugin in `Plugins` → `Manage and Install Plugins`

## Usage

### Creating a New Polygon

1. **Select a polygon layer** from the dropdown or activate one in QGIS
2. **Put the layer in edit mode** (click the pencil icon)
3. **Set your target area** using the spin box
4. **Choose units** (m² or ha)
5. **Click "Apply"** to start digitizing
6. **Left-click** to add vertices
7. **Right-click** (or press Enter) to finish the polygon

The plugin will prevent you from adding vertices that would exceed the target area.

### Editing an Existing Polygon

1. **Select a polygon layer** and put it in edit mode
2. **Select a single polygon feature** in QGIS
3. **Set your target area** 
4. **Click "Edit Selected"**
5. **Move vertices**: Click and drag blue vertex markers
6. **Add vertices**: Click on any polygon edge (turns green)
7. **Right-click** (or press Enter) to save changes
8. **Press Escape** to cancel editing

## Requirements

- QGIS 3.0 or higher
- Python 3.6+
- PyQt5


## Configuration

The plugin adds a dockable panel to QGIS. You can:
- Dock it to any side of the QGIS window
- Float it as a separate window
- Close it when not needed (reopen from `Plugins` → `Area Limiter`)

  
## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### Development Setup

1. Clone this repository
2. Create a symbolic link from your QGIS plugins folder to the repository
3. Make your changes
4. Test thoroughly in QGIS
5. Submit a PR

### Reporting Issues

Found a bug? Please [open an issue](https://github.com/yourusername/arealimiter/issues) with:
- QGIS version
- Operating system
- Steps to reproduce
- Expected vs actual behavior
- Screenshots if applicable

## Changelog

### Version 1.0.0 (2025-10-27)
- Initial release
- Create polygons with area constraints
- Edit existing polygon vertices
- Add new vertices to polygons
- Support for m² and hectares
- Real-time area calculation
- Visual vertex markers

## License

This plugin is licensed under the GNU General Public License v2.0 or later.

See [LICENSE](LICENSE) file for details.

## Author

**Jessie Lindsay**
- Email: jessie.lindsay42@gmail.com
- GitHub: [@Jessie42](https://github.com/Jessie42)

## Acknowledgments

- QGIS Development Team
- PyQGIS Documentation
- Community feedback and testing

## Support

If you find this plugin useful, please:
- ⭐ Star this repository
- 🐛 Report bugs and request features
- 📢 Share with others who might benefit

## Related Projects

- [QGIS](https://qgis.org/) - Free and Open Source Geographic Information System
- [PyQGIS Cookbook](https://docs.qgis.org/latest/en/docs/pyqgis_developer_cookbook/)

---

**Note**: This is an independent plugin and is not officially associated with the QGIS project.
