# Salesforce Battle

This is a silly "space battle" simulator. It is primarily a vehicle to experiment with performing various DML operations and
become more accustomed to designing event/button-driven programs where the state only lasts for as long as a single transaction.

There are some known bugs. In particular, it is sometimes still possible to continue firing photon torpedoes even after the player's ship is destroyed. There are some logic errors that still need to be ironed-out. Many items are set to public or static when they probably don't need to be and exception handling has only been implemented in a couple of places.

## Typical Gameplay
**Figure 1 - The Welcome screen**  
![alt text](https://github.com/mikeuf/SFBattle/blob/master/README-images/1-welcome-screen.jpg "Logo Title Text 1")
