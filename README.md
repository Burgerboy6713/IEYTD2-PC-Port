# IEYTD2-PC-Port (Shaken, Not VR)

A fan-made MelonLoader mod that lets you play **I Expect You To Die 2: The Spy and the Liar** on PC with a mouse and keyboard, without a VR headset.

Not affiliated with or endorsed by Schell Games. You need to own the game on Steam.

## Requirements

- *I Expect You To Die 2* (Steam version)
- **MelonLoader v0.5.7.** It must be this exact version, because newer versions won't load the mod.

## Installation

### 1. Install MelonLoader v0.5.7

**Option A: manual (recommended)**

1. Download [MelonLoader.x64.zip (v0.5.7)](https://github.com/LavaGang/MelonLoader/releases/download/v0.5.7/MelonLoader.x64.zip). The full release page is [here](https://github.com/LavaGang/MelonLoader/releases/tag/v0.5.7).
2. Open the game folder. In Steam, right-click the game and choose **Manage → Browse local files**. It's usually
   `C:\Program Files (x86)\Steam\steamapps\common\I Expect You To Die 2`.
3. Extract the zip's contents straight into that folder. You should end up with `version.dll` and a `MelonLoader` folder next to `I Expect You To Die 2.exe`.

**Option B: installer**

1. Download [MelonLoader.Installer.exe](https://github.com/LavaGang/MelonLoader/releases/download/v0.5.7/MelonLoader.Installer.exe) (v0.5.7).
2. Select the game's `.exe`, untick **Latest**, choose **v0.5.7** from the version list, and click **Install**.

### 2. Run the game once

Launch the game from Steam. The first launch with MelonLoader takes a few minutes, while it downloads and generates the files it needs (an internet connection is required). When the game reaches the menu, quit. This creates the `Mods` and `UserData` folders.

### 3. Install the mod

1. Download the latest `ShakenNotVR_vX.X.X.zip` from [Releases](https://github.com/Burgerboy6713/IEYTD2-PC-Port/releases/latest).
2. Extract it into the game folder. If Windows asks, merge the `Mods` and `UserData` folders with the existing ones. You should end up with these files:
   ```
   I Expect You To Die 2\Mods\ShakenNotVR_Mods.dll
   I Expect You To Die 2\UserData\ShakenNotVR_UserData\ControlsPC.png
   I Expect You To Die 2\UserData\ShakenNotVR_UserData\SplashPC.png
   I Expect You To Die 2\UserData\ShakenNotVR_UserData\MenuTitle.png
   ```
3. Launch the game from Steam. If Steam asks how to launch, pick the normal (non-VR) option. Press **F1** in game to see the controls.

### Updating

Download the newer zip from [Releases](https://github.com/Burgerboy6713/IEYTD2-PC-Port/releases) and extract it over the old files. Each release lists its fixes, changes and new features.

### Uninstalling

Delete `Mods\ShakenNotVR_Mods.dll`. To remove MelonLoader as well, delete `version.dll` and the `MelonLoader`, `Mods`, `Plugins` and `UserData` folders.

## Controls

| Key | Action |
| --- | --- |
| LEFT CLICK | Interact and Grab/Drop |
| RIGHT CLICK | Look around |
| W, A, S, D, CTRL, SPACE | Move head position |
| Q | Telekinesis On/Off |
| WHEEL | Move item closer/further |
| R | Rotate grabbed item |
| F | Freeze item in air |
| E | Use item |
| Z | Zoom |
| G | Manual Grab |
| TAB | Free/Lock the mouse |
| V | Grab/Place accessory on head |
| X | Switch active hand |
| F1 | Open/close the controls menu |
| F8 | Enable/Disable PC mod |

Keys and options can be changed in `UserData\MelonPreferences.cfg`, in the `[ShakenNotVR_Preferences]` section. The file appears after the first run with the mod.
