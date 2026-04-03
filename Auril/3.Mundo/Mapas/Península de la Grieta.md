```zoommap
image: z_Resources/Images/Peninsula_Grieta.jpg
# markers is optional; defaults to <image>.markers.json
# markers: Assets/Map.jpg.markers.json

# Map view limits
minZoom: 0.36
maxZoom: 8

# Size & interactivity
height: 560px
width: 100%
resizable: true
resizeHandle: native     # left | right | both | native
render: dom           # or: dom

# Responsive display (fit into width, no wheel/pinch/dblclick pan/zoom)
responsive: false        # true → always fit; disables pan/zoom gestures

# Storage (optional)
# storage: note          # default is json; use "note" to store markers inline
# id: map-1              # optional stable id for inline storage (per code block)

# Alignment / wrapping (optional)
align: right             # left | center | right
wrap: true               # wrap text; useful with left/right alignment
```
%%
ZOOMMAP-DATA id=map-0
{
  "size": {
    "w": 2048,
    "h": 1536
  },
  "layers": [
    {
      "id": "default",
      "name": "Default",
      "visible": true,
      "locked": false
    }
  ],
  "markers": [
    {
      "type": "pin",
      "id": "marker_yft51l",
      "x": 0.22413465711805555,
      "y": 0.6484420211226852,
      "layer": "default",
      "link": "Ceding",
      "iconKey": "radial-balance",
      "tooltip": "Ceding",
      "scaleLikeSticker": true,
      "iconColor": "#121212",
      "tooltipAlwaysOn": true
    },
    {
      "type": "pin",
      "id": "marker_3gr9kx",
      "x": 0.6415979942077378,
      "y": 0.26917704200352305,
      "layer": "default",
      "link": "Disonancia Magica",
      "iconKey": "radial-balance",
      "tooltip": "Corazón de la Disonancia Mágíca",
      "scaleLikeSticker": true,
      "tooltipAlwaysOn": true,
      "iconColor": "#171717"
    },
    {
      "type": "pin",
      "id": "marker_d3c9b4",
      "x": 0.7487595683396464,
      "y": 0.8311673045559763,
      "layer": "default",
      "link": "Pantano",
      "iconKey": "radial-balance",
      "tooltip": "Hogar de la bruja del Pantano",
      "scaleLikeSticker": true,
      "iconColor": "#1f1f1f",
      "tooltipAlwaysOn": true
    }
  ],
  "bases": [
    "z_Resources/Images/Peninsula_Grieta.jpg"
  ],
  "overlays": [],
  "activeBase": "z_Resources/Images/Peninsula_Grieta.jpg",
  "measurement": {
    "displayUnit": "km",
    "scales": {},
    "customUnitPxPerUnit": {},
    "travelTimePresetIds": [],
    "travelDaysEnabled": false
  },
  "pinSizeOverrides": {},
  "grids": [],
  "panClamp": true,
  "drawLayers": [],
  "drawings": [],
  "textLayers": [],
  "secondScreen": {
    "showGrids": true
  }
}
/ZOOMMAP-DATA
%%

