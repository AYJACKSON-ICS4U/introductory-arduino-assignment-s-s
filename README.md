# Introductory Arduino Assignment Log

## November 1st 2017 - Log 1 
* Today we worked on trying to switch around our board. 
* We thought that our board was a reflection of all the other ones and were trying to work in reflection to the prototype. This wouldn't make sense though because we know that the board works by connecting horizontal lines. We are still working with this puzzle
* We got the light blinking on our board and got the LED working on Leon's board. We went and retreived Ms. Kirby's LED code and are now going to try and switch around aspects so that the button goes on when the light is pressed and the light stays off when the button is untouched. 
* Our biggest challenge is still trying to work with our board. We have tried resetting our board like the prototype, reversed from the prototype, set like leon;s board and also set like Greg's example board.
* Next week we want to be able to work on our board and be less dependant on other peoples boards before we continue with coding.
* Kahyaps and Ali merged into the group

## November 8th 2017 - Log 2
* We figured out our LED positive and negative were flipped by checking our buttons on another groups board and realizing that the positives and negatives do play a part
* We realized the placements of the wires on either side of the button played a part in its functionality. We had one large wire traveling from 27 to 24 both on the ground side. We then changed to 27 on ground side to 22 on the opposite side if the button. Now our button WORKS!
* Uploaded micros pdf for easy access

## November 15th 2017 - Log 3
* We fixed the LED high and low code to make the light switch more natural. Now when the button is pressed, the light turns on and when the button is released the light returns to it's original state (off).
* We also worked on the toggle code and worked on analyzing and understanding each line. Notably, we focused on the delay, nested if statements and temps. Now our light changes state permanently when the button is clicked. We learned that delay allows it to work seemlessly. 

## November 22nd 2017 - Log 4
* We have added two pdf's containing information on how to set-up our boards to our repository so that we can easily access them in the future.
* We have also started investigating how to add a second LED to our board. We noticed that our new light (the red light) always overrides the other light (the green light) when it's added to the board. Next week we would like to attempt to get both lights on at the same time and perhaps eventually involve the button (meaning the button could turn one light off and one light on).

## November 29nd 2017 - Log 5
* Today we worked on removing the delay function and thought about how to create a new function that uses other things (ex. conditionals) to immitate the delay using miliseconds. 
* We are also in the process of adding our second light. We learned that we should add the second LED to D4 instead of connecting it to D3 like the first light. We are now adding another pathway from D4 to the second LED. 
