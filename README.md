m.2 to Oculink for the Framework 16 dual m.2 expansion card.

Goes in the top (furthest) slot, probably need to remove the dual m.2 expansion card to get clearance for the Oculink port.

Footprint and Library need to be put in their respective folder. For KiCad on Linux it's ~/.local/share/kicad/9.0

Made in KiCad v9. 


There are two "competing" versions that are .. workable.

The stock (no suffix) version, and the "cpr" version.

Both version pass DRC, however the cpr might have better signal integrity. Or worse.

TODO:
1. Tune differential pair skew
2. Finalize GND path traces and plan for GND flood fill
3. (optional) finalize silkscreen comments
