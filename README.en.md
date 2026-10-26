# Star Citizen voice copilot — download

[Français](README.md) · English

A copilot that listens to you, presses the keys in Star Citizen and answers out loud.
Everything runs on your PC: speech recognition, voice and local AI work without Internet.

```
You     : "Copilot, we're landing: call the tower and lower the landing gear."
Copilot : "Contacting the control tower. Landing gear down."
```

> **Language:** for now, the copilot's interface, voice commands and replies are in **French only**
> (the example above is translated). This page is the only part available in English.

## Download

**[Latest version](https://github.com/Grumf81/copilote-sc-telechargement/releases/latest)**: download **all** the
files of the release and put them **in the same folder**:

- `CopiloteSC-Installation-<version>.exe` (the installer, the one to run)
- `CopiloteSC-Installation-<version>-1.bin`, `-2.bin`, `-3.bin` (the data, ~5.5 GB in total)

Windows cannot run a program larger than 4 GB, so the data sits next to the installer, in pieces.

## Install

1. Run `CopiloteSC-Installation-<version>.exe`. Windows SmartScreen may show "Windows protected your PC"
   (the program is not signed): *More info › Run anyway*.
2. No administrator rights are needed. Default folder: `%LOCALAPPDATA%\Programs\Copilote Star Citizen`
   (you can pick another drive; ~7 GB with all components).
3. Components:
   - **Core** (required): the copilot, Python, speech recognition, voices;
   - **Local AI** (Qwen 2.5 3B): answers questions without Internet. Not needed if you use an online AI;
   - **NVIDIA acceleration**: speech recognition on the graphics card, faster and more accurate. Unchecked by
     default when there is no NVIDIA card.
4. When it finishes, the copilot starts and opens its interface: **http://127.0.0.1:4732**. An icon appears
   next to the clock.

**Recommended setup**: 64-bit Windows 10 or 11, 16 GB of RAM, a microphone or a headset. An NVIDIA card
(6 GB of video memory or more) is recommended but not required. Run Star Citizen in *Borderless windowed* mode
to see the overlay.

## Update, uninstall

- **Update**: from the copilot, **Mises à jour** page (Updates) › *Programme du copilote* › **Mettre à jour et
  redémarrer** (a few seconds, nothing to download again). The copilot checks every day and, if "Télécharger
  automatiquement" and "Appliquer automatiquement" are ticked (the default), installs the new version by itself,
  never during a game session. This automatic installation exists from version 2026.10.26.0059: before that,
  click the button once. The version history is on the same page. Your settings, commands, voices and avatars
  are kept.
- Copilots installed before the 22 October 2026 version do not have this built-in update yet: reinstall once with
  the latest installer (same folder, nothing is lost).
- **Uninstall**: *Windows Settings › Apps › Copilote Star Citizen*. It offers to keep or delete your settings.

## Phone remote control

Only one screen? Open the copilot's **Téléphone** page (Phone): allow the remote control, then scan the QR code with
your phone (same Wi-Fi as the PC). The phone shows the animated avatar, the conversation, the game announcements and
a few settings, with a **Stop** button. Views change by voice ("Copilot, show the announcements"). No command is ever
sent from the phone: orders always go through your voice. Windows asks once to allow the copilot through its firewall.

## Licenses

Star Citizen voice copilot — created by [Grumf81](https://github.com/Grumf81). Copyright © 2026 Plagnito — https://plagnito.com/

The installer also contains software and models by other authors, each under its own license: see
[LICENCES.md](LICENCES.md) (in French).

### Star Citizen, Cloud Imperium and Roberts Space Industries

<img src="made-by-the-community.png" alt="Star Citizen Made By The Community" width="96" align="right">

This is an **unofficial fan project**. Notice required by CIG:

> This project is not endorsed by or affiliated with the Cloud Imperium or Roberts Space Industries group of
> companies. All game content and materials are copyright Cloud Imperium Rights LLC and Cloud Imperium Rights Ltd.
> Star Citizen®, Squadron 42®, Roberts Space Industries®, and Cloud Imperium® are registered trademarks of
> Cloud Imperium Rights LLC. All rights reserved.
