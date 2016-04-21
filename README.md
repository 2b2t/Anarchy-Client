Wurst client- 2b2t edition

Todo:

figure out copyright/license shit (high)(don't want this project getting shut down due to alex doing an DCMA takedown, which is unlikely due to him doing that to him likely getting massive backlash from his community, but is just an safeguard)
add optifine (high)

Remove/optimized unused/unneeded class files (medium)

    remove wurst google doxxing

    remove wurst capes

    remove twitch

    modify dependencies to only include needed class files

    remove playerfinder

disable wurst updater(may be renabled if can be used and be worthwhile)

optimized default settings/keybinds

add macro mod(lowish)

    remove resource pack scripting(no real use for 2b2t, will remove unless someone gives an valid use of keeping it)
    
    remove server based restrictions used by server companion plugin
    
    merge this somehow with spammer?or maybe remove spammer? not sure what to do with this atm, research needed

add world downloader(low)

add replay mod(low)

    modify to make f3/having the file useless to finding bases shown(move chunks around 0,0 relatively)

add/make some kind of world mapper(medium)

add irc/discord support(low)(may become useless if hause reimplement party chat)

add basic link content checker(low-medium)

add imgur/puush upload support(account login opatinal if possible)

add "strip" mod(auto-mining mod with various parameters)

    "gape" mode(mines out chunks down to bedrock)

    "flatten" mode(flatten area specified,can be set to flatten to Y level set, or flatten between two y levels)

    "resource" mode(auto pathfinds to all blocks specified,setting include ores,trees,more may be added upon request)

    "liquid" mode(removes lava and/or water,likely hardest to implement)

add "notable" features logger(automatically logs notable features to a file for later review,possibility to add setting to announce 
finds on client side chat)

    quality mobs spawner location(2-5+ possible mob spawner farm location, also calculates area where all spawners would be 
    active,maybe shown visually client side,also calculates where to mine out spawners to provide max efficiency farm)
    
    portal logger(mark all portals,more features to be planned upon more research)
    log player positions(useful for "tombing" combat loggers)

add greentext mod(makes all chat go to the server with the prefix >,making text become green,only for servers with this enabled)

add plugin discovery(for maybe finding hidden commands, such as the rumored backdoor,not sure is this is possible for 2b2t, as if i recall, it has something to do with the "tab complete" packet, which may be blocked, this assumption being due to the incapability of tab completing for most commands such as /msg and such, the only exception to that being is /ignore which is likely due to the case sensitivity of it)

add greeting
    
    add custom greetings depending on player(first time join, "hello newfag/newfreind USERNAME,welcome to hell", not first time,  "welcome back UserName", notable player, each one gets their own custom greeting, example: JamesRustles, "Welcome back Archivist and blogger James", The_fox, "Welcome back Junkie The_fox,what are you hopped up on this fine day?)
    
    P2Pish player list, needs more research to figure out how to do this, used to make sure each client produces same message, doubles as username scraper,stats?)(use IRC?)

add "yaw" mod(make it so you don't drift into blocks while walking in the nether)
 
Scrape server greetings for use as menu splashes(low)

make "skybox" of spawn with shaders for menu(low)
    add players in skybox to give more depth to the menu
    (maybe use a certain minecraft render program which name i forget to see if that might work)

make an built in wiki of players,events and places(only useful for newfreinds or for refreshing knowledge of players events or places)
    
    for players, if the player comes into chunks, give a notice saying something like "User_Name is nearby and known, would you like to know more about this player?"; maybe on notice tell player whether its a good idea to trust this player or not, such as saying "run the fuck away if you don't want to die" if it is popbob, or "this player may or may not rape you, use self-judgement" if it is a spawnkiller
    
    for locations, stumbling into a known area such as gape 1.0(1k -1k), put up an similar notification as the player notification.
