---
title: CoaezSlayer
description: All-in-one Slayer script supporting all masters.
slug: /CoaezSlayer
---

import React from 'react';
import TopBanner from '@site/src/components/TopBanner';
import ContentBlock from '@site/src/components/ContentBlock';
import Changelog from '@site/src/components/Changelog';
import BrowserWindow from '@site/src/components/BrowserWindow';
import changes from './changes.json'

<TopBanner title="CoaezSlayer" author="coaeasy" version="v1.0.0" skill="Slayer">
</TopBanner>

:::hidden

## Cost

:::

<ContentBlock title="Cost">

> - 20$ / week (subject to change and not including client access)

</ContentBlock>

:::hidden

## Combat Settings

### Ability Options
- **Use Darkness**: Automatically activates the Darkness ability when available
- **Movement Abilities**:
    - Use Surge: Enables Surge ability during movement
    - Use Dive: Enables Dive ability during movement
    - Use Teleports: Allows teleportation during movement

### Targeting Options
- **Attack Range**: Sets the maximum distance to target NPCs (0-30 tiles)

### Prayer Settings
- **Auto Prayer Switching**: Automatically switches protection prayers based on monster attack styles
    - Use Curse Prayers: Uses Deflect prayers instead of Protect prayers
- **Prayer Categories**:
    - Protective: Soul Split, Protect/Deflect prayers
    - Melee: Melee-boosting prayers
    - Ranged: Ranged-boosting prayers
    - Magic: Magic-boosting prayers
    - Necromancy: Necromancy-related prayers
- **Prayer Restoration**:
    - Prayer Restore Potions: Uses prayer/restore potions when prayer points drop below set percentage
    - Prayer Renewal: Maintains prayer renewal buff
    - Elven Ritual Shard: Uses the shard when available for prayer restoration

### Potions
- **Combat Potions**:
    - Overloads: Maintains overload buff
    - Antifire: Uses antifire potions (automatic for dragon tasks)
    - Weapon Poison: Maintains weapon poison buff
    - Aggression Potion: Uses aggression potions to draw monster attention
    - Charming Potion: Uses charming potions for increased charm drops

## Slayer Settings

### Basic Configuration
- **Slayer Master Selection**: Choose your preferred Slayer master
- **Point Farming**: Enables efficient Slayer point farming
    - Speed Farming Mode: Optimizes movement for faster tasks
    - Custom Highest Master: Select specific master for bonus point tasks

### Task Management
- **NPC Contact**: Uses NPC Contact spell to get new tasks (must be on action bar)
- **Bank on Full Inventory**: Automatically banks when inventory is full
- **Task Block List**: Manage list of tasks to block/skip
- **Cancel Only**: Only cancels tasks instead of blocking them

### Safety Features
- **Low Health Teleport**: Automatically teleports when health drops below set percentage
- **Teleport Options**:
    - War's Retreat: Uses War's Retreat teleport
    - Archaeology Book: Uses Archaeology teleport
    - Max Guild: Uses Max Guild teleport

## Loot Settings

### Area Looting
- **Enable Area Loot**: Automatically loots items in area
- **Loot Range**: Sets distance for area looting (tiles)
- **Loot Delay**: Delay between looting items

### Loot Options
- **Loot All**: Picks up all items except blacklisted ones
- **Loot All Stackables**: Only picks up stackable items
- **Use Value Threshold**: Only picks up items that meet the game's monetary value threshold (must be enabled in game settings)
- **Use Magic Notepaper**: Automatically notes specific items
- **High Alchemy**: Performs high alchemy on specified items

### Loot Lists
- **Items to Loot**: Custom list of items to pick up
- **Notepaper Items**: Items to use notepaper on
- **Alchemy Items**: Items to high alchemize
- **Blacklist**: Items to never pick up

## Tips
- Ensure area looting is enabled in-game settings with 1 item opens loot inventory
- For value-based looting, configure your preferred value threshold in the game settings
- Bank presets should be properly configured in-game before use

## Extra Features

### Bones and Ashes
- **Auto-bury Bones**: Automatically buries bones
- **Auto-scatter Ashes**: Automatically scatters ashes
- **Custom Lists**: Configure which bones/ashes to process

### World Hopping
- **World Type**: Choose between P2P/F2P worlds
- **Player Check**: Hops when players are detected within range
- **World Criteria**: Set ping and player count preferences

### Break System
- **Task Delay**: Time between tasks
- **Break Duration**: Length of breaks
- **Break Scheduling**: Configure multiple break periods

### Preset Management
- **Use Preset Manager**: Enables custom bank presets
- **Default Preset**: Set default preset number
- **Task Presets**: Configure specific presets for different tasks

## Tips
- Ensure area looting is enabled in-game settings
- NPC Contact must be on action bar for automatic task getting
- For dragon tasks, antifire protection is automatically enabled
- Prayer switching works best with appropriate prayers unlocked
- Bank presets should be properly configured in-game before use