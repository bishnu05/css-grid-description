# css-grid-description
**CSS grid Terminology**

Grid container
Grid Item
Grid line
Grid cell
Grid Track
Grid Area
Grid gap
1. A grid is a structure of intersecting lines or bars. It is used as a guide to divide and organize a space. Usually, a grid is two-dimensional, and the lines are evenly spaced, intersecting at right angles.

Grids are useful for organizing and ordering information. When information is organized in a grid structure, any unit of information is located by specifying two of the intersecting lines.

In maps
Often, maps are overlaid with a grid to help define locations. On a world map, latitude grid lines are oriented parallel to the equator, and longitude grid lines are oriented perpendicular to the equator. By specifying a latitude and a longitude, you can uniquely identify any point on the map.

In spreadsheets
In a spreadsheet, information is organized in rows and columns, forming a grid. Individual locations on the grid are called cells. Any cell in the spreadsheet is uniquely identified by its column id (usually a letter) and row id (usually a number). For example, the cell located at the intersection of column C and row 13 is identified as cell "C13."

In graphic design
Many graphic design applications provide a grid that is displayed over or under the contents of an image. The grid helps the artist to visually align graphic elements. Some programs provide the option to snap elements to points on the grid. When an artist using the snap feature moves an item near a point on the grid, the element "snaps" (moves automatically) to that precise location.

2. In web design, CSS Grid is a technology for defining the layout of a web page with CSS (cascading style sheets). It provides attributes and logic for organizing visual elements in two dimensions on the web page.

Although not yet an official W3C specification, CSS Grid is supported natively by all major browsers since October 2017. It is a core component of several CSS frameworks, such as Bootstrap.



## when to use grid and when to use flex?
**1. Dimensionality and Flexibility:

Flexbox offers greater control over alignment and space distribution between items. Being one-dimensional, Flexbox only deals with either columns or rows.
Grid has two-dimension layout capabilities which allow flexible widths as a unit of length. This compensates for the limitations in Flex.

2. Alignment:

Flex Direction allows developers to align elements vertically or horizontally, which is used when developers create and reverse rows or columns.
CSS Grid deploys fractional measure units for grid fluidity and auto-keyword functionality to automatically adjust columns or rows.

3. Item Management

Flex Container is the parent element while Flex Item represents the children. The Flex Container can ensure balanced representation by adjusting item dimensions. This allows developers to design for fluctuating screen sizes.
Grid supports both implicit and explicit content placement. Its inbuilt automation allows it to automatically extend line items and copy values into the new creation from the preceding item.

