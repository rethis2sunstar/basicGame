# basicGame
This is the essence of a video game using javascript to event
You can clone the HTML and CSS for the game layout here.  
## Objective: 
Create an api that processes on button click the attack and def of both the goblin and Neyru.  Now Neyru is the hero character so he should have an edge on our goblin.
## Requirements:
•	There should be two objects that define the stats of the goblin and neyru
•	The api must respond to a click
•	Once the attack button is clicked Neyru will have a random roll that compares his attack value vs defence.  This means there needs to be a random number added to his atk value that will be compared to goblin defence.
•	Upon successful atk there is a random damage roll.  There should be a str value that will be added to the damage to differentiate the strength of the two characters.
•	The damage that was rolled has to be subtracted from the goblin hp meaning this will update the goblin object.
•	Messages about what the results were need to be displayed in the centre box.
•	The goblin attacks back and the hp should be deducted from Neyru Object.
## Hints:
•	Create two objects that is the “character sheet” of the two characters.
•	Create two functions for atk and damage rolls that use the math.ceil math.random methods.
•	Use an event listener and conditional logic to measure the conditions of the battle
•	Use nested if’s to create the logic of attack and defence for both aswell as the messages that will be displayed.
You can see the JS here but I recommend trying to logic it out yourself.  This is the beginning of understanding how to set and return information so that it can make more complex functionality. 

Now we note we are not using a constant input value for something like movement or including animations in our code.  This is more the API that handles the battle logic of classic RPG’s.  
