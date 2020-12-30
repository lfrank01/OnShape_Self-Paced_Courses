# Notes From Part Design Using Part Studios (fundamentals):

* The tangent (t) constraint is helpful for making sure a line does not pass through a circle. 

* A line with the tangent constraint with the only touch a circle at one point. It is different from a coincident constraint in that a coincident constraint will allow a line to intersect a circle. A tangent line is able to keep on traveling infidelity in both directions while still touching the circle at only one point. A secant is a line that touches a circle at two points. 

* An ellipse is basically an oval.

* There is a transparency slider at the bottom of the features.

* For a sketch or feature, clicking the final button (located at the bottom of the sketch box) will make a preview that can have its dimensions adjusted.

**Revolves:**

* The revolve axis is the center of rotation for the revolve command.

* Moving a cursor past the axis of rotation when dimensioning a sketch will change the dimension from a radius to a diameter dimension.

* There are revolve types as an option when setting the axis of rotation, such as one direction, symmetric, full (not sure what full entails), and two directions.

**Sweeps:**

* It is helpful to make a path and then a profile when creating a sweep.

* A construction plane can be created at a point, allowing the path of the sweep to be extended in different planes.

* The sketch plane of a sweep’s profile must be normal to the sweep path. The profile (circle, for example) must be coincident or connected to the sweep path (some line).

* Vertical and horizontal constraints can be used to align lines or points to an axis.

* Naming sketches is a helpful organizational tool, such as naming a sweep sketch “Path Sketch.”

* A constraint will show up as blue if it is referencing geometry that is of a different sketch.

**Lofts:**

* Loft entities should be selected in a specific order, such as first to last; otherwise, twisting can occur in the loft.

* Loft entities should ideally have the same amount of vertices. The split command is useful in creating vertices so that a circle and square in a loft will have the same amount of vertices.

* Lofts should not have a loft entity with closed geometry, such as a circle inside a square. It is better to do two separate lofts instead of one loft that uses two shapes that overlap.

**Reference planes:**

* Reference planes can be created by selecting the “planer” command in the top right corner. Alternatively, and more usefully, selecting the geometry that the plane will be based on and then selecting the “planar” command will autoselect a plane that should work.

* There are different planes, each with helpful uses:

  * An offset plane creates a plane that is offset from a plane. The offset distance and direction can be changed.

  * A plane point will intersect a chosen point.

  * The line angle plane will pass through a line at an angle.

  * The point normal plane will make a plane that is normal to a selected entity, and then it will go through another selected entity.

  * The three-point plane will make a plane that passes through three points.

  * The midplane will make a plane that is in between to planes that are selected. It also works if the selected planes are not parallel.

  * The curve point plane passes through a point and is normal to an entity that is selected. It is useful for sweeps.

**Boolean options:**

* Boolean options come with most OnShape features or commands. Here are the boolean options:

  * “New” creates a new part in a part studio. 

  * “Add” will merge a part with a selected part. The “Merge Scope” option asks for which parts to add to.

  * “Remove” will cut away from a part. There is a merge scope that allows the “Remove” command to cut through more than one part

  * “Intersect” creates a part that is made from the shared space of a part and a feature.

* The option “Select all” makes every part in the part studio part of the merge scope.

**Chamfer, Fillet, and Draft:**

* “Tangent propagation” applies a fillet pr chamfer to all tangent lines.

* A variable fillet will make the fillet value that of a variable.

* Chamfers can have options of equal distance, two different tangent distances, and a chamfer option with a selected angle and distance.

* Chamfers and fillets should ideally be done after a part is designed; otherwise, they might interfere with other geometry.

* A draft is a planar cut or extrude.

**Hole:**

* The hole command creates a hole that can be customized.

* The option “Blind in last” for a hole is helpful for choosing how deep a hole should cut into one part out of a series of parts.

* The option “Start from sketch plane” is helpful for changing where a hole starts based on another sketch or point.

**Patterns:**

* Creating a pattern with the “new” option will make new, individual parts in a part studio.

* A face pattern is more efficient than a part pattern when both options can be used. The difference between the two is that a part pattern uses an endpoint, meaning it can adopt the quality of going toward the very edge of something, even if it makes that individual part a different size than the original.

* A linear pattern makes a pattern parallel to a line or normal to a face.

**Rib:**

* The “Rib” feature requires a sketch beforehand. It can be used to create a medium between two surfaces.

* The option “Apply per instance” for the rib will use the end type for each rib, making it go to the end of the part.

**Shell:**

* The “Shell” feature can be used to hollow out a feature.

* The “Faces to remove” option allows one to choose faces that are removed from the hollowed geometry. It is useful for making a hole in a bottle or canister. 

