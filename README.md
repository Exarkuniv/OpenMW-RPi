# OpenMW-RPi
Open Morrowind for the Pi4

this install does take a long time and there are 2 scrpits that need to be run 
first the `openmwdriver` needs to be ran first. that one will be found in the driver section of the menu
then once that is done you can install openmw.
you will need to play around with the settings.

AND do not INSTALL the video files. they will cause the game to crash. 

![Openmw-RPI](https://i.ytimg.com/vi/gK2xs57VgZg/maxresdefault.jpg)


```
wget https://raw.githubusercontent.com/Exarkuniv/OpenMW-RPi/Master/openmw.sh -P $HOME/RetroPie-Setup/scriptmodules/ports/
```

Driver script

```
wget https://raw.githubusercontent.com/Exarkuniv/OpenMW-RPi/Master/openmwdriver.sh -P $HOME/RetroPie-Setup/scriptmodules/ports/
```
