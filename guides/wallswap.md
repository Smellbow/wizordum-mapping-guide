## Wall swapping

Wall movers can be used to make textures appear to "swap out". Your imagination is the limit here but one simple example is the player lighting a fireplace.

![Fireplace setup 1](/assets/fireplace1.png)

Above we have a simple wall with an unlit fireplace texture on one wall. Behind it we have another block textured as the lit fireplace. Also laid out we have an invisible button and two wall movers.


![Fireplace setup 2](/assets/fireplace2.png)

Above we set the movers up so they will move the needed number of blocks in distance and set the speed to "INST" (Instant)

![Fireplace setup 3](/assets/fireplace3.png)

Next we connect the switch to the two movers so when activated, they move effectively swap places.

![Fireplace setup 4](/assets/fireplace4.png)

Lastly we move the movers into the correct spots, move the switch onto the unlit fireplace block (on top of the mover) and if you want, like below ive added a fire sound effect to also trigger on the switch use.

So the player interacts with the unlit fireplace, the lit fireplace appears instantly and the fire sound effect begins to play. Nice.
