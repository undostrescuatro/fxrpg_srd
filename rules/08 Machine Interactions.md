---
title: Machine Interactions
parent: Rules
nav_order: 8
---

# Machine Interactions

## Table of Contents

- [Machine Interactions](#machine-interactions)
  - [Table of Contents](#table-of-contents)
  - [Abstracted Crew Actions](#abstracted-crew-actions)
  - [Changing Movement Systems](#changing-movement-systems)
  - [Towing Capacity](#towing-capacity)
    - [Aquatic Movement](#aquatic-movement)
  - [Underwater Movement](#underwater-movement)
    - [Turning](#turning)
  - [Atmospheric Movement](#atmospheric-movement)
    - [Altitude](#altitude)
    - [Falling and Stalling](#falling-and-stalling)
    - [Atmospheric Maneuvers](#atmospheric-maneuvers)
      - [Sidestep](#sidestep)
      - [Atmospheric Turning](#atmospheric-turning)
      - [Tight Turn](#tight-turn)
      - [Gliding](#gliding)
      - [Atmospheric Diving](#atmospheric-diving)
    - [Atmospheric Pilot Fumbles](#atmospheric-pilot-fumbles)
    - [Flying with Space Movement](#flying-with-space-movement)
  - [Space Movement](#space-movement)
    - [Acceleration](#acceleration)
    - [Vectors](#vectors)
      - [Facing](#facing)
    - [Thrust](#thrust)
    - [Reaction Mass](#reaction-mass)
    - [Gravitational Effects](#gravitational-effects)
    - [Reaching Orbit](#reaching-orbit)
    - [Orbital Entry](#orbital-entry)

Used for engagements between mechanical entities like vehicles, mechs, drones, and any type of machine that can perform these actions if constructed that way.

These rules are specifically designed to mirror those used for regular characters, maintaining consistent mechanics while only adding case specific exceptions.

For the sake of avoiding confusion machines will be referred by different names depending on their type of movement.

- Walker: Mech.
- Ground: Vehicle.
- Atmospheric: Aircraft.
- Water: Ship.
- Underwater: Submarine.
- Space: Spaceship.

## Abstracted Crew Actions

A machine can have a large crew and they can grant additional actions. For small crews each crew member gets one action related to their role in the machine. For example. a Driver drives, a gunner shoots, a loader reloads.

When vehicles and crews become too large, abstraction is necessary. The referee may consider these rules when combat scales with their increased time-frames is being used.

- Crew required = 2^(actions-1)
- Actions = 1+log₂(Crew Available)

| Crew | Actions |
| ---- | ------- |
| 1    | 1       |
| 2    | 2       |
| 4    | 3       |
| 8    | 4       |
| 16   | 5       |
| 32   | 6       |
| 64   | 7       |
| 128  | 8       |
| 256  | 9       |
| 512  | 10      |

Crew Actions Limits:

- Each equipment can only be activated once.
- An equipment cannot Attack while performing the Aim Action.
- The Full Attack and Full Defense actions is unavailable to machines with crews larger than 1.
- The Vehicle can only move once.

## Changing Movement Systems

Machines equipped with multiple movement systems may switch between them while operating at Combat Speed or lower. A machine can only switch types once per turn.

During the Transition:

- The initial movement type determines the total available movement for that turn.
- The movement cost may change after the movement type has changed.

## Towing Capacity

Machines follow the same principles as character for pulling and dragging. The value of their Basic lift differs depending on their Movement type.

- Ground: Basic Lift = Mass.
- Atmospheric: Basic Lift = Mass\*0.5.
- Space: Loaded Thrust = (Spaceship Mass \* MP)/(Spaceship Mass + Cargo Mass)

Cargo must fit within the machine, or use some equipment to connect it to the machine.

Space has no basic lift since space has no drag. The limitations of towing are purely based on thrust to gain speed.

### Aquatic Movement

Machines with the Water and Underwater movement type expend 1 Movement Point (MP) per Water surface or Liquid Hex.

Machines that are sealed against water but lack aquatic propulsion must either walk along the bottom or be towed in the surface.

## Underwater Movement

Submarines can change depth by spending additional Movement Points (MP).

- 2 MP per hex to ascend or descend normally.
- 0.1 MP per hex to perform an emergency surface.

Emergency buoyancy cannot be stopped until the surface is reached.

### Turning

A Submarines cannot turn freely and side changes requires 1 MP to power the appropriate thrusters.

## Atmospheric Movement

Atmospheric movement follows the same general principles as ground movement, with the addition of altitude levels to represent three dimensional positioning.

### Altitude

One altitude level is equal to one “hex” of elevation. Moving up or down, cost additional movement points as shown below. Machines must stay at one level of altitude above the ground or crash.

| Direction  | Cost |
| ---------- | ---- |
| Horizontal | 1    |
| Up         | 3    |
| Down       | 0.5  |

Terrain effects are ignored for Atmospheric movement, except when attacking ground targets ( for which Obscurement still applies). High terrain, such as mountains can also block line of sight between Atmospheric and ground units.

### Falling and Stalling

All Aircraft have a minimum airspeed (stall speed) that must be maintained to remain aloft. If at the end of a round an aircraft has not moved at least this amount, it begins to loose altitude equal to the difference between its current movement speed and its stall speed in MP.

To regain control a pilot must make a Piloting Skill test with a Threshold of 1 per each turn loosing altitude.

Success: The pilot regains control of the aircraft.
Failure: The aircraft continues to stall.

IF the pilot cannot met the threshold in any way the aircraft starts stalling.

### Atmospheric Maneuvers

#### Sidestep

- CPX 0

A pilot can change hexes left or right without changing facing, it costs 2 Movement per change. A pilot can choose to lose altitude to make the movement cheaper.

#### Atmospheric Turning

- CPX 0

- VTOL aircraft can change their facing using regular turning rules.
- Non-VTOL aircraft must travel straight 2 Hexes ad High Speed and 3 Hexes at Top Speed.

#### Tight Turn

A pilot can attempt to make a tighter Turn.

- Non-VTOL aircraft add 1 to the Threshold at High Speed and 2 at top speed.
- The Pilot must make Constitution (CON) Attribute test equal to the Turn Threshold to avoid loosing consciousness.

Result:

- Failure: Lose consciousness for 1 second.
- Fumbles: Lose consciousness for 1d6 seconds.

#### Gliding

- CPX 0

Each round an aircraft glides, it loses 2 points of speed or altitude levels (any combination). Should the aircraft’s speed fall below its Stall Speed, it will immediately stall and lose altitude levels accordingly. Gliding aircraft can use the diving maneuver to gain speed.

#### Atmospheric Diving

- CPX 1

A pilot can perform a controlled dive to gain speed or reposition:

- Spend MP equal to or greater than half the Combat Speed lowering altitude accordingly.
- Make a Threshold 4 Piloting Skill Test.

Results:

- Success: you regain control of the aircraft.
- Failure: you continue to fall.

### Atmospheric Pilot Fumbles

Whenever a pilot fails a maneuver,

- Roll 1D on the table
- Fumbles roll 2D

The Effects are cumulative when different, if the effect is the same only apply the worst one.

| Result+MoF | Effect                                      |
| ---------- | ------------------------------------------- |
| 1          | Pilot stunned                               |
| 2          | Forced sidestep left or right (1 Hex)       |
| 3          | Aircraft sidestep left or right (MoF hexes) |
| 4          | Loose altitude (1 level)                    |
| 5          | Loose altitude (1d6 levels)                 |
| 6          | Gains a Failure (light to structure)        |
| 7          | Aircraft Speed = Stall Speed                |
| 8          | Aircraft Speed = 0                          |
| 9          |                                             |
| 10         | Gain a Failure (Heavy to structure)         |
| 11         |                                             |
| 12         | Uncontrollable spin; must eject             |

### Flying with Space Movement

If an aircraft has a Space Movement Type capable of producing thrust greater than the planet's gravity, It can fly. After spending MP to counter gravity, the remaining MP can be used as Atmospheric Movement. This MP can be combined with another Atmospheric Movement Type.

## Space Movement

Space movement differs form ground and atmospheric because there is no friction or drag. Motion continues until acted up/on. Spaceships use Velocity Vectors and Reaction Mass to control their position and facing.

### Acceleration

The reduction in reaction mass does not increase the acceleration. Referees wanting a more realistic representation of space movement. Simply divide the Reaction mass by the Top Speed movement points. These are the stages, each time the reaction mass drops by 1 stage, increase the Top Speed by 1.

### Vectors

In space, All movement is tracked using Velocity Vectors. Each Spaceship records its current velocity on four axes:

- A, B, and C representing each of the three hex facings. (clockwise around the map).
- Z representing vertical movement up and down.

On their turn:

- Spaceship can use MP to alter any of the values.
- It moves a number of hexes equal to the updated values.

#### Facing

A Spaceship can freely rotate facing by spending Thrust. Facing is a Vector independent of speed. it can only have values of with their highest value being -1 or +1, it cannot have 0 in all its values as cannot be facing 0 sides.

To turn facing spend MP accordingly. Turning does not change velocity. Turning more than 60 degrees per turn at high speed uses the regular turning rules.

### Thrust

Space Movement Points are expressed as Thrust. Each MP spent on thrust allows changing the vector values by adding or subtracting. To break in space the Spaceship must make the vector equal 0 in all its values.

### Reaction Mass

When changing vector, each movement of Thrust spent removes one Reaction Mass. When the vehicle reaches zero Reaction Mass, it can no longer change its vector.

### Gravitational Effects

For simplicity, gravitational effects from nearby bodies are ignored during space combat. The levels of space acceleration are simply too high for gravity to meaningfully affect it.

For special scenarios the Referee could consider applying a gravitational pull as a form of an added or subtracted number to 1 vector. Consider small values so that spaceships can escape it even after taking some damage.

### Reaching Orbit

{: .note}
TO-DO

### Orbital Entry

A spaceship only need the thrust to come out of orbit, not for the reentry. The vehicle must be equipped with the Reentry Perk. If such a system is not present, the vehicle suffer a Fire attack. Reentry last until the spaceship can safely use another form of movement.
