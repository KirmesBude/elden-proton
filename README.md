# elden-proton

Noob friendly Elden Ring mod loader for linux/proton/steam

![steam launch options](.github/images/launch-options.png)
![launcher ui](.github/images/ui.png)

## Usage

- Place the `elden-proton.bash` into your preferred location and mark it as executable (`chmod +x` from shell).
- Run the script once through terminal or through graphical file manager to output steam launch options.
- Set the provided launch options in steam for Elden Ring
- Launch Elden Ring from steam and customize settings to your liking

## Features

- Run Elden Ring modded or unmodded easily
- Zenity based GUI
- Automatically manages EldenModLoader and ModEngine2-proton
- Automatically manages and downloads popular DLL mods
- Easy access to DLL mod configuration files
- Run ModEngine2 compatible mods simply by choosing the mod directory

## Modengine2 mods

Many mods in NexusMods come with ModEngine2 bundled. Simply choose any folder that contains a `config_eldenring.toml` file and you are all set.

## Env variables

- `STEAM_PATH` control where steam is located
- `ER_PATH` control where `Elden Ring/Game` is located

## Start from scratch

In your `Elden Ring/Game` location, remove the `mods` and `EldenProton` folders. 
Remove only the `EldenProton` folder if you want to reset state and re-download everything.
Note that all DLL mod settings will be reset.
