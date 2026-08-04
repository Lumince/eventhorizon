![singularity icon](https://github.com/Lumince/singularity/blob/main/icon.png)

# Singularity

Singularity is an AIO pancake (IonStack port) temproot app for Meta Quest VR headsets. You can find more about IonStack [here](https://github.com/NebuSec/CyberMeowfia/tree/main/IonStack).

This supports Quest 2 (Hollywood), Quest Pro (Seacliff), Quest 3 (Eureka), and Quest 3s (Panther) currently. The process can take a bit to achieve root access. If you are having issues with it failing, please power the device off and on and try again.
> [!CAUTION]
> Gaining root access on your Meta Quest device can be dangerous in the fact that executing certain commands can have your headset permanently bricked and unrepairable without sending it back to Meta! It is strongly advised you do not write to partitions, execute arbitrary commands, open untrusted apps/websites, etc. Additionally, please note, this is a **temproot, not a root** which means that your root access will be destroyed after rebooting the headset, and the exploit must be run again.


> [!WARNING]
> This exploit may be patched at any time without prior notice by Meta. We recommend disabling updates if you wish to continue having root access on your Meta Quest Device.

## Features
- Root-on-boot for root
- FreeXR [safe root things](https://github.com/FreeXR/safe-root-things)
- Root Terminal
- Internet kill switch and Domain Blocker
- Wireless ADB Setup
- Frida-Server 
- Meta Based Zygisk "Fix"
- USB notification auto accepting for MTP access
- Meta Telemetry disabling
- No-controller requirement
- OS Update Monitoring to unqueue forced updates
- Build type spoofer (user, userdebug, eng)
- CPU/GPU monitoring/config
- App manager (Installing/Uninstalling/Launching)

## Installation

Download the latest APK from [releases](https://github.com/Lumince/singularity/releases), and sideload it with "**adb install -g Singularity.apk**"

"-g" will grant the needed "WRITE_SECURE_SETTINGS" permission so Singularity can enable Wireless ADB on the device.

## Frida

This repo contains Frida-Server, source is [here](https://github.com/frida/frida)

## Credits

- [ionstack source](https://github.com/NebuSec/CyberMeowfia/tree/main) 
- pancake source TBD
- topjohnwu and the Magisk developers for Magisk
- Beom, & Darknight for their work on Pancake (ionstack quest port)
- TrashyOne, ToastConcern, ARDiva, for testing Singularity
