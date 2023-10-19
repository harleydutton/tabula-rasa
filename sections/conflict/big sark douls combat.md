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