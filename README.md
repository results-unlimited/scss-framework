# scss-framework
A light front-end framework including a grid, a reset and some base styling.

** Grid Instructions **
The grid is named using the common col- naming scheme, but rather than just having set widths like col-2, we have adapted it to be col-1-2. The purpose of this is to have a more semantic naming scheme that makes sense without any external context. The grid is built to be as lightweight as possible, while maintaining as much power as a designer or developer needs in layout. To use a grid part you simply uncomment the line that it is on and then put the class on the relevant markup.

You can read the grid classes as follows: col- designates that this is a grid column sometimes this will be prefixed by a size like lg- for media queries and responsive design, the numbers are simply a fraction. A col-1-2 would be a column that fills 1/2 of the width of the current wrapper, a col-2-3 would fill 2/3 of the current wrapper etc.

** Offset Instructions **
The grid classes that begin with offset- are for semantically offsetting. It is used much the same as the col- prefix, but rather than creating size it offsets the markup to the left by x-x amount. Every media query has a built in offset-0 class that can reset the offset for that screen size.
