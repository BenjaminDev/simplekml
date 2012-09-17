Release History
===============

simplekml 1.1.2 - 17 September 2012
-----------------------------------
**Fixes**
  * Fixed the import error regarding networklinkcontrol

simplekml 1.1.1 - 16 September 2012
-----------------------------------
**New Features**
  * Added the property *gxballoonvisibility* to all features
  * Added :attr:`simplekml.Kml.networklinkcontrol` to the :class:`simplekml.Kml`. Thus, there is a new class called
    :class:`simplekml.NetworkLinkControl` and relevant properties (including :class:`simplekml.LinkSnippet`)

simplekml 1.1.0 - 09 August 2012
--------------------------------
**New Features**
  * Added methods to all container classes for querying features already created. The new methods are: features,
    allfeatures, geometries, allgeometries, containers, allcontainers, styles, allstyles, stylemaps, and allstylemaps
  * Added a hint attribute to the Kml class that allows hints to be added to the kml tag, such as: *target=moon*

**Enhancements**
  * The CDATA tags within text attributes are not escaped with the rest of the text and remain as is whether or not
    parsetext of the Kml class is set to True or False

**Fixes**
  * FlyTo is now generating the Abstract View (Camera and LookAt) tag correctly

simplekml 1.0.0 - 24 July 2012
------------------------------
First production version release.