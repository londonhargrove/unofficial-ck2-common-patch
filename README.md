<!-- SPDX-FileCopyrightText: 2026 London Hargrove -->
<!-- SPDX-License-Identifier: GPL-3.0-only -->

# Unofficial CK2 Common Patch

Developed by **London Hargrove**. A loose-file mod for Crusader Kings II that fixes bugs, improves existing systems, and adds content where it fits the original game. This project continues the original [Unofficial CK2 Patch](https://github.com/EliteNinjaX/unofficial-ck2-patch).

The inherited Roman update includes changes to the Colosseum, the decision to give Rome to the Pope, access to the Imperial Diadem and Reichskrone, and the Latin Empire bookmark. See the original repository for its release history.

## Using the mod

Keep a backup of your saves. Install an authorized release in CK2's mod directory and enable it in the launcher. For a loose-file development checkout, use a separate copy named `unofficial-common-patch` in that directory and create a sibling `unofficial-common-patch.mod` with these contents:

```text
name = "Unofficial CK2 Common Patch"
path = "mod/unofficial-common-patch"
```

Start a fresh local campaign for initial testing. The inherited package descriptor targets the original ZIP release. Test the mod against CK2 3.3.5.1 before adopting it for an existing campaign.

## Companion project

[Unofficial CK2 Engine Patch](https://github.com/LondonHargrove/unofficial-engine-patch) handles executable-level compatibility and achievement behavior. The Common Patch can be developed and tested independently. Loose-file changes can affect CK2's achievement checksum.

## Credits and licensing

The original project was published as **EliteNinjaX**. The original release credits the Colosseum work to **When the World Stopped Making Sense**.

[GPL-3.0-only](LICENSE) applies to this README and project-owned contributions explicitly marked with that license. Inherited game data, artwork, and third-party mod material retain their original terms. Publication of this split repository is pending review of the rights to redistribute those files and their historical revisions.
