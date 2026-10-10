# re4-crouch-priority
A Resident Evil 4 Remake mod that lets crouch interrupt sprinting and aiming more reliably for evasive maneuvers.

When you press crouch while holding sprint or aim, your crouch command will interrupt those actions.

**Both overrides are enabled by default and can be disabled independently.**

## Requirements

[REFramework](https://www.nexusmods.com/residentevil42023/mods/12)

## Installation

1. Install **REFramework**.
2. Extract this mod’s `reframework` folder into your game folder, beside `re4.exe`.
3. Launch the game. If it’s already running, select **Reset Scripts** in REFramework.
4. Open **Script Generated UI → RE4 Crouch Priority** in the REFramework menu to configure the mod.

The installed script should be located at:

```text
reframework/autorun/RE4_CrouchPriority.lua
```

### Uninstallation

Remove `reframework/autorun/RE4_CrouchPriority.lua` and restart the game.

## Main features

| Setting | Default |
| --- | --- |
| Crouch Overrides Sprint | Enabled |
| Crouch Overrides Aim | Enabled |

- Both options can be toggled independently, and your preferences are saved.
- Automatically follows the game’s assigned controls, including rebound inputs.
- Supports hold and toggle settings for sprint and crouch.
- When you exit crouch, a still-held aim or eligible sprint input can resume without another press.
- Releasing and pressing aim or sprint again still restores its normal action.

### Testing and compatibility

- Controller support works, but has not been thoroughly tested.
- Prompted evades have worked in testing, but have not been thoroughly tested.
- Extended keyboard/mouse gameplay testing has found no issues, but testing is not exhaustive.

## Diagnostics

Optional diagnostic recording is available under:

**Script Generated UI → RE4 Crouch Priority → Diagnostics**

Leave it disabled for normal play. If you encounter a problem, enable it to record recent inputs and state changes for troubleshooting.

The report is saved locally to:

```text
reframework/data/RE4_CrouchPriority_runtime.json
```

## Credits

Thanks to **praydog** and the **REFramework contributors** for making RE Engine scripting possible.

## Development note

This mod was developed with assistance from **OpenAI Codex** and refined through hands-on testing in-game.
