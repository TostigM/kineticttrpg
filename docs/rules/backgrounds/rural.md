# Rural Background

This file defines the 5-level branching tree for the Rural origin. Every decision grants exactly one of: +1 stat point, +2 stat points with -1 stat point, or a basic proficiency.

## Decision Keys

### Level 1
* `1` **Farmstead:** +1 Stat Point to Constitution.
* `2` **Hinter Hamlet:** +1 Stat Point to Will.

### Level 2
* `.1` **Fieldcraft:** Gain proficiency in Survival.
* `.2` **Workbench:** Gain proficiency in Simple Weapons.

### Level 3
* `.1` **Cooperative:** +2 Stat Points: +1 Constitution and +1 Will; -1 Stat Point to Agility.
* `.2` **Weatherwise:** +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.

### Level 4
* `.1` **Herding Route:** Gain proficiency in Animal Handling.
* `.2` **Militia Yard:** Gain proficiency in Martial Weapons.

### Level 5
* `.1` **Harvest Sense:** +1 Stat Point to Intellect.
* `.2` **Long Winter:** +2 Stat Points: +1 Constitution and +1 Will; -1 Stat Point to Intellect.

## Explicit Branch Tree

* **Decision Level 1:**
  * `1` Farmstead (+1 Stat Point to Constitution.)
  * `2` Hinter Hamlet (+1 Stat Point to Will.)
* **Decision Level 2:**
  * `1` -> `1.1` (Fieldcraft: Gain proficiency in Survival.) or `1.2` (Workbench: Gain proficiency in Simple Weapons.)
  * `2` -> `2.1` (Fieldcraft: Gain proficiency in Survival.) or `2.2` (Workbench: Gain proficiency in Simple Weapons.)
* **Decision Level 3:**
  * `1.1` -> `1.1.1` (Cooperative: +2 Stat Points: +1 Constitution and +1 Will; -1 Stat Point to Agility.) or `1.1.2` (Weatherwise: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.)
  * `1.2` -> `1.2.1` (Cooperative: +2 Stat Points: +1 Constitution and +1 Will; -1 Stat Point to Agility.) or `1.2.2` (Weatherwise: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.)
  * `2.1` -> `2.1.1` (Cooperative: +2 Stat Points: +1 Constitution and +1 Will; -1 Stat Point to Agility.) or `2.1.2` (Weatherwise: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.)
  * `2.2` -> `2.2.1` (Cooperative: +2 Stat Points: +1 Constitution and +1 Will; -1 Stat Point to Agility.) or `2.2.2` (Weatherwise: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.)
* **Decision Level 4:**
  * `1.1.1` -> `1.1.1.1` (Herding Route: Gain proficiency in Animal Handling.) or `1.1.1.2` (Militia Yard: Gain proficiency in Martial Weapons.)
  * `1.1.2` -> `1.1.2.1` (Herding Route: Gain proficiency in Animal Handling.) or `1.1.2.2` (Militia Yard: Gain proficiency in Martial Weapons.)
  * `1.2.1` -> `1.2.1.1` (Herding Route: Gain proficiency in Animal Handling.) or `1.2.1.2` (Militia Yard: Gain proficiency in Martial Weapons.)
  * `1.2.2` -> `1.2.2.1` (Herding Route: Gain proficiency in Animal Handling.) or `1.2.2.2` (Militia Yard: Gain proficiency in Martial Weapons.)
  * `2.1.1` -> `2.1.1.1` (Herding Route: Gain proficiency in Animal Handling.) or `2.1.1.2` (Militia Yard: Gain proficiency in Martial Weapons.)
  * `2.1.2` -> `2.1.2.1` (Herding Route: Gain proficiency in Animal Handling.) or `2.1.2.2` (Militia Yard: Gain proficiency in Martial Weapons.)
  * `2.2.1` -> `2.2.1.1` (Herding Route: Gain proficiency in Animal Handling.) or `2.2.1.2` (Militia Yard: Gain proficiency in Martial Weapons.)
  * `2.2.2` -> `2.2.2.1` (Herding Route: Gain proficiency in Animal Handling.) or `2.2.2.2` (Militia Yard: Gain proficiency in Martial Weapons.)
* **Decision Level 5:**
  * `1.1.1.1` -> `1.1.1.1.1` (Harvest Sense: +1 Stat Point to Intellect.) or `1.1.1.1.2` (Long Winter: +2 Stat Points: +1 Constitution and +1 Will; -1 Stat Point to Intellect.)
  * `1.1.1.2` -> `1.1.1.2.1` (Harvest Sense: +1 Stat Point to Intellect.) or `1.1.1.2.2` (Long Winter: +2 Stat Points: +1 Constitution and +1 Will; -1 Stat Point to Intellect.)
  * `1.1.2.1` -> `1.1.2.1.1` (Harvest Sense: +1 Stat Point to Intellect.) or `1.1.2.1.2` (Long Winter: +2 Stat Points: +1 Constitution and +1 Will; -1 Stat Point to Intellect.)
  * `1.1.2.2` -> `1.1.2.2.1` (Harvest Sense: +1 Stat Point to Intellect.) or `1.1.2.2.2` (Long Winter: +2 Stat Points: +1 Constitution and +1 Will; -1 Stat Point to Intellect.)
  * `1.2.1.1` -> `1.2.1.1.1` (Harvest Sense: +1 Stat Point to Intellect.) or `1.2.1.1.2` (Long Winter: +2 Stat Points: +1 Constitution and +1 Will; -1 Stat Point to Intellect.)
  * `1.2.1.2` -> `1.2.1.2.1` (Harvest Sense: +1 Stat Point to Intellect.) or `1.2.1.2.2` (Long Winter: +2 Stat Points: +1 Constitution and +1 Will; -1 Stat Point to Intellect.)
  * `1.2.2.1` -> `1.2.2.1.1` (Harvest Sense: +1 Stat Point to Intellect.) or `1.2.2.1.2` (Long Winter: +2 Stat Points: +1 Constitution and +1 Will; -1 Stat Point to Intellect.)
  * `1.2.2.2` -> `1.2.2.2.1` (Harvest Sense: +1 Stat Point to Intellect.) or `1.2.2.2.2` (Long Winter: +2 Stat Points: +1 Constitution and +1 Will; -1 Stat Point to Intellect.)
  * `2.1.1.1` -> `2.1.1.1.1` (Harvest Sense: +1 Stat Point to Intellect.) or `2.1.1.1.2` (Long Winter: +2 Stat Points: +1 Constitution and +1 Will; -1 Stat Point to Intellect.)
  * `2.1.1.2` -> `2.1.1.2.1` (Harvest Sense: +1 Stat Point to Intellect.) or `2.1.1.2.2` (Long Winter: +2 Stat Points: +1 Constitution and +1 Will; -1 Stat Point to Intellect.)
  * `2.1.2.1` -> `2.1.2.1.1` (Harvest Sense: +1 Stat Point to Intellect.) or `2.1.2.1.2` (Long Winter: +2 Stat Points: +1 Constitution and +1 Will; -1 Stat Point to Intellect.)
  * `2.1.2.2` -> `2.1.2.2.1` (Harvest Sense: +1 Stat Point to Intellect.) or `2.1.2.2.2` (Long Winter: +2 Stat Points: +1 Constitution and +1 Will; -1 Stat Point to Intellect.)
  * `2.2.1.1` -> `2.2.1.1.1` (Harvest Sense: +1 Stat Point to Intellect.) or `2.2.1.1.2` (Long Winter: +2 Stat Points: +1 Constitution and +1 Will; -1 Stat Point to Intellect.)
  * `2.2.1.2` -> `2.2.1.2.1` (Harvest Sense: +1 Stat Point to Intellect.) or `2.2.1.2.2` (Long Winter: +2 Stat Points: +1 Constitution and +1 Will; -1 Stat Point to Intellect.)
  * `2.2.2.1` -> `2.2.2.1.1` (Harvest Sense: +1 Stat Point to Intellect.) or `2.2.2.1.2` (Long Winter: +2 Stat Points: +1 Constitution and +1 Will; -1 Stat Point to Intellect.)
  * `2.2.2.2` -> `2.2.2.2.1` (Harvest Sense: +1 Stat Point to Intellect.) or `2.2.2.2.2` (Long Winter: +2 Stat Points: +1 Constitution and +1 Will; -1 Stat Point to Intellect.)

* **Level 5 Final Paths (32 total):**
  * `1.1.1.1.1`, `1.1.1.1.2`, `1.1.1.2.1`, `1.1.1.2.2`, `1.1.2.1.1`, `1.1.2.1.2`, `1.1.2.2.1`, `1.1.2.2.2`, `1.2.1.1.1`, `1.2.1.1.2`, `1.2.1.2.1`, `1.2.1.2.2`, `1.2.2.1.1`, `1.2.2.1.2`, `1.2.2.2.1`, `1.2.2.2.2`, `2.1.1.1.1`, `2.1.1.1.2`, `2.1.1.2.1`, `2.1.1.2.2`, `2.1.2.1.1`, `2.1.2.1.2`, `2.1.2.2.1`, `2.1.2.2.2`, `2.2.1.1.1`, `2.2.1.1.2`, `2.2.1.2.1`, `2.2.1.2.2`, `2.2.2.1.1`, `2.2.2.1.2`, `2.2.2.2.1`, `2.2.2.2.2`
