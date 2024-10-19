# E3LDoN based on LDoN.mac 1.0 by TreeHuginDruid

Use /E3LDON HELP or /E3LDON while the macro is running for a list of commands.

Use custom navmesh files provided for all LDoN zones.
===============================================================================

Based off of LDON.mac v5.0 by Cannonballdex
June 10, 2021
Credits: TreeHuginDruid, CWTN, earthsnemesis, Kaen01 and others on the forums at Redguides
-----------------------------------------------------------------

LDON Aventures Available at Commonlands, South Ro, North Ro, Butcherblock & Everfrost
You need at least 3 group members. One can be a mercenary

Take your group to a starting zone and run /mac E3LDON to start the macro

After the first run two ini files will be created.
LDoN_YOURTOOONNAME.ini and LDoNMobIgnore.ini

(A populated E3LDoNMobIgnore.ini is provided in this distribution.)

You can edit these files directly or use the commands below while the macro is running.

-----------------------------------------------------------------

USAGE:
Use /E3LDON HELP or /E3LDON while the macro is running for a list of commands.

-----------------------------------------------------------------

If you want your group to assist and follow the group leader (Requires EQBC or DanNet
/E3LDON GroupNavToMe on

There is Click Buff Settings and Click Damage Settings in the macro for the group leader
You will need to edit the items to use this section and turn it on
/E3LDON UseClickBuffs on (and) /E3LDON UseClickDamage on

Switch to SwarmPull method in game:
/E3LDON SwarmPull on (to use SwarmPull)

Switch to SinglePull targetting in game:
/E3LDON SwarmPull off (to use SinglePull)

Switch camp selection method in game:
/E3LDON ThemeCheck on (to use SMarrT Theme Check method)
/E3LDON ThemeCheck off (to use SMarrT RoundRobin method)

Signal an annoying Beep sound when the group leader gets stuck
/E3LDON UseBeep on (or) /E3LDON UseBeep off

Foraging - If you want to forage after a task ends. Set in 10ths of a second 18000 max is 30 minutes. Off is 0
/E3LDON ForageTime 18000 (or) LDON ForageTime 0

Tips: Set MQ2Nav window, Debug Tools, Door Handler Debug to 25.000 if you have issues with doors in takish

-----------------------------------------------------------------
While the macro is running, To add mobs to ignore, target the mob and type

/ignorethis -- temporarily ignores your current target

/ignorethese -- temporarily ignores all targets with your current targets name

/permignore -- permanently ignores all targets with your current targets name

-----------------------------------------------------------------

