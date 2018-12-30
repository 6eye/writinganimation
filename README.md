![Demo](https://github.com/Shriinivas/writinganimation/blob/master/git.gif)
# Blender Add-on for Generating Writing Animation<br>
This add-on generates writing animation for the selected Bezier curves in blender <br><br>
Supported Blender version<br>
2.79b (Script File - writinganim.py) <br>

# Installation
- Download writinganim.py, open Blender and select File->User Preferences <br>
- Click install Add-ons tab and then Install Add-on from File<br>
- Select the downloaded file <br>
- Check the 'Create Writing Animation' option in the add-ons dialog <br>

After installation, a new 'Writing Animation' tab is displayed on the tools panel in object mode.

# Quick start
Select the bezier curves, enter startig frame and length of the animation and click 'Create Writing Animation'<br>

<a href=https://youtu.be/_tATQJhAkIg> The introductory video</a> provides a detailed overview of the add-on functionality and various options available

# Limitations
If you undo the generate animation operation, the eye dropper selections made previously in 'Properties of' and 'Custom Writer'  options do not function consistently. So after undoing, even if these options show some values, you will have to select the corresponding objects once again (if they were selected before undoing). I am trying to find the root cause.<br>

Exercise caution when using this add-on in production as it's in beta stage<br>

# License
<a href=https://github.com/Shriinivas/writinganimation/blob/master/LICENSE>MIT</a>
