# Proton Game compatibility list
This is a list containing all results I can find on the internet. Help by correcting or expanding this list!

## Common tricks
- Steam Launch options: "-force-d3d9"
- Arch Linux and others: "set DefaultLimitNOFILE=1048576 in /etc/systemd/system.conf and /etc/systemd/user.conf if you're having trouble launching some games with proton" [3]


## List
|Source|Game|Tested on|Status|What to do|
|---|----|---------|------|----------|
|1|Astebreed|Core i7 7700 + Radeon RX 580 8GB	Ubuntu MATE 18.04 LTS + Mesa 18.1.7 + Proton 3.7-5 beta|works perfectly|
|2|Banished||works perfectly
|1|Batman: Arkham Origins|Core i7 7700 + Radeon RX 580 8GB	Ubuntu MATE 18.04 LTS + Mesa 18.1.6 + Proton 3.7-3|random stuttering but still playable|
|2|Battlezone 98 Redux||works perfectly
|0|Beat Saber|Steam Official|works perfectly|
|0|Bejeweled 2 Deluxe|Steam Official|works perfectly|
|2|Bejeweled 3||works perfectly
|2|Crimzon Clover WORLD IGNITION||works perfectly|
|2|Dark Souls 3|RX 480 8GB|works perfectly|
|2|Dead Space||works ok|works only with gamepad, keyboard gets unresponsive after some minutes
|1|Defense Grid: The Awakening|Core i7 7700 + Radeon RX 580 8GB	Ubuntu MATE 18.04 LTS + Mesa 18.1.7 + Proton 3.7-4 beta|works perfectly|
|1|Dishonored|Core i7 7700 + Radeon RX 580 8GB	Ubuntu MATE 18.04 LTS + Mesa 18.1.6 + Proton 3.7-4 beta|works perfectly|
|0|Doki Doki Literature Club!|Steam Official|works perfectly|
|0,1|Doom (2016)|Core i7 7700 + Radeon RX 580 8GB	Ubuntu MATE 18.04 LTS + Mesa 18.1.6 + Proton 3.7-3, Steam Official|works good|put “+r_renderapi 1” in Steam Launch Option|
|0|DOOM II: Hell on Earth|Steam Official|works perfectly|
|0|DOOM VFR|Steam Official|works perfectly|
|2|Eastside Hockey Manager||works perfectly|
|2|ELEX||works perfectly
|2|FRONTIERS||works perfectly|
|1|Elder Scrolls V: Skyrim|Core i7 7700 + Radeon RX 580 8GB	Ubuntu MATE 18.04 LTS + Mesa 18.1.6 + Proton 3.7-3|crashes when exiting the game|
|0|Fallout Shelter|Steam Official|works perfectly|
|2|Fallout: New Vegas||Works maybe|Very crashy, maybe just old drivers, need feedback. antialiasing=off, screeneffect=HDR
|0|FATE|Steam Official|works perfectly|
|0|FINAL FANTASY VI|Steam Official|works perfectly|
|0|Geometry Dash|Steam Official|works perfectly|
|0|Google Earth VR|Steam Official|works perfectly|
|2|GTA Grand theft auto 5||a little bit choppy|
|2|Home Sheep Home 2||works perfectly|
|2|Inside||works perfectly|
|0|Into The Breach|Steam Official|works perfectly|
|2|Jamestown||works perfectly|
|1|Kingdoms of Amalur: Reckoning|Core i7 7700 + Radeon RX 580 8GB	Ubuntu MATE 18.04 LTS + Mesa 18.1.6 + Proton 3.7-3|works perfectly|
|0|Magic: The Gathering - Duels of the Planeswalkers 2012|Steam Official|works perfectly|
|0|Magic: The Gathering - Duels of the Planeswalkers 2013|Steam Official|works perfectly|
|2|Man Hunt||works perfectly|
|2|Max Payne||works perfectly|
|2|Metal Gear Solid V: The Phantom Pain||works perfectly|
|1|Metro 2033|Core i7 7700 + Radeon RX 580 8GB	Ubuntu MATE 18.04 LTS + Mesa 18.1.6 + Proton 3.7-4 beta|intro videos don’t display correctly|
|1|Mitsurugi Kamui Hikae|Core i7 7700 + Radeon RX 580 8GB	Ubuntu MATE 18.04 LTS + Mesa 18.1.7 + Proton 3.7-4 beta|works perfectly|
|0|Mount & Blade|Steam Official|works perfectly|
|0|Mount & Blade: With Fire & Sword|Steam Official|works perfectly|
|2|Monster Hunter: World||works perfectly|
|0,2|NieR:Automata||works perfectly|
|2|Nosferatu: The Wrath of Malachi||works perfectly|
|2|Offspring Fling!||works perfectly|
|2|Orcs Must Die!||works perfectly|
|0|PAYDAY: The Heist|Steam Official|works perfectly|
|2|Prince of Persia 2008||works perfectly|
|0|QUAKE|Steam Official|works perfectly|
|2|Risen 3||works perfectly
|2|Sanctum||works perfectly|
|2|Shantae: Risky's Revenge - Director's Cut||works perfectly|
|2|Skyrim SE||works perfectly|
|2|South Park: The Stick of Truth||works perfectly|
|2|Spelunky||works perfectly|
|0|S.T.A.L.K.E.R.: Shadow of Chernobyl|Steam Official|works perfectly|
|0|Star Wars: Battlefront 2|Steam Official|works perfectly|
|2|Star Wars: Knights of the Old Republic||works perfectly
|2|Tekken 7||works perfectly
|2|The Last Remnant||works perfectly
|1|The Witcher|Core i7 7700 + Radeon RX 580 8GB	Ubuntu MATE 18.04 LTS + Mesa 18.1.6 + Proton 3.7-4 beta|cutscenes are static|
|2|The Witness||works perfectly
|2|THE KING OF FIGHTERS XIII STEAM EDITION||works perfectly|
|1|Torchlight|Core i7 7700 + Radeon RX 580 8GB	Ubuntu MATE 18.04 LTS + Mesa 18.1.7 + Proton 3.7-5 beta|works perfectly|
|0|Tropico 4|Steam Official|works perfectly|
|0|Ultimate Doom|Steam Official|works perfectly|
|2|Vanquish||works perfectly|
|0|Warhammer® 40,000: Dawn of War® - Dark Crusade|Steam Official|works perfectly|
|0|Warhammer® 40,000: Dawn of War® - Soulstorm|Steam Official|works perfectly|
|2|Wolfenstein II||works perfectly|put “+r_renderapi 1” in Steam Launch Option|



# Sources
0. [Steam](https://steamcommunity.com/games/221410/announcements/detail/1696055855739350561)
1. [back2gaming](https://www.back2gaming.com/reviews/b2g-games/pc/steam-play-proton-game-compatibility-list/)
2. [reddit](https://www.reddit.com/r/linux_gaming/comments/9cfgir/which_steamplay_title_are_you_most_happy_to_enjoy/)
3. [reddit](https://www.reddit.com/r/linux_gaming/comments/9c4rs2/if_youre_using_proton_an_archbased_distro_make/)
