# cwmi-compost-map

This is a Leaflet map to replace the old Carto map at https://compost.css.cornell.edu/maps.html

The files in this repo were originally generated using the qgis2web plugin for QGIS.  These files were then heavily edited to match the map style of the old map, remove unneeded components, and pull the data directly from the [Compost Facility Survey](https://docs.google.com/spreadsheets/d/1qdddXs_PzMwFsb3PMadLf9Dh7_UjBx6i7h8MDQRIRVI/edit?usp=sharing) Google spreadsheet.  Compost facilities can be added or edited in that spreadsheet, and this map will automatically update.

This map can be embedded in a webpage using the following HTML code:

```
<iframe style="height: 700px; width: 100%; border:none" src="https://cornell-gis.github.io/cwmi-compost-map/" allowfullscreen></iframe>
```