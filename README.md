# CargoPolis
Usage -- REQUIIRES MOOSE.lua run first. Then called with DO SCRIPT from your DCS mission.

What is the point of this? 

Normally, when a player spawns cargo using DCS dynamic cargo they get unlimited access to put anything in that cargo item.
This script regulates what goes into each cargo item.
When the cargo is spawned this script checks the contents and replaces any bullshit.

So, exactly?

If its any of these:

ammo_cargo, 

iso_container, 

oiltank_cargo,

barrels_cargo, 

fueltank_cargo

then

If its ammo_cargo then you only get 3 weapons,

If its an ISO conainer, you get 24 weapons,

if its oiltank, you get a DCS amount of JetFuel,

If its a barrel, you get  a DCS amount of gasoline,

If its a fueltank you get  a DCS amount of diesel.

If its anything else, like aircraft, or a mix, you get the first equipment only or then the right fuel shape.
If its any other shape at all, you get nothing, the script empties and returns everything thats not valid.

Too complicated? You are a user... if you want  to transport a specific weapon, Spawn items into an ammoCrate or ISO container. You get 3 weapons if its an ammo crate and 24 if its an iso container. Anything else is removed. Else if its oil tank you get jetfuel, barrel is gas, and fueltank is diesel, for the sizes and weights DCS expects. So you need to tell users thats all they get if they try to put random stuff in.
