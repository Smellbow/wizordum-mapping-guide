## Wall tower
The wall tower actor is well detailed in the official documentation. When placed onto a block and connected to "node" actors, the block will move between them in sequence. It will crush any other actors in it path including the player.

If a wall tower is given only one connected node it will, on map load, move to and remain at that position.

Wall towers can create looping crush traps, moving scenery etc. 

They can also be used to create moving walls / secret doors that move in more than one direction with manuipulation.

Using level start flags coupled with deactivators, you can trigger a movement patter with a wall tower and nodes then deactivate it at a chosen point. (Wheyy used this to great effect to create doom IIs e1m1 stairway)

![wall tower basic](/assets/walltower1.png)

In the above example a node actor is also directly underneath the wall block and wall tower actor. It is the first actor the tower is connected to and then the one further to the right. Upon level start this block will move from point to point forever.

![wall tower as a secret](/assets/walltower2.png)
