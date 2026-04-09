# The Heat Economy

Heat is the pressure engine of the Kinetic System. Every time players act — attacking, casting, pushing hard — Heat Ticks accumulate in the GM's pool. The GM spends that Heat to make the world fight back.

Heat is not a timer. It is consequence. The Definition does not act on a schedule; it acts when it has the resources to do so, and the party controls how fast those resources build.

---

## The Heat Pool

Each encounter has one shared Heat Pool. It begins at 0 at the start of most encounters (see Encounter Types for exceptions). Ticks accumulate throughout the encounter with no maximum cap. The pool resets to 0 when the encounter ends.

**Multi-Definition encounters:** When two or more distinct Definitions are active simultaneously (e.g., a warlord and her two lieutenants), each Definition maintains a separate Heat Pool. Players must manage which pool they are feeding with each action.

---

## Part 1: Gaining Heat

### Standard Generation

Every player action adds Ticks to the pool based on its weight. Individual skills list their exact Heat cost in their Skill Anatomy block. For actions not covered by a specific skill, use this table:

| Action Type | Heat Generated |
|---|---|
| Quick Action — reposition, draw item, minor interaction | +0 to +1 |
| Core Attack / Standard Skill | +2 |
| Power Move / Heavy Skill / Area of Effect | +3 to +4 |
| Critical Failure (1-1-1) | See below |
| Critical Success (8-8-8) | See below |

When a skill's Heat cost conflicts with the table (e.g., a Power Move that explicitly lists +2), the skill's listed cost takes precedence.

### Critical Failure

When a player rolls 1-1-1, the catastrophe draws the Definition's immediate attention. The GM receives one free Spotlight Steal at **0 Heat cost**. The existing Heat Pool is not consumed — the Definition simply acts. This is in addition to the catastrophic failure of the roll itself.

### Critical Success

When a player rolls 8-8-8, the overwhelming success disrupts the Definition's momentum. **Reduce the Heat Pool by 2 Ticks.** If the pool is below 2, reduce it to 0.

### Escalating Pressure

Definitions may list threshold effects on their stat sheets that increase Heat generation as the encounter deepens:

- *"When the Heat Pool first reaches 8, all player Quick Actions generate +1 Heat."*
- *"After Round 3, Core Attacks generate +3 Heat instead of +2."*

These escalation triggers are listed on the Definition, not imposed by the GM at will. They represent a fight getting more dangerous as the Definition grows desperate or enraged.

### Environmental and Situational Heat

Some conditions impose additional Heat generation regardless of the action taken:

| Situation | Additional Heat |
|---|---|
| Acting within a Definition's designated territory | +1 on first action in the zone |
| Using an Area of Effect skill in a confined space | +1 (the chaos is greater) |
| Failing a roll while a Power-tier Primer is active on you | +1 |
| Acting after a Spotlight Steal has already occurred this round | +0 (no additional penalty) |

GMs may also assign flat base Heat to an encounter's starting pool to reflect a situation the players entered already behind (ambush, disrupted ritual, a fight halfway through).

---

## Part 2: Reducing Heat

Players are not passive observers of the Heat economy. Several mechanics give the party tools to actively reduce or manage the pool.

### The Snap Pass

The primary player-controlled release valve. When a player passes the Spotlight to a teammate in under 10 seconds of real time, they choose one benefit:

- The receiving player gets **+1 to their next roll**, OR
- The Heat Pool is **reduced by 1 Tick**

The choice is made by the passing player, not the receiver. The snap timer begins the moment the passing player's last action resolves.

### The Group Interrupt

When the GM performs a Spotlight Steal, the party receives **1 Group Interrupt**. Before the Definition fully resolves its turn, the party quickly decides which player reacts and how. A successful Group Interrupt does not cancel the Steal but blunts its impact:

- Reduce damage taken
- Negate a condition being applied
- Reposition a threatened ally
- Force the Definition to spend 1 additional Heat to complete its action

The Group Interrupt is a reaction, not a roll — its success is narrative and GM-adjudicated based on what the reacting player describes.

### Skill-Based Mitigation

Some skills reduce Heat as part of their effect. This is listed in the skill's Skill Anatomy block as a negative value under Heat Generation. Examples:

- *Heat Generation: +1 (net, after self-reduction)*
- *Heat Generation: +2 / −1 if Impactful Hit triggered*

These reductions apply after the standard generation and are noted on the skill card itself.

### Feature-Based Mitigation

Species features, background features, and some skills provide passive or conditional Heat mitigation. The common patterns are:

| Pattern | Example |
|---|---|
| Generate fewer Ticks on a specific action | *"Melee Main Actions generate 1 fewer Heat Tick."* |
| Reduce pool after specific trigger | *"When you score an Impactful Hit, reduce Heat Pool by 1."* |
| Force the Definition to spend more | *"The first Reaction targeting you each round costs 1 additional Heat."* |
| Per-encounter pool reduction | *"Once per encounter as a Quick Action, reduce the Heat Pool by 2."* |
| Snap Pass upgrade | *"When you use the Snap Pass to reduce Heat, reduce it by 2 instead of 1."* |

These stack with each other and with the Snap Pass, but each source is independent — they do not compound.

---

## Part 3: Spending Heat

The GM spends Heat to trigger abilities listed on the active Definition's stat sheet. Definitions have their own specific abilities, but all abilities fall into one of three categories that determine when and how they can be used.

### Reactions (Cost: 1–2 Heat)

Triggered responses to specific player actions. Each Reaction is written as an If/Then condition on the Definition's sheet.

- **Timing:** Fires immediately when the trigger condition is met, during the active player's Spotlight turn.
- **Effect:** Typically a targeted counterattack, movement denial, or minor condition.
- **Does not end the player's turn:** The player continues their Spotlight after the Reaction resolves.

**Common Reaction triggers:**
- A player moves away from the Definition
- A player applies a specific Primer
- A player targets a specific body part or weak point
- A player ends their Spotlight turn without attacking

### Interrupts (Cost: 2–4 Heat)

Actions that fire during the gap between Spotlight turns — after one player ends and before the next receives the token.

- **Timing:** During the Spotlight Swap, after the passing player acts but before the receiving player begins.
- **Effect:** Adds a hazard, condition, positional change, or environmental shift the receiving player must contend with on their turn.
- **Does not stop the Swap:** The Spotlight still transfers. The receiving player begins their turn in a worse position.
- **Cannot be Snap Passed through:** The Interrupt resolves before the Snap Pass bonus applies.

**Common Interrupt uses:**
- Reposition multiple targets
- Create new difficult terrain or hazards
- Apply a Primer to a player before they act
- Destroy or move an objective

### Spotlight Steals (Cost: 6–10 Heat)

The Definition seizes the Spotlight Token entirely and takes a full Enemy Turn.

- **Timing:** Declared at any Spotlight Swap. The GM announces the Steal before the receiving player begins their turn.
- **Effect:** The Definition acts freely for one full turn — it may attack multiple targets, reposition, apply conditions, spend additional lower-cost abilities, and reshape the encounter.
- **The Group Interrupt:** The party receives 1 Group Interrupt before the Definition's turn fully resolves.
- **After the Steal:** The GM returns the Spotlight to the player who was about to receive it. If that player is incapacitated, it passes to the next highest Initiative player.

**The cost range reflects the Definition's power tier:**

| Definition Tier | Spotlight Steal Cost |
|---|---|
| Minor threat (bandit captain, minor spirit) | 6 Heat |
| Standard threat (veteran soldier, elemental) | 7–8 Heat |
| Elite threat (warlord, greater beast) | 8–9 Heat |
| Boss-tier Definition | 10 Heat |

### GM Spending Rules

- The GM may only spend Heat on abilities explicitly listed on the active Definition's stat sheet.
- Heat cannot be spent below 0.
- The GM may spend multiple abilities in the same trigger window if the pool allows, but each costs its listed amount independently.
- **The Definition does not bank infinitely:** Definitions are reactive and in-the-moment. If the Heat Pool exceeds the Spotlight Steal threshold for more than 3 consecutive player turns without the GM spending, the GM should spend — Definitions that do nothing are not threatening. This is a pacing guideline, not a hard rule.

---

## Part 4: Heat Across Encounter Types

The Heat pool and all spending rules apply identically to every encounter type. What changes is the starting state, the pace of generation, and what the Definition represents.

### Combat

**Definition:** A creature, army, force, or hazard in direct conflict with the party.

**Starting Heat:** 0 (or GM-set base if the party was ambushed or disadvantaged at the start).

**Generation pace:** Fast. Combat skills regularly generate +2 to +4 Heat. A sustained fight will push the pool into Spotlight Steal range within 2–3 rounds.

**GM spend pattern:** Frequent Reactions and Interrupts keep the pressure constant. Spotlight Steals represent the Definition's most dangerous capabilities — a dragon's breath weapon, a golem's full-force slam, a captain rallying flanking soldiers.

---

### Social

**Definition:** An NPC or group of NPCs being negotiated, persuaded, or manipulated.

**Starting Heat:** 0–3 depending on initial NPC disposition (hostile NPCs begin with Heat already in the pool).

**Generation pace:** Slow. Social skills generate +1 to +2 Heat. A skilled party can resolve a social encounter before the NPC ever Steals the Spotlight.

**Primers in social:** Players apply tags like [Flattered], [Intimidated], or [Swayed]. The NPC Definition spends Heat to resist — shutting down conversation threads, calling for reinforcements, or shifting emotional register.

**GM spend pattern:** Reactions represent the NPC responding in-conversation (a deflection, a pointed question, a change in tone). A Spotlight Steal represents the NPC ending the conversation on their terms — walking out, summoning guards, or issuing a public accusation.

---

### Exploration

**Definition:** An environment or obstacle — a crumbling ruin, a flooding mine, a burning ship, a collapsing bridge.

**Starting Heat:** GM-set base, typically 3–6. Environments have inherent pressure before the party arrives. A stable dungeon might start at 2; a collapsing one might start at 6.

**Generation pace:** Moderate. Players apply [Progress] tags toward their objective. Even movement and investigation generate Heat because the environment is already failing.

**GM spend pattern:** Interrupts are the primary tool — falling debris, rising water, a floor collapse. Spotlight Steals represent catastrophic environmental events that dramatically change the situation: a cave-in that cuts off retreat, a flood surge that separates the party, a fire that engulfs the exit.

---

### Downtime

**Definition:** A project, goal, or endeavor — crafting a weapon, running an investigation, building political capital, training a skill.

**Starting Heat:** 0. Downtime is not immediately dangerous.

**Generation pace:** Very slow. Each Spotlight turn in downtime represents hours or days of work. Actions generate +0 to +2 Heat.

**GM spend pattern:** Interrupts and Reactions represent setbacks and complications: a supply shortage, a rival's interference, a design flaw discovered late, unexpected costs. Spotlight Steals in downtime represent major disruptions that threaten the project's viability entirely — not a minor delay, but a fundamental crisis requiring the party's direct attention.

---

## Quick Reference

| Event | Heat Change |
|---|---|
| Quick Action / minor move | +0 to +1 |
| Standard attack / skill | +2 |
| Power move / heavy skill / AoE | +3 to +4 |
| Critical failure (1-1-1) | Free Spotlight Steal (pool unchanged) |
| Critical success (8-8-8) | −2 from pool |
| Snap Pass (player choice) | −1 from pool OR +1 to receiver's roll |
| Reaction triggered (GM spends) | −1 to −2 from pool |
| Interrupt triggered (GM spends) | −2 to −4 from pool |
| Spotlight Steal (GM spends) | −6 to −10 from pool |
