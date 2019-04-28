# cohdocs
Repo for CoH i25/24 Docs
------------------------------
## Server Incoming Commands and SPs

+ This folder contains SPs that are run at certain triggers
+ The ents update sp happens at regular intervals and this is what saves the last state of the character.
+ The map event update sp is triggered on an event starting on a particular map.
+ In both files, the variable values are set at the end, and in these files they are listed in order, starting from @P1's value.

## PDiags

+ This folder will hold reference PDFs that detail what each P# refers to. 
+ P#s are NPC dialogues that are called and referenced throught the server-side bins.
+ _This is currently a WIP_ so not all dialogues are available.
+ Ideally I will combine all of them into one searchable document at the end.
+ **quickchat** breakdown is also found here.
+ There is a detailed guide on how to create new popmenus or edit the existing quickchat menu already in-game.

PDFS
------------------------------
PDFs are converted schemas with information on each indvidual column.

They are available individually in the folder OR as a zip for convenience.

**USE THESE AT YOUR OWN RISK!**



GM Commands
-----------------------------
This contains a text file of GM Server-sided commands and their required access levels to use.

Could help if you need GMs (or higher-level GMs) but not Admins.

~~As far as I can tell, there is currently no way to edit which level has access to which commands(to make your own GMs, for instance).~~

In the I24 Binaries there is c file called cmdgame.c, you should theorhetically be able to edit access levels or add new commands to the game in I24.



Other Files
----------------------------
**cebsnar.txt**

As far as I can tell, this is being used by the server, so make sure to place it back into the dir it came from **(\data\texts\English)**

Add words here you want censored from chat by the client when "Filter Profanity" is on. Or leave them out. Funny read anyway.

**title.def, v_title.def, p_title.def, i_titles.def**

These files determine the available titles for players to choose from, by origin. 

Title = Heroes

V Title = Villians

P Title = Prae

I Title = Incarnate?

These files also need to be placed in the right dir **(\data\texts\English)**



**Other files will be added to this Repo as I find them, if they're useful.**


TODO:
---------------------------------
Dialogue Builds

Badges

AutoCommand Document

ETC.

