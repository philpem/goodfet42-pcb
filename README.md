GoodFET42 Modified PCB

This is a modified version of Travis Goodspeed's "GoodFET42" JTAG pod design.
The schematic has not been modified (except for renaming "LED1" to "MO" to
indicate its role as the Mode LED), but the PCB has been modified to allow it to
be built by hobbyists with a relatively modest home PCB lab.

Design rules are thus:

  * Top and bottom sides are linked by large vias, well away from ICs. This
    allows the top and bottom sides to be linked with Harwin track pins, pieces
    of solid-core wire, or similar things.
  * Tracks may enter SMD pads from the short side only, perpendicular with the
    long side (in other words: "make the pad longer"). This makes it easier to
    determine whether a short between two IC pins is intentional.
  * IDC connector is soldered on the bottom side only; tracks may connect from
    the bottom layer only. Most home PCB labs don't have through-plating
    facilities :)
  * 16 mil isolation from ground plane to tracks and pads.

Enjoy!

