A fan-made multiplayer style deathmatch game 

To install, you need to go into your savefiles directory (e.g. ~/.config/retroarch/saves), as defined in your retroarch.cfg file (or in the RetroArch UI in Settings -> Directories), download the [data files](https://github.com/mmatyas/supermariowar-data/archive/refs/heads/master.zip) in it, unzip the data files, and rename the unzipped directory from `supermariowar-data-master` to `superbroswar`. Then enter `superbroswar` and create an empty file called smw.game.

To run, just do a `retroarch -L superbroswar_libretro.so ~/.config/retroarch/saves/superbroswar/smw.game` (adjusting for your platform of course, e.g. using superbroswar_libretro.dll on Windows). 
