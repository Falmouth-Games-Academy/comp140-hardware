# comp140-hardware
Base repository for the COMP140 Hardware Hacking assignment

####BA Game: A Novel Ambition
![BA Game](https://raw.githubusercontent.com/MaddieK19/comp140-hardware/master/BA%20game%20instructions.png)  
The screenshot above shows the controls for the BA game I've chosen to deisgn my controller for. It requires 4 directional buttons (WASD or arrows), the mouse to aim and throw the crackers and four additional buttons for space, ctrl, shift and esc. The number of buttons required is similar to the amount required on most existing controllers.


###Exsisting Controllers:
The current generation consoles' controllers all have a similar shape:  
#####PS4 controller:  
![PS4 controller](http://www.evilcontrollers.com/media/catalog/product/cache/1/image/490x351/9df78eab33525d08d6e5fb8d27136e95/p/s/ps4-frontview.png)
#####XBOX One controller:  
![xbox one](https://www.evilcontrollers.com/media/catalog/product/cache/1/image/490x351/9df78eab33525d08d6e5fb8d27136e95/x/b/xboxone-frontview-stockblack.png)
#####Wii U controller:
![wii u](http://ecx.images-amazon.com/images/I/7115A2m702L._SX522_.jpg)

As all four controllers have a similar basic shape it's likely that a lot of research and testing has been done to decide that that basic shape with two hand grips is ergonomically the best shape. The Wii U also has it's large game pad controller but reviews (link some reviews) suggest that many users favour the pro controller shown above. 

Another issue is that people don't want to adapt how they play to use a radically different controller, they'll want one that is relatively simple to use if they have used other controllers such as the ones above.  Therefore my controller will use this basic shape with two hand grips.  

A complaint I often saw about controllers was their size, with such a variety in players it's hard to design a controller that will be comfortable for all players. Therefore I plan to make controller resizeable, most likely only the width will be adustable letting players find a size that is comfortable for them.  The recent xbox elite controller was a customizable controller that despite it's large price tag still sold very well suggesting that many people like to customize their controllers to what fits their play style. (add links to 

###My controller:  
![Intial concept](https://raw.githubusercontent.com/MaddieK19/comp140-hardware/master/design.png)

My controller will use the basic shape with two handgrips that the other controllers use. My controller will be wired as it's using the Makey Makey kit.

The esc key exits the game and therefore needs to be somewhere where the user can't easily press it by accident.
I'll attempt to make a joystick using the MakeyMakey kit for the the aiming the mouse controls.

![analoguestick button](https://raw.githubusercontent.com/MaddieK19/comp140-hardware/master/js%20button.png)  
I also want to make a analoguestick that is surrounded by a button allowing the player to aim with the joystick then move straight to pressing the fire button.

### Trello Board:  
![Trello board](https://raw.githubusercontent.com/MaddieK19/comp140-hardware/master/Trello%20board.PNG)

###First Sprint:  
![End of sprint trello board](https://raw.githubusercontent.com/MaddieK19/comp140-hardware/master/End%20of%20sprint%201.PNG)
  
![Photo of prototype 1](https://raw.githubusercontent.com/MaddieK19/comp140-hardware/master/Prototype%201.jpg)  

The first prototype was using the Makey Makey kit. The game I've chosen needs teh Shift and Ctrl keys which the Makey Makey can't be remapped to, therfore for the prototype I will use a hotkey tool to use those keys.  The controls for contolling the fire cracker direction and firing worked better than I though it would as it was more responsive. the only issue is that it needs to be more sturdy to allow the player to press it rather than tap it. The metal ring worked well for earthing the controller as it didn't get in the way if the player wheres it on their thumb. 
The next version will need a casing and buttons for the user to press.


###Second Sprint:  
![Sprint 2 Trello board](https://raw.githubusercontent.com/MaddieK19/comp140-hardware/master/End%20of%20sprint%202.PNG)  

![Photo of prototype 2](https://raw.githubusercontent.com/MaddieK19/comp140-hardware/master/Prototype%202.jpg)    

At the end of this sprint the controller was functional and could be used in the game, I used a piece of open source software called [AutoHotKey](https://autohotkey.com/) to create two files that remap Shift and Ctrl to the B and M keys, this allowed the MakeyMakey to be used for all the controls in the game.   

I also made a second prototype in this sprint that was more compact and had a case, the main point of this prototype was to try and get the controller to fit in a box so the user can hold it without wires getting in the way.   

![2.2 Front](https://raw.githubusercontent.com/MaddieK19/comp140-hardware/master/Prototype%202.2%20front.jpg)  
![2.2 Top](https://raw.githubusercontent.com/MaddieK19/comp140-hardware/master/Prototype%202.2%20top.jpg)  

This prototype used silver foil as buttons, these buttons work but they can't be pressed just touched or tapped. Also after this prototype I noticed that without the use of the arduino and light sensors the controller isn't very creative so I researched Japanese and ninja weapons for inpisiration as that would make the controller more relevant to the BA game I've chosen. I decided that throwing stars would be a good weapon to base my controller on as my current design can easily be reshaped to fit it.

![Controller v2](https://raw.githubusercontent.com/MaddieK19/comp140-hardware/master/controller%20v2.png)





