== CSS Star Creater ==
This is a very simple script to create "stars" [polygons] for `shape-inside`, `shape-outside` and `clip-path` properties. (See [CSS Exclusions and Shapes](http://dev.w3.org/csswg/css3-exclusions/#basic-shapes-from-svg-syntax) as well as [CSS Masking](http://dvcs.w3.org/hg/FXTF/raw-file/tip/masking/index.html#the-clip-path).)

== Howto ==

The `calculateStar()` star function takes 4 arguments (no type checking yet).

* Number of outside corners.
* Array of radii: `[50,20]` would use 50 as a radii for the outside corner, 20 for the inside corner. Multiple radii possible.
* Array for the size of the canvas. `[100,100]` the width and height would be 100x100 (unit less).
* String that represents the unit type of the output arguments. The unit type will be added to all arguments.