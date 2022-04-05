{
  "version": "v1",
  "config": {
    "visState": {
      "filters": [
        {
          "dataId": [
            "4dlxe2l4n"
          ],
          "id": "k7mocu2c6",
          "name": [
            "in:WWR"
          ],
          "type": "range",
          "value": [
            4.98,
            5.86
          ],
          "enlarged": false,
          "plotType": "histogram",
          "animationWindow": "free",
          "yAxis": null,
          "speed": 1
        }
      ],
      "layers": [
        {
          "id": "wl2d3u",
          "type": "point",
          "config": {
            "dataId": "4dlxe2l4n",
            "label": "out:",
            "color": [
              255,
              203,
              153
            ],
            "highlightColor": [
              252,
              242,
              26,
              255
            ],
            "columns": {
              "lat": "out:latitude",
              "lng": "out:longitude",
              "altitude": null
            },
            "isVisible": true,
            "visConfig": {
              "radius": 10,
              "fixedRadius": false,
              "opacity": 0.8,
              "outline": false,
              "thickness": 2,
              "strokeColor": null,
              "colorRange": {
                "name": "Uber Viz Diverging 1.5",
                "type": "diverging",
                "category": "Uber",
                "colors": [
                  "#00939C",
                  "#5DBABF",
                  "#BAE1E2",
                  "#F8C0AA",
                  "#DD7755",
                  "#C22E00"
                ]
              },
              "strokeColorRange": {
                "name": "Global Warming",
                "type": "sequential",
                "category": "Uber",
                "colors": [
                  "#5A1846",
                  "#900C3F",
                  "#C70039",
                  "#E3611C",
                  "#F1920E",
                  "#FFC300"
                ]
              },
              "radiusRange": [
                0,
                50
              ],
              "filled": true
            },
            "hidden": false,
            "textLabel": [
              {
                "field": null,
                "color": [
                  255,
                  255,
                  255
                ],
                "size": 18,
                "offset": [
                  0,
                  0
                ],
                "anchor": "start",
                "alignment": "center"
              }
            ]
          },
          "visualChannels": {
            "colorField": {
              "name": "Energy generation [kWh/m2]",
              "type": "real"
            },
            "colorScale": "quantile",
            "strokeColorField": null,
            "strokeColorScale": "quantile",
            "sizeField": null,
            "sizeScale": "linear"
          }
        }
      ],
      "interactionConfig": {
        "tooltip": {
          "fieldsToShow": {
            "4dlxe2l4n": [
              {
                "name": "Energy generation [kWh/m2]",
                "format": null
              },
              {
                "name": "Energy Class required to reach ZEB",
                "format": null
              },
              {
                "name": "out:AC generation (kWh/m2)",
                "format": null
              }
            ]
          },
          "compareMode": false,
          "compareType": "absolute",
          "enabled": true
        },
        "brush": {
          "size": 0.5,
          "enabled": false
        },
        "geocoder": {
          "enabled": false
        },
        "coordinate": {
          "enabled": false
        }
      },
      "layerBlending": "normal",
      "splitMaps": [],
      "animationConfig": {
        "currentTime": null,
        "speed": 1
      }
    },
    "mapState": {
      "bearing": 0,
      "dragRotate": false,
      "latitude": 46.18081459478733,
      "longitude": 9.27690370033565,
      "pitch": 0,
      "zoom": 4.555762370911119,
      "isSplit": false
    },
    "mapStyle": {
      "styleType": "dark",
      "topLayerGroups": {},
      "visibleLayerGroups": {
        "label": false,
        "road": true,
        "border": false,
        "building": true,
        "water": true,
        "land": true,
        "3d building": false
      },
      "threeDBuildingColor": [
        9.665468314072013,
        17.18305478057247,
        31.1442867897876
      ],
      "mapStyles": {}
    }
  }
}
