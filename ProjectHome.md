This image tiler uses Free Software, is released under the GPL, and has the following features:

  * Tiles most image formats, including GIF, JPEG, PNG and TIFF.
  * Works on most flavours of Unix, including Mac OS X.
  * Supports version 1 and version 2 zoom levels.
  * Automatically calculates offsets for all zoom levels.
  * Supports padding from the upper-left as output by the [web-based tiling helper](http://open.atlas.free.fr/GMapsTransparenciesImgOver.php).
  * Automatically pads image to size appropriate to Google Maps (ie. multiple of 256).
  * Optionally discards empty transparent tiles to save space.
  * Optional prefix for each tile.
  * Outputs tiles in PNG format.
  * Compresses tiles with either [advpng](http://advancemame.sourceforge.net/comp-readme.html) or [pngcrush](http://pmt.sourceforge.net/pngcrush/).

The tiler requires [ImageMagick](http://www.imagemagick.org/) and [advpng](http://advancemame.sourceforge.net/comp-readme.html) or [pngcrush](http://pmt.sourceforge.net/pngcrush/) for PNG compression. (I recommend advpng as it is faster and compresses smaller in most situations.) Tiled image size is restricted only by disk space and ImageMagick limitations.