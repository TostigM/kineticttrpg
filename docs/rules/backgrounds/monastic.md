# Monastic Background

This file defines the 5-level branching tree for the Monastic origin. Every decision grants exactly one of: +1 stat point, +2 stat points with -1 stat point, or a basic proficiency.

## Decision Keys

### Level 1
* `1` **Scholastic Order:** +1 Stat Point to Intellect.
* `2` **Vigil Order:** +1 Stat Point to Will.

### Level 2
* `.1` **Scriptorium:** Gain proficiency in Lore.
* `.2` **Infirmary:** Gain proficiency in Medicine.

### Level 3
* `.1` **Meditative:** +2 Stat Points: +1 Will and +1 Constitution; -1 Stat Point to Prowess.
* `.2` **Ritualist:** +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Agility.

### Level 4
* `.1` **Discipline Arms:** Gain proficiency in Simple Weapons.
* `.2` **Novice Adept:** Gain proficiency in one basic Cantrip.

### Level 5
* `.1` **Warden Prayer:** +1 Stat Point to Constitution.
* `.2` **Ascetic Strike:** +2 Stat Points: +1 Prowess and +1 Will; -1 Stat Point to Intellect.

## Explicit Branch Tree

* **Decision Level 1:**
  * `1` Scholastic Order (+1 Stat Point to Intellect.)
  * `2` Vigil Order (+1 Stat Point to Will.)
* **Decision Level 2:**
  * `1` -> `1.1` (Scriptorium: Gain proficiency in Lore.) or `1.2` (Infirmary: Gain proficiency in Medicine.)
  * `2` -> `2.1` (Scriptorium: Gain proficiency in Lore.) or `2.2` (Infirmary: Gain proficiency in Medicine.)
* **Decision Level 3:**
  * `1.1` -> `1.1.1` (Meditative: +2 Stat Points: +1 Will and +1 Constitution; -1 Stat Point to Prowess.) or `1.1.2` (Ritualist: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Agility.)
  * `1.2` -> `1.2.1` (Meditative: +2 Stat Points: +1 Will and +1 Constitution; -1 Stat Point to Prowess.) or `1.2.2` (Ritualist: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Agility.)
  * `2.1` -> `2.1.1` (Meditative: +2 Stat Points: +1 Will and +1 Constitution; -1 Stat Point to Prowess.) or `2.1.2` (Ritualist: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Agility.)
  * `2.2` -> `2.2.1` (Meditative: +2 Stat Points: +1 Will and +1 Constitution; -1 Stat Point to Prowess.) or `2.2.2` (Ritualist: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Agility.)
* **Decision Level 4:**
  * `1.1.1` -> `1.1.1.1` (Discipline Arms: Gain proficiency in Simple Weapons.) or `1.1.1.2` (Novice Adept: Gain proficiency in one basic Cantrip.)
  * `1.1.2` -> `1.1.2.1` (Discipline Arms: Gain proficiency in Simple Weapons.) or `1.1.2.2` (Novice Adept: Gain proficiency in one basic Cantrip.)
  * `1.2.1` -> `1.2.1.1` (Discipline Arms: Gain proficiency in Simple Weapons.) or `1.2.1.2` (Novice Adept: Gain proficiency in one basic Cantrip.)
  * `1.2.2` -> `1.2.2.1` (Discipline Arms: Gain proficiency in Simple Weapons.) or `1.2.2.2` (Novice Adept: Gain proficiency in one basic Cantrip.)
  * `2.1.1` -> `2.1.1.1` (Discipline Arms: Gain proficiency in Simple Weapons.) or `2.1.1.2` (Novice Adept: Gain proficiency in one basic Cantrip.)
  * `2.1.2` -> `2.1.2.1` (Discipline Arms: Gain proficiency in Simple Weapons.) or `2.1.2.2` (Novice Adept: Gain proficiency in one basic Cantrip.)
  * `2.2.1` -> `2.2.1.1` (Discipline Arms: Gain proficiency in Simple Weapons.) or `2.2.1.2` (Novice Adept: Gain proficiency in one basic Cantrip.)
  * `2.2.2` -> `2.2.2.1` (Discipline Arms: Gain proficiency in Simple Weapons.) or `2.2.2.2` (Novice Adept: Gain proficiency in one basic Cantrip.)
* **Decision Level 5:**
  * `1.1.1.1` -> `1.1.1.1.1` (Warden Prayer: +1 Stat Point to Constitution.) or `1.1.1.1.2` (Ascetic Strike: +2 Stat Points: +1 Prowess and +1 Will; -1 Stat Point to Intellect.)
  * `1.1.1.2` -> `1.1.1.2.1` (Warden Prayer: +1 Stat Point to Constitution.) or `1.1.1.2.2` (Ascetic Strike: +2 Stat Points: +1 Prowess and +1 Will; -1 Stat Point to Intellect.)
  * `1.1.2.1` -> `1.1.2.1.1` (Warden Prayer: +1 Stat Point to Constitution.) or `1.1.2.1.2` (Ascetic Strike: +2 Stat Points: +1 Prowess and +1 Will; -1 Stat Point to Intellect.)
  * `1.1.2.2` -> `1.1.2.2.1` (Warden Prayer: +1 Stat Point to Constitution.) or `1.1.2.2.2` (Ascetic Strike: +2 Stat Points: +1 Prowess and +1 Will; -1 Stat Point to Intellect.)
  * `1.2.1.1` -> `1.2.1.1.1` (Warden Prayer: +1 Stat Point to Constitution.) or `1.2.1.1.2` (Ascetic Strike: +2 Stat Points: +1 Prowess and +1 Will; -1 Stat Point to Intellect.)
  * `1.2.1.2` -> `1.2.1.2.1` (Warden Prayer: +1 Stat Point to Constitution.) or `1.2.1.2.2` (Ascetic Strike: +2 Stat Points: +1 Prowess and +1 Will; -1 Stat Point to Intellect.)
  * `1.2.2.1` -> `1.2.2.1.1` (Warden Prayer: +1 Stat Point to Constitution.) or `1.2.2.1.2` (Ascetic Strike: +2 Stat Points: +1 Prowess and +1 Will; -1 Stat Point to Intellect.)
  * `1.2.2.2` -> `1.2.2.2.1` (Warden Prayer: +1 Stat Point to Constitution.) or `1.2.2.2.2` (Ascetic Strike: +2 Stat Points: +1 Prowess and +1 Will; -1 Stat Point to Intellect.)
  * `2.1.1.1` -> `2.1.1.1.1` (Warden Prayer: +1 Stat Point to Constitution.) or `2.1.1.1.2` (Ascetic Strike: +2 Stat Points: +1 Prowess and +1 Will; -1 Stat Point to Intellect.)
  * `2.1.1.2` -> `2.1.1.2.1` (Warden Prayer: +1 Stat Point to Constitution.) or `2.1.1.2.2` (Ascetic Strike: +2 Stat Points: +1 Prowess and +1 Will; -1 Stat Point to Intellect.)
  * `2.1.2.1` -> `2.1.2.1.1` (Warden Prayer: +1 Stat Point to Constitution.) or `2.1.2.1.2` (Ascetic Strike: +2 Stat Points: +1 Prowess and +1 Will; -1 Stat Point to Intellect.)
  * `2.1.2.2` -> `2.1.2.2.1` (Warden Prayer: +1 Stat Point to Constitution.) or `2.1.2.2.2` (Ascetic Strike: +2 Stat Points: +1 Prowess and +1 Will; -1 Stat Point to Intellect.)
  * `2.2.1.1` -> `2.2.1.1.1` (Warden Prayer: +1 Stat Point to Constitution.) or `2.2.1.1.2` (Ascetic Strike: +2 Stat Points: +1 Prowess and +1 Will; -1 Stat Point to Intellect.)
  * `2.2.1.2` -> `2.2.1.2.1` (Warden Prayer: +1 Stat Point to Constitution.) or `2.2.1.2.2` (Ascetic Strike: +2 Stat Points: +1 Prowess and +1 Will; -1 Stat Point to Intellect.)
  * `2.2.2.1` -> `2.2.2.1.1` (Warden Prayer: +1 Stat Point to Constitution.) or `2.2.2.1.2` (Ascetic Strike: +2 Stat Points: +1 Prowess and +1 Will; -1 Stat Point to Intellect.)
  * `2.2.2.2` -> `2.2.2.2.1` (Warden Prayer: +1 Stat Point to Constitution.) or `2.2.2.2.2` (Ascetic Strike: +2 Stat Points: +1 Prowess and +1 Will; -1 Stat Point to Intellect.)

* **Level 5 Final Paths (32 total):**
  * `1.1.1.1.1`, `1.1.1.1.2`, `1.1.1.2.1`, `1.1.1.2.2`, `1.1.2.1.1`, `1.1.2.1.2`, `1.1.2.2.1`, `1.1.2.2.2`, `1.2.1.1.1`, `1.2.1.1.2`, `1.2.1.2.1`, `1.2.1.2.2`, `1.2.2.1.1`, `1.2.2.1.2`, `1.2.2.2.1`, `1.2.2.2.2`, `2.1.1.1.1`, `2.1.1.1.2`, `2.1.1.2.1`, `2.1.1.2.2`, `2.1.2.1.1`, `2.1.2.1.2`, `2.1.2.2.1`, `2.1.2.2.2`, `2.2.1.1.1`, `2.2.1.1.2`, `2.2.1.2.1`, `2.2.1.2.2`, `2.2.2.1.1`, `2.2.2.1.2`, `2.2.2.2.1`, `2.2.2.2.2`
