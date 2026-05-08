---
title : Machine Creation
parent: Creation
nav_order: 2
---
# Machine Creation

The machine creation system works differently than the character creation one. In character creation to prioritize the creation of characters that are “balanced”, characters are assigned point values in order when compared one to another. This is to ensure that one character does not steal the spotlight from others. But the process of creating machines works in reverse. Machines are created with a purpose first, and depending on the technology, they are often unbalanced to the point of performing their respective tasks with efficiency and precision in mind while ignoring other areas of their design. The reason for reversing this process is to ensure flexibility in the creation process, allowing you to create hyper specialized machines while worrying about balancing point values later. This design process also allows you to focus on the real capabilities of the machine instead of worrying about an efficient way of spending points to get the machine you want. Rules wise as a designer you should worry about what it can and can't do, and then calculate their point value for last to get a glimpse of how it would fare against other machines.

Nothing besides common sense prevents you from designing a machine with many weapons crammed into a tiny vehicle. Remember, each choice you make affects your chronicle.

### The Machine Concept

The first step of designing a machine should be to define its purpose, what kind of machine is it? Is it a vehicle, is it a stationary machine, is it a tool or a weapon?

Next you should try to translate said purpose into Ratings and Attributes. A weapon would have a damage rating, a vehicle would have a speed rating, a tank would have a high Toughness rating. Remember to use common sense and keep the final costs in mind as it will increase the better they are.

Try to use real machines as guidelines, during this section you will find aids that will help you translate some real life measurements into game mechanics.

### The Power Plant

FxRPG does not concern itself with power plants, it is assumed that the engineers that build this machine provided it with a system that is designed to provide sufficient power to all its components. The way a power plant works is left to the description of the Referee and the chronicle being run.

Special power plant cases can be implemented through the use of SpecialFx.

### Attributes

#### Size

Size is an Abstract measurement of the relation between the machine’s Volume, Mass and, how it is built. It also determines the damage it will cause on a collision. Machines that occupy more or less space than average are detailed with the use of SpecialFx.

Machines require a volume for access and maintenance, This is done to determine if a machine would fit properly in certain spaces. Ultimately it has no bearing in the game mechanics, and it is used for consistency purposes.

Volume= $(0.5*Size+1)^3$

#### Mass

The size of a machine can be calculated based on its mass in Kilograms by using the following formula:

$Size = ((Mass(kg)^\frac{1}{3})/3)-0.5$

Inversely The maximum mass a machine can have is calculated by reversing the formula:

$Mass(kg) = ((Size+0.5)*3)^3$

In both cases the Size value should be rounded for simplicity.

Remember that Size is a general representation of volume, mass, and sizes, certain examples can have larger volumes with less mass while others have more mass and less volume, keep that in mind when designing your machine.

### Decimal Size Scores

If the game master feels that the Size ranges cover a range too broad, the recommended solution is to use decimals and simply divide the range into smaller equally sized ranges. When test are made that require a machine's size rating, simply use the fraction to calculate the modifiers for a size difference.

### Toughness

A Machine’s Toughness rating defines how resistant to damage the machine is, it is an abstraction of the thickness and position of the external plating as well as the resistance of the inner components. The minimum value of Toughness rating is 1 and Toughness can be affected by specific SpecialFx. This rating works similarly to a character’s Toughness.

The toughness of a machine can be related to its build quality and armored construction. The following table gives a general guideline as to how much toughness a machine should have.

Toughness General Guideline Table

| General Reinforcement | General Toughness     |
| --------------------- | --------------------- |
| Flimsy Unarmored      | $\simeq 1*SizeRating$ |
| Normal Unarmored      | $\simeq 2*SizeRating$ |
| Though Unarmored      | $\simeq 3*SizeRating$ |
| Light Armored         | $\simeq 4*SizeRating$ |
| Moderate Armored      | $\simeq 5*SizeRating$ |
| Heavy Armored         | $\simeq 6*SizeRating$ |

Toughness Examples

| Example           | Range  |
| ----------------- | ------ |
| Civilian. Vehicle | 1-5    |
| Utility Vehicle   | 3-8    |
| Battle suit       | 5-10   |
| Small Mech        | 10-20  |
| Mech/ Tank        | 15-30  |
| fighter jet       | 8-10   |
| AP                | 10-20  |
| Naval Ship        | 50-150 |

Toughness can be calculated approximately by the following formula:

$Toughness = Plating Thickness(mm)^\frac{1}{2}$

This is not an approximated representation, since certain materials are stronger than others.

### Armor

Toughness represents the general resistance of a machine's construction, but some vehicles also include armor as a separate component of their construction. This attribute represents that, Some kinds of armor can be modified by SpecialFx to further customize them.

### Crew

A Machine’s crew attribute represents the number of individuals required to operate the vehicle, this could be living or computerized crew members. All machines need at least one crew member. Machines are generally considered to be piloted by a full crew of Qualified operators (lvl 2 in the relevant skills). It is possible to assign a better or worse crew according to the referee’s needs. Crew quality modifies both the vehicle’s General value and its price value.

#### Living Crew

A crew member occupies around 2 cubic meters of space, this includes access, operation, and sitting space.

For combat crew it is assumed that soldiers have skills in the respective machine pilot skill and gunnery for its guns, besides that, the soldier itself also has {Socialization}\[leadership\] and Engineering [Radio Electronics]. Regular soldiers have one less level of {Socialization}\[leadership\] and {Engineering} \[Radio Electronics\], scouts have one less level of \[gunnery\] and \[leadership\], while commanding soldiers have the same level all around.

| Crew      | Lvl | Multiplier |
| --------- | --- | ---------- |
| Rookie    | 1   | 0.5        |
| Qualified | 2   | 1          |
| Veteran   | 3   | 2.5        |
| elite     | 4   | 4          |
| Legendary | 5   | 7          |
| Legendary | 6   | 9          |
| Legendary | 7   | 14         |
| Legendary | 8   | 16         |

#### Artificial Crew

The machine may have one or more built-in Artificial crew in the form of basic computers or Artificial intelligence, Their capabilities are simply rated as equivalent to a living crew. Computers and AI have different costs. Computer crew is more expensive because they are immune to crew hits and any condition that specifically affects living beings.

The distinction of a computer and artificial intelligence are covered in the IT section of the FxRPG. Basically a computer has no initiative and can only follow orders while an Artificial intelligence have decision capabilities that may even pass as humans.

A computer crew uses the same multipliers as a living crew, while AI crew doubles the living crew multiplier before applying it.

#### Passengers

A machine can contain passengers in addition to the crew. They are marked in an “A|B” notation where 'A' is the number of crew and 'B' is the number of passengers. Passengers do not confer extra actions to a machine, they are simply along for the ride. Passengers count as crew for damage purposes when an attack affects the crew. Ejection systems must be purchased separately for crew and passengers at its regular cost.

### Fire Control

Fire control rating represents the quality of a machine’s targeting computer. Weapons mounted on a machine do not use their accuracy ratings, instead they use the machine's Fire Control rating. Pintle mounted weapons do not use the fire control system, because they are not integrated with the machine's targeting system.

Fire control affects a mounted equipment's point value, usually it enhances the capabilities of low accuracy weapons. Weapons with higher accuracy that wish to keep their high value must purchase the 'Stand-Alone Fire Control' SpecialFx.

### Sensors

Sensors Represent a machine’s ability to detect other entities, machines, humans, or anything depending on its specifications. Sensors have 2 characteristics, a Range in Kilometers and a Quality rating.

A generic sensor for military combat purposes has a quality rating of 0.Less sophisticated sensors are rated with a negative value, while high quality sensors have a positive rating. If the machine has no sensors then the attribute is simply ignored and the no sensor SpecialFx is added.

Sensor ranges are assigned with ground usage in mind. Generic military sensors have a range of at least 2 km, Sensors ranges are rarely greater than 7 km to 8 km mainly because of the distance to the horizon of around 5 km, though there are always some exceptions. These limitations are not made because the sensors can’t sense things beyond these rangers but because there is very little point in designing a sensor that senses something that it can't target for combat purposes. So, generally it is recommended that a sensor’s range should be at least equal or higher than the machine’s main weapon.

The range of a sensor is considered its passive range, this range can be extended by actively engaging in the sensors, but this makes the emitter visible to other sensors.

#### Sensors in Different Environments

Sensors mounted on flying vehicles have an advantage of being at a higher altitude and can reach further for the same power. When an aircraft is in the Atmospheric its sensor range is multiplied by 10.

Sensors in space have an even greater advantage, since there is no atmosphere to alter the readings, the range of a spacecraft sensor array is multiplied by one hundred.

Sensors in underwater work differently by using sonar, magnetic detectors and specialized cameras and microphones. Aquatic-only sensors ignore Obscurement from water, but don’t detect targets out of it. You must choose whether sensors are standard or aquatic, to have both each must be purchased individually.

| Rating | System                           |
| ------ | -------------------------------- |
| -5     | Hand Held Sensors                |
| -4     | Basic Optical                    |
| -3     | Basic Infrared                   |
| -2     | Low Light                        |
| -1     | Basic Radar                      |
| 0      | LiDAR, Integrated sensors        |
| 1      | Thermal-imaging, High-Res Images |
| 2      | Magnetic Resonance, Ultrasonic   |
| 3      | Broadband High Power Sensors     |
| 4      | Multi-scanner (Legendary)        |
| 5      | Subatomic Resonance (Legendary)  |

### Communications

Communications represent a machine’s ability to communicate with other entities, be it other machines, humans, or anything else depending on its specifications. Communications has 2 characteristics. A Range in Kilometers and a Quality rating similar to sensors.

A generic communication system for military Combat purposes has a quality rating of 0, less sophisticated communications are rated with a negative value, while high quality communications have a positive rating. If the machine has no communications, then the attribute is simply ignored and the no communications SpecialFx is added, communications come with recording and playback capabilities.

Communications base range is assigned with ground usage in mind. Generic military sensors have a range of at least 10 km. The communication base range is considered its passive range, this range can be extended by actively engaging in the equipment, but this makes the emitter visible to other sensors. Some SpecialFx can affect the rating and range of a communication system

Communications base range represents a one way signal, if the receiver will not send any response then only the sender’s range is used, but if the communication is two-way then both machines have to be within each other’s range.

#### Communications in Different Environments

Communications mounted on flying vehicles have an advantage of being at a higher altitude and can reach further for the same power. When an aircraft is in the Atmospheric its sensor range is multiplied by 10.

Communications in space have an even greater advantage, since there is no atmosphere to alter the signal, the range of a spacecraft sensor array is multiplied by one hundred.

| Rating | System                               |
| ------ | ------------------------------------ |
| -5     | Basic Signals and Lights             |
| -4     | Short Range hand held radio          |
| -3     | Basic large Radio                    |
| -2     | Shortwave Radio with basic scrambler |
| -1     | Military radio with a scrambler      |
| 0      | Laser comm                           |
| 1      | Advanced unscrambler                 |
| 2      | Dedicated comm suite                 |
| 3      | Broadband High Power communications  |
| 4      | Multi-communications (Legendary)     |
| 5      | Subatomic communications(Legendary)  |

A functional communication system is very important. It allows the machine to receive or send information like instructions, coordinates, targeting data for indirect fire, key codes, and information in general.

Noncombat vehicles often have poor communication systems, this does not mean that they are of poor quality but simply that they are not made to pass through military jamming.

### Movement System

Movement types are grouped into categories depending on the terrain: Atmospheric, Naval, Ground, and Space movement. Each one is divided into specific types of mechanical movements. Each movement has its advantages and disadvantages and a vehicle can have more than one movement type. There is no limit to the number of movement types a vehicle can have.

#### Atmospheric

Atmospheric defines the general concept for all atmospheric flight capable vehicles. Atmospheric does not just mean earth's Atmospheric, it just means an atmosphere with similar qualities. Vehicles can range from Planes, Balloons, Helicopters, and drones.

Atmospheric movement does not discriminate between methods of propulsion, But the Stall speed differentiates a regular aircraft with one that has VTOL capabilities, Stall Speed is the minimum speed at which the aircraft can travel before falling.

A VTOL craft has a stall speed of 0 which means it can over in place. Non VTOL aircraft Need a secondary form of movement to reach a speed above the stall speed, or they have to be moved around by another vehicle until they reach it.

Usually Non VTOL aircraft have a secondary movement with poor qualities and uses its flight speed to push themselves. This secondary movement has no acceleration, a top speed enough to get above stall speed safely and a very low maneuverability.

#### Ground

This movement type the most general type of movement, it defined vehicles that move along a surface this includes Tracked, Wheeled, or vehicles on rails. They are assumed to be rated for off-road by having large wheels or strong tracks. Ground refers to any surface that has gravity.

Ordinary non-off-road vehicles have a "road only" negative SpecialFx.

Hover type is used by machines that displace on the ground by floating above it at a short distance, like hovercraft and some fantastical machines.

Ordinary hover movement only works in atmospheres as they need to move some form of gas to generate the force that keeps them hovering, Vehicles able to hover without atmosphere have the "Alternate Hover" SpecialFx.

Hover Vehicles can move over Naval Surfaces

#### Naval

This movement type is used by machines that travel on a liquid surface, most commonly water. For this, the part of the machine that makes contact with the liquid is “liquid-proof”, but there is still a chance of the machine being flooded or capsized depending on its design.

Naval Also include Submersible machines, submarine counts as a different movement than naval movement and must be purchased separately. Most submarines have naval movement as well, but this is not required, submarines with no naval movement are just assumed to fare very poorly on the surface.

#### Space

This movement type is for those machines that use thrusters to move through space, these types of thrusters are exclusive for space movement and do not work for Atmospheric flight within atmospheres. The space movement does not make a distinction between thrusters that use reaction mass and those that don't. The description on how the space movement actually works is left to the designer.

#### Walker

This movement type is used by machines that perform a multi legged walk like movement, the number of legs is up to the designer and has no bearing on the movement speed or toughness of the machine.

### Top Speed

The most important values for movement types of a machine are its Top speed, its half point Combat Speed, and its Reverse value.

Movement points are an abstract representation of hex movement, this is done to simplify and maintain the scale of tactical maps, use the following table to get appropriate measurements in km/h and m/s

| 1MP         | m/s    | km/h     |
| ----------- | ------ | -------- |
| Ground      | 2 m/s  | 7.2 km/h |
| Naval       | 2 m/s  | 7.2 km/h |
| Atmospheric | 10 m/s | 36 km/h  |
| Space       | 20 m/s | 72 km/h  |

Space movement uses acceleration rather than speed, and it is calculated by multiplying the MP by 0.2g $1.667m/s^2$ to figure out the machine’s acceleration.

You can reverse the process to calculate a machine’s movement points based on their top speed in km/h or in G’s for space machines. Machines with fractional MP are possible for slow space movements like solar sails and ion drives.

### Maneuverability

The Maneuverability rating represents the ease of control and agility of a vehicle when presented with fast directional changes. Zero is the generic average for a cheap civilian vehicle. Positive ratings indicate extra nimbleness and responsive controls.

Maneuverability is the maximum number of dice that can a pilot can roll when performing a piloting test to perform evasive maneuvers.

| Rating | Multiplier | Example            |
| ------ | ---------- | ------------------ |
| 0      | 0.2        | Civilian unwieldy  |
| 1      | 0.5        | Civilian           |
| 2      | 1          | Basic Combat       |
| 3      | 2          | Agile Combat       |
| 4      | 3          | Exceptional        |
| 5      | 4          | Machine of Legends |
| 6      | 5          | Legendary          |
| 7      | 6          | Legendary          |
| 8      | 7          | Legendary          |
| 9      | 8          | Legendary          |
| 10     | 9          | Legendary          |

### Deployment Range

This is the maximum distance in kilometers that the vehicle can cover without refueling or maintenance, excluding the crew’s need for rest and food.

Combat vehicles often have inefficient engines that prioritize delivering the power requirements over fuel efficiency. As a general guideline most ground vehicles cover between 200 km and 800 km before needing refueling. Machines with Atmospheric movement tend to have pretty big deployment ranges and need fuel and maintenance crew. As a general guideline aircraft with fixed wings have more autonomy covering a range from 800 km to 5000 km while rotary wing aircraft rarely exceed 1000 km. The generic cost-efficient value for all designs is 500 km, though small vehicles will have a lower range.

#### Space Deployment

Space vehicles cover Far larger distances by using inertia without spending fuel, for that reason when in space each hour of acceleration is treated as one kilometer of deployment range. Example: A machine that has a 500 km of ground deployment would have 500 hours of space flight before requiring maintenance.

Space movement is intended to be realistic, for that reason some kind of reaction mass is needed. Reaction mass is the burn points capacity of the internal tanks (jettison able tanks can be designed using the one way transformation guidelines). The weight of the reaction mass will be added to the final weight of the vehicle after the design is completed.

| Mass Type           | Weight Multiplier | Volume per Weight |
| ------------------- | ----------------- | ----------------- |
| Hydrogen            | $0.00001*BP$      | $0.071 ton/m^3$   |
| Helium-3            | $0.00002*BP$      | $0.142 ton/m^3$   |
| Water               | $0.0002*BP$       | $1 ton/m^3$       |
| Refined Rocket Fuel | $0.01*BP$         | $2 ton/m^3$       |
| Rocket Fuel         | $0.05*BP$         | $5 ton/m^3$       |

Multiply the weight multiplier by the weight of the machine in order to know how much weight is dedicated to reaction mass. The volume per weight is used for storage

If a machine is intended to have ground to orbit capacity it must have enough reaction mass to sustain acceleration during the time to reach orbit.

### Finalizing

After this, the core FxRPG mechanics of the machine is considered to be done. Further details can be explored by adding equipment.

## Machine Metadata

### Machine Defensive Points

This is an overall rating of the machine’s survival capabilities, it is calculated adding up the machine’s following attributes:

- $Toughness^2$
- The sum of each Movement’s Top Speed in $MP^2$
- Minus the sum of each Atmospheric movement’s Stall speed in $MP^2$
- The SpecialFx values on the armor section

The total of these calculations is then multiplied by the maneuver rating multiplier.

### Machine Offensive Points

This is an overall rating of the machine’s offensive potential, it is calculated by adding up the ratings of all the machine’s offensive equipment. Mounted weapons have their point value modified by the machine's fire control. Pintle mounted weapons use their accuracy modifier. Weapons with the 'Stand-Alone Fire Control' SpecialFx use their Accuracy modifier and add the perk value to their point value.

### Machine Utility Points

This is an overall rating of the machine’s other potentials that don't involve survival or offensiveness. Generally a vehicle with high utility provides a wide range of useful tools for its user. It is calculated by using the machine’s following attributes:

- Number of actions by the $crew^3$
- $(comms distance/10)^3$
- $(sensors distance/2)^3$
- $(Deployment range/60)^2$
- $(Burn Points/120)^2$
- $(Sensor rating+comm rating)^2$ if the base is negative the final result is negative
- Positive SpecialFx Point Total Squared
- Negative SpecialFx Point total Squared

The minimum value is 0

## Total Value Rating

The general value gives you an overall rating of the total capabilities of a machine, it is calculated by adding the Offensive Value Rating, Defensive Value Rating, and Utility Value Rating. It is meant to give Referees a general value of the machine for balancing purposes when comparing them against each other.

## Default Size

Default Size = (Total Value Rating)$^\frac{1}{3}$

## Default Cost

Default cost in credits = (Total Value Rating)\*100,000

The machine does not need to have the default size. This is only a suggestion. It may be as small as 0.2 of the default size and as large as twice the default size. This does not modify the general value of the vehicle because the advantages and disadvantages tend to cancel out. For example, a smaller vehicle is easier to transport while a larger vehicle causes more damage on physical attacks.

## Production Cost

Production cost= Default Cost\*(Default Size/Desired Size)

By following the formula, one can notice the increasing price of miniaturization so to speak, making things smaller has always been costly.

After having the Production Cost you now must select the Assembly Type. This defines the amount of care, research, the conditions in which the machine was built and a general amount of units assembled. Assembly type also lets you introduce the concept of Production errors

| Type               | Conditions       | # Produced | Design Errors | Assembly error | Cost Multiplier |
| ------------------ | ---------------- | ---------- | ------------- | -------------- | --------------- |
| Test bed prototype | Breaking Tech    | 1-3        | 12            | 2              | x100            |
| Early Prototype    | First Test Model | 1-6        | 8             | 1              | x50             |
| Late Prototype     | Final Test Model | 1-12       | 4             | 1              | x20             |
| Limited Production | High-end model   | 10-100     | 3             | 3              | x5              |
| Regular Production | Market Release   | 50-500     | 1             | 2              | x1              |
| Mass Production    | Economy Version  | 500+       | 2             | 3              | x0.5            |
| Scrap Built        | Assembled Scraps | 1          | 0             | 14             | x0.2            |

## Production Errors

New vehicles may contain flaws or defects in workmanship, caused by design flaws or by an error during the build process. These errors can range from parts being installed incorrectly to human error or materials with structural or chemical flaws. The number of production errors depend on the assembly type.

A design error is an error common to all machines of the same design, these errors cannot be removed unless the design is altered at the factory. It is the reason new variants are produced of the same model in order to remove these errors and sometimes even adding new ones.

Assembly errors are not part of the design and they can be corrected. But repairing these errors involves taking the machine apart and putting it back together. These errors are repaired using the repairs rule, but the repair time is doubled for each error repaired, and the completion threshold is also doubled.

[!> [!NOTE]

> TODO: Defect Table

## Assembly Cost

The assembly cost is calculated by using the production cost and modifying it by the assembly cost multiplier. This is the real cost that you should use in your chronicle for the purpose of credit value.
