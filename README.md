Leaflet.SimpleGraticule
------------
A graticule for maps in Leaflet's L.CRS.Simple coordinate system.Code inspiration came from Jan Pieter Waagmeester's fantastic
[Leaflet.Grid](https://github.com/jieter) for world projections. It is very similar in nature but assumes an infinite flat plane.

Usage
-----
Adding L.SimpleGraticule:

```JavaScript
var options = {interval: 20,
               showOriginLabel: true,
               redraw: 'move'};

L.simpleGraticule(options).addTo(map);
```
####Options:####
- interval: The spacing in map units between horizontal and vertical lines.
- showOriginLabel: true Whether or not to show '(0,0)' at the origin.
- redraw: on which map event to redraw the graticule. On `move` is default but `moveend` can be smoother.

Notes
-----
- This is my first open source contribution. I appreciate feedback on any topics!
