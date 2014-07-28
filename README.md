osm-animate
===========

![Medellin, Colombia](https://dl.dropboxusercontent.com/u/27150206/Think%20before%20deleting/Medellin.gif)

Dependencies: [osm-snap](https://github.com/ericfischer/osm-snap), [datamaps](https://github.com/ericfischer/datamaps), and [ImageMagick](http://www.imagemagick.org/)

Desired Outcome:

- User specifies a bounding box (via ...)
- User sees a gif/video/Mapbox GL layer of the OSM changes (only way creation/last edit) over time

Plan:

- get osm file from some input specification
- use erics stuff to convert, encode, and render as pngs or tiles
- output as something
