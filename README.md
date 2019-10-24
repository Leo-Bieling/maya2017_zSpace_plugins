# Collection of zSpace plugins for maya 2017
written by Vishu Bhooshan, Leo Bieling and Marko Margeta <br>
v0.2
## Install
---
* copy the content of the **plug-ins** folder to: *C:\Program Files\Autodesk\Maya2017\bin\plug-ins*
* copy the content of the **script** folder to: *C:\Users\%USERPROFILE%\Documents\maya\2017\scripts*
* open Maya2017 and drag&drop the **setup.mel** into the viewport
* from then on the zSpace shelf and menu title will always show up

## Deinstall/ Reinstall

* go to *C:\Users\%USERPROFILE%\Documents\maya\2017\scripts* and open the userSetup.mel file in a test editor
* delete the line saying **"//zSpace"** and the follworing line starting with **"source"**
* save and close the file
* in the same directory (*C:\Users\%USERPROFILE%\Documents\maya\2017\scripts*) delete the follworing files/ folders:
  * folder called **icons**
  * file called **maya2017_zSpace_IO.mel**
  * file called **maya2017_zSpace_menu.mel**
  * file called **maya2017_zSpace_polytopals.mel**
* in your **plug-ins** directory (*C:\Program Files\Autodesk\Maya2017\bin\plug-ins*) delete the following files:
  * file called **maya2017_zSpace_JSON_IO.mll**
  * file called **maya2017_zSpace_Polytopal.mll**
* at that point the zSpace plugin is deinstalled
* to reinstall after e.g. pulling a newer version of the plugin follow the steps of **Install** again
---
---
## Plugins
---

### zSpace_IO
##### export curves to TXT
* with individual curves selected it exports them as individual graphs
* with a parent group selected it exports all children curves as one graph

##### import mesh JSON
* check the **import multiple files** to import multiple files and select one file in the dialog window
* the naming of the files has to follow the same structure like the **export meshes to JSON** is producing _(FILENAME_0.json, FILENAME_1.json, FILENAME_2.json,)_
* check **import colors** to receive the color data

##### export meshes to JSON
* check **export colors** to add the color data
* if multiple meshes are selected for export it will export one .json file per mesh with the _0 suffix automatically added
---
### zSpace_3DGS
3D Graphic Statics Plugin
##### documentation will be added soon.
---
### zSpace_M2P
Mesh2Pix Plugin
##### documentation will be added soon.
