# Earth Explorer

A 3D globe for Earth Science class that runs in Chrome on school Chromebooks, no Google Earth needed.

**Open it:** https://fractalated.github.io/earth-explorer/

## What it does

- Spinning 3D globe with satellite imagery, land elevation **and** ocean-floor depth (trenches and ridges show in 3D)
- Opens with the **Plate Tectonics Tour**: 9 numbered flags on poles that stand straight up from the surface, so hills never hide them. Click one in the list or on the globe to fly there
- Shows each place's location and approximate elevation
- **Plate boundaries** layer (can be turned on or off)
- **Viewing angle** box: Tilt and Rotate sliders, **North up**, and **Reset view** (north up at the standard 50° angle, or straight down when viewing the whole Earth)
- **Open KMZ…** button: load any `.kmz` or `.kml` saved from Google Earth to explore a different set of pins

## Controls

- Drag: spin the globe
- Scroll or pinch: zoom
- Ctrl + drag: tilt the view (or use the Tilt slider)

## Changing the built-in tour

The default pins are the KML text inside the `<script id="tour-kml">` block in `index.html`.
The original file is in [`tours/`](tours/).

## Web filter checklist

Student Chromebooks need to reach these sites:

- `fractalated.github.io`: the page
- `cdn.jsdelivr.net`: the CesiumJS globe library
- `services.arcgisonline.com`: satellite imagery and place labels
- `elevation3d.arcgis.com`: 3D terrain and ocean depth

## Credits

Globe: [CesiumJS](https://cesium.com/platform/cesiumjs/) (Apache 2.0). Imagery and elevation: Esri, Maxar, Earthstar Geographics.
Plate boundaries: Bird, P. (2003), *An updated digital model of plate boundaries*, G³ 4(3), via [fraxen/tectonicplates](https://github.com/fraxen/tectonicplates) (ODC-BY).
