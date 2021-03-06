# Salesforce Battle

This is a silly "space battle" simulator.<br /><br />
It is primarily a vehicle to experiment with performing various DML operations and
become more accustomed to designing event/button-driven programs where the state only lasts for as long as a single transaction.

**Note:** At this time most variables are set to public. It's possible that they don't need to be -- I may update this in the future. Exception handling has only been implemented in a couple of places.

## Typical Gameplay
The player is initially presented with a Welcome screen (Figure 1). Clicking **New Game** begins the game. <br />

**Figure 1 - The Welcome screen**  
![The Welcome screen](https://github.com/mikeuf/SFBattle/blob/master/README-images/1-welcome-screen.jpg "The Welcome screen")
<br />
<br />

The game generates new enemy ships (Figure 2). The player can **Fire Photon Torpedoes**.<br />

**Figure 2 - Enemy ships approaching**  
![Enemy ships approaching](https://github.com/mikeuf/SFBattle/blob/master/README-images/2-enemy-ships-approaching.jpg "Enemy ships approaching")
<br />
<br />

During each round, the player and the enemy ships fire at each other (Figure 3). The amount of damage is a random seed multiplied by a "power level" for each weapon type.

**Figure 3 - Battle begins**  
![Battle begins](https://github.com/mikeuf/SFBattle/blob/master/README-images/3-battle.jpg "Battle begins")
<br />
<br />

When an enemy ship's health reaches zero, it is destroyed. The table lists it as "deceased" (Figure 4). The player can click the **Generate More Enemies** button to add more enemy ships to the battle. The game will add a small number of random ship types each time the button is clicked.

**Figure 4 - Some enemy ships destroyed**  
![Some enemy ships destroyed](https://github.com/mikeuf/SFBattle/blob/master/README-images/4-deceased.jpg "Some enemy ships destroyed")
<br />
<br />

After all enemy ships are destroyed, the game is won (Figure 5).

**Figure 5 - Game is won**  
![Game is won](https://github.com/mikeuf/SFBattle/blob/master/README-images/5-game-won.jpg "Game is won")
<br />
<br />

If the player's health reaches zero first, the game is lost (Figure 6).

**Figure 6 - Game is lost**  
![Game is lost](https://github.com/mikeuf/SFBattle/blob/master/README-images/6-game-lost.jpg "Game is lost")
<br />
<br />

A custom tab can be added, allowed the user to browse the ships, make changes, or even add new ships (Figure 7).

**Figure 7 - Fleet list**  
![Fleet list](https://github.com/mikeuf/SFBattle/blob/master/README-images/7-ships-list.jpg "Fleet list")
<br />
<br />

The game utilizes a custom object called "Ships" (Figure 8) with the following custom fields:
* Attack Power
* Health
* Playable_or_Enemy
* Status
* Weapon

**Figure 8 - "Ship" custom object**  
![Ship custom object](https://github.com/mikeuf/SFBattle/blob/master/README-images/8-ship-custom-object.jpg "Ship custom object")

