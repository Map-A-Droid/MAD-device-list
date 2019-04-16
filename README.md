# MAD-device-list
List of devices known to work or not to work with the listed ROMs and Magisk versions (pass Safety Net, run Pogo along with RGC and stuff)

| Modelname | OS | Magisk | Effort | Notes |
| --- | :---: | :---: | :---: | :---: |
| Google Nexus 7 (2013) | [LineageOS 14.1](https://download.lineageos.org/flo) | v18 | easy | Disabling fused location causes GPS to stop working entirely, but does not rubberband with this enabled |
| Google Pixel | Stock (Android 8.1 Oreo) | v18.1 | mid | Do not use Link2SD for RGC as it's an A/B phone, use [Systemizer](https://github.com/Magisk-Modules-Repo/terminal_systemizer) instead |
| HTC Desire 430 | Stock | v18 | mid | 1.5GB RAM so slow but works well, no custom ROMs available and stock is kinda bloaty. Autostarting of pogodroid/RGC requires third party app like tasker |
| HTC Desire 626 | Stock | v18 | mid | No custom ROMs available and stock is kinda bloaty. Autostarting of pogodroid/RGC requires third party app like tasker. |
| HTC One -  M7 | [LineageOS 14.1](https://forum.xda-developers.com/htc-one/orig-development/rom-lineage-os-14-1-t3531331) | v18 | mid | heat |
| HTC One -  M8 | [LineageOS 14.1](https://download.lineageos.org/m8) | v18 | mid | heat |
| Huawei P Smart | Stock | v18 | very hard | Requires paid bootloader unlock through DCunlocker and building own kernel with CONFIG_HUAWEI_PTRACE_POKE_ON=y and CONFIG_SECURITY_SELINUX_DEVELOP=y |
| LG Aristo | LineageOS 14.1 for stylo 2 plus by messi2050 | v18.1 | mid | Needs safetypatcher magisk module. |
| Motorola E4 - Plus | [LineageOS 14.1](https://androidfilehost.com/?fid=5862345805528046723)(Mediatek CPU(nicklaus)) | v18 | mid | - |
| Motorola E4 (Mediatek) | Stock/[LineageOS Unofficial](https://forum.xda-developers.com/moto-e4/development/rom-lineageos-14-1-moto-e4-mediatek-t3717926) | v18 | easy | Device is available with Qualcomm processor as well - untested |
| Motorola E5 - Play (james) | [firmware](https://forum.xda-developers.com/moto-e5/how-to/firmware-moto-e5-xt1944-4-dual-sim-t3820901) [Directions](https://forum.xda-developers.com/moto-e5/how-to/guide-root-twrp-moto-e5-play-explained-t3856182) | v18.1 | mid | youtube FRP unlock method worked for me |
| Motorola G4 - Plus | [LineageOS 15.1](https://forum.xda-developers.com/moto-g4-plus/development/rom-lineageos-15-1-unofficial-t3768420) | v18 | mid | - |
| Motorola G4 | [LineageOS 14.1 unofficial](https://forum.xda-developers.com/moto-g4-plus/development/rom-cyanogenmod-14-1-t3522101) | v18 | easy | - |
| Motorola G5 | Stock | v18 | hard | their firmware for 7 has bugs, use android 8 and consider formatting data ext4 |
| Motorola X4 | [LineageOS 16.0](https://download.lineageos.org/payton) | v18 | easy | A/B Device, requires at least one OTA update before root or a BlankFlash is required. Intall RGC as Sys-priv app with Systemizer. Avoid Amazon Prime version. Android One version untested. SmaliPatch required. ARM64 injection. |
| OnePlus 2 | [LineageOS 15.1](https://wiki.lineageos.org/devices/oneplus2/install) | v18 | easy | - |
| OnePlus 3 | [LineageOS 15.1](https://forum.xda-developers.com/oneplus-3/oneplus-3--3t-cross-device-development/rom-lineageos-15-1-oneplus-3-3t-t3739169) | v18 | easy | - |
| OnePlus 3T | [ArrowOS 8.10](https://forum.xda-developers.com/oneplus-3/oneplus-3--3t-cross-device-development/official-arrowos-t3822779) | v18 | easy | - |
| OnePlus 6 | Stock (Android 9.0 Pie) | v18 | easy | Pie requires MAD running behind a TLS reverse proxy |
| Redmi 5A | [LineageOS 15.1](https://forum.xda-developers.com/xiaomi-redmi-5a/development/2018-10-10-lineageos-15-1-t3864961) | v18 | easy | - |
| Samsung Galaxy A3 2017 | [Resurrection Remix](https://forum.xda-developers.com/samsung-a-series-2017/development/rom-resurrection-remix-6-0-t3787726) | v18 | mid | phone is very inconsitsent, sometimes not powering on. Use with risk. |
| Samsung Galaxy A5 | [LineageOS 14.1](https://download.lineageos.org/a5y17lte) | v17.1 | mid | laggy |
| Samsung Galaxy A5 2017 | Stock | v18 | easy | - |
| Samsung Galaxy J2 - Prime G532M | HadesRom 6.0.1 | v18.1 | easy | the only hard part was waiting for a working rom |
| Samsung Galaxy J2 | Stock | v18 | easy | Often RGC/PogoDroid Lost Connection |
| Samsung Galaxy On5 | Stock | v18 | mid | needs pogodroid systemized. systemize both apps before installing smali |
| Samsung Galaxy S4 - Mini | [LineageOS 14.1](https://forum.xda-developers.com/galaxy-s4-mini/orig-development/rom-cyanogenmod-14-0-s4-mini-3g-lte-t3471761) | v17.1 | mid | laggy |
| Samsung Galaxy S4 | [LineageOS 14.1](https://download.lineageos.org/jfltexx) | v17.1 | mid | laggy |
| Samsung Galaxy S5 - mini | [LineageOS 14.1](https://forum.xda-developers.com/galaxy-s5-mini/development/g800f-m-y-lineageos-14-1-g800f-m-y-t3549055) | v18 | easy | runs "OK" , Needs delay for pogodroid to start |
| Samsung Galaxy S5 - Plus | [LineageOS 15.1](https://download.lineageos.org/kccat6) | v18 | mid | - |
| Samsung Galaxy S5 - Sport | [LineageOS 14.1](https://forum.xda-developers.com/sprint-galaxy-s5/development/rom-lineageos-14-1-galaxy-s5-sport-sm-t3727763) | v18 | easy | often stops injecting. Needs delay for pogodroid to start |
| Samsung Galaxy S5 | [LineageOS 14.1 Unofficial](https://androidfilehost.com/?fid=11410963190603877710) | v18 | easy | Unofficial 14.1 is much more stable than Official LineageOS 15.x |
| Samsung Galaxy S6 - Edge | Stock | v18 | easy | - |
| Samsung Galaxy S7 | Stock | v18 | easy | - |
| Samsung Galaxy S8 | Stock | v18 | mid | Need to flash a custom kernel in order to set SELinux to permissable [kernel](https://forum.xda-developers.com/galaxy-s8/samsung-galaxy-s8--s8-cross-device-development/kernel-tgpkernel-t3654423) |
| Samsung Tab S2 9.7 WiFi | [LineageOS 15.1](https://download.lineageos.org/gts210vewifi) | v18 | easy | - |
| Samsung XCover 3 (SM-G389F) | Stock | v18.1 | easy | needs pogodroid systemized |
| Samsung XCover 4 | Stock | v18.1 | (super)easy | No Smali and no PogoDroid Mocking needed |
| Sony Z3 Compact | [CarbonRom](https://forum.xda-developers.com/z3-compact/orig-development/8-1-x-carbonrom-cr-6-1-t3771549) | v18 | easy | - |
| Ulefone Metal | [madOS 8.1](https://forum.xda-developers.com/android/development/rom-official-mados-ulefone-metal-t3709342) | v18 | easy | - |

Stock = Native default ROM

# Contribute
If you could not find your working device, rom and magisk combination, please do open a PR adding it.
If you find a device, rom, magisk combination did not work out for you, open up an issue to start a discussion.

