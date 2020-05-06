
Fan blows onto the underside of the bed - this causes the bed to work less efficiently
-- To solve this relocate the electronics board, rear electronics case (by teaching tech) or remore mount for printer in enclosure.

Initial firmware questionable thermal protection settings
-- It is best to flash Marlin 1.1.9 on the standard creality boards.
-- For board upgrades 32 bit is reccomended running the latest Marlin 2.0

Extruder limitations (under testing)
-- Modified extruder gear for more grip

Bowden tube limitations (under testing)
-converted to direct drive, allows printing of flexible filaments
-This increases the extruder weight which is counterproductive for resonance

Ghosting/ringing/resonance especially when printing at higher speeds
Rigidity - raises the natural frequency of the frame
Damping - absorbs the unwanted energy

general reliability
first layer performance impacted with flexible bed-flexing to remove prints causes warping of the bed
manual mesh bed leveling can help address this issue but best solved with a Auto bed leveling sensor
Bl touch chosen for my setup as it can work with any bed surface
