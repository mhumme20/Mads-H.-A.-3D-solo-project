# Mads H.-A. mini project 
The goal of the project was to implement a simplified version of shadowrun 5th editions combat system into a turnbased tactics game.

When the games starts up 5 enemies (black squares) and one hero (red square will be created. The enemies each get a single random weapon, while the hero gets 3 randoom weapons.

The game will roll initiative for all characters and then the character with the highest initiative will act. This will be the hero, the game will highlight the squares a character can move to in green and yellow. Green means the character can move there without taking a penalty to their ranged attacks, while yellow means moving there will grant them a penalty to their ranged attacks and a bonus to their melee attacks.

When it is a characters turn a set of buttons repressentting their weapons will be created. The buttons come with an arrow that will reveal subweapons, each ranged weapon can have up to 3 firering mode: singleshot, 3 round burst and full auto. For 3 round burst and fullauto grant the target a penalty to their defense but build up greater recoil, which will penalise the attack until it has been reset by eith reloading the weapon or taking the aim action.

When every character with initiative has acted, all of them will lose 10 initiative. Afterards all characers who stil have initiative will get a another turn, this cunitiues until no one has iniatiative left, at which point initiative will be rerolled. 

Movement only refreshes once initiative is rerolled.

Characters attack by rolling a number of six sided dice equal to their attack pool. Every 5 and 6 count as a succes. Succes's above the weapons accuracy are not counted.

After rolling an attack, the hero unit can spend an edge point to reroll all dice that did not roll a 5 or 6.

Next to the roll button is a little square, clicking this will activate pre edge on the next roll. If a roll is pre edge acuracy is ignorred (good for weapons with low accuracy) and every 6 rolled will result in another dice being rolled, which cuntinues until no more 6's are rolled.

The game ends when either all enemies are dead or the hero is defeated, at which point the player can reset the game. The winner will most likely be the hero as the hero has greatly inflated stats along with better weapons.

!!Note there is no programed behavior for the enemies, they have to be controlled by a player.
