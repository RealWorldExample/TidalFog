# TidalFog

Version 1.0.0 only Mod BetterLavaSpawns updating the gamemode _floor_is_lava to exclude spawns that are on buildings and are potentially oob (out of bounds) this makes a huge difference playing on complex, crashsite, and drydock.

Needs to dynamically control the fogheight in a riff_floorislava game. It currently does nothing.

# How to use

Add this mod to the mods folder of you dedicated server

Add "riff_floorislava 1" to your +setplaylistvaroverrides located in your ns_startup_args_dedi.txt
                            v------Somthing like this------v
+setplaylist private_match +ns_private_match_only_host_can_change_settings 2 +setplaylistvaroverrides "run_epilogue 0 classic_mp 0 timelimit 12 riff_floorislava 1"

