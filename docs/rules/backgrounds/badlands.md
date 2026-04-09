# Badlands Background

This file defines the 5-level branching tree for the Badlands origin. Every decision grants exactly one of: +1 stat point, +2 stat points with -1 stat point, or a basic proficiency.

## Decision Keys

### Level 1
* `1` **Salt Flats:** +1 Stat Point to Constitution.
* `2` **Stone Wastes:** +1 Stat Point to Prowess.

### Level 2
* `.1` **Scavenger:** Gain proficiency in Survival.
* `.2` **Beast Driver:** Gain proficiency in Animal Handling.

### Level 3
* `.1` **Dust Tracker:** +2 Stat Points: +1 Agility and +1 Will; -1 Stat Point to Intellect.
* `.2` **Raider Reader:** +2 Stat Points: +1 Prowess and +1 Intellect; -1 Stat Point to Will.

### Level 4
* `.1` **Salt Gunner:** Gain proficiency in Martial Weapons.
* `.2` **Pit Fighter:** Gain proficiency with one Exotic Weapon.

### Level 5
* `.1` **Mean Opening:** +1 Stat Point to Prowess.
* `.2` **Last Dry Powder:** +2 Stat Points: +1 Prowess and +1 Agility; -1 Stat Point to Will.

## Explicit Branch Tree

* **Decision Level 1:**
  * `1` Salt Flats (+1 Stat Point to Constitution.)
  * `2` Stone Wastes (+1 Stat Point to Prowess.)
* **Decision Level 2:**
  * `1` -> `1.1` (Scavenger: Gain proficiency in Survival.) or `1.2` (Beast Driver: Gain proficiency in Animal Handling.)
  * `2` -> `2.1` (Scavenger: Gain proficiency in Survival.) or `2.2` (Beast Driver: Gain proficiency in Animal Handling.)
* **Decision Level 3:**
  * `1.1` -> `1.1.1` (Dust Tracker: +2 Stat Points: +1 Agility and +1 Will; -1 Stat Point to Intellect.) or `1.1.2` (Raider Reader: +2 Stat Points: +1 Prowess and +1 Intellect; -1 Stat Point to Will.)
  * `1.2` -> `1.2.1` (Dust Tracker: +2 Stat Points: +1 Agility and +1 Will; -1 Stat Point to Intellect.) or `1.2.2` (Raider Reader: +2 Stat Points: +1 Prowess and +1 Intellect; -1 Stat Point to Will.)
  * `2.1` -> `2.1.1` (Dust Tracker: +2 Stat Points: +1 Agility and +1 Will; -1 Stat Point to Intellect.) or `2.1.2` (Raider Reader: +2 Stat Points: +1 Prowess and +1 Intellect; -1 Stat Point to Will.)
  * `2.2` -> `2.2.1` (Dust Tracker: +2 Stat Points: +1 Agility and +1 Will; -1 Stat Point to Intellect.) or `2.2.2` (Raider Reader: +2 Stat Points: +1 Prowess and +1 Intellect; -1 Stat Point to Will.)
* **Decision Level 4:**
  * `1.1.1` -> `1.1.1.1` (Salt Gunner: Gain proficiency in Martial Weapons.) or `1.1.1.2` (Pit Fighter: Gain proficiency with one Exotic Weapon.)
  * `1.1.2` -> `1.1.2.1` (Salt Gunner: Gain proficiency in Martial Weapons.) or `1.1.2.2` (Pit Fighter: Gain proficiency with one Exotic Weapon.)
  * `1.2.1` -> `1.2.1.1` (Salt Gunner: Gain proficiency in Martial Weapons.) or `1.2.1.2` (Pit Fighter: Gain proficiency with one Exotic Weapon.)
  * `1.2.2` -> `1.2.2.1` (Salt Gunner: Gain proficiency in Martial Weapons.) or `1.2.2.2` (Pit Fighter: Gain proficiency with one Exotic Weapon.)
  * `2.1.1` -> `2.1.1.1` (Salt Gunner: Gain proficiency in Martial Weapons.) or `2.1.1.2` (Pit Fighter: Gain proficiency with one Exotic Weapon.)
  * `2.1.2` -> `2.1.2.1` (Salt Gunner: Gain proficiency in Martial Weapons.) or `2.1.2.2` (Pit Fighter: Gain proficiency with one Exotic Weapon.)
  * `2.2.1` -> `2.2.1.1` (Salt Gunner: Gain proficiency in Martial Weapons.) or `2.2.1.2` (Pit Fighter: Gain proficiency with one Exotic Weapon.)
  * `2.2.2` -> `2.2.2.1` (Salt Gunner: Gain proficiency in Martial Weapons.) or `2.2.2.2` (Pit Fighter: Gain proficiency with one Exotic Weapon.)
* **Decision Level 5:**
  * `1.1.1.1` -> `1.1.1.1.1` (Mean Opening: +1 Stat Point to Prowess.) or `1.1.1.1.2` (Last Dry Powder: +2 Stat Points: +1 Prowess and +1 Agility; -1 Stat Point to Will.)
  * `1.1.1.2` -> `1.1.1.2.1` (Mean Opening: +1 Stat Point to Prowess.) or `1.1.1.2.2` (Last Dry Powder: +2 Stat Points: +1 Prowess and +1 Agility; -1 Stat Point to Will.)
  * `1.1.2.1` -> `1.1.2.1.1` (Mean Opening: +1 Stat Point to Prowess.) or `1.1.2.1.2` (Last Dry Powder: +2 Stat Points: +1 Prowess and +1 Agility; -1 Stat Point to Will.)
  * `1.1.2.2` -> `1.1.2.2.1` (Mean Opening: +1 Stat Point to Prowess.) or `1.1.2.2.2` (Last Dry Powder: +2 Stat Points: +1 Prowess and +1 Agility; -1 Stat Point to Will.)
  * `1.2.1.1` -> `1.2.1.1.1` (Mean Opening: +1 Stat Point to Prowess.) or `1.2.1.1.2` (Last Dry Powder: +2 Stat Points: +1 Prowess and +1 Agility; -1 Stat Point to Will.)
  * `1.2.1.2` -> `1.2.1.2.1` (Mean Opening: +1 Stat Point to Prowess.) or `1.2.1.2.2` (Last Dry Powder: +2 Stat Points: +1 Prowess and +1 Agility; -1 Stat Point to Will.)
  * `1.2.2.1` -> `1.2.2.1.1` (Mean Opening: +1 Stat Point to Prowess.) or `1.2.2.1.2` (Last Dry Powder: +2 Stat Points: +1 Prowess and +1 Agility; -1 Stat Point to Will.)
  * `1.2.2.2` -> `1.2.2.2.1` (Mean Opening: +1 Stat Point to Prowess.) or `1.2.2.2.2` (Last Dry Powder: +2 Stat Points: +1 Prowess and +1 Agility; -1 Stat Point to Will.)
  * `2.1.1.1` -> `2.1.1.1.1` (Mean Opening: +1 Stat Point to Prowess.) or `2.1.1.1.2` (Last Dry Powder: +2 Stat Points: +1 Prowess and +1 Agility; -1 Stat Point to Will.)
  * `2.1.1.2` -> `2.1.1.2.1` (Mean Opening: +1 Stat Point to Prowess.) or `2.1.1.2.2` (Last Dry Powder: +2 Stat Points: +1 Prowess and +1 Agility; -1 Stat Point to Will.)
  * `2.1.2.1` -> `2.1.2.1.1` (Mean Opening: +1 Stat Point to Prowess.) or `2.1.2.1.2` (Last Dry Powder: +2 Stat Points: +1 Prowess and +1 Agility; -1 Stat Point to Will.)
  * `2.1.2.2` -> `2.1.2.2.1` (Mean Opening: +1 Stat Point to Prowess.) or `2.1.2.2.2` (Last Dry Powder: +2 Stat Points: +1 Prowess and +1 Agility; -1 Stat Point to Will.)
  * `2.2.1.1` -> `2.2.1.1.1` (Mean Opening: +1 Stat Point to Prowess.) or `2.2.1.1.2` (Last Dry Powder: +2 Stat Points: +1 Prowess and +1 Agility; -1 Stat Point to Will.)
  * `2.2.1.2` -> `2.2.1.2.1` (Mean Opening: +1 Stat Point to Prowess.) or `2.2.1.2.2` (Last Dry Powder: +2 Stat Points: +1 Prowess and +1 Agility; -1 Stat Point to Will.)
  * `2.2.2.1` -> `2.2.2.1.1` (Mean Opening: +1 Stat Point to Prowess.) or `2.2.2.1.2` (Last Dry Powder: +2 Stat Points: +1 Prowess and +1 Agility; -1 Stat Point to Will.)
  * `2.2.2.2` -> `2.2.2.2.1` (Mean Opening: +1 Stat Point to Prowess.) or `2.2.2.2.2` (Last Dry Powder: +2 Stat Points: +1 Prowess and +1 Agility; -1 Stat Point to Will.)

* **Level 5 Final Paths (32 total):**
  * `1.1.1.1.1`, `1.1.1.1.2`, `1.1.1.2.1`, `1.1.1.2.2`, `1.1.2.1.1`, `1.1.2.1.2`, `1.1.2.2.1`, `1.1.2.2.2`, `1.2.1.1.1`, `1.2.1.1.2`, `1.2.1.2.1`, `1.2.1.2.2`, `1.2.2.1.1`, `1.2.2.1.2`, `1.2.2.2.1`, `1.2.2.2.2`, `2.1.1.1.1`, `2.1.1.1.2`, `2.1.1.2.1`, `2.1.1.2.2`, `2.1.2.1.1`, `2.1.2.1.2`, `2.1.2.2.1`, `2.1.2.2.2`, `2.2.1.1.1`, `2.2.1.1.2`, `2.2.1.2.1`, `2.2.1.2.2`, `2.2.2.1.1`, `2.2.2.1.2`, `2.2.2.2.1`, `2.2.2.2.2`
