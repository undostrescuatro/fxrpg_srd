---
title: Machine Damage Interaction
parent: Rules
nav_order: 11
---

# Machine Damage Interaction

## Table of Contents

- [Machine Damage Interaction](#machine-damage-interaction)
  - [Table of Contents](#table-of-contents)
  - [Machine Integrity \& Damage Thresholds](#machine-integrity--damage-thresholds)
  - [Effects of Damage](#effects-of-damage)
    - [Structure](#structure)
    - [Weapon Systems](#weapon-systems)
    - [Movement](#movement)
    - [Auxiliary Systems](#auxiliary-systems)
    - [Fire Control](#fire-control)
    - [Crew](#crew)
    - [Avoiding Failure Locations](#avoiding-failure-locations)
    - [Nonlethal Damage on Machines](#nonlethal-damage-on-machines)
    - [Damage Tracking](#damage-tracking)
  - [Machine Integrity Collapse](#machine-integrity-collapse)
  - [Machine Destruction](#machine-destruction)

## Machine Integrity & Damage Thresholds

Machine Integrity is defined by the Machine's Toughness Attribute. For Machine Damage the integrity is affected by Failures.

Failures are divided into three Thresholds:

| Failure  | Threshold | Description                                      |
| -------- | --------- | ------------------------------------------------ |
| Light    | 0.5\*TGH  | Minor Failure, reduced efficiency.               |
| Heavy    | TGH       | Major Failure, damage systems.                   |
| Critical | 2\*TGH    | Catastrophic Failure, complete system breakdown. |

## Effects of Damage

When a machine get a Failure, the Referee determines which subsystem is affected by rolling 2d6 and consulting the table bellow:

| Result | Location         |
| ------ | ---------------- |
| 2      | Crew             |
| 3      | Fire Control     |
| 4      | Auxiliary System |
| 5      | Movement         |
| 6      | Weapon System    |
| 7      | Structure        |
| 8      | Weapon System    |
| 9      | Movement         |
| 10     | Auxiliary System |
| 11     | Fire Control     |
| 12     | Crew             |

Each location has different outcomes depending on the severity of the Failure:

### Structure

- Light: -1 TGH.
- Heavy: -2 TGH.
- Critical: Machine Totaled, no damage to crew.

### Weapon Systems

- Light: -1 to a weapon.
- Heavy: One weapon destroyed.
- Critical: One weapon destroyed, ammunition explodes, the machine takes light damage.

### Movement

- Light: One Movement type reduced to combat speed max.
- Heavy: One Movement destroyed.
- Critical: Transmission Failure, Immobile.

### Auxiliary Systems

- Light: -1 to one Auxiliary system.
- Heavy: One Auxiliary system destroyed.
- Critical: 1d6 Auxiliary systems destroyed.

### Fire Control

- Light: -1D to fire control, Minimum 0.
- Heavy: Fire Control destroyed, Cannot take Aim Action.
- Critical: Ammunition destroyed (all weapons), Machine takes Heavy damage.

### Crew

- Light: Crew stunned 1d6 turns.
- Heavy: 10% Casualties, minimum 1.
- Critical: All crew dead.

The Referee may optionally transfer the Crew Failure level directly as a Wound level to machines piloted by Player Characters.

### Avoiding Failure Locations

To avoid damaging a specific location, a character can use the Aim Action. The Attacker sacrifices one die gained from aiming to exclude one location from the hit roll (for example, avoiding the Crew compartment). If the location roll results in the avoided area, reroll.

To intentionally target a system, use the standard Targeting rules.

### Nonlethal Damage on Machines

Machines are immune to nonlethal damage, Such impacts represent only scratches, dents, or superficial scarring of the chassis.

### Damage Tracking

Machines do not suffer like living characters. They have no blood or organs that fail under stress. Instead, damage affects their systems directly, reducing performance until a component fails or the machine becomes inoperable.

They do not suffer:

- Damage Stabilization
- Damage Destabilization
- Damage Deterioration
- Damage Recovery

## Machine Integrity Collapse

Machine Integrity Collapse simply happens as each subsystem becomes inoperable. But a Machine cannot be overwhelmed from loosing too many systems.

## Machine Destruction

Destruction happens only on the Critical Failure on the Structure subsystem.
