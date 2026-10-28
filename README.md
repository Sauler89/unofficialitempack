# BG2:EE Unofficial Item Pack

**A community-maintained continuation of the mod originally created by [Edvin](https://forums.beamdog.com/profile/Edvin).**

## Repository documents

[README](README.md) ·
[Changelog](CHANGELOG.md) ·
[Contributing](CONTRIBUTING.md) ·
[AI setup](AI-CONFIGURATION.md) ·
[Contributors](CONTRIBUTORS.md) ·
[Maintenance notice](MAINTENANCE-NOTICE.md)

> [!IMPORTANT]
> [Edvin](https://forums.beamdog.com/profile/Edvin) is the original author of BG2:EE Unofficial Item Pack.
>
> This repository preserves and maintains the project through a community-led
> continuation coordinated by [DaveTheBrave](https://forums.beamdog.com/profile).
>
> For authorship, stewardship, return-of-author policy, and rights information,
> read [MAINTENANCE-NOTICE.md](MAINTENANCE-NOTICE.md).

## Table of contents

- [Overview](#overview)
- [Project information](#project-information)
- [Requirements](#requirements)
- [Installation](#installation)
- [Components and item catalogue](#components-and-item-catalogue)
  - [1. Unofficial Item Pack](#1-unofficial-item-pack)
  - [4. Holy symbols](#4-holy-symbols)
  - [5. New Items](#5-new-items)
  - [7. Better archery shop](#7-better-archery-shop)
- [Translations](#translations)
- [Compatibility](#compatibility)
- [Known historical issues](#known-historical-issues)
- [Reporting problems](#reporting-problems)
- [Contributing](#contributing)
- [Credits](#credits)
- [History and original discussion](#history-and-original-discussion)
- [Rights and disclaimer](#rights-and-disclaimer)

## Overview

For many years bothered me that lot of items have completely untapped
potential.
So I decided to rework large number of them and "Unofficial Item Pack" was
born.

The project is divided into four optional components. Players may install only
the components they want.

The community-maintained continuation seeks to preserve the original concept
while improving reliability, compatibility, translation support, and
documentation.

## Project information

| Field | Information |
|---|---|
| **Original author** | [Edvin](https://forums.beamdog.com/profile/Edvin) |
| **Community maintainer** | [DaveTheBrave](https://forums.beamdog.com/profile) / [@threetimesdavey](https://github.com/threetimesdavey) |
| **Historical baseline** | Version 2.7b |
| **Primary game** | Baldur’s Gate 2: Enhanced Edition |
| **Minimum game patch stated by the original release** | Patch 2.0 or newer |
| **Installer** | WeiDU |
| **Original languages** | English and Czech |
| **Community translations** | Italian |
| **Installation model** | Four optional components |
| **New game** | Required or strongly recommended for most components |
| **Original discussion** | [Beamdog forum](https://forums.beamdog.com/discussion/56567/mod-bgii-ee-unofficial-item-pack/p1) |

## Requirements

- *Baldur’s Gate 2: Enhanced Edition*;
- game patch 2.0 or newer;
- a WeiDU-compatible installation;
- permission to write files into the game directory;
- a new game for components that alter creature inventories, stores, drops,
  encounters, or world placement.

> [!WARNING]
> Unfortunately, (most parts) this mode (part one is exception) requires
> starting a new game and patch version 2.0 or higher.

Back up important saves before changing a heavily modded installation.

## Installation

### Standard installation

1. Download the desired archive from the repository’s **Releases** page.
2. Extract the archive into the BG2:EE game directory.
3. Confirm that the mod folder and WeiDU setup program are beside `chitin.key`.
4. Run the included WeiDU setup program.
5. Select the desired components and language.
6. Review the generated debug file if installation reports an error.
7. Start a new game when installing components that change stores, creatures,
   drops, encounters, or item placement.

The historical package may use a setup filename containing spaces. Community
release packages may normalize that filename. Run the setup program included
with the release you downloaded.

### Installing on a modded game

Before installing:

- review the [Compatibility](#compatibility) section;
- record the installation order;
- preserve `WeiDU.log`;
- check the issue tracker for current compatibility reports;
- use a new game for meaningful placement changes.

## Components and item catalogue

Installation of this mode has four optional parts:

This personal fork removes Scarlet Katana, Gourmet from Underdark, SoD Items,
and Reworked free action. The remaining sections retain their historical numbers.
WeiDU IDs remain 0, 3, 4, and 6. The key ring and archery ammunition are retained
with their required graphics, independently of the removed SoD Items component.
Uninstall removed components using the previous version before updating an
existing installation.

Available previews use repository-relative image paths under:

- `docs/images/items/`;
- `docs/images/components/`.

Image filenames are normalized to lowercase kebab-case. Keeping these names
stable prevents documentation links from breaking. Entries without an original
source screenshot omit the preview image.

Each item summary uses the short note from the original first-page catalogue
when one is available. Entries without an original source note show only the
item title.

---

## 1. Unofficial Item Pack

<details>
  <summary><strong>Malla’s Soul Stone</strong> — Human souls are source great strength. Gotta catch 'em all!</summary>

  <img src="docs/images/items/mallas-soul-stone.jpg" alt="Malla’s Soul Stone in-game item description">

  This fork patches the installed `AMSOUL01.ITM` instead of replacing it. It
  adds +1 Strength and +10 Hit Points while equipped, unless an equivalent
  unconditional bonus already exists. Existing effects, active abilities,
  icons, usability restrictions and other item fields are preserved. The
  existing description is retained, with a localized note for bonuses added.
  Install this component after the other mod that changes Malla’s Soul Stone.
  The historical preview above shows the original pack's replacement; the
  patched item's final properties depend on the previously installed version.

</details>

<details>
  <summary><strong>Sigil of Tyr</strong> — Only for the best of us.</summary>

  <img src="docs/images/items/sigil-of-tyr.jpg" alt="Sigil of Tyr in-game item description">

</details>

<details>
  <summary><strong>Dark Elven Chain</strong> — Armor Class: +1</summary>

  <img src="docs/images/items/dark-elven-chain.jpg" alt="Dark Elven Chain in-game item description">

</details>

<details>
  <summary><strong>Mask of King Strohm 2I</strong> — I do not see practically nothing.</summary>

  <img src="docs/images/items/mask-of-king-strohm-iii.jpg" alt="Mask of King Strohm 2I in-game item description">

</details>

<details>
  <summary><strong>Symbol of Amaunator</strong> — Praise the sun!</summary>

  <img src="docs/images/items/symbol-of-amaunator.jpg" alt="Symbol of Amaunator in-game item description">

</details>

<details>
  <summary><strong>Human Flesh +5</strong> — You can be evil and also look elegant. (recolored)</summary>

  <img src="docs/images/items/human-flesh-plus-5.jpg" alt="Human Flesh plus 5 in-game item description">

</details>

<details>
  <summary><strong>Keepsake Locket</strong> — True love make you stronger.</summary>

  <img src="docs/images/items/keepsake-locket.jpg" alt="Keepsake Locket in-game item description">

</details>

<details>
  <summary><strong>Shadow Dragon Wardstone</strong> — Loks like Ioun stone to me...</summary>

  <img src="docs/images/items/shadow-dragon-wardstone.jpg" alt="Shadow Dragon Wardstone in-game item description">

</details>

<details>
  <summary><strong>Mantle of Waukeen</strong> — You can save the world with this stylish jewelry!</summary>

  <img src="docs/images/items/mantle-of-waukeen.jpg" alt="Mantle of Waukeen in-game item description">

</details>

<details>
  <summary><strong>Kurtulmak’s Crystal Shard</strong> — Ruby crystal? Hmm...</summary>

  <img src="docs/images/items/kurtulmaks-crystal-shard.jpg" alt="Kurtulmak’s Crystal Shard in-game item description">

</details>

<details>
  <summary><strong>Deirex’s Gems</strong> — Souls belonging drow warriors? That sounds useful.</summary>

  <img src="docs/images/items/deirexs-gems.jpg" alt="Deirex’s Gems in-game item description">

</details>

<details>
  <summary><strong>Talisman of the Hearthfire</strong> — Jump to left or jump to the right!</summary>

  <img src="docs/images/items/talisman-of-the-hearthfire.jpg" alt="Talisman of the Hearthfire in-game item description">

</details>

<details>
  <summary><strong>Blackmist +4</strong> — Now you see me...</summary>

  <img src="docs/images/items/blackmist-plus-4.jpg" alt="Blackmist plus 4 in-game item description">

</details>

<details>
  <summary><strong>Cloak of Balduran</strong> — New drop from Firkraag</summary>
</details>

<details>
  <summary><strong>Helm of Opposite Alignment</strong> — Ask undead mayor</summary>
</details>

<details>
  <summary><strong>Girdle of Femininity/Masculinity</strong> — Owned by biggest Casanova in Amn</summary>
</details>

<details>
  <summary><strong>Bracers of the Blinding Strike</strong> — New drop from Drizzt (According lore he should have them)</summary>
</details>

<details>
  <summary><strong>Silver Dragon Scales</strong> — New drop from Adalon (Right now usable only in ToB. Modification for Cromwell will be in the next version.)</summary>
</details>

---

## 4. Holy symbols

All six holy symbols will now have Armor Class: +1

<details>
  <summary><strong>Six cleric Holy Symbols</strong> — All six holy symbols will now have Armor Class: +1</summary>
</details>

---

## 5. New Items

Completely new (almost) original items.

(Adventure Mart)

<details>
  <summary><strong>Butcherer of Innocents</strong> — BLOOD!</summary>

  <img src="docs/images/items/butcherer-of-innocents.jpg" alt="Butcherer of Innocents in-game item description">

</details>

<details>
  <summary><strong>Guenhwyvar’s Figurine</strong> — New drop from Drizzt</summary>

  <img src="docs/images/items/guenhwyvars-figurine.jpg" alt="Guenhwyvar’s Figurine in-game item description">

</details>

<details>
  <summary><strong>Ring of Superior Arcane Clumsiness</strong> — In possession of a well-known religious madman</summary>

  <img src="docs/images/items/ring-of-superior-arcane-clumsiness.jpg" alt="Ring of Superior Arcane Clumsiness in-game item description">

</details>

<details>
  <summary><strong>Hourglass of Gond</strong> — In the inventory of its original recipient, MAGE18Z.</summary>

  <img src="docs/images/items/hourglass-of-gond.jpg" alt="Hourglass of Gond in-game item description">

  This fork places `HODIN.ITM` only on its original recipient, `MAGE18Z.CRE`,
  in an inventory slot. Duplicate or equipped copies on that creature are
  consolidated into one inventory copy. An existing single inventory copy
  is preserved. This item installs no encounter scripts; vanilla scripts and
  script assignments from other mods are preserved. The current mod package
  contains no custom scripts for this encounter.

</details>

<details>
  <summary><strong>Kangaxx’s Robe</strong> — New robe for evil mages</summary>

  <img src="docs/images/items/kangaxxs-robe.jpg" alt="Kangaxx’s Robe in-game item description">

</details>

---

## 7. Better archery shop

This guy will have much bigger inventory + some ammunition from SoD.

<details>
  <summary><strong>Expanded archery merchant</strong> — This guy will have much bigger inventory + some ammunition from SoD.</summary>

  <img src="docs/images/components/better-archery-shop.jpg" alt="Better Archery Shop component preview">

</details>

<details>
  <summary><strong>Bullet of Fire +1</strong></summary>

  <img src="docs/images/items/bullet-of-fire-plus-1.jpg" alt="Bullet of Fire plus 1 in-game item description">

</details>

<details>
  <summary><strong>Bullet of Ice +1</strong></summary>

  <img src="docs/images/items/bullet-of-ice-plus-1.jpg" alt="Bullet of Ice plus 1 in-game item description">

</details>

<details>
  <summary><strong>Bullet of Electricity +1</strong></summary>

  <img src="docs/images/items/bullet-of-electricity-plus-1.jpg" alt="Bullet of Electricity plus 1 in-game item description">

</details>

<details>
  <summary><strong>Bolt of Fire +1</strong></summary>

  <img src="docs/images/items/bolt-of-fire-plus-1.jpg" alt="Bolt of Fire plus 1 in-game item description">

</details>

<details>
  <summary><strong>Bolt of Ice +1</strong></summary>

  <img src="docs/images/items/bolt-of-ice-plus-1.jpg" alt="Bolt of Ice plus 1 in-game item description">

</details>

---

## Translations

Additional translations are welcome.

Read [CONTRIBUTING.md](CONTRIBUTING.md#contributing-a-translation) before
starting a translation so that terminology, encoding, file ownership, and
testing can be coordinated.

## Compatibility

Compatibility depends on game type, component selection, other mods, and
installation order.

| Game or mod | Status | Notes |
|---|---|---|
| **BG2:EE 2.0+** | Primary target | This is the platform specified by the original release. |
| **Throne of Bhaal content in BG2:EE** | Supported by relevant components | Some items and placements are late-game or expansion-oriented. |
| **EET** | Historically reported as usable with restrictions | The bulk SoD Items component is removed in this fork. The main component retains its key ring and Better archery shop retains its ammunition; check these for overlap. Current community testing is still required. |
| **Item Revisions** | Known overlap | Historical reports identify overlap involving Blackmist and Dark Elven Chain. Review current issues before combining the affected components. |
| **Cowled Menace** | Known historical interaction | Recent versions have worked around several conflicts, but creature inventory changes may still depend on installation order and patching behavior. |
| **Existing saved games** | Limited reliability | Components that modify stores, creatures, drops, or encounters may require a new game. |
| **Other item and store mods** | Test carefully | Conflicts are possible when another mod changes the same item, store, creature, or script. |

### Compatibility principles for future releases

Community maintenance should:

- patch existing resources rather than overwrite them;
- detect game type and optional content;
- avoid importing duplicate SoD items;
- preserve component numbers;
- use unique resource names;
- document affected resources;
- test installation and uninstallation;
- record known installation-order requirements;
- avoid silently removing another mod’s changes.

## Known historical issues

The following issues have been reported against the historical `2.7b` package.
They are listed here for transparency and should not be interpreted as already
fixed unless a release note says so.

### Missing imported-item dependencies

Selected SoD items have been reported to reference EFF, SPL, or other resources
that are absent from some installations.

The maintenance project should audit every imported item and include or patch
all legally redistributable dependencies required by BG2:EE.

### Circlet of the Cynosure restriction

A historical report identified an apparently unintended `CAELAR` usability
restriction associated with **Circlet of the Cynosure**.

The restriction should be confirmed against the source game and corrected
through a targeted patch if it is not intentional.

### Complete resource overwrites

The historical package has been reported to replace complete game resources in
places where a targeted WeiDU patch would be safer.

Complete replacements may erase changes made by other mods.

The community maintenance line should audit these operations and replace them
with cooperative patching wherever possible.

### Creature and store placement conflicts

Items added directly to existing creatures or stores may disappear when another
mod later replaces or reconstructs the same resource.

Affected placements should use resilient patching and be tested with known
overlapping mods.

### Historical archive uncertainty

Some early release notes and intermediate version packages have not yet been
recovered.

See [CHANGELOG.md](CHANGELOG.md) for the reconstructed history and unresolved
gaps.

## Reporting problems

Open a GitHub issue and include:

- game and version;
- operating system;
- mod release or commit;
- installed components;
- other relevant mods;
- installation order;
- relevant `WeiDU.log` entries;
- reproduction steps;
- expected and actual behavior;
- a save game, screenshot, or debug file when useful.

Read [CONTRIBUTING.md](CONTRIBUTING.md#reporting-a-bug) for the complete
bug-report format.

## Contributing

Bug reports, compatibility research, WeiDU improvements, translations,
documentation, tests, screenshots, and carefully discussed new content are
welcome.

Before contributing, read:

- [CONTRIBUTING.md](CONTRIBUTING.md);
- [MAINTENANCE-NOTICE.md](MAINTENANCE-NOTICE.md);
- [CHANGELOG.md](CHANGELOG.md).

Substantial changes should begin with an issue.

## Credits

### Original creator

**[Edvin](https://forums.beamdog.com/profile/Edvin)**

Original concept, design, implementation, item work, component structure,
English and Czech text, and historical releases through version `2.7b`.

### Community maintenance

**[DaveTheBrave](https://forums.beamdog.com/profile) / [@threetimesdavey](https://github.com/threetimesdavey)**

Italian translation, repository stewardship, preservation, documentation,
community coordination, and future maintenance-release preparation.

### Additional contributors

See [CONTRIBUTORS.md](CONTRIBUTORS.md).

## History and original discussion

The project was first published by [Edvin](https://forums.beamdog.com/profile/Edvin) on the Beamdog forums in May 2016.

The original discussion contains:

- the original component descriptions;
- item screenshots;
- release announcements;
- player feedback;
- compatibility reports;
- the Italian translation;
- requests for GitHub hosting;
- later bug reports and preservation efforts.

Useful links:

- [Original post and item catalogue](https://forums.beamdog.com/discussion/56567/mod-bgii-ee-unofficial-item-pack/p1)
- [Later discussion, Italian translation, and GitHub request](https://forums.beamdog.com/discussion/56567/mod-bgii-ee-unofficial-item-pack/p10)
- [Historical changelog](CHANGELOG.md)
- [Community maintenance policy](MAINTENANCE-NOTICE.md)

## Rights and disclaimer

BG2:EE Unofficial Item Pack was originally created by [Edvin](https://forums.beamdog.com/profile/Edvin).

This repository does not claim that inactivity transferred copyright or
authorship to the community maintainer.

See [MAINTENANCE-NOTICE.md](MAINTENANCE-NOTICE.md#rights-and-licensing-status)
for the current rights and permission statement.

This is an unofficial fan-made modification. It is not affiliated with or
endorsed by Beamdog, BioWare, Wizards of the Coast, or their respective owners.

*Baldur’s Gate*, *Baldur’s Gate 2*, *Siege of Dragonspear*,
*Throne of Bhaal*, the Forgotten Realms, and related names and assets belong to
their respective rights holders.

Repository screenshots and item previews are provided for documentation of the
mod and remain subject to applicable rights.

