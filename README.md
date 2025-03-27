# cwmi-woodchip-map

This is a Leaflet map to replace the old Carto map at https://compost.css.cornell.edu/carbonmap.html

The files in this repo were originally generated using the qgis2web plugin for QGIS.  These files were then heavily edited to match the map style of the old map, remove unneeded components, and pull the data directly from the [Woodchip Map](https://docs.google.com/spreadsheets/d/1bKNOVa89aJMSgPJ7xHHabM-KNSC1PFCbl6nk5KoAjfU/edit?usp=sharing) Google spreadsheet.  Woodchip facilities can be added or edited in that spreadsheet, and this map will automatically update.

This map can be embedded in a webpage using the following HTML code:

```
<iframe style="height: 700px; width: 100%; border:none" src="https://cornell-gis.github.io/cwmi-woodchip-map/" allowfullscreen></iframe>
```