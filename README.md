# hardware_mister_de0-nano-soc
**MiSTer add-on board for DE0-Nano-SoC FPGA dev board.**

__Caution__: althoug the version 0.2d was tested and seems to work, consider it as **BETA**. That means there might be slight modifications of the design in the future. There is a bunch of cores for the board released here: [app.box.com](https://app.box.com/s/yjo2nohp7ewukmtkq2o19nnrff4sm0uw) in a form of an SD card image for DE0-nano-Soc board.

__What is it for__: an add-on board for Terasic DE0-Nano-SOC FPGA development board which is compatible (on hardware level) with the [MiSTer project](https://github.com/MiSTer-devel/Main_MiSTer/wiki). Software (cores) are only compatible on the source code level, therefore have to be recompiled for DE0-Nano-SOC. 

__Who is it for__: for adventurous tinkerers who already have DE0-Nano-Soc or DE0-Altas-SOC dev boards. If you don't have such a dev board, then the recomendation is to use DE10-Nano board which is superior to DE0-Nano-SOC and also have official support of MiSTer cores. 

__What can I find here__: you can find a design file for the add-on board (IO board). It can be opened and
edited in free gEDA-pcb editor (http://pcb.geda-project.org/). Also the gerber files are provided - the gerber zip file can be uploaded to PCB manufacturesrs like pcbway or allpcb and possibly others. Both of the mentioned PCB manufacturers had no problem producing the boards in the past using the provided zip file. You can also export your own gerbers directly from gEDA-pcb editor, just press the 'Export' option in the
File menu to do that.

__Manufacturing parameters__:
* Type: Single PCB
* Size: 68 x 99mm (W x H)
* Layers: 2
* Thickness of board: 1.6mm
* Min hole size: 0.4mm
* Min spacing: 6/6 mil
* Finish: any is good, HASL with lead is the cheapest
* Via process: tenting
* Finished copper (thickness): 1oz

__Schematic__:

The board is hardware compatible with the original MiSTer IO board for DE10-nano, therefore the schematic is almost the same (missing TOS link on DE0ns).

[MiSTer schematic](https://github.com/MiSTer-devel/Hardware_MiSTer/blob/master/Addons/IOBoard/iobrd_5.2.pdf)

__Links__:

[official MiSTer hardware for DE10-nano board](https://github.com/MiSTer-devel/Hardware_MiSTer)

[MiSTer forum](http://www.atari-forum.com/viewforum.php?f=117)

[MiSTer forum for DE0-Nano-Soc](http://www.atari-forum.com/viewtopic.php?f=117&t=32651)



