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

