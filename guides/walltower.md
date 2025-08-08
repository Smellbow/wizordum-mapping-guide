## Wall tower
The wall tower actor is well detailed in the official documentation. When placed onto a block and connected to "node" actors, the block will move between them in sequence. It will crush any other actors in it path including the player.

If a wall tower is given only one connected node it will, on map load, move to and remain at that position.

Wall towers can create looping crush traps, moving scenery etc. 

They can also be used to create moving walls / secret doors that move in more than one direction with manuipulation.

Using level start flags coupled with deactivators, you can trigger a movement patter with a wall tower and nodes then deactivate it at a chosen point. (Wheyy used this to great effect to create doom IIs e1m1 stairway)

![wall tower basic](/assets/walltower1.png)

In the above example a node actor is also directly underneath the wall block and wall tower actor. It is the first actor the tower is connected to and then the one further to the right. Upon level start this block will move from point to point forever.

![wall tower as a secret](/assets/walltower2.png)

In the above example a wall tower has been set on a block, it has nodes under itself and two more to give it an K shaped travel path. 
A level start flag is connected to a deactivator and then to the wall tower. This stops the wall tower from moving along its given path as soon as the map starts. 
This means we can instead trigger it when we choose.

In this case a player trigger spot is used to trigger the wall tower, which sets it along its path of nodes.

The player trigger activtes the wall tower but also at the same time activates a timer. On the timers end it activates another deactivator also connected to the wall tower. 

This allows the wall tower to complete its path once upon player trigger and then stop in place. With some careful setup this can be used to create all manner of moving blocks, secret doors and terrain shifting actions! 
