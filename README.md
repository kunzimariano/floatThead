jquery.floatThead
=================

Float the table header without losing your events or styles.  

[DEMOS and Documentation](http://programmingdrunk.com/floatThead/)



Why do we need another plugin that does this?
=============================================

I was fed up the current state of floating header plugins. They either lose your styles or lose your events, or dont support the edge cases.  
This is why i wrote jQuery.floatThead.

Features:
---------

-   Floats the table header - so that the user can always see it
-   Supports tables with inner scroll bars, or whole page scrolling
-   Horizonal or vertical scrolling
-   Doesnt clone the thead - so your events stay bound
-   Doesnt mess with your styles
-   Works on any table
-   Requires no special css
-   Works with datatables out of the box

Requirements:
-------------

-   jQuery 1.7.x or better
-   Underscore.js 1.3 or better
-   IE7, IE8, IE9, FF10+ or Chrome15+. (in ie7 tables with colspans arent supported)


