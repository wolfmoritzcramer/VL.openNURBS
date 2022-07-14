


DEPRECATED! Please use VL.Rhino.3dm
https://github.com/wolfmoritzcramer/VL.Rhino.3dm




VL.openNURBS


Just started to integrate the openNURBS library in vl.
https://www.rhino3d.com/en/opennurbs

To use it you will need the NuGet https://www.nuget.org/packages/Rhino3dmIO.Desktop
and need to add a search path for VL via a batch file:

SET PATH=%PATH%;c:\path\to\nugets\nativelibs;
vvvv.exe


See also:

https://discourse.vvvv.org/t/opennurbs-rhinoceros3d-grasshopper-3dm/16621

Topics:

  1. Read the relevant contents of a Rhino3D file (*.3dm)
  2. Use the library in context of vl for geometry generation and manipulation
  3. Write back to *.3dm
  4. Use this to have realtime communication from vl to Rhino/Grasshopper and backwards replacing:
      https://vvvv.org/contribution/vulture-exchange-plugin-for-grasshopper-vvvv

If anyone wants to help and contribute, just let me know.
