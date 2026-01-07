# Basic Food Company Extended

(The following documentations are Copilot-generated)

A Victoria 3 1.12+ mod that extends the Basic Food Company with all grain farm types as available industry rights.

See [STEAM_DESCRIPTION.txt](STEAM_DESCRIPTION.txt) for the Steam Workshop description.

## Overview

This mod uses Victoria 3 1.12's `INJECT` modding format to safely append grain farm building types to the `company_basic_food` definition without overwriting other properties or causing mod conflicts.

## What It Does

The Basic Food Company can now purchase industry right charters for:
- Rye Farms
- Rice Farms
- Maize Farms
- Millet Farms

In addition to its existing Wheat Farms.

## Technical Details

**Game Version**: Victoria 3 1.12+  
**Multiplayer**: Yes (synchronized)  
**Mod Format**: INJECT (1.12+)  
**File**: `mod/common/company_types/00_basic_food_extensions.txt`

## Repository Structure

- **mod/** - The mod files (upload this to Steam)
  - `common/company_types/` - Company type modifications
  - `.metadata/metadata.json` - Mod metadata
  - `thumbnail.png` - Workshop thumbnail
- **MOD_DOCUMENTATION.md** - Technical documentation
- **STEAM_DESCRIPTION.txt** - Steam Workshop description template

## For Developers

To extend or modify this mod:

1. Edit `mod/common/company_types/00_basic_food_extensions.txt`
2. Test with Victoria 3 debug mode and hotloading enabled
3. Update documentation as needed
4. Build/test before committing

## Compatibility

- **No conflicts** (uses INJECT format)
- **Minimal performance impact** (single company type extension)
- **Safe for existing saves**
