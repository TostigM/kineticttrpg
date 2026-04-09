# Frontier Background

This file defines the 5-level branching tree for the Frontier origin. Every decision grants exactly one of: +1 stat point, +2 stat points with -1 stat point, or a basic proficiency.

## Decision Keys

### Level 1
* `1` **Outpost:** +1 Stat Point to Constitution.
* `2` **Trail Town:** +1 Stat Point to Agility.

### Level 2
* `.1` **Pathfinder:** Gain proficiency in Survival.
* `.2` **Stockade Guard:** Gain proficiency in Simple Weapons.

### Level 3
* `.1` **Surveyor:** +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.
* `.2` **Lookout:** +2 Stat Points: +1 Agility and +1 Will; -1 Stat Point to Constitution.

### Level 4
* `.1` **Trail Marksman:** Gain proficiency in Martial Weapons.
* `.2` **Camp Chirurgeon:** Gain proficiency in Medicine.

### Level 5
* `.1` **Steady Fire:** +1 Stat Point to Agility.
* `.2` **Cold Nerves:** +2 Stat Points: +1 Will and +1 Constitution; -1 Stat Point to Intellect.

## Explicit Branch Tree

* **Decision Level 1:**
  * `1` Outpost (+1 Stat Point to Constitution.)
  * `2` Trail Town (+1 Stat Point to Agility.)
* **Decision Level 2:**
  * `1` -> `1.1` (Pathfinder: Gain proficiency in Survival.) or `1.2` (Stockade Guard: Gain proficiency in Simple Weapons.)
  * `2` -> `2.1` (Pathfinder: Gain proficiency in Survival.) or `2.2` (Stockade Guard: Gain proficiency in Simple Weapons.)
* **Decision Level 3:**
  * `1.1` -> `1.1.1` (Surveyor: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.) or `1.1.2` (Lookout: +2 Stat Points: +1 Agility and +1 Will; -1 Stat Point to Constitution.)
  * `1.2` -> `1.2.1` (Surveyor: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.) or `1.2.2` (Lookout: +2 Stat Points: +1 Agility and +1 Will; -1 Stat Point to Constitution.)
  * `2.1` -> `2.1.1` (Surveyor: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.) or `2.1.2` (Lookout: +2 Stat Points: +1 Agility and +1 Will; -1 Stat Point to Constitution.)
  * `2.2` -> `2.2.1` (Surveyor: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.) or `2.2.2` (Lookout: +2 Stat Points: +1 Agility and +1 Will; -1 Stat Point to Constitution.)
* **Decision Level 4:**
  * `1.1.1` -> `1.1.1.1` (Trail Marksman: Gain proficiency in Martial Weapons.) or `1.1.1.2` (Camp Chirurgeon: Gain proficiency in Medicine.)
  * `1.1.2` -> `1.1.2.1` (Trail Marksman: Gain proficiency in Martial Weapons.) or `1.1.2.2` (Camp Chirurgeon: Gain proficiency in Medicine.)
  * `1.2.1` -> `1.2.1.1` (Trail Marksman: Gain proficiency in Martial Weapons.) or `1.2.1.2` (Camp Chirurgeon: Gain proficiency in Medicine.)
  * `1.2.2` -> `1.2.2.1` (Trail Marksman: Gain proficiency in Martial Weapons.) or `1.2.2.2` (Camp Chirurgeon: Gain proficiency in Medicine.)
  * `2.1.1` -> `2.1.1.1` (Trail Marksman: Gain proficiency in Martial Weapons.) or `2.1.1.2` (Camp Chirurgeon: Gain proficiency in Medicine.)
  * `2.1.2` -> `2.1.2.1` (Trail Marksman: Gain proficiency in Martial Weapons.) or `2.1.2.2` (Camp Chirurgeon: Gain proficiency in Medicine.)
  * `2.2.1` -> `2.2.1.1` (Trail Marksman: Gain proficiency in Martial Weapons.) or `2.2.1.2` (Camp Chirurgeon: Gain proficiency in Medicine.)
  * `2.2.2` -> `2.2.2.1` (Trail Marksman: Gain proficiency in Martial Weapons.) or `2.2.2.2` (Camp Chirurgeon: Gain proficiency in Medicine.)
* **Decision Level 5:**
  * `1.1.1.1` -> `1.1.1.1.1` (Steady Fire: +1 Stat Point to Agility.) or `1.1.1.1.2` (Cold Nerves: +2 Stat Points: +1 Will and +1 Constitution; -1 Stat Point to Intellect.)
  * `1.1.1.2` -> `1.1.1.2.1` (Steady Fire: +1 Stat Point to Agility.) or `1.1.1.2.2` (Cold Nerves: +2 Stat Points: +1 Will and +1 Constitution; -1 Stat Point to Intellect.)
  * `1.1.2.1` -> `1.1.2.1.1` (Steady Fire: +1 Stat Point to Agility.) or `1.1.2.1.2` (Cold Nerves: +2 Stat Points: +1 Will and +1 Constitution; -1 Stat Point to Intellect.)
  * `1.1.2.2` -> `1.1.2.2.1` (Steady Fire: +1 Stat Point to Agility.) or `1.1.2.2.2` (Cold Nerves: +2 Stat Points: +1 Will and +1 Constitution; -1 Stat Point to Intellect.)
  * `1.2.1.1` -> `1.2.1.1.1` (Steady Fire: +1 Stat Point to Agility.) or `1.2.1.1.2` (Cold Nerves: +2 Stat Points: +1 Will and +1 Constitution; -1 Stat Point to Intellect.)
  * `1.2.1.2` -> `1.2.1.2.1` (Steady Fire: +1 Stat Point to Agility.) or `1.2.1.2.2` (Cold Nerves: +2 Stat Points: +1 Will and +1 Constitution; -1 Stat Point to Intellect.)
  * `1.2.2.1` -> `1.2.2.1.1` (Steady Fire: +1 Stat Point to Agility.) or `1.2.2.1.2` (Cold Nerves: +2 Stat Points: +1 Will and +1 Constitution; -1 Stat Point to Intellect.)
  * `1.2.2.2` -> `1.2.2.2.1` (Steady Fire: +1 Stat Point to Agility.) or `1.2.2.2.2` (Cold Nerves: +2 Stat Points: +1 Will and +1 Constitution; -1 Stat Point to Intellect.)
  * `2.1.1.1` -> `2.1.1.1.1` (Steady Fire: +1 Stat Point to Agility.) or `2.1.1.1.2` (Cold Nerves: +2 Stat Points: +1 Will and +1 Constitution; -1 Stat Point to Intellect.)
  * `2.1.1.2` -> `2.1.1.2.1` (Steady Fire: +1 Stat Point to Agility.) or `2.1.1.2.2` (Cold Nerves: +2 Stat Points: +1 Will and +1 Constitution; -1 Stat Point to Intellect.)
  * `2.1.2.1` -> `2.1.2.1.1` (Steady Fire: +1 Stat Point to Agility.) or `2.1.2.1.2` (Cold Nerves: +2 Stat Points: +1 Will and +1 Constitution; -1 Stat Point to Intellect.)
  * `2.1.2.2` -> `2.1.2.2.1` (Steady Fire: +1 Stat Point to Agility.) or `2.1.2.2.2` (Cold Nerves: +2 Stat Points: +1 Will and +1 Constitution; -1 Stat Point to Intellect.)
  * `2.2.1.1` -> `2.2.1.1.1` (Steady Fire: +1 Stat Point to Agility.) or `2.2.1.1.2` (Cold Nerves: +2 Stat Points: +1 Will and +1 Constitution; -1 Stat Point to Intellect.)
  * `2.2.1.2` -> `2.2.1.2.1` (Steady Fire: +1 Stat Point to Agility.) or `2.2.1.2.2` (Cold Nerves: +2 Stat Points: +1 Will and +1 Constitution; -1 Stat Point to Intellect.)
  * `2.2.2.1` -> `2.2.2.1.1` (Steady Fire: +1 Stat Point to Agility.) or `2.2.2.1.2` (Cold Nerves: +2 Stat Points: +1 Will and +1 Constitution; -1 Stat Point to Intellect.)
  * `2.2.2.2` -> `2.2.2.2.1` (Steady Fire: +1 Stat Point to Agility.) or `2.2.2.2.2` (Cold Nerves: +2 Stat Points: +1 Will and +1 Constitution; -1 Stat Point to Intellect.)

* **Level 5 Final Paths (32 total):**
  * `1.1.1.1.1`, `1.1.1.1.2`, `1.1.1.2.1`, `1.1.1.2.2`, `1.1.2.1.1`, `1.1.2.1.2`, `1.1.2.2.1`, `1.1.2.2.2`, `1.2.1.1.1`, `1.2.1.1.2`, `1.2.1.2.1`, `1.2.1.2.2`, `1.2.2.1.1`, `1.2.2.1.2`, `1.2.2.2.1`, `1.2.2.2.2`, `2.1.1.1.1`, `2.1.1.1.2`, `2.1.1.2.1`, `2.1.1.2.2`, `2.1.2.1.1`, `2.1.2.1.2`, `2.1.2.2.1`, `2.1.2.2.2`, `2.2.1.1.1`, `2.2.1.1.2`, `2.2.1.2.1`, `2.2.1.2.2`, `2.2.2.1.1`, `2.2.2.1.2`, `2.2.2.2.1`, `2.2.2.2.2`
