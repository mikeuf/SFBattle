# Salesforce Battle

This is a silly "space battle" simulator. It is primarily a vehicle to experiment with performing various DML operations and
become more accustomed to designing event/button-driven programs where the state only lasts for as long as a single transaction.

There are some known bugs. In particular, it is sometimes still possible to continue firing photon torpedoes even after the player's ship is destroyed. There are some logic errors that still need to be ironed-out. Many items are set to public or static when they probably don't need to be and exception handling has only been implemented in a couple of places.

## Typical Gameplay
**Figure 1 - The Welcome screen**  
![The Welcome screen](https://github.com/mikeuf/SFBattle/blob/master/README-images/1-welcome-screen.jpg "The Welcome screen")  
**Figure 2 - Enemy ships approaching**  
![Enemy ships approaching](https://github.com/mikeuf/SFBattle/blob/master/README-images/2-enemy-ships-approaching.jpg "Enemy ships approaching")

**Figure 3 - Battle begins**  
![Battle begins](https://github.com/mikeuf/SFBattle/blob/master/README-images/3-battle.jpg "Battle begins")

**Figure 4 - Some enemy ships destroyed**  
![Some enemy ships destroyed](https://github.com/mikeuf/SFBattle/blob/master/README-images/4-deceased.jpg "Some enemy ships destroyed")

**Figure 5 - Game is won**  
![Game is won](https://github.com/mikeuf/SFBattle/blob/master/README-images/5-game-won.jpg "Game is won")

**Figure 6 - Game is lost**  
![Game is lost](https://github.com/mikeuf/SFBattle/blob/master/README-images/6-game-lost.jpg "Game is lost")

**Figure 7 - Fleet list**  
![Fleet list](https://github.com/mikeuf/SFBattle/blob/master/README-images/7-ships-list.jpg "Fleet list")

**Figure 8 - "Ship" custom object**  
![Ship custom object](https://github.com/mikeuf/SFBattle/blob/master/README-images/8-ship-custom-object.jpg "Ship custom object")

