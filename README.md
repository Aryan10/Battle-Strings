# Battle-Strings
A project to change the in-game battle text to match Generation 7.

If you know any other text change, then you can inform us, 
You can also contribute codes and pointers, you will get credit for this.



### Credits
Special Thanks to [Bulbapedia](http://bulbapedia.bulbagarden.net/) for GBA Character Encoding.

All other people are listed in [credits.md](https://github.com/Aryan10/Battle-Strings/blob/master/credits.md)



### How to use?
Follow these steps to use it in your hack.

##### Requirments
• A Hex Editor 

• A rom (Ruby, FireRed or Emerald)

##### Steps
• Open the md file you want to use, all are in [research folder](https://github.com/Aryan10/Battle-Strings/tree/master/research). And open your hex editor.

• Insert the **New Code** somewhere in free space. (It's same for all Roms)

• Now at all your rom pointers, insert your offset(where you inserted new code) in reverse hex.


###### Note
You will see **Extra Byte Changes** in [foe.md](https://github.com/Aryan10/Battle-Strings/blob/master/research/foe.md), it's actually some more byte changes required, it's basically fixes some text that goes out of screen _(because `The opposing` is way too bigger than `Foe`)_

The fixed messages are the battle text of **Ingrain** & **Curse(Ghost)**.


The [data folder](https://github.com/Aryan10/Battle-Strings/tree/master/data) keeps the data of the things researched while this project was running. You can check it out for information.
