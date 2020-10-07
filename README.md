# Basic Online Pokemon Game

 > Original by ByteCampio at https://github.com/bytecampio/pokemon
 > Readme written with [StackEdit](https://stackedit.io/).
 > Changes made by thenerdoflight of jadestudios.uk

**Navigating the folders**

 - str_poke contains all the HTML/CSS/JS that runs the game
 - str_images contains all the image files used by the game
	 - bg.jpg is used by index.html
 - index.html is for the page that holds the game

This means that the pokemon.html in the str_poke can be ran. However, ***this version is optimized for w=789 and h=762.***

![Image of Game](https://github.com/thenerdoflight/basiconlinepokemongame/blob/main/Screenshot_2020-10-06%20Pokemon%20on%20Web.jpg?raw=true)

**Major changes compared to the original**
	
 - Near full flexbox implementation
 - Game can restart after a game over
 - Supports evolution given a HP threshold
 
**Minor changes compared to the original**

 - CSS value changes
 - JS changes

**Bug Fix**

    var move = Math.floor((Math.random() * 4) + 1); // choose move randomly
Original JS line calculated moves in a random fashion. The issue was this code created the possibility for var move = 5 when the array was only 4 objects.

Fixed by changing the 4 to a 3. This allowed the maximum var move to be the same as the size of the array.


**About Me**
I can't code. It has bugs. I'm still learning. AND GOD DO I HATE JS and HTML