## Minecarts

The minecart actor, as youd expect, creates rideable minecarts.

![minecart actor](/assets/minecart1.png)
![minecart actor 2](/assets/minecart2.png)

Like wall towers, a minecart can be connected to node actors in sequence to form its "track". These can change height. Note the player will be ejected at the last node. Once a minecart reaches its last node, it can be used again to go back to the first.

![minecart basic nodes](/assets/minecart3.png)

In this example the minecart connects to a series of nodes in the order it should travel to them. One is on a higher block. The cart will slow down on the climb and accelerate to the lower node on its way around.

Also note that the last node has another node connected to it, this is where the player will land when "ejected" from the minecart. You can send the player to almost anywhere on exit and they will "hop" to that location. in this case the wooden tile.

![mine cart nodes with elevation]()
