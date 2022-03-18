# Meadow
This file is for creating a low poly field of grass. The first (HexPlane) creates clusters with rotations of 1, 61, and 121 degrees (to prevent z fighting). The second (SpritePlane) produces single planes that are aligned to the camera. If you're bringing this into an existing scene update the "Rotation target" field to your main scene camera. The BSDF Shader has been added to its own group and linked to all the materials used in the individual plates therefore changing settings like Roughness will be updated on all plates at once.


Future Development: see if it's possible to generate normal maps to make the grass more 3d.


# Known Issues
Renders best in Eevee. To render in cycles you must set an absurdely high number of transparent bounces (32 or more, along with total bounces) otherwise the grass will be way too dark.

# Attribution
Clover texture is cc0 and was acquired from here: https://opengameart.org/sites/default/files/oga-textures/clover%201.png


Grass, flower, and rock sprite plates were generated from the free version of Chuck_cg's Natural Set found here: https://chuckcg.gumroad.com/l/joGTC
