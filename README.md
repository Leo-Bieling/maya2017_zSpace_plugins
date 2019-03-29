# Collection of zSpace plugins for maya 2017 
written by Vishu Bhooshan, Leo Bieling and Marko Margeta

## Install
---
* copy the content of the __plug-ins__ folder to: C:\Program Files\Autodesk\Maya2017\bin\plug-ins
* copy the content of the __script__ folder to: C:\Users\%USERPROFILE%\Documents\maya\2017\scripts
* open Maya2017 and drag&drop the __setupScript.mel__ into the viewport
* from then on the zSpace shelf and menu title will always show up
---
---
## Plugins
---

### zSpace_IO
##### export curves to TXT
* with individual curves selected it exports them as individual graphs
* with a parent group selected it exports all children curves as one graph

##### import mesh JSON
* check the __import multiple files__ to import multiple files and select one file in the dialog window
* the naming of the files has to follow the same structure like the __export meshes to JSON__ is producing _(FILENAME_0.json, FILENAME_1.json, FILENAME_2.json,)_
* check __import colors__ to receive the color data

##### export meshes to JSON
* check __export colors__ to add the color data
* if multiple meshes are selected for export it will export one .json file per mesh with the _0 suffix automatically added
---