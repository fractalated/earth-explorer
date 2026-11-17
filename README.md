# Earth Explorer

A 3D globe for Earth Science class that runs in Chrome on school Chromebooks, no Google Earth needed.

**Open it:** https://fractalated.github.io/earth-explorer/

## What it does

- Spinning 3D globe with satellite imagery, land elevation **and** ocean-floor depth (trenches and ridges show in 3D)
- Opens with an empty globe; no tour is built in
- Shows each place's location and approximate elevation
- **Viewing angle** box: Tilt and Rotate sliders, **North up**, and **Reset view** (north up at the standard 50° angle, or straight down when viewing the whole Earth)
- **Open KMZ…** button: load any `.kmz` or `.kml` saved from Google Earth. Its places show as numbered flags on poles that stand straight up from the surface, so hills never hide them. Click one in the list or on the globe to fly there

## Controls

- Drag: spin the globe
- Scroll or pinch: zoom
- Ctrl + drag: tilt the view (or use the Tilt slider)

## Sample tour

[`tours/Plate Tectonics Tour.kmz`](tours/) is a sample file you can download and open with **Open KMZ…**.

## Web filter checklist

Student Chromebooks need to reach these sites:

- `fractalated.github.io`: the page
- `cdn.jsdelivr.net`: the CesiumJS globe library
- `services.arcgisonline.com`: satellite imagery and place labels
- `elevation3d.arcgis.com`: 3D terrain and ocean depth

## Credits

Globe: [CesiumJS](https://cesium.com/platform/cesiumjs/) (Apache 2.0). Imagery and elevation: Esri, Maxar, Earthstar Geographics.
