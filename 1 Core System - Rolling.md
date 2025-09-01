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

The probabilities in the table are derived from the logistic function $\frac{1}{1+e^{-\frac{1}{2}x}}$. The values have been manually smoothed to ensure a unique target number for each integer of the Difference `(x)` and are capped at a Difference of +10 (for a 100% chance of success) and -10 (for a 0% chance of success).

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

| Difficulty Rank (DR) | Description | Example Tasks |
| :--- | :--- | :--- |
| 1-2 | Trivial: A simple task that a professional would barely need to think about. | Picking a simple lock; Recalling a common historical fact; Convincing a friendly guard to let you pass. |
| 3-5 | Standard: A professional challenge requiring focus and skill. | Disarming a simple tripwire trap; Crafting a standard longsword; Persuading a skeptical merchant for a discount. |
| 6-8 | Challenging: A task that would push a skilled individual to their limits. | Picking a complex vault lock; Deciphering a coded message; Performing field surgery to set a broken bone. |
| 9-10 | Heroic: A feat that is difficult even for the greatest masters of the craft. | Translating a forgotten, pre-cataclysmic language; Forging a flawless masterwork weapon; Calming a panicked crowd during a disaster. |
| 11+ | Legendary: A feat that borders on the impossible. | Crafting a legendary artifact; Devising a plan to outwit a demigod; Recalling a secret known only to the world's creators. |

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

### 1.5 Extended Tasks

Extended Tasks are used to resolve complex actions that require a significant investment of time and effort, where a single roll would not adequately represent the process. These tasks are not finished until they are completed, failed, or the character gives up. Examples include crafting a masterwork item, researching an ancient ritual, tracking a target across the wilderness, or engaging in a lengthy chase.

To set up an Extended Task, the Game Master determines three key components:

1.  **The Check:** The specific `Attribute + Skill` combination used for each roll in the task, and the opposition, which can either be a static Difficulty Rank (DR) for unopposed actions or an opponent's score for contested actions.
2.  **Success Threshold:** The total number of successful rolls a character must accumulate to complete the task. This is set by the GM based on the task's complexity (e.g., 3 for a standard task, 5 for a complex one, 10+ for a monumental effort).
3.  **Time Interval:** The amount of in-game time that passes with each roll. This is determined by the nature of the task. A roll could represent seconds (disarming a bomb), minutes (a chase), hours (research), days (crafting), or even weeks (translating a tome).

#### **Resolving the Task**

The player makes a series of checks. Each roll that meets or exceeds its Target Number (TN) adds one success to a running total. The task is successfully completed when the character's accumulated successes equal or exceed the Success Threshold.

#### **Failure and Complications**

Not all Extended Tasks carry the same risks. The GM decides which of the following models best fits the situation:

* **Persistence Model (No Failure Condition):** For low-risk tasks like crafting a non-volatile item or researching common history, a failed roll simply means no progress was made during that Time Interval. The character can continue making checks until they eventually reach the Success Threshold, with the only cost being the time spent.

* **Contested Model:** This is used when a character is in a direct race against an opponent, such as a chase, a debate, or two blacksmiths competing to finish a commission first. Both sides have a Success Threshold. They make opposed checks at each Time Interval, and the first to accumulate the required number of successes wins the contest.

* **Complications Model:** For high-stakes tasks, each failed roll introduces a Complication. The GM sets a **Failure Threshold** (e.g., 3 Complications). If the character accumulates a number of Complications equal to the Failure Threshold before they reach the Success Threshold, the entire task fails, often with negative consequences.
    * A Complication could be narrative (e.g., making a loud noise while sneaking) or mechanical (e.g., imposing a **Minor Setback** on future checks for this task).
    * On a player's failed roll, the GM may also gain 1 Momentum as usual.

* **Time Limit Model:** The task must be completed within a certain number of rolls (and thus, a certain amount of time). For example, if a character must pick a vault lock (Success Threshold 5) before the guards return in five minutes (Time Interval of one minute per roll), they have only five rolls to achieve the five successes.

### 1.6 Glossary of Terms & Conditions

* **Action (►)**: A primary task a character can perform on their turn. Actions have a cost, typically one or more action points.
* **Afflicted**: While Afflicted, you take damage over time. At the end of each of your turns, you take a specified amount of direct damage to one of your Health Pools (Vitality, Poise, or Clarity). The effect specifies the damage in brackets (e.g., Afflicted [1d6 Vitality]). You can be Afflicted by multiple sources simultaneously; resolve each instance of damage separately.
* **Availability**: A rank from 1 to 5 that represents an item's rarity and provides a guideline for its market price.
* **Blinded**: A blinded character's attacks suffer a -5 penalty to the Difference (x), and attacks made against them gain a +5 bonus to the Difference (x).
* **Burden**: A social Wound a character receives when their Poise pool is reduced to 0.
* **Challenged**: A challenged enemy suffers a -3 penalty to the Difference (x) on any attack that does not include the character who challenged them as a target.
* **Clarity**: A Health Pool representing a character's mental fortitude and willpower.
* **Dazed**: A dazed character suffers a -2 penalty to the Difference (x) on all checks and cannot use reactions.
* **Defeated**: A character is defeated when their accumulated Wounds of a single type (Injuries, Burdens, or Traumas) equal their corresponding Resistance Attribute.
* **Determined**: While Determined, if you fail a check, you can choose to treat the result as a simple success instead. After you use this ability, you are no longer Determined.
* **Difference (x)**: The numerical result of subtracting the opposition's score from the actor's score (`Actor’s Attribute + Skill` − `Opposition Score`), which is then used to find the Target Number for a d100 roll.
* **Difficulty Rank (DR)**: A static value from 1 to 11+ that serves as the opposition's score for an unopposed action.
* **Disoriented**: While Disoriented, your senses are disrupted. You cannot use Reactions and suffer a **Minor Setback (-1 to x)** on all Perception checks and other checks that rely heavily on your senses.
* **Edge**: A positive situational modifier that adds to the Difference `(x)` on a roll. A Minor Edge is +1, Major is +2, and Overwhelming is +3.
* **Empowered**: While Empowered, you are filled with a burst of power. You gain a **Minor Edge (+1 to x)** on all checks, and your Focus pool refills to its maximum at the start of each of your turns. This condition is removed at the end of the scene.
* **Enhanced**: While Enhanced, one of your attributes is temporarily increased. The specific attribute and bonus are noted in brackets (e.g., Enhanced [+1 Agility]). This bonus applies to any checks made using that attribute but does not change your derived statistics like Health Pools, Focus, or passive Defense scores.
* **Exhausted**: While Exhausted, you are fatigued. When you gain this condition, it includes a value in brackets (e.g., Exhausted [-1]). You suffer a **Setback** equal to this value on the Difference `(x)` for all checks you make. After each Long Rest, reduce the Setback value by 1; the condition is removed when the value reaches 0. This condition is cumulative.
* **Expertise**: A deep, focused understanding of a specific field, such as a piece of equipment or an area of knowledge. Expertise is required to benefit from an item's Expert Traits.
* **Fast Turn**: A turn in combat where a character gains two actions (►►) and acts before enemies.
* **Focus**: A personal pool of energy used to power special abilities, such as Reactions and certain powerful Talents.
* **Focused**: While Focused, the Focus cost of any action or ability you use is reduced by 1.
* **Free Action (▷)**: A minor task, such as speaking a short sentence, that does not cost an action point.
* **Immobilized**: While Immobilized, your movement speed is 0, and you cannot use the `Move` action. You cannot be moved by external effects like the `Shove` action.
* **Injury**: A physical Wound a character receives when their Vitality pool is reduced to 0.
* **Momentum**: A shared resource representing the flow of a scene, gained on successful rolls (by players) or failed rolls (by the GM), with a maximum of 5 for each side.
* **Pacified**: A pacified character will not take hostile actions unless they or their allies are attacked first.
* **Poise**: A Health Pool representing a character's social grace and composure.
* **Prone**: While Prone, you are lying on the ground. You are considered **Slowed**, and melee `Strike` actions made against you gain a **Minor Edge (+1 to x)**. You can use the `Brace` action without needing to be near cover. Standing up requires using a `Move` action (►).
* **Reaction ( )**: An action taken outside of a character's turn in response to a specific trigger. A character typically has one Reaction per round.
* **Recovery Dice**: A resource pool representing a character's resilience, which they can spend to make a Recovery Roll to restore Health Pools and Focus.
* **Restrained**: While Restrained, your movement speed is 0. You suffer a **Minor Setback (-1 to x)** on all checks, except for those made to escape the effect causing the condition.
* **Setback**: A negative situational modifier that subtracts from the Difference `(x)` on a roll. A Minor Setback is -1, Major is -2, and Overwhelming is -3.
* **Slow Turn**: A turn in combat where a character gains three actions (►►►) and acts after fast-moving enemies.
* **Slowed**: While Slowed, your movement speed per `Move` action is halved (rounded down to the nearest 5-foot increment).
* **Soak**: A character's ability to reduce incoming physical damage. This value is referred to as Soak (typically from armor) or Damage Reduction (often from talents). When a character with Soak takes Vitality damage from an attack, the damage is reduced by their Soak value.
* **Stunned**: While Stunned, you are overwhelmed and cannot act effectively. You lose any Reactions you have, and on your turn, you gain two fewer action points (►►).
* **Surprised**: While Surprised at the start of combat, you lose any Reactions you have. On your first turn, you cannot take a Fast Turn and you gain one fewer action point (►). This condition is removed after you take your first turn.
* **Target Number (TN)**: The number on a d100 that a player must roll equal to or greater than to succeed on an action.
* **Tier of Play**: A range of character levels (e.g., Tier 1 is Levels 1-5) that defines the general scope of their adventures and the size of their Recovery Dice pool.
* **Trauma**: A mental Wound a character receives when their Clarity pool is reduced to 0.
* **Unconscious**: While Unconscious, you are incapacitated. Your movement speed is 0, you fall **Prone**, and you drop anything you are holding. You are unaware of your surroundings and cannot communicate or take any actions or Reactions. A PC can choose to regain consciousness with 1 Vitality at the end of one of their turns.
* **Vitality**: A Health Pool representing a character's physical health and stamina.
* **Wealth**: An abstract rank from 0 to 5 that represents a character's purchasing power and ability to acquire goods without tracking currency.
* **Wound**: A general term for the consequences of a Health Pool being reduced to 0. Wounds are categorized as Injuries, Burdens, and Traumas.