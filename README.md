[ALL YOU NEED TO DOWNLOAD IS THE ZIP FILE, THE EXE(APPLICATION) IS ALL YOU NEED TO RUN AND YOU ONLY NEED TO EDIT PASSWORD.TXT]

@xfzqz game/sim alpha test

edit password.txt with the given password to be able run the .exe
as in
password.txt:
*password*

to run the program
extract the zip
then run xfzqz_alpha.exe !

notes important:
for better experience you should reload the file each sim/game
whilst using v2 or v3(player controlled) balls, setting the health high, will cause greater loading time of spawning balls
this wont affect gameplay speed but is still a latency nuance
(note this is not a bug or an oversight, its just a dev simplification for the moment)

interface:
spawn - spawns given balls, within parameters, note it can be buggy to call spawn more than once, or performance may drop,
this is why its advised to reload the file after each spawn

run - if balls have been spawned runs the sim/game

health, color, weapon(starts at sword) are self explanatory

v2 left most on l and r ball, v2 balls run smoother in game but take some time to load esp at higher health count,
if you have a solid pc and going below 700 on v2s is fine, if you dont mind, the aesthetic and performance hit use v1s, each click cycles through each
note: you cannot use player controlled v1 balls as the class for player controlled balls inherits from v2

note when the rest of the buttons cycle it goes to v1 v2, this is a graphic error im too lazy to change, but the buttons functionality stays the same!
dm(green) l2 toggles off damage effects, doesnt really effect performance or load times at higher h (as damage is only for 1-80) just a visual toggle

cr(cyan) l3 click to turn on control mode, the left most ball now you control via, wasd or arrow keys, as shown in the vid, as before be wary as it will always be v2 style

ps(blue) r2 click if you are not using *splash* or *duality* saves processing time

some known issues, that i am aware of and are fixable but i havent as im too lazy or beacuase as its dev build its an overcommitment to do so
the biggest bug (due to it being a dev build, i havent fixed it) game will crash if healing balls *splash*, *scepter*'s health exceeds 2*base health, annoying but for now it would be extremely slow for this short build to fix
unarmed has some interesting mechanics when controlled as a player
v2 can take time to load esp as health increases
bow is laggy, some other weapons are laggier too, its runs well on my pc around (90fps avg) but idk about your's lol
hammer takes extra time to load, again this is a dev thing that can be easily fixed in the real game
i mean off the top of my head yeah i cant think of anything else, but there are lots of bugs haha so lmk if you find any
