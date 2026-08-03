![singularity icon](https://github.com/Lumince/singularity/blob/main/icon.png)

# Singularity

Singularity is an AIO pancake (ionstack port) root app for Meta VR headsets.

This supports Quest 2, pro, 3, and 3s currently. The process can take a bit to achieve root access. If you are having issues with it failing. Please power the device off and on and try again.

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