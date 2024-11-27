---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Print settings

We’ve designed our parts to work with the settings displayed below. Make sure to respect these settings, otherwise parts might turn out weak or look weird.

If you’re not happy with the print quality, join our [Discord](https://discord.gg/zerog) and ask for some help.

### <mark style="color:red;">Recommended print settings</mark> <a href="#recommended-print-settings" id="recommended-print-settings"></a>

* First layer height: 0.25mm (This is required. Our parts have been designed for this.)
* Layer height: 0.2mm
* Extrusion width: 0.4mm, forced
* Infill percentage: 40%
* Infill type: Adaptive Cubic, grid, gyroid, honeycomb, triangle, or cubic
* Wall count: 4
* Solid top/bottom layers: 5
* Seam placement: **REAR**
  * This is important as we have seam relieve features that line up with the seam placement.
* Supports: NONE

### <mark style="color:red;">Importing ZeroG files</mark> <a href="#importing-zerog-files" id="importing-zerog-files"></a>

Please be aware that the files you receive from us are already optimized for printing; we’ve exported everything as they should be printed. When importing them into your preferred slicer, they should display in the correct orientation. We advise against using the ‘auto rotate’ function in your slicer, as it can negatively impact seam placement and other print details. Improper rotation might also affect how materials shrink, leading to off-centered features and other discrepancies

> Credits for most of the recommended print settings [Voron](https://vorondesign.com/)
