---
title: Character Creation
parent: Rules
nav_order: 3
---

# Character Creation

## Table of Contents

- [Character Creation](#character-creation)
  - [Table of Contents](#table-of-contents)
  - [Attribute, Skills, and Complexity](#attribute-skills-and-complexity)
  - [Purchasing Primary Attributes](#purchasing-primary-attributes)
  - [Calculating Action Mode Attributes](#calculating-action-mode-attributes)
  - [Purchasing Skill](#purchasing-skill)
    - [Skill Specializations](#skill-specializations)
  - [Purchasing Complexity](#purchasing-complexity)
  - [Acquiring SpecialFx](#acquiring-specialfx)
  - [Character Improvement](#character-improvement)
    - [Attribute Improvement](#attribute-improvement)
    - [Skill Improvement](#skill-improvement)
    - [Complexity Improvement](#complexity-improvement)
    - [Evasion Improvement](#evasion-improvement)

## Attribute, Skills, and Complexity

Characters are built using two types of points:

- Attribute Points (ATP): Used to buy Physical capabilities.
- Experience Points (EXP): Used to buy Skills and SpecialFx.

The number of starting points depends on the tone of the Chronicle and the Referee's preferences. The Referee also sets the character's initial Evasion 'EVA' value.

| Gritty Type      | ATP | EXP | EVA |
| ---------------- | --- | --- | --- |
| Player Character | 20  | 60  | 1   |
| Average NPC      | 10  | 30  | 1   |
| Major NPC        | 20  | 90  | 1   |

| Adventurous Type | ATP | EXP | EVA |
| ---------------- | --- | --- | --- |
| Player Character | 30  | 80  | 2   |
| Average NPC      | 10  | 40  | 1   |
| Major NPC        | 30  | 120 | 2   |

| Cinematic Type   | ATP | EXP | EVA |
| ---------------- | --- | --- | --- |
| Player Character | 50  | 90  | 3   |
| Average NPC      | 10  | 40  | 1   |
| Major NPC        | 50  | 150 | 3   |

## Purchasing Primary Attributes

Players spend Attribute Points (ATP) to define their characters' physical and Mental capabilities. All ten primary Attributes must have some rating.

- Normal humans cannot have attributes above '+3' or below '-3'. Ratings above or below this range represent superhuman or crippled extremes.

| Rating | AP Cost | Definition              |
| ------ | ------- | ----------------------- |
| -3     | -4      | Crippling Disability    |
| -2     | -1      | Clear Disability        |
| -1     | 0       | Recognizable impediment |
| 0      | 1       | Human Average           |
| 1      | 4       | Recognizable Talent     |
| 2      | 9       | Competitive Talent      |
| 3      | 16      | World Renowned Talent   |

To calculate Attribute cost beyond ±3 range, use:

- Cost = $(Rating+1)^2$
- Negative ratings return points instead of costing points.

Any unused Attribute Points are converted to Experience points at a rate of:

- 1ATP = 5EXP

After purchasing Primary Attributes, Calculate Action Attributes using their formulas.

## Calculating Action Mode Attributes

| Character Attributes | Formula                                           |
| -------------------- | ------------------------------------------------- |
| BL                   | Match FIT Rating to the CON Table, get the weight |
| EVA                  | Initial level defined by Referee                  |
| INI                  | $4+AGI+CRE+SEN+INS$                               |

| Attack Damage | Formula     |
| ------------- | ----------- |
| TBD           | $4+CON+AGI$ |
| GBD           | $4+AGI+FIT$ |
| SBD           | $4+FIT+CON$ |

| Biological Defense | Formula                      |
| ------------------ | ---------------------------- |
| TGH                | $25+(CON*3)+(FIT*4)+(AGI*2)$ |
| PHT                | $6+CON$, Minimum 1           |
| LWT                | $TGH/2$, Round up            |
| HWT                | $TGH$                        |
| CWT                | $TGH*2$                      |

| Mental Defense | Formula                      |
| -------------- | ---------------------------- |
| DET            | $25+(FOC*4)+(CHA*3)+(INS*2)$ |
| MHT            | $6+FOC$, Minimum 1           |
| LAT            | $DET/2$, Round up            |
| HAT            | $DET$                        |
| CAT            | $DET*2$                      |

## Purchasing Skill

Players Buy Skill Levels using Experience Points (EXP), they are assigned by the Referee at the start of the Chronicle, or gained throughout play. The cost of each level is equal to its value squared. The total cost is cumulative, meaning you must pay for every level up to the desired one.

| Skill Lvl | Cost  | Cumulative cost     |
| --------- | ----- | ------------------- |
| 1         | 1     | 1                   |
| 2         | 4     | 5                   |
| 3         | 9     | 14                  |
| 4         | 16    | 30                  |
| 5         | 25    | 55                  |
| 6         | 36    | 91                  |
| 7         | 49    | 140                 |
| 8         | 64    | 204                 |
| 9         | 81    | 285                 |
| 10        | 100   | 385                 |
| $x$       | $x^2$ | $\sum_{n=1}^{x}n^2$ |

{: .example }
To reach Lvl 3 you pay. 1 (for Lvl 1) + 4 (for Lvl 2) + 9 (for Lvl 3) = 14 EXP total.

{: .note }

> Skill Advancement is intentionally slow for balance reasons:
>
> - Each extra dice grants a smaller performance gain due to diminishing returns.
> - Levels around 3 provide a strong advantage at a manageable cost.
> - Core skills are typically around Level 2.
> - Hobby or casual Skills are typically around Level 1.

### Skill Specializations

A character may purchase a Skill Specialization for 5 Experience Points. Each Specialization grants a +1 bonus to Skill Tests made under specific conditions. A character may purchase multiple Specializations within the same Skill, but only one specialization bonus can apply to a single roll.

Generally this represents a higher focus on specific equipment or techniques.

## Purchasing Complexity

Complexity (CPX) represents a character's formal training or academic understanding of a Skill. Players buy CPX levels by using Experience Points (EXP). The cost of each level is the value squared then multiplied by 3. The cost is cumulative, meaning you must pay for every level up to the one desired.

| CPX Lvl | Cost | Cumulative cost |
| ------- | ---- | --------------- |
| 0       | Free | 0               |
| 1       | 3    | 3               |
| 2       | 12   | 15              |
| 3       | 27   | 42              |
| 4       | 48   | 90              |
| 5       | 75   | 165             |

{: .example }
To reach CPX 2, you must pay for CPX 1 (3 EXP) and CPX 2 (12 EXP). 3+12 = 15 Total.

## Acquiring SpecialFx

SpecialFx represent traits, conditions, or unique abilities that modify what a character can or cannot do. They are bought with Experience Points (EXP).

- Positive-cost SpecialFx expands a character's capabilities and must be paid with EXP.
- Negative-cost SpecialFx impose limitations to a character's capabilities and refund EXP equal to their cost. Players may spend those refunded points elsewhere.

{: .note }
To maintain balance, a character's total SpecialFx (positive or negative) should not exceed double their Attribute Point (ATP) total. This is a guideline not a rule, the Referee has final approval over SpecialFx to ensure they align with the tone and logic of the Chronicle.

## Character Improvement

Character Improvement is one of the most rewarding aspects of play. As characters overcome challenges, they gain Experience Points (EXP), which can be spent to enhance their abilities, learn new skills or refine existing ones.

{: .note }
Generally EXP is gained trough Edge Dice. But the referee may choose to award EXP by other means.

### Attribute Improvement

Attributes rarely change over a character's lifetime. Improving them is possible but costly, reflecting the time and dedication required.

- Cost: 100 EXP per Attribute rating increase.
- Limits: Each Attribute can only be raised up to three times, and never beyond the -3 to +3 range, unless the character becomes superhuman.
- Players should provide narrative justification for Attribute Growth. For Example: Training, studying, or rehabilitation.

Recommended investment for attribute growth:

- One year of part time effort.
- 6 months of full-time training.

| Attribute    | Activity Required                                                    |
| ------------ | -------------------------------------------------------------------- |
| Agility      | Stunts, pirouettes, and juggling exercises.                          |
| Constitution | A diet plan.                                                         |
| Fitness      | Endurance workout, running, swimming, cardio.                        |
| Appearance   | Posture work, walking drills, voice training, and personal grooming. |
| Sense        | Meditation and awareness training.                                   |
| Creativity   | Timed puzzles and problem solving drills.                            |
| Knowledge    | Retention and memorization drills.                                   |
| Focus        | Meditation and introspection.                                        |
| Charisma     | Socialization, interaction, and group involvement.                   |
| Instinct     | Therapy, mindfulness, and sensitivity training.                      |

### Skill Improvement

Skills are easier to advance than Attributes. Improvement requires consistent practice or in-game use.

- Recommended training time: EXP cost in weeks of practice.

### Complexity Improvement

Raising a Skill's Complexity represent a deeper understanding of formal training in the subject. It is slower than Skill advancement and usually requires extended study or mentorship.

- Recommended training time: EXP cost in weeks of formal training.

### Evasion Improvement

Evasion measures a character's Ability to anticipate and avoid danger, not just react to it. It is the only Action Attribute that can be improved after character creation.

- Starting evasion is set by the referee at the beginning of the Chronicle.
- Cost: Each new level cost the Level cubed in EXP.
- Limits: Evasion can only be raised two levels above the starting value.

| Evasion Lvl | Cost                                |
| ----------- | ----------------------------------- |
| 1           | Always Free                         |
| 2           | 8 or Free in adventurous chronicles |
| 3           | 27 or Free in cinematic chronicles  |
| 4           | 64                                  |
| 5           | 125                                 |
