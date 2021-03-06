---
title: selectHelper
since_version: 1.4.6
---

Whether to draw a "placeholder" event while the user is dragging.

<div class='spec' markdown='1'>
Boolean/Function, *default*: `false`
</div>

**This option only applies to the agenda views.**

A value of `true` will draw a "placeholder" event while the user is dragging (similar to what Google Calendar does for its week and day views). A value of `false` (the default) will draw the standard highlighting over each cell.

A function can also be specified for drawing custom elements. It will be given 2 arguments: the selection's start date and end date (Date objects). It must return a DOM element that will be used.
