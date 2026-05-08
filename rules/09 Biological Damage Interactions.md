---
title: Biological Damage
parent: Rules
nav_order: 9
---

# Biological Damage Interaction

## Table of Contents

- [Biological Damage Interaction](#biological-damage-interaction)
  - [Table of Contents](#table-of-contents)
  - [Integrity \& Damage Thresholds](#integrity--damage-thresholds)
  - [Damage Effects](#damage-effects)
    - [Trauma Test](#trauma-test)
      - [Stunned](#stunned)
      - [Incapacitated](#incapacitated)
  - [Biological Action Penalties](#biological-action-penalties)
  - [Wound Locations](#wound-locations)
  - [Damage Stabilization](#damage-stabilization)
  - [Damage Destabilization](#damage-destabilization)
  - [Damage Deterioration](#damage-deterioration)
  - [Damage Recovery](#damage-recovery)
    - [Without Medical Aid](#without-medical-aid)
    - [With Medical Aid](#with-medical-aid)
  - [Integrity Collapse](#integrity-collapse)
    - [Shock Trauma](#shock-trauma)
    - [Resuscitation](#resuscitation)
  - [Biological Destruction](#biological-destruction)
  - [Biological Damage Special Rules](#biological-damage-special-rules)
    - [Fatigue](#fatigue)
    - [Nonlethal Damage on Biological](#nonlethal-damage-on-biological)

## Integrity & Damage Thresholds

Biological Integrity is defined by the Character's Toughness Attribute. For Biological Damage The integrity is affected by Wounds.

Wound are divided into three Thresholds:

| Type     | Threshold | Description                   |
| -------- | --------- | ----------------------------- |
| Light    | 0.5\*TGH  | Nasty but not crippling.      |
| Heavy    | TGH       | Immediately life-threatening. |
| Critical | 2\*TGH    | Mortal, Survival is unlikely. |

## Damage Effects

A wound applies an Action Penalty (AP) and an effect:

| Wound    | AP  | Effect              | Description                                    |
| -------- | --- | ------------------- | ---------------------------------------------- |
| Light    | -1  | Can't Sprint or Run | Deep cuts, concussions, minor gunshots         |
| Heavy    | -2  | Can't jog           | Fractures, punctured organs, or blood vessels. |
| Critical | -3  | Must crawl          | Gruesome wounds, Destroyed organs, or limbs.   |

### Trauma Test

Any wound gained forces a Trauma Test.

- Threshold 0 Constitution Attribute Test.
- Modified by Action Penalty (AP).

| Wound Type | Failure       | Success       |
| ---------- | ------------- | ------------- |
| Light      | Stunned       | Nothing       |
| Heavy      | Incapacitated | Stunned       |
| Critical   | Dead          | Incapacitated |

#### Stunned

Character must pass another Trauma Test to act on their turn, Failing forces a Do Nothing Action. Regardless of result subsequent turns do not require testing until a new wound happens.

#### Incapacitated

The character becomes unconscious for duration based on wounds:

- Light: A quarter-hour time-frame (2d6+3 minutes).
- Heavy: A Half day time-frame (1d6 hours).
- Critical: A Week time-frame (1d+1 Days).

Add the times together to determine the total duration.

## Biological Action Penalties

AP is a penalty that applies globally to all the rolls of the affected character as the injury and pain does not let them act properly. They stacks cumulatively.

Tracking Biological Damage Action Penalties is done using the Biological Health Tracker (BHT). Wounds are tracked individually as they heal or worsen independent of each other.

## Wound Locations

- Torso uses Standard Thresholds. Halve Thresholds to Vitals, Limbs, and Extremities (armor is not halved).
- Limbs (arms, legs): 2 Light wounds or 1 Heavy wound incapacitates a limb (cannot be used).
- Extremities (hands, feet): 1 Light wound or 1 Heavy wound incapacitates the extremity (cannot be used)
- Critical wounds to Limbs or Extremities are treated as a Heavy wound, and the Limb or Extremity is destroyed.

The type of damage contextualizes the outcome: Crushing, Severing, Shattering, etc. Destroyed Limbs or Extremities are considered no longer part of the main body (even if they are visually attached).

## Damage Stabilization

To stabilize one wound a medic must pass a Threshold 0 Medicine Skill. Modified by the following:

- Patient’s Constitution Attribute (CON).
- Patient's Action Penalty (AP).

Result:

- Success: Stabilize the worst wound first. Stabilized wounds do not deteriorate.
- Failure: A quarter-hour time-frame passes (2d6+3 minutes).
- Fumbles: Create an additional Light wound.

A medic treating themselves is penalized twice. Once as an injured medic and once as an injured patient.

## Damage Destabilization

Stabilized wounds can be destabilized.

- Light: Destabilized by any heavy activity (including close combat).
- Heavy: Destabilized by anything greater than minimal activity (bed rest, feeding, bathroom, and little else).
- Critical: Destabilized by anything greater than bed rest.

Destabilized wounds begin deteriorating until they are stabilized again. Cinematic games may choose to ignore wound destabilization.

## Damage Deterioration

Destabilized wounds if left untreated, will deteriorate. Each wound has an onset period in which it will be Tested:

- Light: daily.
- Heavy: Hourly.
- Critical: every minute.

Deterioration Test:

- Threshold 0 Constitution Attribute Test.
- Success: The wound does not worsen.
- Failure: The wound worsens to its next level.
- Fumbles: The wound worsens to its next level, and a new light wound is gained.

Considerations:

- Wounds do not deteriorate during medical treatment.
- A Critical wound deterioration causes the character to die.
- Wound deterioration raises AP and can bring a character into Shock Trauma.

## Damage Recovery

Recovery speed depends on care level. All wounds recover at the same time.

### Without Medical Aid

- Light: 1 week.
- Heavy: 4 weeks, and causes the Crippled (-1) SpecialFx until treated.
- Critical: 8 weeks, and causes the Crippled (-1) SpecialFx until treated. can also cause an additional SpecialFx depending on the nature of the wound at the Referee's discretion.

### With Medical Aid

- Halve the Without Medical Aid recovery times.

## Integrity Collapse

Biological Integrity Collapse happens when the body has acquired too many wounds and goes into shock trauma.

### Shock Trauma

A character enters Shock Trauma when their Biological Health Tracker (BHT) value is reduced to 0 by Action Penalties (AP), Shock Trauma initiates a countdown to death:

- Time to death: $(2*PHT-AP)*60seconds$

Characters with medical skills recognize shock trauma for free, others must make a Threshold 6 Untrained Medicine (KNO) Test to recognize Shock Trauma and act accordingly.

### Resuscitation

Resuscitation is a special stabilization test.

- Success: As per Stabilization rules.
- Failure: As per Stabilization rules, reduce the time to death by the Degree of Failure.
- Fumbles: Patient dies.

If a successful resuscitation do not reduce the AP so that PHT goes above 0, Additional resuscitation is required. Recalculate the time to death accordingly. Continue until the character is resuscitated or dead.

## Biological Destruction

Biological Destruction is represented by Death, it occurs by:

- Failing a Trauma Test when gaining a critical wound.
- Reaching the Time to Death during Shock Trauma.

Certain circumstances may instantly kill a character as determined by logic. Death can also be dealt with depending on the Chronicle. For example: Magic, cloning, etc.

## Biological Damage Special Rules

### Fatigue

Fatigue is tracked as a Damage Rating (xDR) value, separate from wounds, it begins at 0xDR and increases when a character endures prolonged exertion.

- After Combat you gain fatigue equal to the number of turns taken.
- Other situations can also make a character gain fatigue.
- Fatigue xDR naturally falls by 1 per hour of rest or 2 per hour of sleep.

After exerting effort a second after the first (2 seconds), test for Fatigue.

Fatigue test:

- Fatigue makes an Enabled Attack with a number of dice equal to the seconds of exertion, and xDR equal to the Tacked Fatigue.
- The character Enabled Defense uses the Constitution Attribute.
- Fatigue wounds are stable and do not deteriorate.

| Fatigue | Source |
| ------- | ------ |
| 1       |        |
| 2       |        |
| 3       |        |
| 4       |        |
| 5       |        |
| 6       |        |
| 7       |        |
| 8       |        |
| 9       |        |
| 10      |        |
| 20      |        |
| 25      |        |
| 50      |        |
| 100     |        |

### Nonlethal Damage on Biological

Experienced fighters can choose to make nonlethal damage with the following properties:

- Untrained Skills cannot do nonlethal damage.
- Some Weapons can do nonlethal damage.
- Enabled Attacks add to the Fatigue tracker instead of wounding.
- A successful Attack forces a Fatigue Test on the Defender.

| Nonlethal Wound | Intensity | Effect      |
| --------------- | --------- | ----------- |
| Light           | 1         | +4 Fatigue  |
| Heavy           | 2         | +8 Fatigue  |
| Critical        | 3         | +16 Fatigue |
