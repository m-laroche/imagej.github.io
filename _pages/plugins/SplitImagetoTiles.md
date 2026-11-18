---
title: Split Image to Tiles (Image divider/destitcher)
description: Divides images into tiles of specified dimensions or quantity with optional overlap
team-founder: "@m-laroche"
team-maintainer: "@m-laroche"
initial-release: 18 November 2026 (0.8.1)
current-release: 18 November 2026 (0.8.1)
source-URL: https://github.com/m-laroche/ImageJ-split-image-to-tiles/
---

## Split Image to Tiles
### Used to split (divide) an image or image stack into regions (tiles) for subsetting or destitching an image with designated parameters and options

### Installation
Help -> Update -> Manage Update Sites -> Select: SplitImagetoTiles -> Apply and Close

### Usage and features:
1. Open a source image or stack
2. Open plugin from: Plugins -> Split Image to Tiles (destitcher)
3. Select units: Px or uM
4. Selectable reference point for tile plotting: Calculate regions starting at either the origin or image centre
5. Define a bounding region: Limit tiling to dimensions from reference. 0 = include entire image.
6. Select the tiling method: 
    - Number of columns/rows: divide the image (or bounding region) by a quantity of columns/rows (e.g. 10,10)
    - Tile size: Define the tile dimensions and fit as many as possible (e.g. 256,256)
7. Define the horizontal and vertical overlap between tiles (%)
8. Select output options: Select prefix and whether to display tiles as new windows or save to source path
9. Click 'Ok' to proceed. Regions will be presented with the option to Proceed, Adjust, or cancel the operation.

### Dependencies
Developed and tested on FIJI 1.54p with Java 8.

### Correspondance
Please communicate any bugs or feature requests via GitHub.

### Author information
Michael La Roche - David Richmond Laboratory for Cardiovascular Development  
Faculty of Medicine and Health - The University of Sydney

### Licence information
[BSD 2-clause licence](https://github.com/m-laroche/ImageJ-split-image-to-tiles/edit/main/LICENSE.txt)
