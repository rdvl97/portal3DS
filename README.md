portal3DS
=========
This is a modified version of portal3DS (https://github.com/smealum/portal3DS).  This version currently only differs in it's control scheme.  I have modified controls.c to work properly on O3DS (vanilla build only works properly on N3DS systems as it requires the extra Z bumpers).  

I am also looking into fixing a series of crashes / glitches that occur in various parts of the game.  

##PLEASE NOTE BEFORE ATTEMPTING TO BUILD
This currently REQUIRES the c49d5f49c2ac9818aa3ba66a096de3b36c11d3fd commit of ctrulib from smealum's repository.  It will not compile successfully in any previous or subsequent versions. (I am also looking into fixing this.)  

Pre-compiled files will be found in the builds folder for those who dont know how to build it themselves or just don't want to bother with it.  

##Launching
This can only be launched via hacks such as tubehax (depreciated), browserhax, ironhax, browserhax, homemenuhax, etc.  
Do not attempt to launch directly from homemenuhax as any homebrew app you run will be be restricted to CPU0 and as a result the the physics thread will fail to launch. (see: https://github.com/yellows8/3ds_homemenuhax/issues/6 [also provides simple workaround])

##How to play:  
*The 3ds analogue stick is used to move left right and backwards.  
*Shoot red and blue portals using the Left and Right triggers.  
*Jumping is now the A button.  
*Picking up cubes is now done by holding X button.  
