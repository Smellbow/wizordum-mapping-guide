## Teleports

Teleporters... teleport the player. No surpirse there.

![Teleport actors](/assets/teleport1.png)

Hovering over a teleport and pressing X will set it to Off. This will prevent teleportation until you trigger it to toggle back On. This can be done via almost any other actor that can send a signal—player triggers, switches, etc.

The directional arrow at the bast of the teleport will be the direction the player is facing when the arrive at the destination.

Selecting a teleport actor and pressing "TAB" will open the ambient settings, so you can adjust the ambients of a map on teleport.

![Teleport ambient](/assets/teleport2.png)

Teleports can be set to go between each other or just one way by pointing one teleport actor to a simple node.

In the below example the player will be teleported to the node, will not be able to teleport back to the original spot and will be facing the textured wall part on arrival.

![Teleport one way](/assets/teleport3.png)

Below we have a count activator listending to three switches, when activated it is pointed to a teleport set to "Off". This will toggle the teleport on and allow its use, in this exmaple simply moving to the node on the red square. 

With triggers and chained events you can come up with some pretty elaborate teleport schemes :)


![trigger a teleport](/assets/teleport4.png)
