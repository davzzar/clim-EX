<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/davzzar/clim-EX/turnoff/public/images/logos/readme-banner.png" alt="Clim-EX Logo Banner" width="738">
</p>

Clim-EX (Climate Animation Explorer) is a tool for visualising and viewing meteorological data and weather forecasts which will help understanding African droughts. This tool bridges the gap between the layperson and scientific meteorological experts making the viewing of this data enjoyable and aesthetically pleasing.

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/davzzar/clim-EX/screenshots/clim-ex-thumb.png" alt="Clim-EX Logo Banner">
</p>

[//]: <https://davzzar.github.io/clim-AX/>

### Features

Clim-EX is capable of displaying temperature and temperature anomaly, topography, precipitation, the flow of water and rivers across the surface and vegetation health. Each layer can be toggled according to the user's intent and wish.

Clim-EX can dynamically scroll through the time, enabling the user to understand the temporal evolution of droughts.

### Data

Clim-EX uses ERA5 Reanalysis Product data taken from the [Copernicus Data Store](https://cds.climate.copernicus.eu/), river discharge from the [Global Flood Awareness System (GLOFAS)](https://cds.climate.copernicus.eu/cdsapp#!/dataset/cems-glofas-historical?tab=overview) and vegetation health from [AVHRR (produced by NOAA)](https://climatedataguide.ucar.edu/climate-data/ndvi-normalized-difference-vegetation-index-noaa-avhrr). All data is provided in the NetCDF data format.

### Under the hood

- Pre-generates image plots via [MatPlotLib](https://matplotlib.org/) for each time step and each variable
- Send the data to the React frontend
- Stacks the layers via the SVG format to achieve hacky data layer blending
- Auto interpolated between images for a smooth and pleasing viewing experience

### Demo

<p align="center">
  <a href="https://thumbs.gfycat.com/LargeNaiveArgali-mobile.mp4"><img src="https://cdn.jsdelivr.net/gh/davzzar/clim-EX/screenshots/clim-ex-1-op.gif" alt="Clim-EX Demo Gif 1" width="640" height="360"></a>
</p>

<p align="center">
  <a href="https://thumbs.gfycat.com/SophisticatedOldfashionedFairyfly-mobile.mp4"><img src="https://cdn.jsdelivr.net/gh/davzzar/clim-EX/screenshots/clim-ex-2-op.gif" alt="Clim-EX Demo Gif 2" width="640" height="360"></a>
</p>

<p align="center">
  <a href="https://thumbs.gfycat.com/ElasticKaleidoscopicBellsnake-mobile.mp4"><img src="https://cdn.jsdelivr.net/gh/davzzar/clim-EX/screenshots/clim-ex-3-op.gif" alt="Clim-EX Demo Gif 3" width="640" height="360"></a>
</p>

### Team

- [David Simon Tetruashvli](https://github.com/davzzar)
- [Sijmen Huizenga](https://github.com/SijmenHuizenga)
- [Milan Kloewer](https://github.com/milankl)
- [Tommy Lees](https://github.com/tommylees112)

