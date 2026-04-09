# Urban Background

This file defines the 5-level branching tree for the Urban origin. Every decision grants exactly one of: +1 stat point, +2 stat points with -1 stat point, or a basic proficiency.

## Decision Keys

### Level 1
* `1` **Trade Ward:** +1 Stat Point to Intellect.
* `2` **Backstreets:** +1 Stat Point to Agility.

### Level 2
* `.1` **Guild Trained:** Gain proficiency in Sleight of Hand.
* `.2` **Street Taught:** Gain proficiency in Stealth.

### Level 3
* `.1` **Paper Trail:** +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.
* `.2` **Alley Sense:** +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Constitution.

### Level 4
* `.1` **Watchtower Drill:** Gain proficiency in Martial Weapons.
* `.2` **Neon Rite:** Gain proficiency in one basic Cantrip.

### Level 5
* `.1` **Market Leverage:** +1 Stat Point to Will.
* `.2` **Ambush Instinct:** +2 Stat Points: +1 Agility and +1 Intellect; -1 Stat Point to Constitution.

## Explicit Branch Tree

* **Decision Level 1:**
  * `1` Trade Ward (+1 Stat Point to Intellect.)
  * `2` Backstreets (+1 Stat Point to Agility.)
* **Decision Level 2:**
  * `1` -> `1.1` (Guild Trained: Gain proficiency in Sleight of Hand.) or `1.2` (Street Taught: Gain proficiency in Stealth.)
  * `2` -> `2.1` (Guild Trained: Gain proficiency in Sleight of Hand.) or `2.2` (Street Taught: Gain proficiency in Stealth.)
* **Decision Level 3:**
  * `1.1` -> `1.1.1` (Paper Trail: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.) or `1.1.2` (Alley Sense: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Constitution.)
  * `1.2` -> `1.2.1` (Paper Trail: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.) or `1.2.2` (Alley Sense: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Constitution.)
  * `2.1` -> `2.1.1` (Paper Trail: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.) or `2.1.2` (Alley Sense: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Constitution.)
  * `2.2` -> `2.2.1` (Paper Trail: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.) or `2.2.2` (Alley Sense: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Constitution.)
* **Decision Level 4:**
  * `1.1.1` -> `1.1.1.1` (Watchtower Drill: Gain proficiency in Martial Weapons.) or `1.1.1.2` (Neon Rite: Gain proficiency in one basic Cantrip.)
  * `1.1.2` -> `1.1.2.1` (Watchtower Drill: Gain proficiency in Martial Weapons.) or `1.1.2.2` (Neon Rite: Gain proficiency in one basic Cantrip.)
  * `1.2.1` -> `1.2.1.1` (Watchtower Drill: Gain proficiency in Martial Weapons.) or `1.2.1.2` (Neon Rite: Gain proficiency in one basic Cantrip.)
  * `1.2.2` -> `1.2.2.1` (Watchtower Drill: Gain proficiency in Martial Weapons.) or `1.2.2.2` (Neon Rite: Gain proficiency in one basic Cantrip.)
  * `2.1.1` -> `2.1.1.1` (Watchtower Drill: Gain proficiency in Martial Weapons.) or `2.1.1.2` (Neon Rite: Gain proficiency in one basic Cantrip.)
  * `2.1.2` -> `2.1.2.1` (Watchtower Drill: Gain proficiency in Martial Weapons.) or `2.1.2.2` (Neon Rite: Gain proficiency in one basic Cantrip.)
  * `2.2.1` -> `2.2.1.1` (Watchtower Drill: Gain proficiency in Martial Weapons.) or `2.2.1.2` (Neon Rite: Gain proficiency in one basic Cantrip.)
  * `2.2.2` -> `2.2.2.1` (Watchtower Drill: Gain proficiency in Martial Weapons.) or `2.2.2.2` (Neon Rite: Gain proficiency in one basic Cantrip.)
* **Decision Level 5:**
  * `1.1.1.1` -> `1.1.1.1.1` (Market Leverage: +1 Stat Point to Will.) or `1.1.1.1.2` (Ambush Instinct: +2 Stat Points: +1 Agility and +1 Intellect; -1 Stat Point to Constitution.)
  * `1.1.1.2` -> `1.1.1.2.1` (Market Leverage: +1 Stat Point to Will.) or `1.1.1.2.2` (Ambush Instinct: +2 Stat Points: +1 Agility and +1 Intellect; -1 Stat Point to Constitution.)
  * `1.1.2.1` -> `1.1.2.1.1` (Market Leverage: +1 Stat Point to Will.) or `1.1.2.1.2` (Ambush Instinct: +2 Stat Points: +1 Agility and +1 Intellect; -1 Stat Point to Constitution.)
  * `1.1.2.2` -> `1.1.2.2.1` (Market Leverage: +1 Stat Point to Will.) or `1.1.2.2.2` (Ambush Instinct: +2 Stat Points: +1 Agility and +1 Intellect; -1 Stat Point to Constitution.)
  * `1.2.1.1` -> `1.2.1.1.1` (Market Leverage: +1 Stat Point to Will.) or `1.2.1.1.2` (Ambush Instinct: +2 Stat Points: +1 Agility and +1 Intellect; -1 Stat Point to Constitution.)
  * `1.2.1.2` -> `1.2.1.2.1` (Market Leverage: +1 Stat Point to Will.) or `1.2.1.2.2` (Ambush Instinct: +2 Stat Points: +1 Agility and +1 Intellect; -1 Stat Point to Constitution.)
  * `1.2.2.1` -> `1.2.2.1.1` (Market Leverage: +1 Stat Point to Will.) or `1.2.2.1.2` (Ambush Instinct: +2 Stat Points: +1 Agility and +1 Intellect; -1 Stat Point to Constitution.)
  * `1.2.2.2` -> `1.2.2.2.1` (Market Leverage: +1 Stat Point to Will.) or `1.2.2.2.2` (Ambush Instinct: +2 Stat Points: +1 Agility and +1 Intellect; -1 Stat Point to Constitution.)
  * `2.1.1.1` -> `2.1.1.1.1` (Market Leverage: +1 Stat Point to Will.) or `2.1.1.1.2` (Ambush Instinct: +2 Stat Points: +1 Agility and +1 Intellect; -1 Stat Point to Constitution.)
  * `2.1.1.2` -> `2.1.1.2.1` (Market Leverage: +1 Stat Point to Will.) or `2.1.1.2.2` (Ambush Instinct: +2 Stat Points: +1 Agility and +1 Intellect; -1 Stat Point to Constitution.)
  * `2.1.2.1` -> `2.1.2.1.1` (Market Leverage: +1 Stat Point to Will.) or `2.1.2.1.2` (Ambush Instinct: +2 Stat Points: +1 Agility and +1 Intellect; -1 Stat Point to Constitution.)
  * `2.1.2.2` -> `2.1.2.2.1` (Market Leverage: +1 Stat Point to Will.) or `2.1.2.2.2` (Ambush Instinct: +2 Stat Points: +1 Agility and +1 Intellect; -1 Stat Point to Constitution.)
  * `2.2.1.1` -> `2.2.1.1.1` (Market Leverage: +1 Stat Point to Will.) or `2.2.1.1.2` (Ambush Instinct: +2 Stat Points: +1 Agility and +1 Intellect; -1 Stat Point to Constitution.)
  * `2.2.1.2` -> `2.2.1.2.1` (Market Leverage: +1 Stat Point to Will.) or `2.2.1.2.2` (Ambush Instinct: +2 Stat Points: +1 Agility and +1 Intellect; -1 Stat Point to Constitution.)
  * `2.2.2.1` -> `2.2.2.1.1` (Market Leverage: +1 Stat Point to Will.) or `2.2.2.1.2` (Ambush Instinct: +2 Stat Points: +1 Agility and +1 Intellect; -1 Stat Point to Constitution.)
  * `2.2.2.2` -> `2.2.2.2.1` (Market Leverage: +1 Stat Point to Will.) or `2.2.2.2.2` (Ambush Instinct: +2 Stat Points: +1 Agility and +1 Intellect; -1 Stat Point to Constitution.)

* **Level 5 Final Paths (32 total):**
  * `1.1.1.1.1`, `1.1.1.1.2`, `1.1.1.2.1`, `1.1.1.2.2`, `1.1.2.1.1`, `1.1.2.1.2`, `1.1.2.2.1`, `1.1.2.2.2`, `1.2.1.1.1`, `1.2.1.1.2`, `1.2.1.2.1`, `1.2.1.2.2`, `1.2.2.1.1`, `1.2.2.1.2`, `1.2.2.2.1`, `1.2.2.2.2`, `2.1.1.1.1`, `2.1.1.1.2`, `2.1.1.2.1`, `2.1.1.2.2`, `2.1.2.1.1`, `2.1.2.1.2`, `2.1.2.2.1`, `2.1.2.2.2`, `2.2.1.1.1`, `2.2.1.1.2`, `2.2.1.2.1`, `2.2.1.2.2`, `2.2.2.1.1`, `2.2.2.1.2`, `2.2.2.2.1`, `2.2.2.2.2`
