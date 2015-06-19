ting_new_materials
==================

Description
-----------
This module defines a new page type: New Materials. There you can define a search query which gives the newest materials which meet the search query.
In order to find the newest materials the search query is limited to materials which the library has acquired in the last X days.
The module also limits the search to this year and last year in order to not show reacquired materials.

There are 2 view modes. A normal search results mode and a covers only mode.

Requirements
------------

The library has to send the acquisitionDate to the datawell. Most libraries already do this.

Installation
-----------

Enable the Ting New materials feature


Known issues
-------------
Sometimes there are images missing in the first view of a new page. A refreshing of the page fixes this.