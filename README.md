# Mega Man X Online: Deathmatch (Flatpak)

# Installation

Requires [Flatpak](https://flatpak.org/setup/) to already be installed on your system.

```sh
#1 download MMXOD.flatpak
wget https://github.com/Walt-5D/MMXOD-Vanilla-Flatpak-Linux/releases/download/v19.12/MMXOD.flatpak
#2 install MMXOD.flatpak
flatpak install ./MMXOD.flatpak
#3 refresh apps menu
sudo update-desktop-database /var/lib/flatpak/exports/share/applications/
```

Once installed, launch it from your application menu as **Mega Man X Online: Deathmatch**, or from a terminal with:

```sh
flatpak run io.github.walt_5d.MMXOD
```

# Post-Install

Click on [HELP](https://github.com/Walt-5D/MMXOD-Vanilla-Flatpak-Linux/blob/main/help.md) for information on how to add custom maps and connect online.

## More information:

### Packaging Notice
* **Game Developer:** gamemaker19 (Original author)
* **Packager / Maintainer:** Walt-5D
* **Context:** The original author released the game files to the public and discontinued active development. This Flatpak packages the latest stable Linux build to preserve access to the game.

### Credits & Disclaimer
* **Capcom:** The company that created the awesome franchise! Without them, this fan project and its resources wouldn't exist!
* **Developer:** gamemaker19 for creating and programming this fan project.
* **Disclaimer:** This is an unofficial community-maintained Flatpak packaging for Linux distributions. All assets and intellectual property belong to their respective owners.
