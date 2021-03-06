#CNC Control Panel: Schematics and Boards#

(C) 2012 Radu - Eosif Mihailescu <radu.mihailescu@linux360.ro>

All files in this repository except `radu-collected.lbr` are licensed under the
**GNU Generic Public License v3**, a copy of whose text can be accessed
 [here](http://www.gnu.org/licenses/gpl.html).

`radu-collected.lbr` alone is hereby licensed under the **Modified BSD (3-clause) License**, a copy of whose text can be found in the `radu-collected.lbr.license` file.

This repository contains [EDA](http://en.wikipedia.org/wiki/Electronic_design_automation) source files for all of the boards in the *CNC Control Panel* project in CadSoft Eagle 6 format. Only the `.SCH` (schematic) and `.BRD` (board) files are provided as all data needed for manufacturing can easily be derived from the former. No guarantee is made as to which minor version of Eagle was used to save the file, but it *may* be the latest at the time of this writing.

The board description files *may* contain routing information or be supplied unrouted. In the former case, the routing artwork *may* have been generated by either Eagle's internal autorouter or [FreeRouting](http://www.freerouting.net/). A 25mil routing grid and 10/10mil trace/space settings will have been used in both cases.

All files included here are compatible with the free version of Eagle (i.e. describe PCBs having no more than 2 layers and measuring no more than 10cm by 8cm each).

Git tags will be used to mark specific revisions that were actually manufactured so that a correspondence between the evolution of the sources and the status of physical by-products can be maintained.

##WARNING##
*Unless and until explictily noted otherwise, the engineering materials here are laboratory quality and neither intended for manufacturing in production quantities nor for distribution (e.g. as kits) to end-users. The design data here does not explicitly follow any widely-accepted safety/security/EMI regulation or standard, therefore any manufacturing and/or usage in connection with live equipment is entirely at your own risk.*
