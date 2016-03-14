# comp140-hardware
###BA Game: A Novel Ambition
![BA Game](https://raw.githubusercontent.com/MaddieK19/comp140-hardware/master/Images/BA%20game%20instructions.png)  
The screenshot above shows the controls for the BA game I've chosen to design my controller for. It requires 4 directional buttons (WASD or arrows), the mouse to aim and throw the crackers and four additional buttons for space, ctrl, shift and esc. The number of buttons required is similar to the amount present on most existing controllers.

###Existing Controllers:
After researching the most popular consoles and current generation consoles it became obvious that most controllers have a similar shape with a main body section with most of the controls on it and two hand grips:  
#####PS4 controller:  
![PS4 controller](http://www.evilcontrollers.com/media/catalog/product/cache/1/image/490x351/9df78eab33525d08d6e5fb8d27136e95/p/s/ps4-frontview.png)  
#####XBOX One controller:  
![Xbox one](https://www.evilcontrollers.com/media/catalog/product/cache/1/image/490x351/9df78eab33525d08d6e5fb8d27136e95/x/b/xboxone-frontview-stockblack.png)  
#####Wii U controller:
![Wii u](http://ecx.images-amazon.com/images/I/7115A2m702L._SX522_.jpg)  
As the controllers above all have a similar basic shape it's likely that it’s ergonomically the best shape. The Wii U also has its large game pad controller but according to reviews many players prefer to play using the Wii U “Pro controller” shown above.  
Another issue is that people don't want to adapt how they play to use a radically different controller, they'll want one that is relatively simple to use if they have used other controllers such as the ones above.  Therefore my controller will use this basic shape with two hand grips.      
As my controller will be based on a game a ninja like game I have also researched ninja weapons and could incorporate some  

###My controller:  
![Initial concept](https://raw.githubusercontent.com/MaddieK19/comp140-hardware/master/Images/design.png)

My controller will use the basic shape with two handgrips that the other controllers use. My controller will be wired as it's using the MakeyMakey kit.

The esc key exits the game and therefore needs to be somewhere where the user can't easily press it by accident.
I'll attempt to make a joystick using the MakeyMakey kit for the aiming the mouse controls.

![analogue stick button](https://raw.githubusercontent.com/MaddieK19/comp140-hardware/master/Images/js%20button.png)  
I also want to make an analogue stick that is surrounded by a button allowing the player to aim with the joystick then move straight to pressing the fire button.

### Trello Board:  
![Trello board](https://raw.githubusercontent.com/MaddieK19/comp140-hardware/master/Images/Trello%20board.PNG)

###First Sprint:  
![End of sprint Trello board](https://raw.githubusercontent.com/MaddieK19/comp140-hardware/master/Images/End%20of%20sprint%201.PNG)
  
![Photo of prototype 1](https://raw.githubusercontent.com/MaddieK19/comp140-hardware/master/Images/Prototype%201.jpg)  

The first prototype was using the MakeyMakey kit. The game I've chosen needs the Shift and Ctrl keys which the MakeyMakey can't be remapped to, therefore for the next prototype I will use a hotkey tool to use those keys.  The controls for controlling the fire cracker direction and firing worked better than I thought it would as they were more responsive however they weren’t easy to use in the current state as the user can’t hold the controller. The main issue is that it needs to be sturdier to allow the player to press it rather than tap it. The metal ring worked well for as an earth for the controller as it didn't get in the way if the player wears it on their thumb. 
The next version will need a casing and buttons for the user to press.


###Second Sprint:  
![Sprint 2 Trello board](https://raw.githubusercontent.com/MaddieK19/comp140-hardware/master/Images/End%20of%20sprint%202.PNG)  

![Photo of prototype 2](https://raw.githubusercontent.com/MaddieK19/comp140-hardware/master/Images/Prototype%202.jpg)    

At the end of this sprint the controller was functional and could be used in the game, I used a piece of open source software called [AutoHotKey](https://autohotkey.com/) to create two scripts that remap Shift and Ctrl to the B and M keys, this allowed the MakeyMakey to be used for all the controls in the game.   
I also made a second prototype in this sprint that was more compact and had a case, the main point of this prototype was to try and get the controller to fit in a box so the user can hold it without wires getting in the way.   

![2.2 Front](https://raw.githubusercontent.com/MaddieK19/comp140-hardware/master/Images/Prototype%202.2%20front.jpg)  
![2.2 Top](https://raw.githubusercontent.com/MaddieK19/comp140-hardware/master/Images/Prototype%202.2%20top.jpg)  

This prototype used silver foil as buttons, these buttons work but they can't be pressed just touched or tapped lightly. 
I now know the controller works so will now try and use a different box. The Arduino kit I bought was faulty and had to be returned so I can no longer use photo resistors or a similar light based system to control the firing of the fire crackers. Instead I’ve looked at different ninja weapons and settled on a design based on a throwing star. The shape of a throwing star allows me to incorporate that two handle grip base of the controller and also ties into the theme of my chosen BA game. 

![Controller v2](https://raw.githubusercontent.com/MaddieK19/comp140-hardware/master/Images/controller%20v2.png)

###Final version: 
![Final controller image]()  
The final version is mostly the same as the previous version just in a different box. None of the functionality has changed but some buttons and wires are now more secure. 
