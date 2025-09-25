# Challenge-03-Template
Template
Step 1. Download ProBuilder and Terrain Tools
Step 2. Create Plane shape using Pro-Builder 
Step 3. Modify position to (0,0,0) and scaling in Pro-Builder Shape Properties tab in Inspector (250,0,250)

Use Pro-Builder to create a plane that will act as the first level of the structure.  Create plane and modify the dimensions in x and z direction to 120 and 100, respectively.  Next, subdivide all faces pointing in the y-direction twice and move vertices in the orientation presented on the following image.  
<br><br>

<img width="1128" height="697" alt="Base Plane Faces to Grab 2" src="https://github.com/user-attachments/assets/5389da73-9198-457f-9d6f-f65d0a1360ee" />

*Base Plane Vertices*

Merge the faces presented in the following image and extrude them at a distance of 15.  Afterwards, translate vertices from bottom of extruded surface edges to the outer edge of the created plane.  This will create the angled wall the 'Templo Mayor' has.

<img width="1122" height="711" alt="Manipulate Vertices 3" src="https://github.com/user-attachments/assets/3e90182f-260a-4d48-9cff-22525b9fef7a" />

Then, grab vertices close to plane edges in x direction and distance one segment at x = 55 and -55.  Take the other un-modified segments and set their distance in x-position to x = 50 and -50.  This is done for our future copies of the structures.  

Next step, manipulate vertices for the front face of the structure to angle edges similar to the edges as shown in the figure.  Finally, delete any remaining faces in non-extruded segments in the plane.  (Does not include vertices translation-induced extrude.  Angle of edges in the x-positions have a distance between upper and lower vertices of 5 and in z-positions of 7.5.

For the structure levels, reduce x and z-scaling values by 0.2 and 0.25, respectively.  Afterwards, modify x-position of west and east edge vertices to align with bottom vertices of lower level.  Then modify the other set of vertices in current level to be at a distance 5 from the outer vertices.  (Include photo).  Do this for all levels.

Use Pro-Builder->Create Shape->Stairs to create stairs.  Starting from the base of structure, extend it to top-north edge of upper level and modify scaling and distance as desired.  Following are values used for this project.

x-position = -8.5
y-position = 7.125
z-position = 0.4

x-scale = 1
y-scale = 1
z-scale = (depends on drag when creating stairs).

Create a Pro-Builder plane for stair 'railings'.  Subdivide top face of cube twice and align segments as presented (photo initial) (other photo to show action).  Align plane y-position of bottom structure and manually scale it to then align with top level.  Copy object for middle and left portion; manually position them by only moving x-position of object.  For middle railing, modify x-scale to 1.35 to mimic Templo Mayor layout more accurately.

For top houses, create two planes called 'Blue' and 'Red', extrude (modify).

Finally, for Templo Mayor structure, create a base for the structure to be placed in terrain to be created.  

Download assets from Unity (include all)
