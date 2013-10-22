responsive-tiles-css
====================

pure css responsive tiles compatible with bootstrap


How it works
------------

Set the tile sizes from the container div.
There are 4 sizes at which media queires will activate. To set
these sizes you need to use the following class attributes on 
the container div of the tiles.

	Mobile
	.tile-xm-size

	Tablet
	.tile-sm-size

	Small Desktop
	.tile-md-size

	Large Desktop
	.tile-lg-size

To set the tile size for the different screen sizes the interface
uses the second part of the class attribute 
(tile-xm-THIS PART).
	
	Sizes:
		xm, sm, md, lg



Example HTML
------------

	<div class="container tile-xm-md tile-sm-md tile-md-lg tile-lg-sm">
		<div class="tile t-1"></div>
		<div class="tile t-1"></div>
		...
		<div class="tile t-1"></div>
	</div>