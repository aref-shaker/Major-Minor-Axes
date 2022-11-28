# Major-Minor-Axes
# Machine Vision-Shape Feature

The major-axis is the longest line that can be drawn through the object by two endpoints.

Endpoints of that line are from border points. For example {(x_1,y_1),(x_2,y_2)} are those points.

With an algorithmic approach, the major-axis endpoints {(x_1,y_1),(x_2,y_2)} can be found by computing the pixel distance between every combination of border points (pixels) in the object boundary.

And then finding the pair that create a line, within the object, with maximum length. The major-axis length of an object is the pixel distance between the major-axis endpoints and is given by the relation:

Sample Major-axis Length = sqrt((x_1 - x_2)^2 + (y_1 - y_2)^2)

As major-axis, minor-axis is the longest line that can be drawn through the object by two endpoints, except that it is perpendicular to the major-axis.
