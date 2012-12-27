# NSImage+HHTint - Tints grayscale images using CoreImage

This category on NSImage adds a single method:

```objective-c
- (NSImage *)hh_imageTintedWithColor:(NSColor *)tint;
```

This method creates a tinted copy of the image.
Colored / gray pixels of the original image lead to pixels of an equally dark shade of the tint color.

This code was originally written for [Tembo.app](http://www.houdah.com/Tembo).
The navigation bar in Tembo is build from grayscale images. At runtime these are tinted to a dark blue.
In Tembo's drill-down view the same process is applied to a stock NSSegementedControl to make it match the color of the navigation bar.

## License

This code is made available under the terms of the BSD license as included in the source files.
