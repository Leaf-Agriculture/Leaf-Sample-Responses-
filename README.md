### Here you can find example responses from Leaf's API.

Inside **"imagery_data"** you can find example responses from Leaf's Satellite API.
Responses like your fields' RGB PNG, colored NDVIs, raw NDVIS so you can apply your color ramp, being tif or PNG, and even individual bands so you can calculate your indexes.

Inside **"machine_data"** you can find example responses from Leaf's Machine Data API.
The response contains the original file, conversion files, data translated into a unified machine data model, rendered images of the operation, summary data of the operation, polygon of the area, and more. We've added each file generated in this repository for easy viewing.

For our quickstart Postman collection, please see https://github.com/Leaf-Agriculture/Leaf-quickstart-Postman-collection

Our full docs are available here: https://dev.agrigate.io/#introduction



Example response from Leaf's API:

``` json
{
  "id": "2fc21b10-47dc-4318-8476-41da49ef39aa",
  "provider": "Leaf",
  "originalFile": "https://leaf-onboarding.s3.us-west-2.amazonaws.com/sample/cd621104-4ae0-40ba-b363-0bffe4546c12.json",
  "rawGeojson": "https://leaf-onboarding.s3.us-west-2.amazonaws.com/sample/f6138de5-bddb-4447-b7a6-45011b18c276.json",
  "standardGeojson": "https://leaf-onboarding.s3.us-west-2.amazonaws.com/sample/3ffb1b13-1143-40fa-bd6f-b9903a809bdd.json",
  "zippedPNGs": "https://leaf-onboarding.s3.us-west-2.amazonaws.com/sample/44abac92-beae-42eb-a3f8-ce0534951935.zip",
  "leafUserId": "ad2ad025-5bcd-42a6-9b04-002c4dff76a3",
  "apiOwnerUsername": "onboarding4",
  "summary": {
    "type": "Feature",
    "properties": {
      "operationType": "harvested",
      "crop": [
        "corn"
      ],
      "yieldVolume": {
        "average": 0.12190647398821647,
        "standardDeviation": 0.01587468033255807,
        "min": 0.07588749778395842,
        "max": 0.15894974159310413
      },
      "totalArea": 330765.8910826785,
      "totalDistance": 582412.5662580981,
      "speed": {
        "average": 3.4563209340925316,
        "standardDeviation": 0.9235707563855357,
        "min": 0.0,
        "max": 6.690000057220459
      },
      "elevation": {
        "average": 194.1543032166196,
        "standardDeviation": 3.3396686114768617,
        "min": 188.3,
        "max": 360.9
      }
    },
    "geometry": {
      "type": "MultiPolygon",
      "coordinates": [
        [
          [
            [-89.834466,39.719631],
            [-89.834503,39.719698],
            [-89.834532,39.719758],
            [-89.83471,39.72636],
            [-89.834647,39.726401],
            [-89.834643,39.726403],
            [-89.834634,39.726407],
            [-89.834624,39.726411],
            [-89.834615,39.726414],
            [-89.829956,39.72758],
            [-89.829946,39.727569],
            [-89.829938,39.727552],
            [-89.829936,39.727543],
            [-89.829935,39.727534],
            [-89.829872,39.72007],
            [-89.829872,39.720012],
            [-89.829879,39.71978],
            [-89.829888,39.71968],
            [-89.829892,39.719679],
            [-89.829948,39.719672],
            [-89.831934,39.719643],
            [-89.832978,39.719637],
            [-89.834465,39.719631],
            [-89.834466,39.719631]
          ]
        ]
      ]
    }
  },
  "sourceFiles": [
    "18e135aa-0716-40c9-8d50-45b0bf5bb111",
    "7036a180-0609-434b-b797-ce7e3a674f25"
  ],
  "status": "processed",
  "origin": "merged",
  "createdTime": "2020-08-10T17:41:05.134",
  "operationStartTime": "2019-10-02T20:23:33.4",
  "operationEndTime": "2019-10-23T03:04:41.4"
}
```
