INSTALLATION

Copy the file add_mesh_roundBrilliant.py into Blender/.blender/scripts/addons (Windows) or Blender/blender.app/Contents/MacOS/.blender/scripts/addons (OSX). Run blender, go into Blender User Preferences and select the Addons tab. Find the "Add Mesh: Brilliant" entry and activate the add-on by checking its checkbox.


USAGE

Once installed, move your mouse cursor into the 3D View and press Shift-A. Clicking Mesh > Brilliant will generate your object with the default or previous used parameters. A interface is provided in the tool bar (press T) where you can change all parameters (mesh will be updated accordingly) and also save presets. To best and most quickly understand each parameter, simply play around and see what each parameter does. 

The following parameters are available:
Number of Segments          default: 16 
Table width                 default: 0.530
Crown height                default: 0.162
Girdle thickness            default: 0.017
Real Girdle                 default: True
Smooth Girdle               default: False
Pavillion depth             default: 0.431
Upper facet factor          default: 0.250
Lower facet factor          default: 0.400
Culet size                  default: 0.000
Retain lower angle          default: False


MORE

The script is tested with blender version 2.69.
If you encounter any bugs, please contact me.
Thanks.


KNOWN ISSUES

I'm working on the following issues:
- make smooth shading option unclickable if girdle_real = False


CHANGELOG

v0.1.5:
- now available on github
- tested with blender 2.69 (r60991)
v0.1.4:
- smooth, real girdle now displayed correctly
v0.1.3:
- user option for smooth shading of girdle (if real girdle is checked)
- upper and lower girdle polygons are more planar now ( < 1 deg distortion in op presets)
- some clean-up (pep)
- changed some default values
v0.1.2:
- crash on execution in editmode or when other objects active fixed
- code clean-up according to coding conventions
v0.1.1:
- all face normals are now consistent
- smooth shading for complex girdle added