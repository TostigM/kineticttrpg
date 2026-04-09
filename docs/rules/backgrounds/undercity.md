# Undercity Background

This file defines the 5-level branching tree for the Undercity origin. Every decision grants exactly one of: +1 stat point, +2 stat points with -1 stat point, or a basic proficiency.

## Decision Keys

### Level 1
* `1` **Sewer Maze:** +1 Stat Point to Agility.
* `2` **Old Foundations:** +1 Stat Point to Intellect.

### Level 2
* `.1` **Burglar:** Gain proficiency in Sleight of Hand.
* `.2` **Broker:** Gain proficiency in Deception.

### Level 3
* `.1` **Shadow Runner:** +2 Stat Points: +1 Agility and +1 Will; -1 Stat Point to Constitution.
* `.2` **Information Rat:** +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.

### Level 4
* `.1` **Knife School:** Gain proficiency with one Exotic Weapon.
* `.2` **Back Alley Hex:** Gain proficiency in one basic Cantrip.

### Level 5
* `.1` **Whisper Ledger:** +1 Stat Point to Intellect.
* `.2` **Dirty Opening:** +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.

## Explicit Branch Tree

* **Decision Level 1:**
  * `1` Sewer Maze (+1 Stat Point to Agility.)
  * `2` Old Foundations (+1 Stat Point to Intellect.)
* **Decision Level 2:**
  * `1` -> `1.1` (Burglar: Gain proficiency in Sleight of Hand.) or `1.2` (Broker: Gain proficiency in Deception.)
  * `2` -> `2.1` (Burglar: Gain proficiency in Sleight of Hand.) or `2.2` (Broker: Gain proficiency in Deception.)
* **Decision Level 3:**
  * `1.1` -> `1.1.1` (Shadow Runner: +2 Stat Points: +1 Agility and +1 Will; -1 Stat Point to Constitution.) or `1.1.2` (Information Rat: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.)
  * `1.2` -> `1.2.1` (Shadow Runner: +2 Stat Points: +1 Agility and +1 Will; -1 Stat Point to Constitution.) or `1.2.2` (Information Rat: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.)
  * `2.1` -> `2.1.1` (Shadow Runner: +2 Stat Points: +1 Agility and +1 Will; -1 Stat Point to Constitution.) or `2.1.2` (Information Rat: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.)
  * `2.2` -> `2.2.1` (Shadow Runner: +2 Stat Points: +1 Agility and +1 Will; -1 Stat Point to Constitution.) or `2.2.2` (Information Rat: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.)
* **Decision Level 4:**
  * `1.1.1` -> `1.1.1.1` (Knife School: Gain proficiency with one Exotic Weapon.) or `1.1.1.2` (Back Alley Hex: Gain proficiency in one basic Cantrip.)
  * `1.1.2` -> `1.1.2.1` (Knife School: Gain proficiency with one Exotic Weapon.) or `1.1.2.2` (Back Alley Hex: Gain proficiency in one basic Cantrip.)
  * `1.2.1` -> `1.2.1.1` (Knife School: Gain proficiency with one Exotic Weapon.) or `1.2.1.2` (Back Alley Hex: Gain proficiency in one basic Cantrip.)
  * `1.2.2` -> `1.2.2.1` (Knife School: Gain proficiency with one Exotic Weapon.) or `1.2.2.2` (Back Alley Hex: Gain proficiency in one basic Cantrip.)
  * `2.1.1` -> `2.1.1.1` (Knife School: Gain proficiency with one Exotic Weapon.) or `2.1.1.2` (Back Alley Hex: Gain proficiency in one basic Cantrip.)
  * `2.1.2` -> `2.1.2.1` (Knife School: Gain proficiency with one Exotic Weapon.) or `2.1.2.2` (Back Alley Hex: Gain proficiency in one basic Cantrip.)
  * `2.2.1` -> `2.2.1.1` (Knife School: Gain proficiency with one Exotic Weapon.) or `2.2.1.2` (Back Alley Hex: Gain proficiency in one basic Cantrip.)
  * `2.2.2` -> `2.2.2.1` (Knife School: Gain proficiency with one Exotic Weapon.) or `2.2.2.2` (Back Alley Hex: Gain proficiency in one basic Cantrip.)
* **Decision Level 5:**
  * `1.1.1.1` -> `1.1.1.1.1` (Whisper Ledger: +1 Stat Point to Intellect.) or `1.1.1.1.2` (Dirty Opening: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `1.1.1.2` -> `1.1.1.2.1` (Whisper Ledger: +1 Stat Point to Intellect.) or `1.1.1.2.2` (Dirty Opening: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `1.1.2.1` -> `1.1.2.1.1` (Whisper Ledger: +1 Stat Point to Intellect.) or `1.1.2.1.2` (Dirty Opening: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `1.1.2.2` -> `1.1.2.2.1` (Whisper Ledger: +1 Stat Point to Intellect.) or `1.1.2.2.2` (Dirty Opening: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `1.2.1.1` -> `1.2.1.1.1` (Whisper Ledger: +1 Stat Point to Intellect.) or `1.2.1.1.2` (Dirty Opening: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `1.2.1.2` -> `1.2.1.2.1` (Whisper Ledger: +1 Stat Point to Intellect.) or `1.2.1.2.2` (Dirty Opening: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `1.2.2.1` -> `1.2.2.1.1` (Whisper Ledger: +1 Stat Point to Intellect.) or `1.2.2.1.2` (Dirty Opening: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `1.2.2.2` -> `1.2.2.2.1` (Whisper Ledger: +1 Stat Point to Intellect.) or `1.2.2.2.2` (Dirty Opening: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `2.1.1.1` -> `2.1.1.1.1` (Whisper Ledger: +1 Stat Point to Intellect.) or `2.1.1.1.2` (Dirty Opening: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `2.1.1.2` -> `2.1.1.2.1` (Whisper Ledger: +1 Stat Point to Intellect.) or `2.1.1.2.2` (Dirty Opening: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `2.1.2.1` -> `2.1.2.1.1` (Whisper Ledger: +1 Stat Point to Intellect.) or `2.1.2.1.2` (Dirty Opening: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `2.1.2.2` -> `2.1.2.2.1` (Whisper Ledger: +1 Stat Point to Intellect.) or `2.1.2.2.2` (Dirty Opening: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `2.2.1.1` -> `2.2.1.1.1` (Whisper Ledger: +1 Stat Point to Intellect.) or `2.2.1.1.2` (Dirty Opening: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `2.2.1.2` -> `2.2.1.2.1` (Whisper Ledger: +1 Stat Point to Intellect.) or `2.2.1.2.2` (Dirty Opening: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `2.2.2.1` -> `2.2.2.1.1` (Whisper Ledger: +1 Stat Point to Intellect.) or `2.2.2.1.2` (Dirty Opening: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `2.2.2.2` -> `2.2.2.2.1` (Whisper Ledger: +1 Stat Point to Intellect.) or `2.2.2.2.2` (Dirty Opening: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)

* **Level 5 Final Paths (32 total):**
  * `1.1.1.1.1`, `1.1.1.1.2`, `1.1.1.2.1`, `1.1.1.2.2`, `1.1.2.1.1`, `1.1.2.1.2`, `1.1.2.2.1`, `1.1.2.2.2`, `1.2.1.1.1`, `1.2.1.1.2`, `1.2.1.2.1`, `1.2.1.2.2`, `1.2.2.1.1`, `1.2.2.1.2`, `1.2.2.2.1`, `1.2.2.2.2`, `2.1.1.1.1`, `2.1.1.1.2`, `2.1.1.2.1`, `2.1.1.2.2`, `2.1.2.1.1`, `2.1.2.1.2`, `2.1.2.2.1`, `2.1.2.2.2`, `2.2.1.1.1`, `2.2.1.1.2`, `2.2.1.2.1`, `2.2.1.2.2`, `2.2.2.1.1`, `2.2.2.1.2`, `2.2.2.2.1`, `2.2.2.2.2`
