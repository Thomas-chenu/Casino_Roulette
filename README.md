<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Roulette
Hélène & Thomas

DA NOV 2020

## Content
- [Project Description](#project-description)
- [Rules](#rules)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
Write a short description of your project. Write 1-2 sentences about what what you chose to build and why. 

Casino Roulette - a gamble play.
We choose a gamble play to build. Interesting for coding because it include inputs from player, random choice from computeur and increasement or decreasement of earning, all of this with "rounds". We'll see if you can leave the table with money!

## Rules
Describe briefly the rules of the game you chose. 

The player starts the game with 1000€. We ask him to input 'how much he want to bet' and 'what kind of bet he want to do : number, even or odd'. Player can continue to bet unless he's out of money or if he prefers to quit the table with money!

We choose for this 1st game to simplify the rule of our gamble game. Player can only choose between 2 types of bet :
- On a number : In this case, player can earn 36 times his bet.
- Between 'Even' or 'Odd' : in this case the player can earn 2 times his bet. 

## Workflow
Outline the workflow you used in your project. What are the steps you went through?

1er step : We defined the amount of money the player will have at the beginning of his play. And we defined a list of all the possible gamble. 

2d step : We ask to the player 'how much he want to gamble' during the play. And we check that his bet is under or equal to the money he has. He can't gamble more than he earns (Casino doesn't give credit!).

3d step : We ask him what kind of bet he wants to do :
                - On number (between 1 to 36)
                - On Even or Odd

4th step : we generate a random choice of the computer that represente the casino wheel between 1 to 36. 

5th step : Last important step we compare the player gamble and the result of the wheel :
- If the player bet on a number, we compare it to the wheel! If it's the same, this is a huge earning : 36 times your bet. Not the same number and you loose all your gamble.
- If the player choose to bet on 'Even' or 'Odd', we see if the casino wheel number is even or odd with a modulo 2. and after this step we conpare it to the player choice. 

6th step : we see if the player has still enough money to play. if he has enough we ask him if he want to continue or quit the table with the money he has. Otherwise, he just has to quit. 


## Organization
How did you organize your work? Did you use any tools like a trello or kanban board?

What does your repository look like? Explain your folder and file structure.

## Links
Include links to your repository, slides and trello/kanban board. Feel free to include any other links associated with your project. 

[Repository](https://github.com/Thomas-chenu/Roulette) 
[Slides](https://slides.com/)  
[Trello](https://trello.com/en)  