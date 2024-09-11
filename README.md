## Introduction

This project is a modification of [rockerbacon's MO2 installer for linux](https://github.com/rockerbacon/modorganizer2-linux-installer) that (hopefully) aims to add support for GOG games through Heroic (and maybe Lutris)

Hopefully this will enable modding support for all supported Mod Organizer 2 games installed from GOG, and (if I get good at code) enable the automatic launching of MO2 from Heroic, just like rockerbacon's installer

## IMPORTANT: This is VERY much a WIP (like a 3-year-old AO3 fic) that has ZERO guarantee of resulting in a usable project.
I have limited coding experience and this is mainly an exercise in 1) Learning how to use git and github and 2) attempt to fix the lack of broader MO2 support on linux, bacause using bottles get boring really quickly.

## Installing Mod Organizer 2

#### Requirements

You may need to manually install the following programs:

- _7z_
    - Should be readily available in your distribution's package manager
- _protontricks_
    - **Steam Deck users**: Protontricks must be installed through the Discover app.
    - **Other distributions**: carefully read through the [available install methods](https://github.com/Matoking/protontricks#installation) to ensure you're using an up-to-date version of the program.

The following requirements should be available out-of-the-box in most systems:

- _bash_
- either _curl_ or _wget_
- _zenity_
- _protontricks-launcher_: should be available after installing `protontricks` already, if not see [this](https://github.com/Matoking/protontricks#desktop)

