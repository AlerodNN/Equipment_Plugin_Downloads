[Russian](README.ru.md)

# Equipment Plugin for The Lord of the Rings Online

Equipment Plugin helps you choose equipment and essences for your selected stats, compare a proposed build with your confirmed worn gear, and save several builds for your character.

**[Download Equipment Plugin 0.2.24](https://github.com/AlerodNN/Equipment_Plugin_Downloads/releases/latest/download/EquipmentPlugin-0.2.24.zip)** · [Latest version](https://github.com/AlerodNN/Equipment_Plugin_Downloads/releases/latest)

## Features

- Equipment, compatible essence and virtue selection with class, level, selected stats and restrictions taken into account.
- Equipped versus planned totals, with gains and losses for individual stats.
- Minimum and Maximum targets, Importance weights, mandatory-bound locks and equipment-slot locks.
- Armour and jewellery set requirements, piece counts and available item levels.
- Effects selection for supported buffs, food, scrolls and other bonuses, with available choices adapted to character level.
- Manual item and essence replacement, detailed comparison tooltips and exclusion of unavailable item levels.
- Up to five independent character profiles and ten saved builds per profile.
- Generation History comparing original equipment with the current proposal, including manual edits.
- Resizable windows and settings retained between sessions.

The plugin proposes a build; you obtain and equip items in the game yourself. The interface uses English labels. Detailed Russian and English manuals are included.

## Installation

1. Download **EquipmentPlugin-0.2.24.zip** using the link above or the **Assets** section of the latest version. Choose the archive named after the plugin.
2. Find `The Lord of the Rings Online` in your **Documents** folder. Create its `Plugins` folder if necessary.
3. Extract the archive's `EquipmentPlugin` folder into `Plugins`.
4. Check this path: `Documents\The Lord of the Rings Online\Plugins\EquipmentPlugin\EquipmentPlugin.plugin`. Avoid an extra nested `EquipmentPlugin` folder.
5. Load **Equipment Plugin** through LOTRO's plugin manager, then click its icon to open it and begin setup.

If Documents has been moved to OneDrive or another location, use the Documents folder where LOTRO actually stores its settings. No additional plugins or libraries need to be installed.

## First-time setup

1. **Equip your starting gear**, including the legendary items you intend to use. Wait for an expiring temporary effect to end before confirming the starting data.
2. **Complete initial confirmation.** Confirm Glory Rank, actual virtue ranks and the active set. Confirm zero ranks too; rank-zero virtues cannot be active.
3. **Read each item's in-game tooltip.** Item Level describes the item; Minimum Level is its required character level. Confirm supported item levels, base variants and installed essences. Choose the empty option for an empty socket on worn gear. If an active food or scroll needs confirmation, select the one actually used.
4. **Name the profile** and check the starting stats. Use `+` for a separate specialisation or starting build.
5. Open **Generation Settings**, check your important stats and set targets, weights and any required sets, virtues or exclusions.
6. Open **Effects** and select supported bonuses you want included in the calculation.
7. Press **Generate** and inspect **Equipped**, **Planned**, **Change**, **Generation History** and the explanation beneath the main window.
8. Press **Save** for a build you want to keep. You can try other settings and return to saved builds later.

## Main settings

| Setting | Purpose |
| --- | --- |
| Checked stat | Includes that stat in the common objective. Unchecked stats may change with an item but have no independent priority. |
| Minimum | Desired floor. Closing its lock makes it mandatory. |
| Maximum | Useful-growth target. Closing its lock enforces an upper bound, with narrow item/essence level-upgrade exceptions explained in the manuals. Without an entered Maximum, the appropriate game references apply; uncapped stats have no automatic ceiling. |
| Importance | A checked stat's contribution to the overall score. Higher weight does not promise that every stat increases together. |
| Equipment-slot lock | Keeps that slot's item and essences during generation. |
| Armor Sets / Jewellery Sets | Require the selected set, item level and piece count. |
| Temporary Blacklist | Exclude checked items and levels from subsequent searches. |

Start with the stats that really matter to your build. If no suitable improvement is found, review mandatory bounds, slot locks, set requirements and exclusions. The current proposal remains; the nearest checked values in the explanation are not applied automatically. The search does not guarantee that every possible combination has been checked.

Selected **Effects** participate in final totals, targets and limits. An effect actually active on your character and an effect selected for the proposed calculation can require separate confirmation; follow the plugin's prompts.

## Manual edits, virtues and saved builds

- **Left-click an item** to choose a manual replacement in the proposal. **Right-click** for available item and essence actions.
- **Generation History** shows the net difference between confirmed original equipment and the current proposal. Manual changes add to it; restoring an original item removes only its corresponding difference.
- **Initial Update**, on the left in Virtues, confirms the original active virtues for all saved builds in the current profile while keeping the selected build open.
- **Update Generation**, on the right, confirms proposed virtues only in the selected saved build. Without a selected saved build, it creates a working proposal. These confirmations save immediately; no separate Save is needed.
- Changes to the active virtue selection require one of these confirmations before closing settings. **Refresh** preserves both confirmed virtue sets.
- **All ranks: 100** is a proposal-only simulation. **Restore actual ranks** restores earned ranks.
- **Save** creates another saved build. Ordinary edits to other gear or settings do not automatically overwrite a saved build.
- **Restore Initial** clears the proposal and shows confirmed original equipment while keeping search settings.
- After actually changing your equipped items in LOTRO, use **Refresh** and finish the required confirmations to update the comparison baseline.

From level 45, designated legendary slots are excluded from selection even if an ordinary item is temporarily worn there. Equip Main Hand before Generate and use Refresh when needed. See the manuals for class-specific weapon and item rules.

## Complete Russian and English manuals

Every download includes:

- **English:** `EquipmentPlugin/ReadmeEN.html`.
- **Russian:** `EquipmentPlugin/ReadmeRU.html`.

Open either file in a web browser after extracting the archive. No internet connection is required. The manuals cover a first-build walkthrough, bounds, caps and weights, essences and weapons, Effects, virtues, profiles, saved builds and updating the equipped baseline. They describe the version included in that archive.

## Updating and getting help

Unload the plugin or close the game before replacing files. Extract the new version's `EquipmentPlugin` folder into the same `Plugins` directory, replace existing files and load the plugin again. **Keep `PluginData`**, which contains saved settings. The manuals also explain reloading and recovery from loading problems.

When asking for help, include the plugin version, character class and level, expected result and reproduction steps. Check screenshots and diagnostics for personal information before posting them. An item's **Unknown** source means its acquisition method is unconfirmed; it does not guarantee current server availability.

## Current version

**0.2.24** · [Download ZIP](https://github.com/AlerodNN/Equipment_Plugin_Downloads/releases/latest/download/EquipmentPlugin-0.2.24.zip)

Archive SHA-256:

```text
7b3571c9f85d4ee95e3a63a6dd0010206490b9bcc49de05317f2741512a60cc4
```


## Discord community

[Join Equipment Plugin on Discord](https://discord.gg/dwEYvA3FWp) for an introduction, downloads and release notes, FAQ, complete English/Russian manuals and discussions. The same address is available in Generation Settings → Info.
