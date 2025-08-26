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