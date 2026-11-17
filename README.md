# Earth Explorer

A 3D globe for Earth Science class that runs in Chrome on school Chromebooks, no Google Earth needed.

**Open it:** https://fractalated.github.io/earth-explorer/

## What it does

- Spinning 3D globe with satellite imagery, land elevation **and** ocean-floor depth (trenches and ridges show in 3D)
- Opens with an empty globe; no tour is built in
- Shows each place's location and approximate elevation
- **Viewing angle** box: Tilt and Rotate sliders, **North up**, and **Reset view** (north up at the standard 50° angle, or straight down when viewing the whole Earth)
- **Open KMZ…** button: load any `.kmz` or `.kml` saved from Google Earth. Its places show as numbered flags on poles that stand straight up from the surface, so hills never hide them. Click one in the list or on the globe to fly there. The view first swings back to straight down if it is tilted, flies looking straight down the whole way, and only tilts once it arrives, to the viewing angle saved in the file (no saved angle means it stays straight down)
- **Search** box: type a place (a mountain, city, country, address…) and pick a suggestion or press Go. The globe flies there looking straight down, marks the spot with a red dot, and shows its location and elevation
- **Close KMZ** button: removes the open file's places from the globe and the list

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
- `geocode.arcgis.com`: place search

## Credits

Globe: [CesiumJS](https://cesium.com/platform/cesiumjs/) (Apache 2.0). Imagery, elevation and place search: Esri, Maxar, Earthstar Geographics.
