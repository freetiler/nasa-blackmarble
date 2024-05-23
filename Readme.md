
# NASA BlackMarble Tiles

![npm](https://img.shields.io/npm/v/@freetiler/nasa-blackmarble)

This NPM package provides access to tiles from the NASA BlackMarble set, which are believed to be in the public domain. These tiles feature detailed night representations of Earth's surface.

## Usage

The tiles can be used offline, hosted on your own servers, or accessed via the included CDN link for easy integration into web mapping applications.

To install the tiles offline via NPM, use:
```
npm install @freetiler/nasa-blackmarble
```

### CDN Links

You can use any NPM or Github CDN to serve the tiles. 

```
GitHub CDN - Zoom 0-8: 
 - https://cdn.jsdelivr.net/gh/freetiler/nasa-blackmarble/tiles/{z}/{x}/{y}.jpeg

NPM CDNs - Zoom 0-7:
 - https://esm.sh/@freetiler/nasa-blackmarble/tiles/{z}/{x}/{y}.jpeg
 - https://unpkg.com/@freetiler/nasa-blackmarble/tiles/{z}/{x}/{y}.jpeg
```

## Tile Specs:

- **Minimum Zoom Level**: 0
- **Maximum Zoom Level on NPM**: 7
- **Maximum Zoom Level on Github**: 8
- **Projection Used**: EPSG:3857
- **Tile Size**: 256x256
- **Tile Format**: JPEG
- **Attribution**: "FreeTiler.com | NASA"

## License

This package distributes NASA tiles. Please do your own due diligence to confirm this before use. We kindly ask you to add attribution "FreeTiler.com | NASA Earth Observatory"

## Disclaimer

This package is provided "as is", without warranty of any kind. Use at your own risk.
