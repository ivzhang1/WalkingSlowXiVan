## Runmin Lu and Ivan Zhang
## WalkingSlowXzHang
## Todo List for this Weekend
- [ ]  Existing, MDL Commands/Features:
	- [ ]  light (Runmin)
		- [ ]  Add a light to the symbol table
		- [ ]  When calculating diffuse and specular: loop through all the lights.
	- [x]  mesh (Ivan)
		- [x]  Use an external .obj file for polygons
		- [x]  Read up on the obj format [here](https://en.wikipedia.org/wiki/Wavefront_.obj_file).
		- [x]  Find example files [here](http://people.sc.fsu.edu/~jburkardt/data/obj/obj.html).
		- [x]  Make sure you deal with .obj files that list quadrilateral faces instead of triangles.
	- [ ]  set (Runmin)
		- [ ]  Assign a value to a knob
	- [ ]  saveknobs (Runmin)
		- [ ]  Save current knob values to a list
	- [ ]  tween (Runmin)
		- [ ]  Produce an animation by going between two knob lists
	- [ ]  shading (Runmin)
		- [ ]  Use different shading techniques / calculating I more or less frequently.
		- [ ]  As discussed in class, a hash table structure can be very helpful for dealing with vertex normals. If you are woking in c, check out [uthash](https://troydhanson.github.io/uthash/).
	- [ ]  save_coordinate_system (Ivan)
	    - [ ]  Save a copy of the top of the stack to the symbol table
	    - [ ]  Use this coordinate system when drawing shapes (extra argument required)

- [ ]  Additions to MDL that require changes to the language:
	- [ ]  New primitive shapes
	- [ ]  Change the behavior of vary
		- [ ]  add a parameter to change how it calculates the change over time
		- [ ]  Linear , Exponential, Logarithmic, Arbitrary equation, etc.
	- [ ]  Anti-aliasing / Super-sampling
	  - [ ]  Reduce pixelated edges by calculating a higher resolution version of the image then reducing it to the intended size
	- [ ]  Texture mapping
	- [ ]  Using vary to move lights.
