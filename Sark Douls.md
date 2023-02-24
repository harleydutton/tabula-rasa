**

Sark Douls the RPG

# Base Stats

You start with a default value of 10 in each base stat, except health which starts at 40.

## Strength

Used to determine melee damage and dodge type.

## Intelligence

Used to scale sorceries.

## Faith

Used to scale miracles.

## Dexterity

Used for dodge-roll success rate and melee damage.

## Health

When you run out, you die.

## Mana

Used to pay for spells.

## Stamina

Used to pay for actions in combat.

## Level

Determines the cost for making character upgrades.

## Derived Stats

### Poise

Determined by armor. If the incoming damage is greater than your poise value you are stunned for 3 turns and any actions you were performing are lost.

## Load -> Roll Type

Load is the total weight of your gear divided by your strength. It determines your dodge type.

  

  

load

time

Light roll

less than 25% or less

1 second

Med roll

less than 50% or less

2 seconds

Heavy roll

less than 100%

4 seconds

Cannot roll

More than 100%

  

  

## Abilities

Steal these from a medieval white wolf game’s sheet

## Gear

Melee weapons, Ranged weapons, Armor, Consumables, Jewelry, Shields, Magic Focus

## Resources

Mana, Health, Stamina

## Other

Estus Flasks, Ashen Estus Flasks, Hollowing, Humanity/Ember, souls

## Defences

Sharp, Blunt, Fire, Lightning, Dark, Holy, Poison

  
  

# Combat

## Timing

Combat starts at zero seconds. Using actions stuns you for X seconds where X is the action’s cost. Combatants roll for initiative and start on that second. Seconds tick up in combat as the combat progresses. Combatants recover 2 stamina per second by default but this can be altered. Combatants lose 1 point of each status they are affected by each turn.

### Turns

Start with the DM on each second and move clockwise around the table. If there are no turns on a second just skip it. Stamina recovery happens at the end of the second. 

  

## Actions

### Attack/Cast/Use

Stuns you for a number of seconds based on the weapon/power’s delay value. Spells and attacks have stamina costs. Spells also have a mana cost. You don’t regenerate stamina while stunned from an Attack/Cast. Does the thing after all costs are paid and delay/2 seconds rounded up have passed.

### Heavy Cast/Attack

Same as normal Attack/Cast but double all numbers. There is no heavy use for bows//crossbows or consumables.

### Block

Costs one second, reduces stamina recovery per second by one. Weapons can only block sharp/blunt damage and split the damage between your health and stamina. Shields can block any kind of damage and send ¼ of the damage to health and ¼ to stamina, both reduced by shield upgrade value. If you run out of stamina while blocking you are stunned for 15 seconds and take full damage. Shields can be further improved by giving them a damage type. This will make them send 0 damage to health. On successful melee block, increase the attacker’s stun by time-and-a-half rounded down. 

### Parry -> Stab

When you are being attacked by a melee weapon you can parry with a shield and a successful dex roll at TN 27. If you succeed you can stab. Stabs are unavoidable melee attacks that do time and a half damage. Not all attacks are parryable. Attempting to parry costs 2 seconds.

### Dodge

Roll to avoid damage entirely using dex, measure roll cost in seconds using load/strength (Heavy=4, Med =2, light=1). Move one hex.

### Move (and Hold)

Costs one second. Optionally move one hex. You should be using a grid with one character per grid. Bosses probably mess with this.

### Run

Costs one stamina. Move two hexs. You don’t recover stamina on the turn you run.

## Damage Types

Damage types are physical, fire, lightning, and magic. Incoming damage is reduced by a flat value based on armor. If the attack was blocked incoming damage is also reduced by a percentage value based on shield/weapon. Finally, if the incoming damage has not been reduced to 0, it is subtracted from health.

## Status Effects

Whenever you are dealt status damage you will accrue stacks of the status. You lose one point of status per second.

### Bleed

When you reach bleed 10 stacks your stacks are reset to 0 and you take half of your maximum health as unmitigatable damage.

### Poison

Once you reach 10 poison stacks, gain 10 poison stacks and you cannot gain poison until you reach 0 stacks. You take 1 poison damage per second.

### Chill

When you reach 10 chill stacks take 5 damage and reduce your stamina regeneration by 1 per second until you are no longer chilled.

### Curse

When you reach 10 curse points, curse is not removed with time, you die and your max health is halved until you are no longer cursed.

### Leech

Leech gives you one bleed stack per second until you come into contact with fire. The leech status is binary and does not have stacks.

### Stun

You cannot take actions. If you are stunned because you cast/attacked you do not regain stamina.

  

# Powers

## Sorcery

### Soul arrow

Takes 3 seconds and 1 mana to deal your catalyst’s magic damage up to 8 squares away.

### Magic Weapon

Gives your melee weapon additional magic damage equal to half of your catalyst’s magic damage for seconds equal to your catalyst’s magic damage. Takes 4 seconds to cast and costs 2 mana.

  

### Soul-sword

You manifest a blade of soul energy and strike nearby foes with it. Deals magic damage equal to your catalyst’s magic damage. Takes 2 seconds. Costs 1 mana. Cannot be parried.

### Invisibility

Makes you invisible but still audible for seconds equal to your catalyst’s magic damage number of seconds. Costs 2 mana and takes 3 seconds to cast.

## Faith

Lightning spear, force, heal, cleanse, lightning weapon

## Pyromancy

Combustion, fireball, poison mist, inner fire, flaming weapon

# Equipment

## Weapons

### Melee Weapon

Can take whatever shape you like and does physical damage based on the sum of the dex and strength scalings plus the upgrade level. Starting strength and dex for most characters is 10 so a normal weapon would have 20 damage. All characters start with a non-ultra weapon of their choice.

  

  

strength

dex

delay//stamina cost

range

weight

light

0.5

1.5

1

1

1

normal

1

1

2

1

2

heavy

2

0.5

3

2

4

ultra

4

0

4

2

8

  

### Bow // Crossbow

Has a base damage of 10 plus 1 per upgrade level. Scales off of dex//str. Has a short range of 10 and a long range of 60. You must make a dex check to hit if the target is beyond short range. The TN is 20+range/10 rounded up. Requires ammo to use and ammo determines damage type.

### Pyromancy Flame

Has a fire damage value of 0 that increases by 1 per upgrade level. Scales off of int and faith.

### Sorcery Catalyst // Sacred Chime

Has a magic//lightning damage value of 10 that increases by 1 per upgrade level. Scales off of int//faith.

  

## Armor

All characters start with an armor of their choice. More armor can be created by the DM and dropped by enemies.

  

  

physical

magical

fire

lightning

poise

weight

light

3

4

4

4

1

1

medium

6

2

2

2

2

3

heavy

12

2

2

2

9

7

ultra

30

10

10

10

15

10

  

## Jewelry

You can have 2 rings and one necklace. Jewelry is made by the DM and does whatever the DM says.

## Consumables

Used with the use action. Most consumables are made by the DM. They should have a use time.

### (Ashen) Estus Flasks

Heals 3 per upgrade level health on use. Use time of 5. Players start with flasks at level 2. Ashen estus and estus can be freely swapped at a bonfire. You get your max number of flasks back whenever you visit a bonfire.

# Mechanics

## Bonfires

You will respawn at the bonfire you have most recently rested at when you die. Souls can be spent at bonfires to make UPGRADES. You cannot buy new equipment or powers at bonfires. A weapon’s prefix cannot be upgraded.

## Souls

Souls are exp and money all in one. You can spend them on things when you are at a bonfire or vendor. When you die your souls are left with your bloodstain.

## Death

When you die you leave behind a bloodstain at the site of your death and increase your hollowing by one.

## Bloodstain

Left behind when you die, your bloodstain holds your unspent souls. These can be reclaimed by touching the bloodstain. Touching the bloodstains reduces your hollowing by one. Bloodstains can be examined. If you die again without touching your bloodstain your previous bloodstain disappears and a new one appears at the site of your most recent death.

## Hollowing

When your character reaches a hollowing of 10 you turn into a hollow permanently. This means you lose control of your character and start mindlessly attacking anything that isn’t hollow.

  

## Scaling

To say something has a scaling is to say that it increases the relevant number by one of the character’s primary attributes. Something with a base value of 5 and a strength scaling (5+STR) used by a character with a strength of 10 will have a value of 15 for the item. If scaling is not one-to-one it will be marked by default something with a scaling is one-to-one.

## Character upgrades

To make a character upgrade spend a number of souls at a bonfire equal to your character level and increase level by one and a base stat of your choice by one.

  

## Equipment Upgrades

Increase your equipment’s level by one at the cost of the equipment’s current level plus one, in souls.

## Rolls

Rolls are made using attributes. The value of a roll is 3d6 + attribute. For the roll to be a success you must have beaten the TN. Standard TN is 22.

## Rounding

Round up.

  
**