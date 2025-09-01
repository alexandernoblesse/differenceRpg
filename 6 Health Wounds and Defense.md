## 6.0 Health, Wounds, and Defense
### 6.1 Health Pools and Wounds
Characters have three Health Pools. When a pool hits 0, the character takes one Wound of that type. After taking a wound, health goes to maximum - # of wounds. When a character has received a number of wounds equal to their resistance attribute for that type of wound, the character is defeated.
* **Vitality (Physical):** Taking a Wound causes an **Injury**.
* **Poise (Social):** Taking a Wound causes a **Burden**.
* **Clarity (Mental):** Taking a Wound causes a **Trauma**.
* **Defeat:** A character is defeated when their accumulated Wounds of one type equal their corresponding Resistance Attribute.
* **Wound Progression:** The first Wound of a type is Minor, the second is Moderate, and the third and subsequent are Severe.

> **GM Note: Narrative First Wounds**
> The Wound tables provide a quick way to determine the consequences of being defeated in a conflict. However, the GM should always prioritize the narrative. If the event that caused a Wound strongly suggests a specific outcome (e.g., an arrow to the leg causing a movement penalty, or a public insult causing humiliation), the GM is encouraged to choose the most fitting Injury, Burden, or Trauma from the lists directly, rather than rolling randomly.

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

### 6.5 Resting
* **Short Rest (1 Hour):** Spend Recovery Dice up to your Tier of Play. Use skills to remove Minor Wounds.
* **Long Rest (8 Hours):** Regain all spent Recovery Dice. All Health Pools and Focus are restored to maximum. Allows progress on recovering from Moderate Wounds.

### 6.6 **Injuries (Physical Wounds)**
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
| Roll | Wound Name | Mechanical Effect | Mundane Recovery | Magical Recovery Example |
| :--- | :--- | :--- | :--- | :--- |
| **1** | **Pulled Muscle** | Choose Might or Agility. You suffer a -3 penalty to `(x)` on all checks using that attribute. | 1 week of downtime, reducible to 3 days with a `DR 6` Intellect + Medicine check. | A mid-tier "Restoration" charm. |
| **2** | **Serious Laceration** | You are bleeding heavily, taking 1d4 direct Vitality damage at the start of your turn until stopped. | A `First Aid` action `(►►)` with a `DR 5` Intellect + Medicine check. | A mid-tier "Knit Flesh" charm. |
| **3** | **Broken Ribs** | The pain is intense. You cannot use the `Recover` or `Brace` action, and suffer a -2 penalty on all Vigor resistance checks. | 1 week of downtime, reducible to 3 days with a `DR 6` Intellect + Medicine check. | A mid-tier "Restoration" charm. |
| **4** | **Dislocated Joint** | One limb is useless. An ally can use an action `(►►)` to make a `DR 6` Intellect + Medicine check to reset it, downgrading this to a Minor Injury. | 1 week of downtime, reducible to 3 days with a `DR 6` Intellect + Medicine check. | A "Reset Bone" charm that downgrades it. |
| **5** | **Concussion** | Your head is swimming. You cannot take a `Slow Turn` `(►►►)`, and you suffer a -2 penalty to `(x)` on all Mental skill checks. | 1 week of downtime, reducible to 3 days with a `DR 6` Intellect + Medicine check. | A mid-tier "Clarity of Mind" charm. |
| **6** | **Infected Wound** | Your injury is septic. You cannot regain Vitality from any mundane source until the infection is treated with a `DR 6` Medicine check that takes 1 hour. | 1 week of downtime, reducible to 3 days with a `DR 6` Intellect + Medicine check. | A "Purify Body" charm. |

#### Severe Injuries
| Roll | Wound Name | Mechanical Effect | Mundane Recovery | Magical Recovery Example |
| :--- | :--- | :--- | :--- | :--- |
| **1** | **Shattered Bone** | One limb is unusable until properly set and healed. You cannot use it for any action. If a leg, your speed is reduced to 5 feet. | Requires 1 month of professional care OR 1 week with a PC's `Advanced Surgery` talent and a `DR 8` Medicine check. | A high-tier "Regenerate" ritual. |
| **2** | **Crippling Pain** | You are overwhelmed by constant pain. You cannot take a `Slow Turn` `(►►►)`. Your turn is always considered a `Fast Turn` `(►►)`. | Requires 1 month of professional care and recovery. | A high-tier "Sovereign Healing" charm. |
| **3** | **Hamstrung** | A debilitating leg injury. Your speed is reduced to 5 feet, and you cannot use the `Dodge` reaction or take any action that requires significant movement. | Requires 1 month of professional care and physical therapy. | A high-tier "Regenerate" ritual. |
| **4** | **Festering Wound** | Your injury is dangerously infected. You cannot be healed by *any* means until the wound is treated with a `(DR 7)` Intellect + Medicine check, which takes one hour. | Requires 1 month of professional care. | A high-tier "Greater Purification" charm. |
| **5** | **Internal Injury** | You are bleeding internally, taking 1d6 direct Vitality damage at the start of your turn. This can only be stopped with a `(DR 8)` Intellect + Medicine check `(►►►)`. | Requires 1 month of professional care and emergency surgery. | A high-tier "Cure Critical Wounds" charm. |
| **6** | **Severed Tendon** | A key tendon in a limb has been cut. You can no longer use Reactions associated with that limb (e.g., `Parry`, `Reactive Strike`, `Dodge`). | Requires 1 month of professional care and delicate surgery. | A high-tier "Regenerate" ritual. |

### 6.7 **Burdens (Social Wounds)**
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
| Roll | Wound Name | Mechanical Effect | Mundane Recovery | Magical Recovery Example |
| :--- | :--- | :--- | :--- | :--- |
| **1** | **Discredited** | Your arguments are seen as foolish. Suffer a -3 penalty to `(x)` on Persuasion and Leadership checks for the scene. | 1 week of downtime, reducible to 3 days with a `DR 6` Presence + Persuasion check. | A mid-tier "Compelling Voice" charm. |
| **2** | **Mistrusted** | Your motives are suspect. You cannot benefit from the `Aid` action from allies during social encounters for the scene. | 1 week of downtime, reducible to 3 days with a `DR 6` Charm + Deception or Persuasion check. | A "Veil of Sincerity" charm. |
| **3** | **Socially Drained** | You are exhausted by the interaction. Your maximum Poise is halved until you get a full night's rest. | A full night's rest in a safe, quiet place. | A "Rally the Spirit" charm. |
| **4** | **Antagonized** | You have angered a specific character, who now gains a `+2` bonus to `(x)` on all opposed social checks against you. | Requires a significant apology or favor to make amends with the NPC. | A "Forget Transgression" charm. |
| **5** | **Minor Scandal** | A rumor is spreading. You have a persistent `-2` penalty to `(x)` on all social checks in a specific town/region until you clear your name. | Requires a downtime action to find the source of the rumor and publicly discredit it. | A "Whispers of Truth" charm. |
| **6** | **Shunned** | You've deeply offended one person. That specific NPC will not speak to you. You must go through an intermediary or make a grand gesture. | Requires a significant gift or completing a quest for the offended NPC. | A "Soften Heart" charm. |

#### Severe Burdens
| Roll | Wound Name | Mechanical Effect | Mundane Recovery | Magical Recovery Example |
| :--- | :--- | :--- | :--- | :--- |
| **1** | **Humiliated** | You have suffered a complete social defeat. You cannot initiate any opposed Social checks for the rest of the scene. | Requires a full downtime week and a successful `(DR 7)` Composure check to regain your confidence. | A high-tier "Heroic Bearing" charm. |
| **2** | **Overwhelmed** | You're at an emotional breaking point. You cannot regain `Poise` by any means for the rest of the scene. | Requires you to leave the stressful social situation and get a full night's rest. | A high-tier "Sovereign Confidence" charm. |
| **3** | **Cowardly Reputation** | Your allies have seen you break. They must spend 1 Focus to be the target of any of your beneficial Social actions or Talents. | Requires a public and undeniable act of bravery or leadership to prove your worth again. | A "Mantle of the Hero" ritual. |
| **4** | **Social Pariah** | Your presence is toxic. Any ally within 10 feet of you suffers a -1 penalty to `(x)` on their own Social checks. | Requires a significant public favor or quest completed for the community you have offended. | A "Rewrite Reputation" ritual. |
| **5** | **Broken Confidence** | Your self-worth is shattered. You automatically fail the first opposed social check you make in any new scene. | Requires a month of downtime with a mentor or companion to rebuild your spirit. | A "Mind Mending" ritual. |
| **6** | **Marked** | You've angered a powerful faction. They will actively work against you, causing one complication (GM's choice) during each downtime period. | Requires neutralizing the threat or making amends with the faction. | A "Veil of Anonymity" ritual. |

### 6.8 **Traumas (Mental Wounds)**
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
| Roll | Wound Name | Mechanical Effect | Mundane Recovery | Magical Recovery Example |
| :--- | :--- | :--- | :--- | :--- |
| **1** | **Jittery** | You can't stay focused. At the end of your turn, if you did not use a `Move` action, you take 1d4 Clarity damage. | 1 week of downtime, reducible to 3 days with a `DR 6` Wits + Insight check. | A mid-tier "Peace of Mind" charm. |
| **2** | **Fixated** | You latch onto one enemy or goal. You suffer a -3 penalty to `(x)` on any check that does not involve your point of fixation. | 1 week of downtime, reducible to 3 days with a `DR 6` Wits + Insight check. | A "Mental Refocus" charm. |
| **3** | **Mental Block** | You can't access your higher training. One of your Talent Trees (player's choice) is unusable for the rest of the scene. | A full night's rest. | A "Cognitive Unlock" charm. |
| **4** | **Faltering Will** | You find it difficult to push yourself. The Focus cost of all your Reactions is increased by 1. | 1 week of downtime, reducible to 3 days with a `DR 6` Resolve check. | A "Strengthen Will" charm. |
| **5** | **Night Terrors** | You cannot get a full night's rest. You only recover half the normal amount of Health and Focus from resting. | 1 week of downtime spent in a safe and peaceful location. | A "Dreamless Sleep" charm. |
| **6** | **Apathy** | You've lost your motivation. You cannot spend Momentum on your own skill checks. | 1 week of downtime, reducible to 3 days with a `DR 6` Persuasion check from an inspiring ally. | A "Rekindle Spark" charm. |

#### Severe Traumas
| Roll | Wound Name | Mechanical Effect | Mundane Recovery | Magical Recovery Example |
| :--- | :--- | :--- | :--- | :--- |
| **1** | **Broken Concentration** | You cannot perform complex tasks. You cannot take any action that costs two or more action points `(►► or ►►►)`. | Requires 1 month of guided meditation or therapy. | A high-tier "Mental Reorganization" ritual. |
| **2** | **Psychological Shock** | Your mind rejects your specialized skills. Choose one of your Core Talent Trees. You cannot use any talents from that tree. | Requires a significant personal breakthrough, often taking a full downtime period and a quest. | A high-tier "Mind Mending" ritual. |
| **3** | **Terror-Struck** | You are overcome with fear. On your turn, you are limited to a single action `(►)` that must be defensive or evasive. | Requires a month of downtime spent in a perfectly safe and secure environment. | A high-tier "Remove Fear" charm. |
| **4** | **Sensory Overload** | Your mind is reeling. You are **Dazed** (-2 penalty to `(x)` on all checks and you cannot use reactions). | Requires 1 month of downtime in a place with minimal sensory input (a quiet monastery, etc.). | A high-tier "Psychic Reset" ritual. |
| **5** | **Willful Denial** | You refuse to accept reality. You cannot be the recipient of any magical healing or mental enhancement Charms. | Requires a trusted companion to spend a week of downtime making `DR 8` Persuasion checks to talk you through it. | A "Forced Clarity" charm. |
| **6** | **Mental Breakdown** | Your mind is in chaos. At the start of your turn, roll a d6. On a 1, you lose your entire turn, paralyzed by indecision and fear. | Requires 1 month of downtime under the care of a specialist (therapist, elder monk). | A "Mind Mending" ritual. |