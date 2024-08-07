# Leaflet and WMS in Viktor
This sample app demonstrates how to add Leaflet and WMS-layers to a VIKTOR app.

The goal of this app is to demonstrate how to add a WMS-layer to a map. This app was developed using the 
open-source libraries `Leaflet`, `Folium` and `OWSLib`. Leaflet is a powerful open-source JavaScript library to create 
interactive maps. Folium is a Python Leaflet-wrapper, which enables to use Leaflet without the use of JavaScript. 
OWSLib is used to obtain information from the WMS-layer.

In this application the following functionalities are demonstrated:
- Retrieve information from a WMS-layer 
- Add WMS-layer to a map

A published version of this app is available on [demo.viktor.ai](https://demo.viktor.ai/public/wms-app).

### Step 1: Introduction to Leaflet
In the first step a short explanation is given about what Leaflet is. Also, a sample Leaflet map is shown with some of 
it's powerful features enabled.

![Step1](.viktor-template/step1.gif "Step 1")

### Step 2: Set-up WMS data
In this step the information required for adding a WMS-layer is obtained, using the Python library `OWSLib`. Simply 
provide the link to the WMS-layer and all the information of the WMS-layer appears on the right-hand side. This 
information can be used in your own app to add your WMS-layer to your map.

![Step2](.viktor-template/step2.gif "Step 2")

### Step 3: Add WMS layer to map
Finally, the WMS layers are added to the map. Depending on the WMS-layer you provided, the available layers can be 
selected in the drop-down menu. Once selected, the map will automatically reload and display the layers on the map.

![Step3](.viktor-template/step3.gif "Step 3")
