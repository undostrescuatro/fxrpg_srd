---
title: Hazards
parent: Rules
nav_order: 13
---

# Hazards

## Table of Contents

- [Hazards](#hazards)
  - [Table of Contents](#table-of-contents)
  - [Obscurement, Brightness, and Darkness](#obscurement-brightness-and-darkness)
    - [Attacking Light Sources](#attacking-light-sources)
  - [Cover](#cover)
  - [Soft Exposure](#soft-exposure)
  - [Harsh Exposure (Fire, Freeze, Chemical, Electricity, and High Pressure)](#harsh-exposure-fire-freeze-chemical-electricity-and-high-pressure)
    - [🔥 Fire Exposure](#-fire-exposure)
    - [❄️ Freeze Exposure](#️-freeze-exposure)
    - [☣️ Chemical Exposure](#️-chemical-exposure)
    - [⚡ Electrical Exposure](#-electrical-exposure)
    - [💨 Exposure](#-exposure)
  - [Oxygen](#oxygen)
  - [Air Contamination](#air-contamination)
  - [Low Pressure](#low-pressure)
  - [Vacuum](#vacuum)
  - [Radiation](#radiation)

## Obscurement, Brightness, and Darkness

Visibility is handled by Obscurement conditions. It affects how easily a characters can target an Opponent.

- Attack Modifiers apply the Defender's Visibility condition.
- Defense Modifier apply the Defender's Visibility condition.

For Example:

- An Attacker in darkness

| Lighting         | Attack Modifier | Defense Modifier |
| ---------------- | --------------- | ---------------- |
| Minor Brightness | -1              | -1               |
| Mayor Brightness | -2              | -2               |
| Total Brightness | -3              | -3               |

| Darkness       | Attack Modifier | Defense Modifier |
| -------------- | --------------- | ---------------- |
| Minor Darkness | -1              | +1               |
| Mayor Darkness | -2              | +2               |
| Total Darkness | -3              | +3               |

| Obscurement       | Attack Modifier | Defense Modifier |
| ----------------- | --------------- | ---------------- |
| Minor Obscurement | 0               | +1               |
| Mayor Obscurement | 0               | +2               |
| Total Obscurement | 0               | +3               |

If the target is being in total darkness or brightness targeting body parts is impossible, the target of the attack is a random (see the random targeting section).

### Attacking Light Sources

Light sources can be targeted using the standard targeting rules. If a target is carrying a light source it can be attacked at no penalty but it is considered under total brightness for targeting body parts.

## Cover

Cover Works like armor and protects any part of the body that it covers.

To attack while behind cover:

- Expose your head to see the target.
- Expose the hands required to manipulate the weapon.

Targeting someone behind cover:

- Aim for an exposed location, use targeting rules to avoid shooting covered parts.
- Attack randomly, if you hit a covered location, add Cover to the Defender's Armor.

Some cover can also grant obscurement. For example:

- Bulletproof Glass: Armor only.
- Obscurement: tinted glasses foliage.

Most pieces of cover grant enough armor that a hit on the covered part can simply be ignored, things like buildings, and in cinematic cases, vehicles.

If Damage exceeds the armor of a section, it creates a hole, for every multiplier of the Armor Rating the size of the hole increases by the multiplier accordingly. Generally bullets produce holes at around 1CM but larger projectiles produce larger holes.

**_Common Materials_**

| Location                  | Wall Armor |
| ------------------------- | ---------- |
| Decorative Walls, Drywall | 1-3~       |
| Cinder Blocks,            | 5~         |
| Door Wood & Metal         | 7~         |
| Behind Vehicles Chassis   | 10~        |
| Behind Vehicle Motor      | 15~        |
| Thin Concrete             | 15~        |
| Planter                   | 20~        |
| Concrete Wall             | 30~        |
| Sandbags                  | 35~        |

**_Space Stations_**

| Location      | Wall Armor | Door Armor | Bulkhead Armor | By Volume $m^{3}$ |
| ------------- | ---------- | ---------- | -------------- | ----------------- |
| Airlock       | 15         | 15         | 20             | 20                |
| Room          | 15         | 10         | 25             | 200               |
| Hangar        | 20         | 20         | 40             | 5000              |
| Space Station | 500        | 350        | 1000           | $4*10^{10}$       |

## Soft Exposure

Slow and progressive changes in temperature, pressure, and other conditions is represented using fatigue. Extreme temperatures as special damage sources with different rules (see Fire, Freeze, Chemical, and Electricity).

## Harsh Exposure (Fire, Freeze, Chemical, Electricity, and High Pressure)

When a character is exposed in a harsh manner to the environment, They suffer an Enabled Attack.

Each turn of exposure counts as a separate Attack with the following attributes:

- Damage Multiplier (xDR): Source intensity.
- Dice Rolled: Seconds of contact.
- The Defender's Enabled Defense is their Constitution Attribute (CON).

In case no wound is produced by the attack, the character is aware of the danger and is free to choose whether to move away from the source or remain in contact.

Critical wounds can instantly kill the characters as per the regular rules. If they survive then use the described effect.

### 🔥 Fire Exposure

| Intensity | Example                               |
| --------- | ------------------------------------- |
| 1         | Candle, lighter, match                |
| 2         | Lamp (gas or oil)                     |
| 4         | Torch, gas stove                      |
| 6         | Campfire, flare, blowtorch            |
| 8         | Bonfire, napalm, incendiary Grenade   |
| 10        | Chemical fire, white Phosphorous      |
| 20        | Deep space sunlight (vacuum exposure) |
| 30        | Plasma jet, molted metal              |
| 40        | Reentry heat, volcanic vent           |
| 100       | Nuclear strike blast                  |
| 1000      | Nuclear strike ground zero            |

| Wound    | Effect                                                                                                                                | Description                                                                       |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| Light    | flinches away from the source                                                                                                         | Superficial wounds and blistering, reddened skin. Movement of the area is painful |
| Heavy    | Desperate lash out, painful scream, must cool down                                                                                    | Deep burns, cracked and blackened skin. Pain radiated trough the area             |
| Critical | Character collapses, writhes in pain, instinctively rolls on the floor but is not aware if they are moving away from the fire or not. | Flesh charred or melting, Numbing agony, Unconsciousness.                         |

### ❄️ Freeze Exposure

| Intensity | Example                                 |
| --------- | --------------------------------------- |
| 1         | Dry ice contact                         |
| 2         | Ice bath, freezer contact               |
| 4         | Arctic air exposure                     |
| 6         | Poured liquid nitrogen                  |
| 8         | Extreme windchill, direct cryogenic jet |
| 10        | Submerged in liquid nitrogen            |
| 20        | Deep-Space cold (vacuum exposure)       |
| 30        | Cryogenic rupture, coolant explosion    |
| 40        | Super fluid leak, rapid pressure drop.  |
| 100       | Matter flash frozen instantly           |
| 1000      | true 0                                  |

| Wound    | Effect                                                         | Description                                                                    |
| -------- | -------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| Light    | Shakes or rub the affected area, movement slows, grip weakens. | Frostbite forming in the area, numbness, and stiffness.                        |
| Heavy    | Uncontrollable Trembling, slurred speech, difficulty thinking. | Deep frostbite, joints barely respond, blue, or gray skin.                     |
| Critical | Collapse into torpor. Mobility, and coordination lost.         | Tissue frozen solid, immobile limbs, veins dark beneath skin. Unconsciousness. |

### ☣️ Chemical Exposure

Chemicals include both acids and basic compounds.

| Intensity | Example                                     |
| --------- | ------------------------------------------- |
| 1         | Vinegar, Mild irritant                      |
| 2         | Weak acids (lemon juice, alcohol)           |
| 4         | Household cleaning agents (bleach, ammonia) |
| 6         | Industrial Acid/Base splashes               |
| 8         | Concentrated sulfuric/hydrochloride acid    |
| 10        | Strong industrial chemicals, oxidizers      |
| 20        | Corrosive plasma or acid gas clouds         |
| 30        | Chemical weapon (acid gas)                  |
| 40        | Hyper-corrosive experimental compound       |
| 100       | Energetic acid mist in explosion            |
| 1000      | Chemical detonation                         |

| Wound    | Effect                                          | Description                                                                                              |
| -------- | ----------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| Light    | Wipes or shakes area.                           | Mild chemical irritation, stinging, and reddening of skin.                                               |
| Heavy    | Panic, disoriented by pain.                     | Corrosive burns, or inhalation. Smoke and fumes cause cough and tears. Liquids cause burning irritation. |
| Critical | Convulsions, and clawing at the source in agony | Severe corrosion, flesh dissolves, lungs burn. Unconsciousness                                           |

### ⚡ Electrical Exposure

| Intensity | Example                             |
| --------- | ----------------------------------- |
| 1         | 12 volts (small battery)            |
| 2         | 24 volts (car battery)              |
| 4         | 110 volts (household)               |
| 6         | 220 volts (domestic main)           |
| 8         | 600 volts (transformer equipment)   |
| 10        | 1 Kv (power lines)                  |
| 20        | 10 Kv (power main discharge)        |
| 30        | 30 Kv (lightning discharge)         |
| 40        | 50 Kv (power plant fuse arc)        |
| 100       | 100 Kv (power plant direct current) |
| 1000      | Superconducting discharge           |

| Wound    | Effect                                                     | Description                                          |
| -------- | ---------------------------------------------------------- | ---------------------------------------------------- |
| Light    | Involuntary jerk, drops held objects, briefly disoriented. | Muscles twitch, minor burns at contact points.       |
| Heavy    | Uncontrollable spasms, cant let go of source.              | Muscles seize violently, nerves burn.                |
| Critical | Violent Convulsions, Collapse.                             | Hearth arrhythmia, nerves overload. Unconsciousness. |

### 💨 Exposure

| Intensity | Example                                                 |
| --------- | ------------------------------------------------------- |
| 1         | 1.5 atm Slightly pressurized room; minor ear discomfort |
| 2         | 2 atm 10m underwater (swimming pool depth)              |
| 4         | 4 atm 30m dive noticeable ear and chest compression     |
| 6         | 8 atm 70m dive serious Barotrauma risk                  |
| 8         | 16 atm Deep-sea submersible failure;                    |
| 10        | 32 atm Deep-mining collapse bones start to crack        |
| 20        | 64 atm submersible implosion near instant death         |
| 30        | 128 atm industrial press or reactor rupture             |
| 40        | 256 atm Deep-trench or super-dense environment          |
| 100       | 1000 atm abyssal trench or magical compression field    |
| 1000      | 10000 atm super-dense reactor or gravity core           |

| Intensity | Example                                                      |
| --------- | ------------------------------------------------------------ |
| 1         | 0.9 atm Mild altitude minor shortness of breath              |
| 2         | 0.7 atm High altitude city (~3000m)                          |
| 4         | 0.5 atm 5500m elevation, risk of hypoxia                     |
| 6         | 0.3 atm 10000m altitude, severe hypoxia without oxygen.      |
| 8         | 0.2 atm near space cabin leak, loss of consciousness         |
| 10        | 0.1 atm near vacuum exposure, rapid decompression effects    |
| 20        | 0.05 atm high stratosphere ebullism (boiling fluids) being   |
| 30        | 0.02 atm space Vacuum, unconscious in seconds                |
| 40        | 0.01 atm Outer space vacuum, heavy tissue swelling, hypoxia. |
| 100       | 0.001 deep space vacuum. Blood and gas boil instantly        |
| 1000      | 0 atm perfect vacuum, instant decompression and freezing     |

| Wound    | Effect            | Description                                                         |
| -------- | ----------------- | ------------------------------------------------------------------- |
| Light    | Barotrauma        | Ears and sinuses rupture, mild internal bleeding, breathing labored |
| Heavy    | Organ compression | Collapsed lung, ruptured vessels                                    |
| Critical | Internal rupture  | Massive crush trauma, instantaneous unconsciousness                 |

## Oxygen

Any situation involving oxygen deprivation or the loss of breathable atmosphere follows the drowning rules. If breathable air becomes unavailable. Calculate the available air in time for one person, then divide that by the number of occupants in the space.

The formula for breathable air is the following: Time (minutes) = 100 \* Volume (cubic meters) / Occupants

## Air Contamination

Situations dealing with the contamination of breathable atmospheres are treated using the fatigue rules. The referee determines the rate at which 1 point of fatigue is accumulated and rules accordingly.

## Low Pressure

Sudden decompression or loss of atmospheric pressure can injure or kill unprotected characters. The following table shows how long it takes for a room or compartment to fully lose pressure, based on its size and the hole causing the leak.

Location Size

| Hole Size | Airlock    | Room       | Ship       | Hangar      | Colony    |
| --------- | ---------- | ---------- | ---------- | ----------- | --------- |
| 0         | 1 day      | 4 days     | 8 days     | 12 days     | 120 years |
| 1         | 10 seconds | 60 seconds | 90 seconds | 120 seconds | 60 years  |
| 5         | 1 second   | 30 seconds | 60 seconds | 90 seconds  | 30 years  |
| 6         | 0 seconds  | 10 seconds | 30 seconds | 60 seconds  | 1 day     |
| 8         | 0 seconds  | 0 seconds  | 10 seconds | 30 seconds  | 1 hour    |

Every quarter of the total decompression time inflicts 5 points of fatigue, accumulating until all air is gone, then drowning starts.

## Vacuum

The Vacuum of space does not kill instantly. Humans can for roughly the same time as drowning allows.

- Holding breath during decompression causes the lungs to rupture, the character suffers a Heavy wound instantly.
- Exhaling during decompression prevents this damage. Knowing this is a Threshold 4 Knowledge Attribute Check or Threshold 2 Zero-G Skill Check. Halve thresholds if you are recalling this in a calm environment.

Temperature effects in Vacuum are handled as Fire or Freeze Hazards, but measured in 10 seconds instead of seconds. Direct sunlight causes fire exposure, while Cold vacuum of space causes Freeze exposure.

## Radiation

Radiation becomes relevant when characters are exposed to short burst of intense radiation capable of causing immediate tissue injury. Test once per exposure, after the exposure ends for the most severe effect the situation could cause.

Test: Constitution Attribute Test.
Success: Apply only one effect above the tested level (without nausea)
Failure: Apply the listed effect.
Fumbles: Apply one effect below the tested level.

| Rads     | Th  | Onset            | Duration        | Nausea | Impairment              | Injury         |
| -------- | --- | ---------------- | --------------- | ------ | ----------------------- | -------------- |
| 000-100  | 1   | No               | No              | No     | No                      | No             |
| 101-200  | 3   | 1d6 Hours        | 1 full day 4d6  | Yes    | No impairment           | Light Wound    |
| 201-600  | 4   | 4d6 \*10 Minutes | 1 full day 4d6  | Yes    | -1 to mental attributes | Light Wound    |
| 601-800  | 5   | 2d6 \*10 Minutes | 2 full days 8d6 | Yes    | -2 to mental attributes | Heavy Wound    |
| 800-1000 | 6   | 1d6 \*10 Minutes | 2 full days 8d6 | Yes    | -3 to mental attributes | Critical Wound |
| 1000<    | 6   | 1d6 \*10 Minutes | 2 full days 8d6 | Yes    | Unconsciousness         | Death          |

Long term risk: every 100 rads add a 10% chance of developing cancer or a related chronic illness.
Protective Gear: Radiation suits, shielding, or bulkhead plating list protection values in Rads per minute. Subtract this value from total Exposure to determine the effective dose.
