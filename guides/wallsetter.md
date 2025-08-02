## Wall Layer Setters (up/down)

Wall setters are pretty versitile and allow you to work outside the apparant restrictions you might encounter when designing play spaces / buildings. You will find them under the "actors" menu.

Normally if your ground floor was on the middle editor 'level', you would be restricted to building three full blocks above that level.

![normal height](/assets/wallsetter1.png)

Wall setters allow you to exceed that limitation when desired, the same goes for below the lowest level using the "down" variant.

Here we place an extra row of blocks along the top level of our wall example.

![normal blocks prepared](/assets/wallsetter2.png)

Now we place Up wall layer setters on those blocks and configure their parameters for movement, Up and Forward.

Shift + Q, E will rotate the direction for the forward movement. 

Highlight a wall setter and use : 
C = forward movement adjust
X = Upward movement adjust

Here we are saying, when the map loads I want you to move up one more space and move forward one space.

![setters in place](/assets/wallsetter3.png)

When a map loads wall setters activate. So here on map load we see those blocks move up and ontop of the wall, above the editor limit!

![In game view](/assets/wallsetter4.png)

As the same applies for moving downwards also, a little imagination can create some unique spaces around the player.

## Wall Layer Setters - Merge

Another neat feature with wall setters is their ability to "push" a spaces contents into another, even if it has something in it already!

Say you have used a middle wall and an some edges to create a thin wall like this:

![open thin wall missing an edge](/assets/settermerge1.png)

Youd might try cap the end with another half wall like so:

![open thin wall missing an edge2](/assets/settermerge2.png)

Only to find the editor wont allow this. This is where a wall setter can come in! 

Place the capping edge int he adjacent space and add a wallsetter! This tells the game to move that spaces contents as configured by the setter on map load.

![open thin wall missing an edge](/assets/settermerge3.png)

We dont want it to move up or down, just across. So leave the up/down at zero and just set the movement amount.

Then on game load we get a fully capped small wall!

![open thin wall missing an edge](/assets/settermerge4.png)

You can do this with lots of combinations to create some neat architecture!
