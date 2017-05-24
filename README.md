# old-controllers
Footprints located in footprint.zip file unzip to same dir
Schematics are complete chaos may not resemble any of the actual designs, I just threw things into them and did most of the work in PCB editor.


All of these require external capacitors and usually a 15v powersupply in addition to primary supply.
horizontal & BJT PCB small 50mm x 100mm with 12 mosfets and allegro current sense. Probably works but has many less than ideal layout issues.


Sept PCB Large 2 layer PCB with isolated SI8920 current sensors, works very nicely however SI8920 needs complex opamps to be used with cheaper MCUs. Curremt sense on phase A + C. Causes issue with instaspin which expects phase A + B in 2 sensor mode. Lacks any enable or disable pin on gate drivers, attach power without MCU driving them low = bang!
Sept12 & gan same board with space for 12 mosfets and 12 GaNfets should work but untested.
