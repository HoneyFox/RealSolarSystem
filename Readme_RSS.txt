Real Solar System WIP
This mod will convert the Kerbol System into the Solar System, rescaling, moving, and changing KSP's planets, moons, etc. to match our own.

Thanks to asmi for kicking me into to doing this and offering so much help along the way; to ferram for aeronautics and orbital help (and FAR, which is essential), and for countless time spent helping others get the most from this mod (and me the most from my modding); to ZRM for many ideas and info; to yargnit and MedievalNerd for playtesting extraordinaire; to everyone else who offered suggestions, code, help, cool screenshots...


I take no responsibility for this breaking anything, even if it weren't a WIP and totally in alpha stage.

License: CC-BY-SA

INSTALLATION:
Extract to KSP/GameData.
NOTE: You really should play with the recommended mods. See the Realism Overhaul thread for details.

Planets included (no new graphics for now, excepting Kerbin and Mun)
Mercury is represented by Moho
Venus is represented by Eve
Earth is represented by Kerbin
Moon is represented by Mun
Mars is represented by Duna
Phobos is represented by Bop
Deimos is represented by Gilly
Jupiter is represented by Jool
Io is represented by Pol
Europa is represented by Eeloo
Ganymede is represented by Tylo
Callisto is represented by Ike
Saturn is represented by Dres
Titan is represented by Laythe
Uranus is represented by Minmus
Pluto is represented by Vall

Known bugs:
*Parts are wobbly. Get Kerbal Joint Reinforcement by ferram
*Launch Clamps have issues. Make your own using radial decouplers, or place a stack decoupler under the bottom of your rocket and ring it with trusses.
*Water disappears when looking right at it.
*Terrain is smoother and gentler, and looks blurrier.
*Doubled terrain on some planets (I haven't made new scaledspace meshes yet)

Expect problems. But also expect glee.
===========================
Changelog
v5.6  \/
*Fixed wavelenght color parsing to take four arguments (colors are RGBA after all)
*Added compatibility patches for VisualEnhancements and (thanks, jrandom!) SCANSat
 
v5.5  \/
*Fixed for KSP 0.23

v5.4  \/
*Solar panels finally fixed (really!) thanks to StarWaster.
*Fixed atmo editor keychange

v5.3  \/
*Changed atmo editor to ALT-G
*Fixed Mean Anomaly to be Mean Anomaly at Epoch, fixed handling of it to actually work
*Added new root-of-config property Epoch, for setting starting date. Now, KSP year 0 is 1950.
*Support enabling/disabling atmosphere
*Used metaphor's planet config changes
*Added ability to change science parameters for all bodies (includes config by Medieval Nerd)
*Fixed SOI not respecting minimums

v5.2  \/
*Fixed Titan's atmosphere
*Fixed solar panels (I hope)
*Added configurable atmospheres per Starwaster's work.

v5.1  \/
*Fixed bug where scaledspace meshes were being faded too early (now missing planets appear)
*Fixed Duna's atmosphere end height in the info box.

v5 -- \/
*Every KSP body is now a proxy for a body in the real solar system. However, only the terrains of Kerbin and Mun are edited; the others are merely rescaled.
*Added configurable timewarp. By default 5 and 50 are removed and instead 1 million x and 6m x are added on at the end.
*Edited terrain generator for Kerbin and Mun.
*More support for parameters in the config file.
*Using Majiir's KSPAddonFixed.
*Moved KSC to be nearer the shore.

v4 -- \/
*Switched to new config file system
*Fixed max zoomout on map camera
*Fixed some scaledspace issues
*Changed VAB/SPH camera for more freedom (with a fix: thanks, asmi!)
*Removed 5x and 50x timewarp; added 1 million x and 10m ex timewarp.
*Adjusted solar panels to inverse-square law

v3 -- \/
*Automatically multiplies distances in solar panels' powerCurves by 11 so that they yield rated charge.
*Fixed Kerbin's SMA

v2.1 -- \/
*Went back to scaling Mun's scaledspace transform for now
*Fixed Mun's inclination to avg vs. Earth's equator (since we can't tilt Kerbin's rot axis, we tilt what orbits it)

v2 -- \/
*Added asmi's fix to get KSC, KSC2, and Island land to show up
*Fixed Minmus period, changed Minmus inclination and made it like a captured rock.
*No longer changing Mun's scaledspace representation (it defaults to 0 anyway).

v1 -- \/
*First stable release.