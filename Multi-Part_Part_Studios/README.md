# Notes From Part Design Using Part Studios (fundamentals):

* The term “bottom-up design” refers to the design approach of creating parts separately in different part studios, then bringing the parts together in an assembly.

* The term “top-down design” refers to a different approach. It refers to multipart modeling. In multipart modeling, similar parts are designed in one part studio. 
  Top-down design allows for parts to be built in relation to each other. It saves time because one does not have to switch tabs to go from part to part. 
  Also, geometric relationships make the dimensions of the parts in relation to each other.

* The term “multibody design” refers to the approach in top-down design of separating parts to make individual modifications, then merging the parts together again. 
  In multibody design, there is a “multipart studio” or a part studio with several parts in it.

* Multipart studios are based on a master sketch. Below are some attributes of a master sketch:

  * A master sketch is used to make single or multiple parts.

  * It is fine for there to be sketches after it, but those sketches should reference the master sketch.

* The (split) command is key in multibody design. It separates parts for individual design. The boolean command “union” joins parts back together.

* Yet another term: “Bridging.” Bridging refers to the method that multibody design is based upon. It refers to separating parts for individual modification, then rejoining them.

* The function of the part studio is for part design. Assemblies are intended for testing parts and assembling them.

* To create a new part in a part studio, the “new” feature, an option found in commands such as “extrude,” is used.

* The "merge scope" in features or commands allows one to make a command or feature that affects multiple parts. This is useful for the “hole” command. 
  The hole command, when used with merge scopes, can apply to selected parts. 

* In the command “boolean,” the “subtract” option removes overlapping geometry between two parts. It saves time and energy. 

* In a part studio, parts are listed in the order that they were created. If the name of a part in the part studio is clicked, the corresponding part will be highlighted and vice versa.

* Parts can be isolated or hidden by right-clicking on them.

* “Keep tools” for the boolean subtract part keeps the parts that are subtracted from.

**Here are a few bad practices in multipart modeling:**

* The parts in a part studio should be related. Multipart studios are intended for designing parts in relation to each other. Do **not** have unrelated parts in a multi-part 
  part studio.

* In part studios, parts should **not** have multiple instances. If a part will ultimately have several instances, those instances will go in the assembly.
