# Project Gemini TTRPG System - Version 0.7

## 1.0 The Core Mechanic: Resolving Actions
This system resolves all character actions based on a character's skill versus opposition.

### 1.1 Calculating the Difference (x)
Every action begins by calculating the "Difference" between the actor's score and the opposition's score.
* **For Opposed Actions (Character vs. Character/Creature):**
    `x = (Actor’s Attribute + Skill) − (Target’s Attribute + Defense Skill)`
* **For Unopposed Actions (Character vs. Task):**
    `x = (Character’s Attribute + Skill) − (Task’s Difficulty Rank)`

### 1.2 The Action Resolution Table
The calculated Difference (x) is used to find a Target Number (TN) on the d100 table below. To succeed, a player must roll equal to or greater than the TN on a d100.

| Difference (x) | d100 Target (TN) | Chance of Success |
| :--- | :--- | :--- |
| +10 or more | 1+ | 100% |
| +9 | 2+ | 99% |
| +8 | 3+ | 98% |
| +7 | 4+ | 97% |
| +6 | 6+ | 95% |
| +5 | 9+ | 92% |
| +4 | 13+ | 88% |
| +3 | 19+ | 82% |
| +2 | 28+ | 73% |
| +1 | 39+ | 62% |
| 0 | 51+ | 50% |
| -1 | 63+ | 38% |
| -2 | 74+ | 27% |
| -3 | 83+ | 18% |
| -4 | 89+ | 12% |
| -5 | 93+ | 8% |
| -6 | 96+ | 5% |
| -7 | 98+ | 3% |
| -8 | 99+ | 2% |
| -9 | 100+ | 1% |
| -10 or less | 101+ | 0% |

### 1.3 Unopposed Actions & Difficulty Ranks (DR)
A static challenge is assigned a Difficulty Rank (DR), which acts as the opposition's score.

| Difficulty Rank (DR) | Description |
| :--- | :--- |
| 1-2 | Trivial: A simple task that a professional would barely need to think about. |
| 3-5 | Standard: A professional challenge requiring focus and skill. |
| 6-8 | Challenging: A task that would push a skilled individual to their limits. |
| 9-10 | Heroic: A feat that is difficult even for the greatest masters of the craft. |
| 11+ | Legendary: A feat that borders on the impossible. |

### 1.4 Edges & Setbacks (Situational Modifiers)
This system uses predictable math that plugs directly into the Difference `(x)`.

* **Core Rule:** An **Edge** adds `+1` to the Difference `(x)` on a roll. A **Setback** subtracts `−1` from `(x)` on a roll.
* **Cancellation:** Edges and Setbacks from various sources cancel each other out on a one-for-one basis before the net modifier is applied.
* **Cap:** By default, a character can benefit from a maximum of `±3` total from Edges and Setbacks on a single roll. Some rare and powerful talents may explicitly state that they can exceed this cap.
* **Scope:** Unless a source states otherwise, Edges and Setbacks apply only to the next single roll a character makes (or imposes) and then expire.
* **Sizing:** Modifiers come in three tiers to represent their magnitude:
    * **Minor Edge/Setback:** `±1` to `(x)`
    * **Major Edge/Setback:** `±2` to `(x)`
    * **Overwhelming Edge/Setback:** `±3` to `(x)`

## 2.0 Character Creation
**Step 1: Attribute Assignment**
* Baseline: All nine attributes begin at Rank 1.
* Rank Categories: Choose your character's Primary, Secondary, and Tertiary attribute categories (Physical, Social, Mental).
* Receive Points: You get a pool of points to add to your base ranks:
    * Primary Category: +5 points
    * Secondary Category: +4 points
    * Tertiary Category: +3 points
* Distribute Points: Assign these points to the three attributes within their respective categories. No attribute's final rank can exceed 5 at character creation.

**Step 2: Choose an Archetype**
Select one of the mundane Archetypes (Section 8.2). This choice determines your two Core Talent Trees.

**Step 3: Background & Skills**
* Choose a Background: Select one Universal Background (Section 3.3). This provides four free skills at Rank 1 (Novice).
* Spend Skill Points: You receive 10 Skill Points. Spend these to increase skill ranks on a 1-for-1 basis. You can increase your background skills or acquire new ones. No skill can be raised higher than Rank 3 at character creation.

**Step 4: Choose Elective Talent Tree**
Select your third Talent Tree from the list of Elective Trees (Section 8.3).

**Step 5: Calculate Derived Statistics**
* Health Pools: Calculate Vitality, Poise, and Clarity (Section 6.2).
* Focus: Calculate your maximum Focus (Section 5.2).
* Defense Scores: Note your passive defense scores (Attribute + Defense Skill).

**Step 6: Finishing Touches**
Determine starting equipment, name, and other descriptive details.

## 3.0 Attributes & Skills
### 3.1 Attributes
Attributes are ranked from 1 to 5.
* **Physical:** Might (Power), Agility (Finesse), Vigor (Resistance)
* **Social:** Presence (Power), Charm (Finesse), Composure (Resistance)
* **Mental:** Intellect (Power), Wits (Finesse), Resolve (Resistance)

### 3.2 The Skill Rank Ladder
| Rank | Title | Description |
| :--- | :--- | :--- |
| 0 | Untrained | No formal training; you rely purely on your attributes. |
| 1 | Novice | Basic training or hobbyist-level knowledge. |
| 2 | Competent | A trained professional; you can make a living with this skill. |
| 3 | Expert | A seasoned veteran, sought out for difficult tasks. |
| 4 | Master | One of the foremost practitioners in the nation. |
| 5 | Grandmaster | Peak mortal potential; one of the best in the world. |

### 3.3 Universal Backgrounds
Choose one background and select four of its associated skills to gain at Rank 1 for free.
* **Academic:** Lore, Investigation, Medicine, Insight, Persuasion, Deception.
* **Artisan:** Crafting, Athletics, Perception, Persuasion, Insight, Intimidation.
* **Criminal:** Stealth, Deception, Intimidation, Athletics, Perception, Melee.
* **Devotee:** Lore, Medicine, Persuasion, Insight, Intimidation, Leadership.
* **Entertainer:** Performance, Persuasion, Deception, Insight, Athletics, Stealth.
* **Laborer:** Athletics, Melee, Crafting, Perception, Intimidation, Survival.
* **Martial:** Melee, Ranged, Athletics, Perception, Intimidation, Survival.
* **Noble:** Persuasion, Deception, Insight, Intimidation, Leadership, Lore.
* **Outlander:** Survival, Athletics, Stealth, Perception, Ranged, Medicine.
* **Merchant:** Persuasion, Deception, Insight, Perception, Lore, Stealth.

### 3.4 Full Skill List
*(Defense Skills are marked.)*
* **Physical Skills:** Athletics, Crafting, Melee, Ranged, Stealth, *Parry (Defense)*, *Dodge (Defense)*.
* **Social Skills:** Deception, Intimidation, Leadership, Performance, Persuasion, *Rebuke (Defense)*, *Deflect (Defense)*.
* **Mental Skills:** Investigation, Lore, Medicine, Perception, Insight, Survival, *Fortify (Defense)*, *Evade (Defense)*.

## 4.0 Action & Combat
### 4.1 Action Economy
* **Rounds and Turns:** Combat is organized into rounds. On your turn, choose to act fast or slow.
    * **Fast Turn:** Act before enemies, gain two actions (►►).
    * **Slow Turn:** Act after fast-moving enemies, gain three actions (►►►).
* **Actions (►):** Primary tasks. Cost can be one (►), two (►►), or three (►►►).
* **Free Actions (▷):** Minor tasks like speaking a short sentence.
* **Reactions ( ):** Actions taken in response to a trigger. One per round.

### 4.1.1 The Action Prefix Rule & Usage Limits
**The Core Rule: One Prefix Per Turn**
On your turn, you may only perform one action of any given prefix unless the action explicitly states otherwise. This applies to all actions on the Action Lists, as well as special actions granted by talents.

### 4.2 Action Lists
#### General Actions
| Action | Cost | Description |
| :--- | :--- | :--- |
| Brace | ► | Until your next turn, attacks against you suffer a Minor Setback (−1 to x). If you are already in cover, you increase the effectiveness of that cover by one step. |
| Disengage | ► | Move 5 feet without provoking Reactive Strikes. |
| Gain Edge | ► | Make a skill test to gain a Minor Edge (+1 to x) on your next test against the target. |
| Grapple | ► | Make an Athletics test to attempt to make a target Restrained. |
| Interact | ► | Perform a quick object interaction, such as drawing a weapon. |
| Move | ► | Move up to your character's movement rate. This can be used multiple times per turn. |
| **Recover** | **►►** | **Spend one Recovery Die. You generate a pool of Recovery Points to allocate to your Health Pools or Focus. See Section 5.4 for full rules.** |
| Ready | * | Prepare an action. Cost is ► plus the cost of the readied action. |
| Shove | ► | Make an Athletics test to push or pull a target 5 feet. |
| Strike | ► | Make a weapon or unarmed attack. |
| Use a Skill | ► | Perform a task that requires a skill test. |

### 4.3 Conditions
Conditions are persistent effects that modify a character's capabilities.
* **Blinded:** Your attacks suffer a Major Setback (−2 to x); attacks against you gain a Major Edge (+2 to x). You automatically fail any check that requires sight.
* **Challenged:** If your attack doesn't include the source of the challenge as a target, you suffer an Overwhelming Setback (−3 to x) on that attack roll.
* **Concealment:** Attacks against a target with concealment suffer a Setback. Light Concealment (e.g., dim light, foliage) imposes a Minor Setback (−1 to x). Heavy Concealment (e.g., darkness, thick fog) imposes a Major Setback (−2 to x).
* **Cover:** Attacks against a target in cover suffer a Setback. Light Cover (e.g., a crate, a tree trunk) imposes a Minor Setback (−1 to x). Heavy Cover (e.g., a fortified wall) imposes a Major Setback (−2 to x). Total Cover means the target cannot be targeted directly.
* **Dazed:** You suffer a Major Setback (−2 to x) on all checks and cannot take Reactions.
* **Hidden:** Your first attack made while hidden against a creature that is unaware of you gains an Overwhelming Edge (+3 to x). Attacks made against a hidden creature suffer a Major Setback (−2 to x).
* **Prone:** You have a Minor Setback (−1 to x) on melee attack rolls and a Major Setback (−2 to x) on ranged attack rolls. Melee attacks against you gain a Minor Edge (+1 to x), while ranged attacks against you suffer a Minor Setback (−1 to x).

## 5.0 Core Resources
### 5.1 The Momentum System
> **Designer's Note:** The Momentum system below is Version 0.5. It is scheduled for a major overhaul to a "Flow State" mechanic where Momentum provides stacking passive buffs rather than being a spendable resource.

Momentum is a resource representing the flow of a scene. Max 5 per player, and max 5 for the GM.
* **Gaining:** A player gains 1 on a successful roll. The GM gains 1 on a player's failed roll.
* **Spending Player Momentum:**
    * **Push Your Luck (1+):** Lower TN by 15 per Momentum spent.
    * **Declare a Critical (3):** If a declared roll succeeds, it's a best-possible result.
    * **Power Attack (2):** Roll weapon damage an additional time.
    * **Called Shot (2):** Bypass half armor or inflict a minor injury.
    * **Clutch Save (4):** Turn a failed roll into a simple success.

### 5.2 The Focus Resource
Focus is a personal pool of energy for powering special abilities, primarily Reactions and certain powerful Talents.
* **Calculation:** At character creation, choose either your Finesse or Resistance attributes.
    `Maximum Focus = 3 + Lowest Attribute Score from the chosen category`

### 5.3 The Essence Resource (Placeholder)
Essence is a personal pool of energy used to power magical Charms. This resource is only available to characters who select a magical Elective Talent Tree.

### 5.4 The Unified Recovery System
This system is built around a resource called **Recovery Dice**, which characters spend to restore their Health Pools and Focus.

#### Recovery Dice Pool
A character has a single pool of Recovery Dice, representing their general heroism and resilience.
* **Pool Size:** The number of Recovery Dice you have is equal to **`1 + your Tier of Play`**.
    * Tier 1 (Levels 1-5): **2 Recovery Dice**
    * Tier 2 (Levels 6-10): **3 Recovery Dice**
    * Tier 3 (Levels 11-15): **4 Recovery Dice**
    * Tier 4 (Levels 16-20): **5 Recovery Dice**
    * Tier 5 (Levels 21+): **6 Recovery Dice**

#### The Recovery Roll
When you spend one or more Recovery Dice, you roll them to generate **Recovery Points**.
* **The Roll:** For each Recovery Die you spend, you roll **`1d6 + your choice of Vigor, Composure, or Resolve`**.
* **The Choice:** You must choose which of your three Resistance Attributes to add to the roll, reflecting the narrative of your recovery (e.g., adding Vigor is toughing it out, adding Resolve is finding your center).

#### Allocating Recovery Points
The total result of your Recovery Roll becomes a pool of Recovery Points. You can immediately spend these points:
* **1 Recovery Point** = Restore 1 point of **Vitality**.
* **1 Recovery Point** = Restore 1 point of **Poise**.
* **1 Recovery Point** = Restore 1 point of **Clarity**.
* **2 Recovery Points** = Restore 1 point of **Focus**.

## 6.0 Health, Wounds, and Defense
### 6.1 Health Pools and Wounds
Characters have three Health Pools. When a pool hits 0, the character takes one Wound of that type.
* **Vitality (Physical):** Taking a Wound causes an **Injury**.
* **Poise (Social):** Taking a Wound causes a **Burden**.
* **Clarity (Mental):** Taking a Wound causes a **Trauma**.
* **Defeat:** A character is defeated when their accumulated Wounds of one type equal their corresponding Resistance Attribute (Vigor for Injuries, Composure for Burdens, Resolve for Traumas).
* **Wound Progression:** The first Wound of a type is Minor, the second is Moderate, and the third and subsequent are Severe.

### 6.2 Health Pool Calculation
* Max Vitality = `3 * Vigor`
* Max Poise = `3 * Composure`
* Max Clarity = `3 * Resolve`

### 6.3 Damage Calculation
Damage = `Weapon/Tactic Die + Relevant Power or Finesse Attribute`.

### 6.4 Defense System
* **Physical Defense:** `Agility + Dodge Skill` OR `Might + Parry Skill`.
* **Social Defense:** `Charm + Deflect Skill` OR `Presence + Rebuke Skill`.
* **Mental Defense:** `Wits + Evade Skill` OR `Intellect + Fortify Skill`.

### 6.5 Wound & Recovery Reference Tables
*(See Appendix for full tables)*

### 6.6 Resting
A character can benefit from one Short Rest and one Long Rest per 24-hour period.
* **Short Rest (1 Hour):**
    * You can spend a number of available Recovery Dice up to your Tier of Play. Roll all spent dice, total the result, and allocate the Recovery Points.
    * You can use skills to remove Minor Wounds (e.g., a `DR 4` Medicine check to remove a Minor Injury).
* **Long Rest (8 Hours):**
    * Regain all spent Recovery Dice.
    * All Health Pools and your Focus pool are restored to maximum.
    * Allows for progress on recovering from Moderate Wounds.

## 7.0 Equipment
### 7.1 Baseline Weapon Stats
| Weapon | Damage Die | Attribute | Properties |
| :--- | :--- | :--- | :--- |
| Dagger | 1d4 | Agility | Light, Thrown |
| Shortsword | 1d6 | Agility | Light |
| Longsword | 1d8 | Might/Agility | Versatile (1d10) |
| Battleaxe | 1d8 | Might | Versatile (1d10) |
| Greataxe | 1d12 | Might | Heavy, Two-Handed |
| Spear | 1d6 | Agility | Thrown, Versatile (1d8) |
| Shortbow | 1d6 | Agility | Ranged, Two-Handed |
| Longbow | 1d8 | Agility | Ranged, Heavy, Two-Handed |

## 8.0 Archetypes & Talents
### 8.1 The Three-Tree System
Each character has three Talent Trees: two Core Trees from their Archetype and one Elective Tree of their choice. Talents interact with the Edges & Setbacks system, often granting or enhancing them.

* ***Example Talent Update:*** A talent like *"Tower Shield Master"* would be updated to read: *"Attacks against you while Bracing suffer a Major Setback (−2 to x) instead of the usual −1."*
* ***Example Reaction Update:*** Reactions like *"Support Ally"* would be updated to *"grant a Minor Edge (+1 to x)"* on the triggering ally's roll, while a reaction like *"Rebuff"* would *"impose a Minor Setback (−1 to x)"* on a foe's roll.

### 8.2 Mundane Archetypes
* **Physical:** Vanguard, Warrior, Scoundrel
* **Social:** Commander, Envoy, Schemer
* **Mental:** Scholar, Tactician, Investigator

### 8.3 Elective Talent Trees
These are specialized disciplines any character can choose (e.g., Alchemy, Marksman, Medicine). Magical trees that grant Charms are also chosen from this list.

## 9.0 Progression & Tiers of Play
### 9.1 Gaining Levels
Characters advance through XP or Milestones.
* XP to Next Level = `10 x Current Tier Number`

### 9.2 Tiers of Play
* **Tier 1:** Local Heroes (Levels 1–5)
* **Tier 2:** Proven Professionals (Levels 6–10)
* **Tier 3:** Regional Figures (Levels 11–15)
* **Tier 4:** National Leaders (Levels 16–20)
* **Tier 5:** World Shapers (Levels 21+)

## 10.0 Systems Pending Development
* **Momentum System Overhaul:** Redesigning Momentum to be a "Flow State" mechanic with passive buffs.
* **Level-Up Benefits:** Finalizing the specific rewards (Attribute Points, Skill Points, Talents) gained at each level.
* **Full Elective Tree Lists:** Creating the complete lists of mundane and magical trees and their Talents.
* **Equipment Expansion:** Lists for armor, additional weapons, and adventuring gear.
* **GM Toolkit:** Guidelines for creating adversaries, balancing encounters, and managing the game.

---
---

## **Appendix: Wound & Recovery Tables**

### **Injuries (Physical Wounds)**
#### Minor Injuries (Roll 1d6)
| Roll | Wound Name | Mechanical Effect | Mundane Recovery | Magical Recovery Example |
| :--- | :--- | :--- | :--- | :--- |
| **1** | Twisted Ankle / Wrenched Shoulder | -10 ft. movement speed OR a -2 penalty to the Difference `(x)` on checks using a specific arm. | Short Rest + `DR 4` Intellect + Medicine check. | A low-tier "Mend" charm. |
| **2** | Deep Gash | You are bleeding, taking 1 direct Vitality damage at the start of your turn until stopped. | A `First Aid` action `(►)` with a `DR 3` Intellect + Medicine check. | A "Cleanse Wound" cantrip. |
| **3** | Cracked Rib | You cannot take the `Brace` action, and you suffer a -1 penalty to your passive Parry defense. | Short Rest + `DR 4` Intellect + Medicine check. | A low-tier "Mend" charm. |
| **4** | Winded | The Focus cost of any action requiring a Physical skill check is increased by 1 for the scene. | Automatically fades at the end of the scene. | A "Stamina" cantrip. |
| **5** | Bell Rung | A blow to the head leaves you dazed. You suffer a -2 penalty to `(x)` on Perception checks for the scene. | Short Rest + `DR 4` Resolve check. | A "Clear Head" cantrip. |
| **6** | Painful Bruising | Your body aches. You cannot regain Focus by using the `Recover` action for the scene. | Automatically fades at the end of the scene. | A "Soothe Pain" charm. |

#### Moderate Injuries
| Wound Name | Mechanical Effect | Mundane Recovery | Magical Recovery Example |
| :--- | :--- | :--- | :--- |
| **Pulled Muscle** | Choose Might or Agility. You suffer a -3 penalty to `(x)` on all checks using that attribute. | 1 week of downtime, reducible to 3 days with a `DR 6` Intellect + Medicine check. | A mid-tier "Restoration" charm. |
| **Serious Laceration** | You are bleeding heavily, taking 1d4 direct Vitality damage at the start of your turn until stopped. | A `First Aid` action `(►►)` with a `DR 5` Intellect + Medicine check. | A mid-tier "Knit Flesh" charm. |
| **Broken Ribs** | The pain is intense. You cannot use the `Recover` or `Brace` action, and suffer a -2 penalty on all Vigor resistance checks. | 1 week of downtime, reducible to 3 days with a `DR 6` Intellect + Medicine check. | A mid-tier "Restoration" charm. |
| **Dislocated Joint** | One limb is useless. An ally can use an action `(►►)` to make a `DR 6` Intellect + Medicine check to reset it, downgrading this to a Minor Injury. | 1 week of downtime, reducible to 3 days with a `DR 6` Intellect + Medicine check. | A "Reset Bone" charm that downgrades it. |
| **Concussion** | Your head is swimming. You cannot take a `Slow Turn` `(►►►)`, and you suffer a -2 penalty to `(x)` on all Mental skill checks. | 1 week of downtime, reducible to 3 days with a `DR 6` Intellect + Medicine check. | A mid-tier "Clarity of Mind" charm. |
| **Infected Wound** | Your injury is septic. You cannot regain Vitality from any mundane source until the infection is treated with a `DR 6` Medicine check that takes 1 hour. | 1 week of downtime, reducible to 3 days with a `DR 6` Intellect + Medicine check. | A "Purify Body" charm. |

#### Severe Injuries
| Wound Name | Mechanical Effect | Mundane Recovery | Magical Recovery Example |
| :--- | :--- | :--- | :--- |
| **Shattered Bone** | One limb is unusable until properly set and healed. You cannot use it for any action. If a leg, your speed is reduced to 5 feet. | Requires 1 month of professional care OR 1 week with a PC's `Advanced Surgery` talent and a `DR 8` Medicine check. | A high-tier "Regenerate" ritual. |
| **Crippling Pain** | You are overwhelmed by constant pain. You cannot take a `Slow Turn` `(►►►)`. Your turn is always considered a `Fast Turn` `(►►)`. | Requires 1 month of professional care and recovery. | A high-tier "Sovereign Healing" charm. |
| **Hamstrung** | A debilitating leg injury. Your speed is reduced to 5 feet, and you cannot use the `Dodge` reaction or take any action that requires significant movement. | Requires 1 month of professional care and physical therapy. | A high-tier "Regenerate" ritual. |
| **Festering Wound** | Your injury is dangerously infected. You cannot be healed by *any* means until the wound is treated with a `(DR 7)` Intellect + Medicine check, which takes one hour. | Requires 1 month of professional care. | A high-tier "Greater Purification" charm. |
| **Internal Injury** | You are bleeding internally, taking 1d6 direct Vitality damage at the start of your turn. This can only be stopped with a `(DR 8)` Intellect + Medicine check `(►►►)`. | Requires 1 month of professional care and emergency surgery. | A high-tier "Cure Critical Wounds" charm. |
| **Severed Tendon** | A key tendon in a limb has been cut. You can no longer use Reactions associated with that limb (e.g., `Parry`, `Reactive Strike`, `Dodge`). | Requires 1 month of professional care and delicate surgery. | A high-tier "Regenerate" ritual. |

### **Burdens (Social Wounds)**
#### Minor Burdens (Roll 1d6)
| Roll | Wound Name | Mechanical Effect | Mundane Recovery | Magical Recovery Example |
| :--- | :--- | :--- | :--- | :--- |
| **1** | Rattled | The next time you attempt a Social check, you must first make a `DR 3` Composure check or the check automatically fails. | Short Rest + `DR 4` Presence + Persuasion check with an ally. | A "Steadfast Heart" cantrip. |
| **2** | Social Misstep | You have a -2 penalty to `(x)` on Social checks with one specific group for the rest of the scene. | Automatically fades at the end of the scene. | A "Charming Word" cantrip. |
| **3** | Hesitant | You are second-guessing yourself. You cannot use the `Aid` reaction to help an ally on a Social check for the scene. | Short Rest + `DR 4` Presence + Persuasion check with an ally. | A "Bolster Confidence" cantrip. |
| **4** | Flustered | You've lost your train of thought. You cannot use the `Gain Edge` action for social checks for the scene. | Automatically fades at the end of the scene. | A "Moment of Grace" cantrip. |
| **5** | Poorly Received | Your words backfired. The target of your last failed social check gains a `+2` bonus to `(x)` on their next social check against you. | Automatically fades after the target's next social check against you. | A "Silver Tongue" charm. |
| **6** | Embarrassed | Your blunder is fresh in your mind. The Focus cost of any Social skill is increased by 1 for the scene. | Automatically fades at the end of the scene. | A "Soothe Ego" cantrip. |

#### Moderate Burdens
| Wound Name | Mechanical Effect | Mundane Recovery | Magical Recovery Example |
| :--- | :--- | :--- | :--- |
| **Discredited** | Your arguments are seen as foolish. Suffer a -3 penalty to `(x)` on Persuasion and Leadership checks for the scene. | 1 week of downtime, reducible to 3 days with a `DR 6` Presence + Persuasion check. | A mid-tier "Compelling Voice" charm. |
| **Mistrusted** | Your motives are suspect. You cannot benefit from the `Aid` action from allies during social encounters for the scene. | 1 week of downtime, reducible to 3 days with a `DR 6` Charm + Deception or Persuasion check. | A "Veil of Sincerity" charm. |
| **Socially Drained** | You are exhausted by the interaction. Your maximum Poise is halved until you get a full night's rest. | A full night's rest in a safe, quiet place. | A "Rally the Spirit" charm. |
| **Antagonized** | You have angered a specific character, who now gains a `+2` bonus to `(x)` on all opposed social checks against you. | Requires a significant apology or favor to make amends with the NPC. | A "Forget Transgression" charm. |
| **Minor Scandal** | A rumor is spreading. You have a persistent `-2` penalty to `(x)` on all social checks in a specific town/region until you clear your name. | Requires a downtime action to find the source of the rumor and publicly discredit it. | A "Whispers of Truth" charm. |
| **Shunned** | You've deeply offended one person. That specific NPC will not speak to you. You must go through an intermediary or make a grand gesture. | Requires a significant gift or completing a quest for the offended NPC. | A "Soften Heart" charm. |

#### Severe Burdens
| Wound Name | Mechanical Effect | Mundane Recovery | Magical Recovery Example |
| :--- | :--- | :--- | :--- |
| **Humiliated** | You have suffered a complete social defeat. You cannot initiate any opposed Social checks for the rest of the scene. | Requires a full downtime week and a successful `(DR 7)` Composure check to regain your confidence. | A high-tier "Heroic Bearing" charm. |
| **Overwhelmed** | You're at an emotional breaking point. You cannot regain `Poise` by any means for the rest of the scene. | Requires you to leave the stressful social situation and get a full night's rest. | A high-tier "Sovereign Confidence" charm. |
| **Cowardly Reputation** | Your allies have seen you break. They must spend 1 Focus to be the target of any of your beneficial Social actions or Talents. | Requires a public and undeniable act of bravery or leadership to prove your worth again. | A "Mantle of the Hero" ritual. |
| **Social Pariah** | Your presence is toxic. Any ally within 10 feet of you suffers a -1 penalty to `(x)` on their own Social checks. | Requires a significant public favor or quest completed for the community you have offended. | A "Rewrite Reputation" ritual. |
| **Broken Confidence** | Your self-worth is shattered. You automatically fail the first opposed social check you make in any new scene. | Requires a month of downtime with a mentor or companion to rebuild your spirit. | A high-tier "Mind Mending" ritual. |
| **Marked** | You've angered a powerful faction. They will actively work against you, causing one complication (GM's choice) during each downtime period. | Requires neutralizing the threat or making amends with the faction. | A "Veil of Anonymity" ritual. |

### **Traumas (Mental Wounds)**
#### Minor Traumas (Roll 1d6)
| Roll | Wound Name | Mechanical Effect | Mundane Recovery | Magical Recovery Example |
| :--- | :--- | :--- | :--- | :--- |
| **1** | Flash of Panic | Suffer a -3 penalty to `(x)` on your next check to resist fear or intimidation. | Short Rest + `DR 4` Wits + Insight check with an ally. | A "Valorous Mind" cantrip. |
| **2** | Haunting Image | Suffer a -2 penalty to `(x)` on all Perception checks for the scene, as your attention is divided. | Short Rest + `DR 4` Wits + Insight check with an ally. | A "Clear Head" cantrip. |
| **3** | Mental Fatigue | Your maximum Focus pool is reduced by 2 for the scene. | Automatically fades at the end of the scene. | A "Surge of Will" cantrip. |
| **4** | Doubt | Your knowledge is shaken. You cannot use the `Recall Information` action for the scene. | Short Rest + `DR 4` Wits + Insight check with an ally. | A "Clarity" cantrip. |
| **5** | Jumpy | You are easily startled and on edge. You cannot use the `Ready` action for the scene. | Automatically fades at the end of the scene. | A "Calm Nerves" cantrip. |
| **6** | Distracted | Your mind wanders. The first time you `Aid` an ally each scene, it costs you 2 Focus instead of 1. | Automatically fades at the end of the scene. | A "Focusing Mantra" cantrip. |

#### Moderate Traumas
| Wound Name | Mechanical Effect | Mundane Recovery | Magical Recovery Example |
| :--- | :--- | :--- | :--- |
| **Jittery** | You can't stay focused. At the end of your turn, if you did not use a `Move` action, you take 1d4 Clarity damage. | 1 week of downtime, reducible to 3 days with a `DR 6` Wits + Insight check. | A mid-tier "Peace of Mind" charm. |
| **Fixated** | You latch onto one enemy or goal. You suffer a -3 penalty to `(x)` on any check that does not involve your point of fixation. | 1 week of downtime, reducible to 3 days with a `DR 6` Wits + Insight check. | A "Mental Refocus" charm. |
| **Mental Block** | You can't access your higher training. One of your Talent Trees (player's choice) is unusable for the rest of the scene. | A full night's rest. | A "Cognitive Unlock" charm. |
| **Faltering Will** | You find it difficult to push yourself. The Focus cost of all your Reactions is increased by 1. | 1 week of downtime, reducible to 3 days with a `DR 6` Resolve check. | A "Strengthen Will" charm. |
| **Night Terrors** | You cannot get a full night's rest. You only recover half the normal amount of Health and Focus from resting. | 1 week of downtime spent in a safe and peaceful location. | A "Dreamless Sleep" charm. |
| **Apathy** | You've lost your motivation. You cannot spend Momentum on your own skill checks. | 1 week of downtime, reducible to 3 days with a `DR 6` Persuasion check from an inspiring ally. | A "Rekindle Spark" charm. |

#### Severe Traumas
| Wound Name | Mechanical Effect | Mundane Recovery | Magical Recovery Example |
| :--- | :--- | :--- | :--- |
| **Broken Concentration** | You cannot perform complex tasks. You cannot take any action that costs two or more action points `(►► or ►►►)`. | Requires 1 month of guided meditation or therapy. | A high-tier "Mental Reorganization" ritual. |
| **Psychological Shock** | Your mind rejects your specialized skills. Choose one of your Core Talent Trees. You cannot use any talents from that tree. | Requires a significant personal breakthrough, often taking a full downtime period and a quest. | A high-tier "Mind Mending" ritual. |
| **Terror-Struck** | You are overcome with fear. On your turn, you are limited to a single action `(►)` that must be defensive or evasive. | Requires a month of downtime spent in a perfectly safe and secure environment. | A high-tier "Remove Fear" charm. |
| **Sensory Overload** | Your mind is reeling. You are **Dazed** (-2 penalty to `(x)` on all checks and you cannot use reactions). | Requires 1 month of downtime in a place with minimal sensory input (a quiet monastery, etc.). | A high-tier "Psychic Reset" ritual. |
| **Willful Denial** | You refuse to accept reality. You cannot be the recipient of any magical healing or mental enhancement Charms. | Requires a trusted companion to spend a week of downtime making `DR 8` Persuasion checks to talk you through it. | A "Forced Clarity" charm. |
| **Mental Breakdown** | Your mind is in chaos. At the start of your turn, roll a d6. On a 1, you lose your entire turn, paralyzed by indecision and fear. | Requires 1 month of downtime under the care of a specialist (therapist, elder monk). | A high-tier "Mind Mending" ritual. |