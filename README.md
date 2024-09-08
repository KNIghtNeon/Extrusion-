Goal:Create a Babylon.js application that allows users to draw arbitrary 2D shapes on a ground plane, extrude these shapes into 3D objects with a fixed height, and then manipulate the objects by moving and editing their vertices using mode selection buttons.

Features:

1. 3D Scene Setup:
   A ground plane with a grid material for visual reference.

2. Shape Drawing:
   Left Click: Add points to form a 2D shape.
   Right Click: Complete the shape and draw lines connecting the points.
   Draw Button: Enter drawing mode to start creating shapes.

3. Shape Extrusion:
   Extrude Button: Convert 2D closed-loop polygons into 3D objects with a fixed height of 5 units.

4. Object Manipulation:
   Move Button: Switch to move mode to drag and reposition the extruded 3D shapes on the ground plane.
5. Vertex Editing:
   Vertex Edit Button: Switch to vertex editing mode to modify the positions of vertices of the extruded 3D shapes.
6. UI and Visual Cues:
   Buttons for switching between drawing, extrusion, movement, and editing modes.
   Visual markers for the vertices of the drawn shapes.
   Edge rendering for extruded shapes for better visibility.

Run the Application:

1.  Run the index.html file
    OR
2.  Install broswer-sync with http-server to run the applilcation in local
    npm install -g http-server  
    npm install -g browser-sync  
    browser-sync start --server --files "index.html, styles.css, app.js"
