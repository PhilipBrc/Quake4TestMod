# Monopoly

Acts as monopoly with the following changes

Money: Instead of money, you have resources. Resources can be used to buy equipment, land, or defenses.

Rent: When landing on a property, instead of paying rent, you must fight against the defenses set up on a property.
- If you die, you give a portion of resources to your opponent, and if you then have none, you lose.
- If you win, the space is cleared, and the owner must spend resources to restock the space. The more units invested in a space, the more resources it takes to refill.
- If the space is already cleared, you take a portion of the opponent's resources without fighting. Increases with the ammount of upgrades.

Houses: Instead of buying houses, you buy defenses for your properties. Each space has a set default defense, but can be upgraded.

Sets: Owning sets grants you passive resource gain each turn. If any properties of a set are cleared, the passive resource gain from it's set is stopped.

Equipment: You can use resources to buy equipment for when you land on enemy spaces.

Allies: Certain community cards can grant allies if you own certain properties, or spend a certain ammount of resources.

Win: You can win either by starving everyone else out of resources.


_________________________________________

Resources:

- Gain resources by passing GO, community chest cards, set bonuses each round, landing on their base property and landing on cleared enemy spaces.

- Lose resources by buying equipment, reinforcing property, restocking property, having abandoned properties raided (when an enemy lands on a cleared space of yours)

Resource Flow - Start with 200 resources, property costs are the same as monopoly. Set bonuses based off the value of a set.
	when an enemy lands on a rienforced space, they must fight the reinforcements. 
	If they lose, you gain a portion of their resources.
	If they win, the space is cleared, and you will need to restock it using a small (increasing with upgrades) resource cost. 
		You can choose to do this on any of your turns.
	
Equipment -

	The machine gun will start at a cost of 100
	Armor and health needs to be bought to refill it. Health costing about 50 resources, and armor costing 100.
	The higher costing weapons will be around 1500-2000 resources.
	In order to restock ammo for a weapon, you need to buy it again.

Defenses - You can purchase different types of enemies to spawn when a property is landed on.
	When it is cleared, it costs some resources to replace the enemies, about 25 per enemy.
	Each player starts with a property (each train station will be a base for a player)
	If a player's base property is cleared, they are forced to pay the restock cost.
	The base property's restock cost increases each time its cleared.

Win - When a player is forced to pay resources without enough, they lose.
	This can happen if:
		- They lose a fight without enough resources to pay
		- One of their cleared properties is landed on, reducing their resources to 0.
		- Their base is cleared, and they lack enough resources to restock it.
