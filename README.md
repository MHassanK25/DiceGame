# DiceGame

I decided that for my project I would create a two-player dice game, in which the player who rolls a higher number wins. I am extremely interested in creating games and where it can take me. This project can help show me somewhere I could potentially go with my career, so in this project I will be discussing what I created.

![Project Diagram](https://user-images.githubusercontent.com/74241590/196786994-afa9c296-3dc0-4fc2-b749-3992b20d16e6.png)

Here is a basic flowchart of how a game of 2 player dice works. From this I will be creating a code that will automatically print the winner after the input from the two users without the user having to request it or work it out.
In my program, I have used if and else statements to determine which number is larger, and I have also turned the person who wins into a mathematical value, this way at the end of the input, the code will release the variable attached to the higher value which will print which player was the winner. I selected this design as I felt it would be the most efficient in displaying who had won with the least effort required.

I created variables for the users input to determine if they wanted to roll the dice or if they wanted to forfeit the game. I also put the values for whoever wins the game at zero initially, and If one of the users has a larger number rolled on the dice then their value will increase by one making them the winner. If both values are the same then nothing will be added to either of the values, making both of them 0 and calling for a draw.

The challenges I faced in this project were somewhat difficult but in the same vein I believed they were also a little easy to overcome. I was struggling in terms of forfeiting the game, when  I was doing my test runs it would continue to play the game after I had input quit. Soon, I was able to fix the if/else statement and got that to run smoothly. One of the drawbacks of the way I created this game was that after forfeiting the game will simply request you to play again instead of just shutting off the program. This can also be seen as an advantage however, because a forfeit in one game doesn’t necessarily mean they wish to stop playing. If I were to improve this I would possibly add in a slight simple animation whilst rolling the dice. I would also allow the user to input a shorthand for roll or quit such as “r” or “q”.
