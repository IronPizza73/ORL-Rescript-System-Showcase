# ORL-Rescript-System-Showcase
Enemy creation and gun system with seperated server and client actions.

This contains several projects of mine of which culminate into the WIP rescript of Operation: Red Lake (https://www.roblox.com/games/15620205285/Operation-Red-Lake-Beta)

This features OOP based gun and enemy creation systems seperated on client and server. These are not fully complete as I intend to secure server and client further as right now the server basically just trusts the client.

The enemy system handles 250 enemies without any performance loss and can handle up to a thousand on higher performing computers.

The gun system should be able to handle several thousand bullets per second (I only had issues starting up to 20k+ but my computer is on the higher end so performance may vary). It has a small error with false positives when checking the speed the gun fires and occasionally when stopping the game has an error around missing the player which will be fixed at a later date.

Both the gun system and enemy system are also made with a base class I created to automate creation of classes which works universally.

All of the code minus the item giver and some of the math on the pathfinding for the enemies was exclusively created by me. Those were created by the person who manages O:RL at an earlier date before we started on this properly so he just had me reuse them.

Since this is still in the VERY early stages of development enemies do not have animations hooked up and the gun currently appears on the player torso.
