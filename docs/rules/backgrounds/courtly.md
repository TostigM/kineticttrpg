# Courtly Background

This file defines the 5-level branching tree for the Courtly origin. Every decision grants exactly one of: +1 stat point, +2 stat points with -1 stat point, or a basic proficiency.

## Decision Keys

### Level 1
* `1` **Noble Court:** +1 Stat Point to Will.
* `2` **Merchant Court:** +1 Stat Point to Intellect.

### Level 2
* `.1` **Protocol School:** Gain proficiency in Persuasion.
* `.2` **Ledger School:** Gain proficiency in Insight.

### Level 3
* `.1` **Salon Reader:** +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.
* `.2` **Petitioner:** +2 Stat Points: +1 Will and +1 Agility; -1 Stat Point to Constitution.

### Level 4
* `.1` **Honor Guard:** Gain proficiency in Martial Weapons.
* `.2` **Silver Ink:** Gain proficiency in one basic Cantrip.

### Level 5
* `.1` **Silver Name:** +1 Stat Point to Will.
* `.2` **Quiet Dossier:** +2 Stat Points: +1 Intellect and +1 Agility; -1 Stat Point to Prowess.

## Explicit Branch Tree

* **Decision Level 1:**
  * `1` Noble Court (+1 Stat Point to Will.)
  * `2` Merchant Court (+1 Stat Point to Intellect.)
* **Decision Level 2:**
  * `1` -> `1.1` (Protocol School: Gain proficiency in Persuasion.) or `1.2` (Ledger School: Gain proficiency in Insight.)
  * `2` -> `2.1` (Protocol School: Gain proficiency in Persuasion.) or `2.2` (Ledger School: Gain proficiency in Insight.)
* **Decision Level 3:**
  * `1.1` -> `1.1.1` (Salon Reader: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.) or `1.1.2` (Petitioner: +2 Stat Points: +1 Will and +1 Agility; -1 Stat Point to Constitution.)
  * `1.2` -> `1.2.1` (Salon Reader: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.) or `1.2.2` (Petitioner: +2 Stat Points: +1 Will and +1 Agility; -1 Stat Point to Constitution.)
  * `2.1` -> `2.1.1` (Salon Reader: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.) or `2.1.2` (Petitioner: +2 Stat Points: +1 Will and +1 Agility; -1 Stat Point to Constitution.)
  * `2.2` -> `2.2.1` (Salon Reader: +2 Stat Points: +1 Intellect and +1 Will; -1 Stat Point to Prowess.) or `2.2.2` (Petitioner: +2 Stat Points: +1 Will and +1 Agility; -1 Stat Point to Constitution.)
* **Decision Level 4:**
  * `1.1.1` -> `1.1.1.1` (Honor Guard: Gain proficiency in Martial Weapons.) or `1.1.1.2` (Silver Ink: Gain proficiency in one basic Cantrip.)
  * `1.1.2` -> `1.1.2.1` (Honor Guard: Gain proficiency in Martial Weapons.) or `1.1.2.2` (Silver Ink: Gain proficiency in one basic Cantrip.)
  * `1.2.1` -> `1.2.1.1` (Honor Guard: Gain proficiency in Martial Weapons.) or `1.2.1.2` (Silver Ink: Gain proficiency in one basic Cantrip.)
  * `1.2.2` -> `1.2.2.1` (Honor Guard: Gain proficiency in Martial Weapons.) or `1.2.2.2` (Silver Ink: Gain proficiency in one basic Cantrip.)
  * `2.1.1` -> `2.1.1.1` (Honor Guard: Gain proficiency in Martial Weapons.) or `2.1.1.2` (Silver Ink: Gain proficiency in one basic Cantrip.)
  * `2.1.2` -> `2.1.2.1` (Honor Guard: Gain proficiency in Martial Weapons.) or `2.1.2.2` (Silver Ink: Gain proficiency in one basic Cantrip.)
  * `2.2.1` -> `2.2.1.1` (Honor Guard: Gain proficiency in Martial Weapons.) or `2.2.1.2` (Silver Ink: Gain proficiency in one basic Cantrip.)
  * `2.2.2` -> `2.2.2.1` (Honor Guard: Gain proficiency in Martial Weapons.) or `2.2.2.2` (Silver Ink: Gain proficiency in one basic Cantrip.)
* **Decision Level 5:**
  * `1.1.1.1` -> `1.1.1.1.1` (Silver Name: +1 Stat Point to Will.) or `1.1.1.1.2` (Quiet Dossier: +2 Stat Points: +1 Intellect and +1 Agility; -1 Stat Point to Prowess.)
  * `1.1.1.2` -> `1.1.1.2.1` (Silver Name: +1 Stat Point to Will.) or `1.1.1.2.2` (Quiet Dossier: +2 Stat Points: +1 Intellect and +1 Agility; -1 Stat Point to Prowess.)
  * `1.1.2.1` -> `1.1.2.1.1` (Silver Name: +1 Stat Point to Will.) or `1.1.2.1.2` (Quiet Dossier: +2 Stat Points: +1 Intellect and +1 Agility; -1 Stat Point to Prowess.)
  * `1.1.2.2` -> `1.1.2.2.1` (Silver Name: +1 Stat Point to Will.) or `1.1.2.2.2` (Quiet Dossier: +2 Stat Points: +1 Intellect and +1 Agility; -1 Stat Point to Prowess.)
  * `1.2.1.1` -> `1.2.1.1.1` (Silver Name: +1 Stat Point to Will.) or `1.2.1.1.2` (Quiet Dossier: +2 Stat Points: +1 Intellect and +1 Agility; -1 Stat Point to Prowess.)
  * `1.2.1.2` -> `1.2.1.2.1` (Silver Name: +1 Stat Point to Will.) or `1.2.1.2.2` (Quiet Dossier: +2 Stat Points: +1 Intellect and +1 Agility; -1 Stat Point to Prowess.)
  * `1.2.2.1` -> `1.2.2.1.1` (Silver Name: +1 Stat Point to Will.) or `1.2.2.1.2` (Quiet Dossier: +2 Stat Points: +1 Intellect and +1 Agility; -1 Stat Point to Prowess.)
  * `1.2.2.2` -> `1.2.2.2.1` (Silver Name: +1 Stat Point to Will.) or `1.2.2.2.2` (Quiet Dossier: +2 Stat Points: +1 Intellect and +1 Agility; -1 Stat Point to Prowess.)
  * `2.1.1.1` -> `2.1.1.1.1` (Silver Name: +1 Stat Point to Will.) or `2.1.1.1.2` (Quiet Dossier: +2 Stat Points: +1 Intellect and +1 Agility; -1 Stat Point to Prowess.)
  * `2.1.1.2` -> `2.1.1.2.1` (Silver Name: +1 Stat Point to Will.) or `2.1.1.2.2` (Quiet Dossier: +2 Stat Points: +1 Intellect and +1 Agility; -1 Stat Point to Prowess.)
  * `2.1.2.1` -> `2.1.2.1.1` (Silver Name: +1 Stat Point to Will.) or `2.1.2.1.2` (Quiet Dossier: +2 Stat Points: +1 Intellect and +1 Agility; -1 Stat Point to Prowess.)
  * `2.1.2.2` -> `2.1.2.2.1` (Silver Name: +1 Stat Point to Will.) or `2.1.2.2.2` (Quiet Dossier: +2 Stat Points: +1 Intellect and +1 Agility; -1 Stat Point to Prowess.)
  * `2.2.1.1` -> `2.2.1.1.1` (Silver Name: +1 Stat Point to Will.) or `2.2.1.1.2` (Quiet Dossier: +2 Stat Points: +1 Intellect and +1 Agility; -1 Stat Point to Prowess.)
  * `2.2.1.2` -> `2.2.1.2.1` (Silver Name: +1 Stat Point to Will.) or `2.2.1.2.2` (Quiet Dossier: +2 Stat Points: +1 Intellect and +1 Agility; -1 Stat Point to Prowess.)
  * `2.2.2.1` -> `2.2.2.1.1` (Silver Name: +1 Stat Point to Will.) or `2.2.2.1.2` (Quiet Dossier: +2 Stat Points: +1 Intellect and +1 Agility; -1 Stat Point to Prowess.)
  * `2.2.2.2` -> `2.2.2.2.1` (Silver Name: +1 Stat Point to Will.) or `2.2.2.2.2` (Quiet Dossier: +2 Stat Points: +1 Intellect and +1 Agility; -1 Stat Point to Prowess.)

* **Level 5 Final Paths (32 total):**
  * `1.1.1.1.1`, `1.1.1.1.2`, `1.1.1.2.1`, `1.1.1.2.2`, `1.1.2.1.1`, `1.1.2.1.2`, `1.1.2.2.1`, `1.1.2.2.2`, `1.2.1.1.1`, `1.2.1.1.2`, `1.2.1.2.1`, `1.2.1.2.2`, `1.2.2.1.1`, `1.2.2.1.2`, `1.2.2.2.1`, `1.2.2.2.2`, `2.1.1.1.1`, `2.1.1.1.2`, `2.1.1.2.1`, `2.1.1.2.2`, `2.1.2.1.1`, `2.1.2.1.2`, `2.1.2.2.1`, `2.1.2.2.2`, `2.2.1.1.1`, `2.2.1.1.2`, `2.2.1.2.1`, `2.2.1.2.2`, `2.2.2.1.1`, `2.2.2.1.2`, `2.2.2.2.1`, `2.2.2.2.2`
