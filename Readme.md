# NASA BlackMarble Tiles

This NPM package provides access to tiles from the NASA BlackMarble dataset. These tiles feature detailed night representations of Earth's surface.

![Planet](planet.jpeg)

## Usage

The tiles can be used offline, hosted on your own servers, or accessed via the included CDN link for easy integration into web mapping applications.
![npm](https://img.shields.io/npm/v/@freetiler/nasa-blackmarble)

To install the tiles offline via [NPM](https://www.npmjs.com/package/@freetiler/nasa-blackmarble), use:
```
npm install @freetiler/nasa-blackmarble
```

### CDN Links

You can use any NPM or Github CDN to serve the tiles. 

```
GitHub CDNs - Zoom 0-8: 
 - https://cdn.jsdelivr.net/gh/freetiler/nasa-blackmarble/tiles/{z}/{x}/{y}.jpeg
 - https://cdn.statically.io/gh/freetiler/nasa-blackmarble/main/tiles/{z}/{x}/{y}.jpeg
```

## Tile Specs:

- **Minimum Zoom Level**: 0
- **Maximum Zoom Level on NPM**: 7
- **Maximum Zoom Level on Github**: 8
- **Projection Used**: EPSG:3857
- **Tile Size**: 256x256
- **Tile Format**: JPEG
- **Attribution**: "FreeTiler.com | NASA Earth Observatory"

## License

NASA Open Data Policy:
NASA has an open data policy, and you are free to use the imagery from GIBS as you see fit.  Citations are not required but are requested and highly appreciated.  Please see the “Data Use Policy and Acknowledgements” section here for more information:
https://www.earthdata.nasa.gov/eosdis/science-system-description/eosdis-components/gibs

## Disclaimer

This package is provided "as is", without warranty of any kind. Use at your own risk.
