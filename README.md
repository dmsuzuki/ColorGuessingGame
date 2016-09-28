# Dating Web Site

### Tecnical Overview
This assessment task requires an array of colors e.g. 

    colors=["aqua", "black", "cyan", . . . ];

The target color which the player has to guess is a randomly selected color from that array.
The names must be HTML color names. This is so that when the player successfully guesses the color it can be used for the web page background color, to show what the color actually looks like.

------

![Picture1](https://github.com/dmsuzuki/ColorGuessingGame/blob/master/picture1.png)
![Picture2](https://github.com/dmsuzuki/ColorGuessingGame/blob/master/picture2.png)	
![Picture3](https://github.com/dmsuzuki/ColorGuessingGame/blob/master/picture3.png)
![Picture4](https://github.com/dmsuzuki/ColorGuessingGame/blob/master/picture4.png)
![Picture5](https://github.com/dmsuzuki/ColorGuessingGame/blob/master/picture5.png)

#### Requirements
**Part1:** 

 - Should be a simple ‘game’ which uses a loop. In the loop, the player is shown the list of colors and is asked for their guess. However, no feedback is given to the player based upon their input. In other words, the function check_guess() is not required in part 1. The loop finishes when the player enters the correct color;
 - A summary:
  - Include a list of colors in an array;
  - In function do_game():
  -- Randomly select one of those colors in the array as the target;
  -- Display the target (to help with debugging and marking) e.g. alert(target);
  -- Go into a loop which;
  -- Shows the array of colors and asks the player for their guess;
  -- Stops if the player’s guess is the same as the target.

**Part2:** 

 - Include a list of colors in an array;
 - In function do_game():
 - Randomly select one of those colors in the array as the target;
 - Optionally: display the target (to help with debugging and marking) e.g. alert(target);
 - Go into a loop which;
	 - Shows the array of colors and asks the player for their guess;
	 - Using the function check_guess(): 
	 -- Displays a message such as ‘I don’t recognize that color!’ If the text entered by the player is not in the array of colors, OR: 
	 -- Displays a message such as ‘Your input  is alphabetically higher than mine!’ if that is true, OR: 
	 -- Displays a message such as ‘Your input is alphabetically lower than mine!’ if that is true, OR:
	 -- If the player’s input is the same as the target: changes the web page background color to the target color and displays a message which includes the total number of guesses such as ‘You are right! You took 8 guesses!'
	 - Stops if the player’s input is the same as the target.

**Flowchart:** 
![Flowchart](https://github.com/dmsuzuki/ColorGuessingGame/blob/master/flowchart.png)
----------
**Further Notes:**
>  Submit one single HTML file, which includes the JavaScript code within it. That means there are no links to external JavaScript files or any other files in this assessment task.
