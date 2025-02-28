# Update All ![ViewCount](https://views.whatilearened.today/views/github/theypsilon/Update_All_MiSTer.svg) [![Twitter](https://img.shields.io/twitter/url/https/twitter.com/josembarroso.svg?style=social&label=Follow%20%40josembarroso)](https://twitter.com/josembarroso) <span class="badge-buymeacoffee"><a href="https://ko-fi.com/theypsilon" title="Buy Me a Coffee at ko-fi.com'"><img src="https://img.shields.io/badge/buy%20me%20a%20coffee-donate-yellow.svg" alt="Buy Me a Coffee at ko-fi.com'" /></a></span>
All-in-one script for keeping up-to-date with the [MiSTer](https://github.com/MiSTer-devel/Main_MiSTer/wiki) ecosystem.

This script chains the following scripts:
1. __Main MiSTer Updater__. Downloads most of cores and firmware. You are able to select between these two options:
    * [Official Main MiSTer Updater](https://github.com/MiSTer-devel/Updater_script_MiSTer) maintained by [Locutus73](https://github.com/Locutus73) in the [MiSTer-devel](https://github.com/MiSTer-devel) organization.
    * [DB9 Fork Main MiSTer Updater](https://github.com/theypsilon/Updater_script_MiSTer_DB9) with [Extended Native Controller Compatibility](https://github.com/theypsilon/Update_All_MiSTer/wiki#extended-native-controller-compatibility) for Genesis and NeoGeo/Supergun controllers. Requires [SNAC8](https://github.com/theypsilon/Update_All_MiSTer/wiki#snac8) compatible adapter.
2. [Jotego Cores Updater](https://github.com/jotego/Updater_script_MiSTer). Downloads many advanced cores made by [Jotego](https://github.com/jotego).
3. [Unofficial Cores Updater](https://github.com/theypsilon/Updater_script_MiSTer_Unofficial). Downloads [some cores](https://github.com/theypsilon/Updater_script_MiSTer_Unofficial/wiki) that are not yet released but are fairly stable. Disabled by default.
4. [LLAPI Cores Updater](https://github.com/MiSTer-LLAPI/Updater_script_MiSTer). Downloads [LLAPI cores](https://github.com/MiSTer-LLAPI/Updater_script_MiSTer/wiki) which are compatible with BlisSTer and [LLAMA](https://github.com/bootsector/LLAMA). Disabled by default.
5. [BIOS Getter](https://github.com/MAME-GETTER/MiSTer_BIOS_SCRIPTS) download bios for your installed systems from https://archive.org/
6. [MAME and HBMAME Getter](https://github.com/MAME-GETTER/MiSTer_MAME_SCRIPTS) download roms from https://archive.org/
7. [Names TXT Updater](https://github.com/theypsilon/Names_TXT_Updater_MiSTer). Downloads a community curated names.txt file that enables better core names in the menus.
8. [Arcade Organizer](https://github.com/MAME-GETTER/_arcade-organizer). Creates a folder structure under `_Arcade/_Organized` for easy navigation to all the MRA files.

This script also contains some snippets from the __Updater script__ maintained by [Locutus73](https://github.com/Locutus73).


## Setup

Download this [ZIP file](https://github.com/theypsilon/Update_All_MiSTer/raw/master/setups/update_all.zip) and extract `update_all.sh` to your `/Scripts` folder on your primary SD card.

Then turn on your __MiSTer__, go to the _Scripts_ menu and run this script from there.

It will take around 30 minutes the first time you run it, but later runs should take much less time.



## Alternative Setups

Other setups that might be useful for you:
- [DB9/SNAC8 ZIP](https://github.com/theypsilon/Update_All_MiSTer/raw/master/setups/update_all_db9_snac8.zip): Enables [Extended Native Controller Compatibility](https://github.com/theypsilon/Update_All_MiSTer/wiki#extended-native-controller-compatibility) for Genesis and NeoGeo/Supergun controllers.
- [usb0 ZIP](https://github.com/theypsilon/Update_All_MiSTer/raw/master/setups/update_all_usb0.zip): For people using USB as primary storage. You will be able to run this script from there and install all cores, roms, and MRAs on `/media/usb0`.


NOTE: You should extract also all the INI files contained in these.



## MiSTer Offline Setup

Check [updater-pc](./updater-pc) to download all the MiSTer files from your PC.

Useful if you can't connect your MiSTer to internet.



## Further Configuration

In case you would like to configure Update All so it downloads exactly what you need, you can do it through the Settings screen.

![settings screen](https://github.com/theypsilon/Update_All_MiSTer/raw/master/setups/f66d6ba9-91e1-4581-82a2-c51f7f5424d5.jpeg "Settings Screen")

The Settings screen will show up if you press UP in your controller or keyboard during the countdown showing up right after starting `update_all.sh` in your MiSTer. Please, don't forget to select `SAVE` to keep all the changes you have done before leaving.

## Funding

Consider funding [Alexey Melnikov "Sorgelig"](https://www.patreon.com/FPGAMiSTer) for his invaluable work on the [MiSTer project](https://github.com/MiSTer-devel/Main_MiSTer/wiki).

Check also other core developers that you might want to support:
* [Sergey Dvodnenko "srg320"](https://www.patreon.com/srg320)
* [José Tejada "jotego"](https://www.patreon.com/topapate)
* [Josh Bassett "nullobject"](https://www.patreon.com/nullobject)
* [MiSTer-X](https://www.patreon.com/MrX_8B)
* [furrtek](https://www.patreon.com/furrtek)
* [FPGA PSX Project](https://www.patreon.com/laxer3a)

And finally, if you would like to support my work, you may tip me here:

<a href='https://ko-fi.com/theypsilon' target='_blank'><img height='35' style='border:0px;height:46px;' src='https://az743702.vo.msecnd.net/cdn/kofi3.png?v=0' border='0' alt='Buy Me a Coffee at ko-fi.com' />

## License

Copyright © 2020-2021, [José Manuel Barroso Galindo](https://twitter.com/josembarroso). 
Released under the [GPL v3 License](LICENSE).



## Warning

I take no responsibility for any data loss or any damage you may incur because of the usage of this script.

Please check the README.md of the scripts being called by Update All:

https://github.com/MiSTer-devel/Updater_script_MiSTer<br>
https://github.com/MiSTer-DB9/Updater_script_MiSTer_DB9<br>
https://github.com/MiSTer-LLAPI/Updater_script_MiSTer<br>
https://github.com/jotego/Updater_script_MiSTer<br>
https://github.com/theypsilon/Updater_script_MiSTer_Unofficial<br>
https://github.com/theypsilon/Names_TXT_Updater_MiSTer<br>
https://github.com/MAME-GETTER/MiSTer_MAME_SCRIPTS<br>
https://github.com/MAME-GETTER/_arcade-organizer<br>
https://github.com/MAME-GETTER/MiSTer_BIOS_SCRIPTS<br>
