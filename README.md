# geohackmin-mapvader
Making 🇨🇭 maps useable for data viz.

Work in progress on using Swisstopo Vector Tiles in a Leaflet environment and data viz ready styles.

[Demo output](https://cividi.github.io/geohackmin-mapvader/leaflet_example.html)

To pre-configure the map with one of the [configured styles and overlays](config.yaml) add `style=<Style Title>` and/or `overlay=<Overlay Title>` as a parameter to the URL.

Example: https://cividi.github.io/geohackmin-mapvader/leaflet_example.html?style=MapVader%20Light&overlay=Gebäude

To-Do-s:
- [ ] reclassify areas landuse / landcover (e.g. zoo)
- [ ] add public interest places (e.g. hospital, school)
- [ ] display public transport stops 
- [ ] add switch-on/-off layer of POI (e.g. restaurants, etc) - integration OSM-Swisstopo?
- [ ] define update frequency for POI
- [ ] change fonts: zoom-out: Open Sans, zoom-in: Zilla Slab, cities bold
- [ ] reorganize layer logic
- [ ] clean-up colour code area mess
