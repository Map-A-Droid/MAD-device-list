# MAD-device-list
List of devices known to work or not to work with the listed ROMs and Magisk versions (pass Safety Net, run Pogo along with RGC and stuff)

## Compatible Android TV boxes:
Further information about ATVs and how to use them can be found on the [MAD-ATV wiki](https://github.com/Map-A-Droid/MAD-ATV/wiki)

| Modelname | CPU | Image | 32bit | 64bit | Flashing via | Effort | Notes |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [A95X F1 (2GB/16GB)](https://www.amazon.de/gp/product/B07DCL3YPZ/) | S905W | [MAD rom](https://github.com/Map-A-Droid/MAD-ATV/releases) | Yes | Yes, beta, no WiFi | USB A to USB A | ~20 min. | **Recommended!** Double check to get a 2 GB RAM version! Get this ATV, if you're new to it. There are no known fakes of this model, so you should be able to get the F1 from any reseller.|
| [X96 Mini (2GB/16GB)](https://www.amazon.de/dp/B078ZF9YT6/) | S905W | [MAD rom](https://github.com/Map-A-Droid/MAD-ATV/releases) | Yes | Yes, beta, no WiFi | SD Card or USB A to USB A | ~20 min. | Double check to get a 2 GB RAM version! Also important to note: there are fake versions of this ATV out there. These fakes **CANNOT** be flashed! One indicator to check for is the MAC address. Good ones start with `900E`. You can also check the board: <br>Good versions [link](https://i.imgur.com/xh1QEEj.jpg)<br>Bad versions [link](https://i.imgur.com/MT3nV35.jpg), [link](https://i.imgur.com/OVYW76r.jpg) |
| [Sammix R95S 2GB/16GB](https://www.amazon.com/gp/product/B0759V2VHF/) | S905X | [MAD rom](https://github.com/Map-A-Droid/MAD-ATV/releases) | Yes | No | USB A to USB A | ~20 min. | Readme file in the ATV repository |
| [T95 S1 2GB/16GB](https://www.amazon.com/gp/product/B07F8X1PQR/) | S905W | [MAD rom](https://github.com/Map-A-Droid/MAD-ATV/releases) | Yes | No | USB A to USB A | ~20 min. | Warning: half these are coming unusable, buy at your own risk |
| [Yagala YA-II](https://www.amazon.de/dp/B07HD77CPC) | S905W | [MAD rom](https://github.com/Map-A-Droid/MAD-ATV/releases) | Yes | No | SD card (USB A to USB A untested) | ~20 min. | Only tried on one device! ROM and procedure exactly the same as X96 Mini |
| [A95X Nexbox (A95X-B7N)](https://www.aliexpress.com/item/4000186693551.html?spm=a2g0o.productlist.0.0.708f2038EBJeA5&algo_pvid=48125060-4ca6-483c-be62-f772970cfcd1&algo_expid=48125060-4ca6-483c-be62-f772970cfcd1-0&btsid=0ab6d69515964500069758358efa28&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_) | S905W | [MAD rom](https://github.com/Map-A-Droid/MAD-ATV/releases) | Yes | Yes, beta, no WiFi, Use A95X F1 Rom | USB A to A | ~20 min. | Box comes in 2 forms S905W and S905X, only S905W has been tested. Only tried on one device! ROM and procedure exactly the same as A95X F1 |
| [TX9S](https://www.amazon.com/gp/product/B08BL19CQ8) | S912 | [MAD rom](https://github.com/Map-A-Droid/MAD-ATV/releases) | Yes | Yes, beta | USB A to A | ~20 min. | Device seems to be end-of-life and stock is mostly limited. 2GB variant works just as good as the 3GB variant.|
| [Yutmart S10 Mini](https://www.aliexpress.com/i/32994137462.html) | S905W | [MAD rom](https://github.com/Map-A-Droid/MAD-ATV/releases) | Yes | Yes, beta, no WiFi, Use A95X F1 Rom | USB A to A | ~20 min. | Board, ROM, and procedure exactly the same as the A95X F1 |

## Compatible Consoles:
| Console | Magisk | Smali | Effort | Notes |
| :---: | :---: | :---: | :---: | :---: |
| [Nintendo Switch](https://www.amazon.com/Nintendo-Switch-Gray-Joy/dp/B01LTHP2ZK) | 18.1 | Yes | Requires a "hacked" Switch | [Installation](https://forum.xda-developers.com/nintendo-switch/nintendo-switch-news-guides-discussion--development/rom-switchroot-lineageos-15-1-t3951389) & [Steps to get PoGo to work](https://www.reddit.com/r/SwitchHacks/comments/cjmkh5/pokemon_go_running/eveb4ct) |

## Compatible Smartphones:
| Modelname | OS | Magisk | Rem. battery | Run w/o battery | Effort | Notes |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Acer Liquid Zest Plus T08 | Stock | v19 | N/A | N/A | easy | Boot TWRP from [here](https://forum.xda-developers.com/android/help/help-root-acer-liquid-zest-plus-z628-t08-t3542001) to root and install Magisk |
| Google Nexus 7 (2013) | [LineageOS 14.1](https://download.lineageos.org/flo) | v18 | [yes/hard](https://www.youtube.com/watch?v=BzknIzaAijQ) | N/A | easy | Disabling fused location causes GPS to stop working entirely, but does not rubberband with this enabled |
| Google Pixel | Stock (Android 8.1 Oreo) | v18.1 | N/A | N/A | mid | Do not use Link2SD for RGC as it's an A/B phone, use [Systemizer](https://github.com/Magisk-Modules-Repo/terminal_systemizer) instead |
| HTC Desire 430 | Stock | v18 | N/A | N/A | mid | 1.5GB RAM so slow but works well, no custom ROMs available and stock is kinda bloaty. Autostarting of pogodroid/RGC requires third party app like tasker |
| HTC Desire 626 | Stock | v18 | [yes/mid](https://www.youtube.com/watch?v=_Zt4Inymy98) | N/A | mid | No custom ROMs available and stock is kinda bloaty. Autostarting of pogodroid/RGC requires a third party app like tasker. |
| HTC One -  M7 | [LineageOS 14.1](https://forum.xda-developers.com/htc-one/orig-development/rom-lineage-os-14-1-t3531331) | v18 | [yes/hard](https://www.youtube.com/watch?v=U0ePbtqaPVA) | N/A | mid | heat |
| HTC One -  M8 | [LineageOS 14.1](https://download.lineageos.org/m8) | v18 | [yes/hard](https://www.youtube.com/watch?v=zNQM8Nb632Q) | N/A | mid | heat |
| Huawei Nexus 6P | LineageOS 15.1  | v19 | N/A | N/A | easy | - |
| Huawei P Smart | Stock | v18 | [yes/hard](https://www.youtube.com/watch?v=ngeka8enG00) | N/A | very hard | Requires paid bootloader unlock through DCunlocker and building own kernel with CONFIG_HUAWEI_PTRACE_POKE_ON=y and CONFIG_SECURITY_SELINUX_DEVELOP=y |
| LeEco Le 2 X526 | LineageOS 15.1 | v18 | N/A | N/A | easy | - |
| LG Aristo | LineageOS 14.1 for stylo 2 plus by messi2050 | v18.1 | N/A | N/A | mid | Needs safetypatcher magisk module. |
| LG Aristo 2 | LineageOS 14.1 | v19 | yes | N/A | mid | 1) Downgrade to Nougat or earlier to allow Fastboot commands to work. 2) Use TWRP and LineageOS 14.1.zip from here: https://androidfilehost.com/?a=show&w=files&flid=285484. 3) Wipe Data partition with TWRP and format with ext4 to get around any encryption, then reboot back to TWRP.  4) Use Smali Patcher to alleviate rubberbanding. |
| LG G3 (Canadian d852 Telus/Koodo) | [LineageOS 15.1](https://download.lineageos.org/d852) | v19 | yes | N/A | hard | Bootloader not unlockable so must be [downgraded to Lollipop](https://forum.xda-developers.com/showpost.php?p=64624353&postcount=3) and then [rooted via exploit](https://www.henrychang.ca/lg-g3-d852-teluskoodo-version-rooting-and-twrp-recovery-installation/) before going to LineageOS |
| LG G5 | LineageOS 15.1 | v18 | [easy](https://www.youtube.com/watch?v=IjZrQUclt2Y) | N/A | easy | Likes to drop WiFi. |
| LG Nexus 5 | LineageOS 14.1 | v18 | N/A | N/A | easy | Heat, slideshow - needs vps_delay for quests to keep up. Works well for raids. |
| LG Nexus 5X | [LineageOS 15.1](https://download.lineageos.org/bullhead) | v18 | [yes/mid](https://www.ifixit.com/Guide/Nexus+5X+Battery+Replacement/60275) | N/A | easy | - |
| LG V30 | Modified Stock | v18.1 | N/A | N/A | Easy | US998 only. [Root guide](https://forum.xda-developers.com/showpost.php?p=76584629) Contact Beavis for more info |
| Motorola E4 - Plus | [LineageOS 14.1](https://androidfilehost.com/?fid=5862345805528046723)(Mediatek CPU(nicklaus)) | v18 | N/A | N/A | mid | - |
| Motorola E4 (Mediatek) | Stock/[LineageOS Unofficial](https://forum.xda-developers.com/moto-e4/development/rom-lineageos-14-1-moto-e4-mediatek-t3717926) | v18 | N/A | N/A | easy | Device is available with Qualcomm processor as well - untested |
| Motorola E5 - Play (james) | [firmware](https://forum.xda-developers.com/moto-e5/how-to/firmware-moto-e5-xt1944-4-dual-sim-t3820901) [Directions](https://forum.xda-developers.com/moto-e5/how-to/guide-root-twrp-moto-e5-play-explained-t3856182) | v18.1 | N/A | N/A | mid | youtube FRP unlock method worked for me |
| Motorola G4 - Plus | [LineageOS 15.1](https://forum.xda-developers.com/moto-g4-plus/development/rom-lineageos-15-1-unofficial-t3768420) | v18 | N/A | N/A | mid | - |
| Motorola G4 | [LineageOS 14.1 unofficial](https://forum.xda-developers.com/moto-g4-plus/development/rom-cyanogenmod-14-1-t3522101) | v18 | [yes/mid](https://www.ifixit.com/Guide/Motorola+Moto+G4+Battery+Replacement/99582) | yes/soldering | easy | Runs without battery (LM2596 Stepdown Converter, 12V 1A power supply) contact @exilhanseat for more information |
| Motorola G5 | Stock | v18 | N/A | N/A | hard | their firmware for 7 has bugs, use android 8 and consider formatting data ext4 |
| Motorola X4 | [LineageOS 16.0](https://download.lineageos.org/payton) | v18 | N/A | N/A | easy | A/B Device requires at least one OTA update before root or a BlankFlash is required. Install RGC as Sys-priv app with Systemizer. Avoid the Amazon Prime version. Android One version untested. SmaliPatch required. ARM64 injection. |
| OnePlus 2 | [LineageOS 15.1](https://wiki.lineageos.org/devices/oneplus2/install) | v18 | [yes/mid](https://www.youtube.com/watch?v=rtYkV0YiB9g) | N/A | easy | - |
| OnePlus 3 | [LineageOS 15.1](https://forum.xda-developers.com/oneplus-3/oneplus-3--3t-cross-device-development/rom-lineageos-15-1-oneplus-3-3t-t3739169) | v18 | N/A | N/A | easy | - |
| OnePlus 3T | [ArrowOS 8.10](https://forum.xda-developers.com/oneplus-3/oneplus-3--3t-cross-device-development/official-arrowos-t3822779) | v18 | N/A | N/A | easy | - |
| OnePlus 6 | Stock (Android 9.0 Pie) | v18 | N/A | N/A | easy | Pie requires MAD running behind a TLS reverse proxy |
| Samsung Galaxy A3 2017 | [Resurrection Remix](https://forum.xda-developers.com/samsung-a-series-2017/development/rom-resurrection-remix-6-0-t3787726) | v18 | N/A | N/A | mid | phone is very inconsistent, sometimes not powering on. Use with risk. |
| Samsung Galaxy A5 | [LineageOS 14.1](https://download.lineageos.org/a5y17lte) | v17.1 | N/A | N/A | mid | laggy |
| Samsung Galaxy A5 2017 | Stock | v19.0 | N/A | N/A | easy | - |
| Samsung Galaxy A8 2018 | Stock | v18 | N/A | N/A | easy | before magisk flashing you have to flash a custom kernel on TWRP! [Download Kernel](https://github.com/DevKingsTeam/android_kernel_samsung_universal7885/releases/tag/se8.5-v1) |
| Samsung Galaxy J2 - Prime G532M | HadesRom 6.0.1 | v18.1 | N/A | N/A | easy | the only hard part was waiting for a working rom |
| Samsung Galaxy J2 | Stock | v18 | easy | N/A | easy | Often RGC/PogoDroid Lost Connection |
| Samsung Galaxy J5 (SM-J500FN) | Android 6.0.1 | v19.3 | easy | N/A | easy | ATT: Systemize PogoDroid! [Firmware/Odin](https://www.sammobile.com/samsung/galaxy-j5/firmware/SM-J500FN/NEE/download/J500FNXXS1BQG1/180209/) - [TWRP](https://eu.dl.twrp.me/j5nlte/) |
| Samsung Galaxy On5 | Stock | v18 | easy | N/A | mid | needs pogodroid systemized. systemize both apps before installing smali |
| Samsung Galaxy S4 - Mini | [LineageOS 14.1](https://forum.xda-developers.com/galaxy-s4-mini/orig-development/rom-cyanogenmod-14-0-s4-mini-3g-lte-t3471761) | v17.1 | easy | N/A | mid | heat/laggy |
| Samsung Galaxy S4 | [LineageOS 14.1](https://download.lineageos.org/jfltexx) | v17.1 | easy | N/A | mid | laggy |
| Samsung Galaxy S5 - mini | [LineageOS 14.1](https://forum.xda-developers.com/galaxy-s5-mini/development/g800f-m-y-lineageos-14-1-g800f-m-y-t3549055) | v18 | N/A | N/A | easy | runs "OK" , Needs delay for pogodroid to start |
| Samsung Galaxy S5 - Plus | [LineageOS 15.1](https://download.lineageos.org/kccat6) | v18 | easy | N/A | mid | - |
| Samsung Galaxy S5 - Sport | [LineageOS 14.1](https://forum.xda-developers.com/sprint-galaxy-s5/development/rom-lineageos-14-1-galaxy-s5-sport-sm-t3727763) | v18 | easy | N/A | easy | often stops injecting. Needs delay for pogodroid to start |
| Samsung Galaxy S5 | [LineageOS 14.1 Unofficial](https://androidfilehost.com/?fid=11410963190603877710) | v18 | easy | N/A | easy | Unofficial 14.1 is much more stable than Official LineageOS 15.x |
| Samsung Galaxy S6 | Stock | V18 | N/A | N/A | easy | - |
| Samsung Galaxy S6 - Edge | Stock | v18.1 | no | N/A | easy | - |
| Samsung Galaxy S6 | LineageOS 14.1 [MEGA](https://mega.nz/#!BtJBlQhQ!uDZOVZ4zdA-JVV3kfqgB4jWet64mDRKTP_uJnHienX8)| V18.1 | N/A | N/A | easy | - |
| Samsung Galaxy S6 - Edge | LineageOS 14.1[MEGA](https://mega.nz/#!AwBgBAyL!eRX-EvfKsbJ962DnhMuabF4vhHzyyMF1xlPWCFiiFgs)  | v18.1 | no | N/A | easy | - |
| Samsung Galaxy S7 | Stock | v18 | no | N/A | easy | - |
| Samsung Galaxy S7 | LineageOS 14.1[MEGA](https://mega.nz/#!E5AAnKxA!7pYV8CV009itmF5lSxuuc0VDTHkWGJi-5ac7fptjKBw)  | v18.1 | no | N/A | easy | - |
| Samsung Galaxy S7 EDGE| LineageOS 14.1 [MEGA](https://mega.nz/#!1wIGXYSY!dnMHHWhGFnXiI6j4cQLElY6Km44rEYp5zbaBjNfaPUo)| v18.1 | no | N/A | easy | - |
| Samsung Galaxy S7 EDGE| UNOFFICIAL LineageOS 15.1 [MEGA](https://mega.nz/#!k5YyBQjT!1Dn_CcOEsfLUmsT4RMtb5XF6FKFBLlwYrA-eV-oT4Ow)| v18.1 | no | N/A | easy | - |
| Samsung Galaxy S7 - Edge | Stock | V18.1 | no | N/A | mid | Android 7, samsung-antiroot-removal-2.4, in PogoDroid disable the option "Lower SELinux to permissive" to fix reboot issue on inject |
| Samsung Galaxy S8 | Stock | v18 | no | N/A | mid | Need to flash a custom kernel in order to set SELinux to permissable [kernel](https://forum.xda-developers.com/galaxy-s8/samsung-galaxy-s8--s8-cross-device-development/kernel-tgpkernel-t3654423) |
| Samsung Tab S2 9.7 WiFi | [LineageOS 15.1](https://download.lineageos.org/gts210vewifi) | v18 | N/A | N/A | easy | - |
| Samsung XCover 3 (SM-G389F) | Stock | v18.1 | N/A | N/A | easy | needs pogodroid systemized |
| Samsung XCover 3 (SM-G388F) | Stock (Android 5.1.1 Lollipop) | v18.1 | N/A | N/A | N/A | Pogodroid works, RGC crashes  |
| Samsung XCover 4 | Stock | v18.1 | easy | N/A | easy | No Smali and no PogoDroid Mocking needed |
| Sony Xperia Z2 | [CarbonROM](https://forum.xda-developers.com/xperia-z2/development/7-x-x-carbonrom-cr-5-1-t3655016) | v18.1 | [yes/mid](https://www.youtube.com/watch?v=BgmCgjuO20E) | N/A | easy | - |
| Sony Xperia Z3 | [CarbonROM](https://get.carbonrom.org/device-z3.html) | v19 | N/A | N/A | mid | Requires patched build fingerprint to pass SafetyNet, e.g. via [MagiskHide Props Config](https://forum.xda-developers.com/apps/magisk/module-magiskhide-props-config-t3789228) |
| Sony Z3 Compact | [CarbonROM](https://forum.xda-developers.com/z3-compact/orig-development/8-1-x-carbonrom-cr-6-1-t3771549) | v18 | N/A | N/A | easy | - |
| Sony Xperia Tablet Z | LineageOS 15.1 [WiFi](https://download.lineageos.org/pollux_windy) [LTE](https://download.lineageos.org/pollux) | v19 | N/A | N/A | easy | Somewhat laggy, but usable. Sometimes it doesn't boot and needs a power cycle to reset. RGC sometimes doesn't start and requires reboot. Doesn't like to hold charge if not kept cool. Use _device only_ location. |
| Ulefone Metal | [madOS 8.1](https://forum.xda-developers.com/android/development/rom-official-mados-ulefone-metal-t3709342) | v18 | N/A | N/A | easy | - |
| Ulefone Power | Stock | v18 | N/A | N/A | mid | dodgy USB drivers for rooting |
| Xiaomi Redmi 5A | [LineageOS 15.1](https://forum.xda-developers.com/xiaomi-redmi-5a/development/2018-10-10-lineageos-15-1-t3864961) | v18 | N/A | N/A | easy | - |

Stock = Native default ROM

## Runs w/o battery
Determines if the phone runs without a battery.
Possible entries:

* no -
* yes/usb - runs from usb, if you remove the battery
* yes/soldering - runs under special circumstances you are willing to describe

If you put in yes/soldering please leave a note with explanation or contact for questions.

**DON'T TRY THIS AT HOME** (unless you know what you're doing)
If you burn down your house, you'll get a special role in discord. But that's all.

# Contribute
If you could not find your working device, rom and magisk combination, please do open a PR adding it.
If you find a device, rom, magisk combination did not work out for you, open up an issue to start a discussion.
