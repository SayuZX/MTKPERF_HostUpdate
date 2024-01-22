## Changelogs
**V4.0 PONGO - Latest**
- Fixed interactive governor parameters being overwritten by system after a while for some devices
- Added back deep-sleep enhancements props
- SWAPs/zRAM are no longer disabled
- Auto-detect existing profile when upgrading (user interaction is not needed anymore)
- Memory management enhancements
- Removed any deep-sleep related tweaks
- Re-worked EAS profiles
- Prefer schedutil on EAS kernels
- Added CPUSET optimizations
- Added schedtune optimizations
- Added control groups (CGroups) optimization
- IO block tuning enhancements
- FileSystem (FS) enhancements
- Enabled Fast Dormancy (may help with cellular network idle drain)
- Fixed changing MTKMOD+ profile not sticking after reboot
- Improved compatibility for custom kernels
- Removed Low Memory Killer tweaks 
- SoC detecion enhancements
- Added command line controls
- Now MTKMOD+ perefers interactive if kernel has both schedutil & interactive
- Less aggressive LMK
- Fixed soc.txt file not being created when SoC detection fail
- Added new wakelocks to block
- Adreno Idler parameters changes
- Added support for snapdragon 4xx series
- Added support for Helio P10 (MT6755), Helio P65 (MT6768) kirin655, kirin658, kirin659
- Fixed LTE Signal bug
- Fixed some parameters not being applied
- Fixed detection bug for snapdragon 660
- EAS parameters adjustments
- Reverted HMP scheduler changes
- Fixed RAM capacity & CPU frequency not displayed properly in MTKMOD+.prop
- Crashes bug fix
- Scrolling bug fix
- Crashing apps bug fix
- EAS tuning is back for more devices (manual parameters - not WIPE) 
- EAS parameters adjustments
- HMP scheduler adjustments
- Updated RAM detection method
- Memory management fixes
- LMK enhancements
- Added Lazyplug tunning
- Removed busybox check
- Module template Added to latest UNITY 3.2
- Fixed hardware auto-detection fail after last update for some devices
- Added support for sultanxda cpu boost implementations
- Bug fixes for manual chip detection workarround
- Added manual workarround for devices with unrecognized chip (Huawei,Xiaomi etc..)
- Removed EAS support (except sd845) untill further notice (too experimental)
- Corrected SD845 configs
- Agressive tunded LMK for Turbo profile for better gaming experience
- Fixed Termux app conflicts
- Added Performance & Turbo profiles
- Added partial support (balanced profile only) for exynos9810, kirin650, sd615
- Fixed battery drain for EAS devices
- Fixed RAM capacity not being displayed correctlly
- Script refinements
- Fixed connectivity issues for some devices
- Improved SOC chip recognition for some devices
- EAS parameters enhacements
- Memory tuning enhancements
- Added support to SD615/SD616
- Changed hardware detection method
- I/O scheduler changes
- Removed forced doze for GMS & ril services
- Improved scrolling & FPS in applications
- Added detailed battery health check
- Fixed a bug that makes governor parameters not stick after a while
- Fixed a bug where CPU is not recognized correctly (Improved SoC detecting)
- Added missing cpu boost for some SoCs on balanced profile
- Improved swap detection & disabling (again)
- Reviewed & removed some stuff
- Swap partitions detecting improvements
- Some small but important script code fixes
  
**V3.0 NUSANTARA**
* Added GPU specific functionalities
* Fixed Black Screen and Game Graphic glitches.
* Updated I/O related tweaks
* Android OS 12 related bugfixes
* Net congression controller is not touched
* Whole code revised & optimized
* Removed potentially bad tweaks (causing device to not wake up)
* Enabled File System Optimisation
* Enabled System Refresh
* Tuned F2FS tweaks
* Tuned EXT4 FS tweaks
* Tuned Mali GPU tweaks
* Added ro.opa.eligible_device
* Added CPU Freq Stuck To Highest - Experimental
* Updated VM tweaks
* Updated network tweaks
* Tuned CPU governor tweaks
* Improved device info gathering
* More tweaks are calculated by formulas depending on device's specs
* Removed auto I/O scheduler set
* Various bugfixes
* AI removed
* Important you need Busybox Module Installed!

**V2.0 SAGIRI IZUMI**
* Improve scrolling
* Increase network connection speed
* Improve listening ability
* Reduce battery consumption
* Added GPU acceleration
* Module Adjustments
More compatibility fixes for Mediatek G85
Fixed battery drain after last update for some devices
* Enabled & configured exchange for better multitasking and performance
* Eliminated low volume microphone issues for various Android devices. 
* For a better accessibility experience
Repair
* Removes anything added
* bug fixes and code & optimizations
* Important you need Busybox Module Installed!
  
**V1.0 Komodo**
* Added Unlocker Gaming
* Added Disable Thermal
* Added touch screen sensitivity.
* Fixed better performance and battery life.
* optimized CPU Boost Scripts
* Added some necessary Build props
* Miscellaneous Improvements
* And Anymore!
* Important you need Brutal Busybox Module Installed!
* Added HW Overlay Disabler For Better FPS
  
## Credits
_________________________________
@Zackptg5 for MMT Extended
@osm0sis For Busybox NDK
_________________________________

