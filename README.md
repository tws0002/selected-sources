# awesome-works
------------------------

* [Arnold-Shaders](https://github.com/iceprincefounder/awesome-works#arnold-shaders)
* [Katana-Plugins](https://github.com/iceprincefounder/awesome-works#katana-plugins)
* [Katana-SuperTools](https://github.com/iceprincefounder/awesome-works#katana-supertools)
* [OSL-Shaders](https://github.com/iceprincefounder/awesome-works#osl-shaders)
* [Standalone-bin](https://github.com/iceprincefounder/awesome-works#standalone-bin)
* [UE4-Plugins](https://github.com/iceprincefounder/awesome-works#ue4-plugins)
* [USD-Scripts](https://github.com/iceprincefounder/awesome-works#usd-scripts)

------------------------


## Arnold-Shaders

### parallax_map

The parallax_map shader is the implementation of OpenGL parallax map in Arnold, with this shader, we can create very realistic looks of environment with normal map and bump(depth) map, the look is very simillar to displacement map but much more efficient then displacement shader.

![the_rocks](https://user-images.githubusercontent.com/16664056/43674885-e96cf390-980c-11e8-9a1d-b321ed3eef29.png)

### texture_repetition

The texture_repetition shader would repeat a texture into a complex one but with no stitch. With a simple and small texture, we could get a huge size but randomized map.

![the_noise](https://user-images.githubusercontent.com/16664056/43674887-f0f61f4c-980c-11e8-922c-a4746ff5210c.png)

### triplanar_plus

The triplanar_plus shader would project three texture images into three axis(x,y,z), the object without UV information would still get nice shading and the Pref attribute would still get smooth normal.

For more details: [Arnold-Shaders](https://github.com/iceprincefounder/awesome-works/tree/master/Arnold-Shaders).

![the_house](https://user-images.githubusercontent.com/16664056/43674890-f6f6f5ba-980c-11e8-8ee7-6a40046d9eb2.png)

## Katana-Plugins

### LightViewerModifier

The LightViewerModifier plugin would customize the light shapes in Katana viewer for Arnold light.

For more details: [Katana-Plugins](https://github.com/iceprincefounder/awesome-works/tree/master/Katana-Plugins).


## Katana-SuperTools

### ArnoldLightGafferPackage

The ArnoldLightGafferPackage is a GafferThree Supertools that contents all presets of lights and light filters we could create them easily.

### MaterialXBake

The MaterialXBake tools is a Katana Supertools node, since Arnold support MaterialX but didn\`t provide any tools to export MaterialX file so I create Katana version MaterialXBake node to export shading networks from Katana, get ready to replace KLF(Katana look file) file in our pipeline in some special shots.

For more details: [Katana-SuperTools](https://github.com/iceprincefounder/awesome-works/tree/master/Katana-SuperTools).


## OSL-Shaders

We find that there are some shaders we use every day and every where, for gennaral purpuse, I wrote it as an OSL shader so that we could handle it easily. 

For more details: [OSL-Shaders](https://github.com/iceprincefounder/awesome-works/tree/master/OSL-Shaders).


## Standalone-bin

### EXRAutoCropper

The EXRAutoCropper tool would read the EXR file and auto crop it, then write the image data into a new one with optimized RGB information and Scanline type which NUKE preferred so that we would get a pretty pure EXR file for compositing, suporting muti-channel EXR file.

## OpenEXRResizer

The OpenEXRResizer is a C++ command executable file to resize EXR files, supporting muti-threads and cropped file, the resized files could be the proxy files in compositing.

For more details: [Standalone-bin](https://github.com/iceprincefounder/awesome-works/tree/master/Standalone-bin).


## UE4-Plugins

### Cache_Actor

The Cache_Actor plugin would read a custom animation cache file and gennarate the animation frame in Unreal Engine, very similar to Alembic cache but we store vertex data into a texture file.

### DownloadAssets

The DownloadAssets plugin would download project file from server which exported from Maya pipeline.

### ImportAssets

The ImportAssets plugin would import all Maya assets into Unreal Engine and assign the materials automatically.

### MiliBlueprintLibrary

Some useful Blueprint node in Unreal Engine.

### MiliToolBox

A tool box shelf.

For more details: [UE4-Plugins](https://github.com/iceprincefounder/awesome-works/tree/master/UE4-Plugins).


## USD-Scripts

A USD script library which contents all functionality to tanslate a Almebic based pipeline into a USD based one, from Maya to Katana.

For more details: [USD-Scripts](https://github.com/iceprincefounder/awesome-works/tree/master/USD-Scripts).
