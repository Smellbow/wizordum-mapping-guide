## Teleports

Teleporters... teleport the player. No surpirse there.

![Teleport actors](/assets/teleport1.png)

Hovering a teleport and pressing "X" will set it to "Off". This will not teleport the player until you trigger it to toggle to on. This can be done via most any other actor that can send a signal. Player triggers, switches etc.

The directional arrow at the bast of the teleport will be the direction the player is facing when the arrive at the destination.

Selecting a teleport actor and pressing "TAB" will open the ambient settings, so you can adjust the ambients of a map on teleport.

![Teleport ambient](/assets/teleport2.png)

Teleports can be set to go between each other or just one way by pointing one teleport actor to a simple node.

In the below example the player will be teleporte to the node, will not be able to teleport back to the original spot and will be facing the textured wall part on arrival.

![Teleport one way](/assets/teleport3.png)
