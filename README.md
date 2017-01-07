# Positron
[![Build Status](https://travis-ci.org/openmaptiles/positron-gl-style.svg?branch=master)](https://travis-ci.org/openmaptiles/positron-gl-style)

A Mapbox GL basemap style useful for data visualizations. The cartography is based on the
[CartoDB Positron Basemap](https://github.com/CartoDB/CartoDB-basemaps) and it is using the vector tile
schema of [OpenMapTiles](https://github.com/openmaptiles/openmaptiles).

## Preview

**[:globe_with_meridians: Browse the map](https://openmaptiles.github.io/positron-gl-style)**

<img src="http://demo.tileserver.org/styles/positron/static/8.540587,47.370555,15.08/600x400@2x.png" width="600" title="Positron Preview Zurich">

<img src="http://demo.tileserver.org/styles/positron/static/8.619184,47.336203,10.07/600x400@2x.png" width="600" title="Positron Preview Lake Zurich">

<img src="http://demo.tileserver.org/styles/positron/static/8.243967,46.916315,7.21/600x400@2x.png" width="600" title="Positron Preview Switzerland">

<img src="http://demo.tileserver.org/styles/positron/static/10.987258,46.453150,4.02/600x400@2x.png" width="600" title="Positron Preview Europe">

## Edit the Style

Use the [Maputnik CLI](http://openmaptiles.org/docs/style/maputnik/) to edit and develop the style.
After you've started Maputnik open the editor on `localhost:8000`.

```
maputnik --watch --file style.json
```
