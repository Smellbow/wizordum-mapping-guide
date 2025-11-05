## Massive mover

Mass movers can move more than on block at a time. In the example below we have a large wall, lets say the player cant get around that wall in a real map. In front of them is a plain stone section ahead of the grass with the flame icon tile on it. Behind the wall is a wooden section and a furnace or forge.

We would like it so when the player enters the flame tile the terrain around them changes in one go. A mass mover can help here.

![mass movers](/assets/massmove1.png)

First we take mass mover and cover the base of the area we want to move. The text "mass mover" is the active point for connections.

![mass movers](/assets/massmove2.png)

The mover will reposition itself to a target node so we hook up each mover to a node

![mass movers](/assets/massmove3.png)

Next, for this example, we setup a player trigger on the flame icon and connect it to the mass movers. After that we repoistion the nodes under each others origin. The node needs to be positioned exactly where you want the mass mover to move to.


![mass movers](/assets/massmove4.png)

With the trigger set to activate the movers and the movers pointed to new positions via nodes we can walk into the trigger in game and see that the two areas have swapped places. Pretty cool!

With some effort you can hook up sequences of moving terrain with sounds fx and visual fx. Be careful when moving terrain around the active player position as this can nudge the player in some scenarios. Be sure to test!

![mass movers](/assets/massmove5.png)

The mover will bring over blocks above it as well, as shown below. Also making use of "loot glue" you can move across items for the player. Like surprise treasure! 

![mass movers](/assets/massmove6.png)
