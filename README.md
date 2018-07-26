# XDA Keycap 3D Models

These are 3d model of the XDA profile keycaps. I made them from scratch to be used in renders for keycap sets. You may use them for whatever you wish, in accordance with the MIT license. 

They are not for 3D printing, and I cannot verify if they will work at all. Measurements are based off of my XDA Canvas keycaps using a calipers. 

They are UV mapped, so you can use some noise for the top parts to get realistic PBT grain effect. 



## How to add legends to the keycaps

First thing is, I use 3DS Max 2017 so, on your software thing may be different. In general the process should be the same in most 3D modeling programs. 

1. Start with our blank keycap. ![render](https://raw.githubusercontent.com/spooknik/XDA-Keycaps/master/images/01.jpg)
2. We add the text we want, size it, scale it and position it on the keycap. ![render](https://raw.githubusercontent.com/spooknik/XDA-Keycaps/master/images/02.jpg)
3. In 3DS max text is added as a spline, so we need to convert it to polygons and extrude the shape. ![render](https://raw.githubusercontent.com/spooknik/XDA-Keycaps/master/images/03.jpg)
   1. An easy way to do this in Max is to use the symmetry modifier. ![render](https://raw.githubusercontent.com/spooknik/XDA-Keycaps/master/images/04.jpg)
4. We then to need to make sure the 3D shape is intersecting with our keycap top. ![render](https://raw.githubusercontent.com/spooknik/XDA-Keycaps/master/images/05.jpg)
5. Duplicate the top piece (this makes everything much easier)
6. Add a boolean to the duplicated top piece. 
7. Add the legend as an operand. Using 'Intersect' & 'Cookie'. This should produce the result seen below. ![render](https://raw.githubusercontent.com/spooknik/XDA-Keycaps/master/images/06.jpg)
8. You can now add an 'edit poly' modifier to the stack and move the legend up a tiny bit (0.04mm) to prevent z-fighting.
9. Add a different material to the legend. ![render](https://raw.githubusercontent.com/spooknik/XDA-Keycaps/master/images/07.jpg)