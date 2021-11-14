# ClassicWB OS39 Package

ClassicWB OS39 is a feature rich Workbench enhancement by Bloodwych targeted A1200 with accelerator, 3.1 ROM, memory expansion using 16 colour screenmode, GlowIcons using Multisync / Interlaced 640x512 display.

## Description

ClassicWB OS39 Package contains ClassicWB OS39 v28 created by Bloodwych from EAB. 

With permission from Bloodwych it has been converted to a package for HstWB Installer.

Original version of ClassicWB OS39 can be downloaded from http://classicwb.abime.net/.

## Requirements

ClassicWB OS39 package has following requirements:

1. Amiga OS 3.9 and Boing Bag 1 & 2 installed, Amiga OS 3.2 or Amiga OS 3.1.4.
2. About 105MB free space on harddrive for installation.

## Installation

Download latest release from https://github.com/henrikstengaard/classicwb-os39-package/releases and copy it to HstWB Installer "packages" directory, which typically is "c:\Program Files (x86)\HstWB Installer\Packages".

Installation through HstWB Installer will install and configure ClassicWB OS39 package using defined assigns.
During installation dialogs are presented to customize ClassicWB installation.

## Assigns

Installation of ClassicWB OS39 package requires and uses following assign and default value:

- SYSTEMDIR: = DH0:

ClassicWB OS39 files will be installed and configured in SYSTEMDIR: assign, which must be set to harddrive containing Workbench.

## Modifications

ClassicWB is installed from a zip file containing all files from ClassicWB System.hdf.

The install script for HstWB Installer is based on Install_CWB39 from ClassicWB System.hdf with following changes:

- Copying Amiga OS 3.9 files from HD0: to HD1: has been replaced by extract ClassicWB OS39 on top of Amiga OS 3.9 installation.
- Paths has been changed: SYS: to SYSTEMDIR:, C: to SYSTEMDIR:C/, L: to SYSTEMDIR:L/.
- Modified versions of Temp enable and disable option scripts with changed paths.
- Removed all "press enter to continue" expect last one used after installation complete message is shown.
- Removed and reduced waits.
- Adjusted text spacing.
- Fix startup sequence and user startup to support Picasso96.
- Copy disk icon def_disk.info to harddisk DH1: and DH2:.
- Added support for Amiga OS 3.2 and 3.1.4:
  - Patch startup sequence and user startup with ClassicWB OS39 changes for better compatibility.
    - Startup sequence before installing ClassicWB OS39 is backed up as S:Startup-Sequence.WB.
    - Startup sequence patched for ClassicWB OS39 is installed as S:Startup-Sequence.OS39.
  - Reinstall MUI to fix iGame.
  - Added WBDock as replacement to AmiDock.
  - Disabled and removed MyClock.
  - Delete WBStartup's not present with Amiga OS 3.2 and 3.1.4.
  - Updated User-Startup to replace CON with KCON.
  - Updated DirectoryOpus to use CON instead of VNC.
  - Added WBRun to fix run menus.
  - Disable Copper, BorderBlank, StackAttack, CyberBugFix, MyClock.

## Screenshots

Screenshots of ClassicWB OS39 from http://classicwb.abime.net/classicweb/os39pics.htm.

![ClassicWB OS39 3.2 1](screenshots/classicwb_os39_3.2_1.png?raw=true)

![ClassicWB OS39 3.2 2](screenshots/classicwb_os39_3.2_2.png?raw=true)

![ClassicWB OS39 3.2 3](screenshots/classicwb_os39_3.2_3.png?raw=true)

![ClassicWB OS39 3.2 4](screenshots/classicwb_os39_3.2_4.png?raw=true)

![ClassicWB OS39 3.1.4 1](screenshots/classicwb_os39_3.1.4_1.png?raw=true)

![ClassicWB OS39 3.1.4 2](screenshots/classicwb_os39_3.1.4_2.png?raw=true)

![ClassicWB OS39 3.1.4 3](screenshots/classicwb_os39_3.1.4_3.png?raw=true)

![ClassicWB OS39 1](screenshots/classicwb_os39_1.png?raw=true)

![ClassicWB OS39 2](screenshots/classicwb_os39_2.png?raw=true)

![ClassicWB OS39 3](screenshots/classicwb_os39_3.png?raw=true)

![ClassicWB OS39 4](screenshots/classicwb_os39_4.png?raw=true)

![ClassicWB OS39 5](screenshots/classicwb_os39_5.png?raw=true)

![ClassicWB OS39 6](screenshots/classicwb_os39_6.png?raw=true)

![ClassicWB OS39 7](screenshots/classicwb_os39_7.png?raw=true)

![ClassicWB OS39 8](screenshots/classicwb_os39_8.png?raw=true)