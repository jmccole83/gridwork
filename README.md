# gridwork
A responsive grid framework developed with flexbox in mind. Contains no default styling, forcing developers to think more like a designer and vide-versa. Developed using SASS.

Default styling has been removed for < h >,< strong > and < em > tags. < br > tags are hidden in this version, designers will be forced to properly use margins and padding to layout elements.

Basic funtionality similar to "Bootstrap", columns are wrapped in a class of row and columns given a class to cover the number of columns and the screen size at which they are at.

Grid system uses a 16-column layout as opposed to Bootstrap's 12 and has several different screen sizes.

Screen sizes:
xs: 480px
s: 640px
m: 768px
l: 960px
xl: 1024px
xxl: 1200px
xxxl: 1600px

Support for flexbox included by adding the class .flexrow to a row. Class is optional so no need to include it if not needed.

Contains a print media query also in this version.
