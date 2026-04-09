# Nomadic Background

This file defines the 5-level branching tree for the Nomadic origin. Every decision grants exactly one of: +1 stat point, +2 stat points with -1 stat point, or a basic proficiency.

## Decision Keys

### Level 1
* `1` **Caravan Routes:** +1 Stat Point to Agility.
* `2` **Open Steppe:** +1 Stat Point to Constitution.

### Level 2
* `.1` **Trail Scout:** Gain proficiency in Survival.
* `.2` **Camp Maker:** Gain proficiency in Crafting.

### Level 3
* `.1` **Wind Reader:** +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.
* `.2` **Crossing Keeper:** +2 Stat Points: +1 Agility and +1 Constitution; -1 Stat Point to Intellect.

### Level 4
* `.1` **Horsebow Drill:** Gain proficiency in Martial Weapons.
* `.2` **Caravan Guard:** Gain proficiency in Simple Weapons.

### Level 5
* `.1` **Long Marcher:** +1 Stat Point to Constitution.
* `.2` **Rider Pounce:** +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.

## Explicit Branch Tree

* **Decision Level 1:**
  * `1` Caravan Routes (+1 Stat Point to Agility.)
  * `2` Open Steppe (+1 Stat Point to Constitution.)
* **Decision Level 2:**
  * `1` -> `1.1` (Trail Scout: Gain proficiency in Survival.) or `1.2` (Camp Maker: Gain proficiency in Crafting.)
  * `2` -> `2.1` (Trail Scout: Gain proficiency in Survival.) or `2.2` (Camp Maker: Gain proficiency in Crafting.)
* **Decision Level 3:**
  * `1.1` -> `1.1.1` (Wind Reader: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.) or `1.1.2` (Crossing Keeper: +2 Stat Points: +1 Agility and +1 Constitution; -1 Stat Point to Intellect.)
  * `1.2` -> `1.2.1` (Wind Reader: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.) or `1.2.2` (Crossing Keeper: +2 Stat Points: +1 Agility and +1 Constitution; -1 Stat Point to Intellect.)
  * `2.1` -> `2.1.1` (Wind Reader: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.) or `2.1.2` (Crossing Keeper: +2 Stat Points: +1 Agility and +1 Constitution; -1 Stat Point to Intellect.)
  * `2.2` -> `2.2.1` (Wind Reader: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.) or `2.2.2` (Crossing Keeper: +2 Stat Points: +1 Agility and +1 Constitution; -1 Stat Point to Intellect.)
* **Decision Level 4:**
  * `1.1.1` -> `1.1.1.1` (Horsebow Drill: Gain proficiency in Martial Weapons.) or `1.1.1.2` (Caravan Guard: Gain proficiency in Simple Weapons.)
  * `1.1.2` -> `1.1.2.1` (Horsebow Drill: Gain proficiency in Martial Weapons.) or `1.1.2.2` (Caravan Guard: Gain proficiency in Simple Weapons.)
  * `1.2.1` -> `1.2.1.1` (Horsebow Drill: Gain proficiency in Martial Weapons.) or `1.2.1.2` (Caravan Guard: Gain proficiency in Simple Weapons.)
  * `1.2.2` -> `1.2.2.1` (Horsebow Drill: Gain proficiency in Martial Weapons.) or `1.2.2.2` (Caravan Guard: Gain proficiency in Simple Weapons.)
  * `2.1.1` -> `2.1.1.1` (Horsebow Drill: Gain proficiency in Martial Weapons.) or `2.1.1.2` (Caravan Guard: Gain proficiency in Simple Weapons.)
  * `2.1.2` -> `2.1.2.1` (Horsebow Drill: Gain proficiency in Martial Weapons.) or `2.1.2.2` (Caravan Guard: Gain proficiency in Simple Weapons.)
  * `2.2.1` -> `2.2.1.1` (Horsebow Drill: Gain proficiency in Martial Weapons.) or `2.2.1.2` (Caravan Guard: Gain proficiency in Simple Weapons.)
  * `2.2.2` -> `2.2.2.1` (Horsebow Drill: Gain proficiency in Martial Weapons.) or `2.2.2.2` (Caravan Guard: Gain proficiency in Simple Weapons.)
* **Decision Level 5:**
  * `1.1.1.1` -> `1.1.1.1.1` (Long Marcher: +1 Stat Point to Constitution.) or `1.1.1.1.2` (Rider Pounce: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `1.1.1.2` -> `1.1.1.2.1` (Long Marcher: +1 Stat Point to Constitution.) or `1.1.1.2.2` (Rider Pounce: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `1.1.2.1` -> `1.1.2.1.1` (Long Marcher: +1 Stat Point to Constitution.) or `1.1.2.1.2` (Rider Pounce: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `1.1.2.2` -> `1.1.2.2.1` (Long Marcher: +1 Stat Point to Constitution.) or `1.1.2.2.2` (Rider Pounce: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `1.2.1.1` -> `1.2.1.1.1` (Long Marcher: +1 Stat Point to Constitution.) or `1.2.1.1.2` (Rider Pounce: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `1.2.1.2` -> `1.2.1.2.1` (Long Marcher: +1 Stat Point to Constitution.) or `1.2.1.2.2` (Rider Pounce: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `1.2.2.1` -> `1.2.2.1.1` (Long Marcher: +1 Stat Point to Constitution.) or `1.2.2.1.2` (Rider Pounce: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `1.2.2.2` -> `1.2.2.2.1` (Long Marcher: +1 Stat Point to Constitution.) or `1.2.2.2.2` (Rider Pounce: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `2.1.1.1` -> `2.1.1.1.1` (Long Marcher: +1 Stat Point to Constitution.) or `2.1.1.1.2` (Rider Pounce: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `2.1.1.2` -> `2.1.1.2.1` (Long Marcher: +1 Stat Point to Constitution.) or `2.1.1.2.2` (Rider Pounce: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `2.1.2.1` -> `2.1.2.1.1` (Long Marcher: +1 Stat Point to Constitution.) or `2.1.2.1.2` (Rider Pounce: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `2.1.2.2` -> `2.1.2.2.1` (Long Marcher: +1 Stat Point to Constitution.) or `2.1.2.2.2` (Rider Pounce: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `2.2.1.1` -> `2.2.1.1.1` (Long Marcher: +1 Stat Point to Constitution.) or `2.2.1.1.2` (Rider Pounce: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `2.2.1.2` -> `2.2.1.2.1` (Long Marcher: +1 Stat Point to Constitution.) or `2.2.1.2.2` (Rider Pounce: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `2.2.2.1` -> `2.2.2.1.1` (Long Marcher: +1 Stat Point to Constitution.) or `2.2.2.1.2` (Rider Pounce: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)
  * `2.2.2.2` -> `2.2.2.2.1` (Long Marcher: +1 Stat Point to Constitution.) or `2.2.2.2.2` (Rider Pounce: +2 Stat Points: +1 Agility and +1 Prowess; -1 Stat Point to Will.)

* **Level 5 Final Paths (32 total):**
  * `1.1.1.1.1`, `1.1.1.1.2`, `1.1.1.2.1`, `1.1.1.2.2`, `1.1.2.1.1`, `1.1.2.1.2`, `1.1.2.2.1`, `1.1.2.2.2`, `1.2.1.1.1`, `1.2.1.1.2`, `1.2.1.2.1`, `1.2.1.2.2`, `1.2.2.1.1`, `1.2.2.1.2`, `1.2.2.2.1`, `1.2.2.2.2`, `2.1.1.1.1`, `2.1.1.1.2`, `2.1.1.2.1`, `2.1.1.2.2`, `2.1.2.1.1`, `2.1.2.1.2`, `2.1.2.2.1`, `2.1.2.2.2`, `2.2.1.1.1`, `2.2.1.1.2`, `2.2.1.2.1`, `2.2.1.2.2`, `2.2.2.1.1`, `2.2.2.1.2`, `2.2.2.2.1`, `2.2.2.2.2`
