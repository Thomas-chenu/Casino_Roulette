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

Casino Roulette - a gamble game.
We choose a gamble game build. Interesting for coding because it includes inputs from player, random choice from computer and increasement or decreasement of earnings, all of this with "rounds". We'll see if you can leave the table with money!

## Rules
Describe briefly the rules of the game you chose. 

The player starts the game with 1000€. We ask him to input 'how much he want to bet' and 'what kind of bet he wants to do : it must be a number between 1 to 36, even or odd'. Player can continue to bet unless he's out of money or if he prefers to quit the table with money!

We choose for this 1st game to simplify the rule of our gamble game. Player's earnings can be as follows :
- If he bets on a number and the roulette's number is the same : in this case player earns 35 times his bet.
- If he bets on 'Even' or 'Odd' and it corresponds to roulette's number : in this case the player earns 1 times his bet. 

## Workflow
Outline the workflow you used in your project. What are the steps you went through?

1st step : We defined the amount of money the player has at the beginning (bank). And we defined a list of all the possible gambles. 

2d step : We ask the player 'how much he wants to gamble'. And we check that his bet is under or equal to the money he has. He can't gamble more than what he has in the bank (Casino doesn't give credit!).

3d step : We ask him what kind of bet he wants to do :
                - On number (between 1 and 36)
                - Or on Even or Odd

4th step : we generate a random choice of the computer that stands for the casino wheel between 1 to 36. 

5th step : Last important step we compare the player choice and the result of the wheel :
- If the player bets on a number, we compare it to the wheel! If it's the same, this is a huge earning : 35 times your bet. Not the same number and you lose all your gamble.
- If the player chose to bet on 'Even' or 'Odd', we see if the casino wheel number is even or odd with a modulo 2. and after this step we conpare it to the player choice. 

6th step : we see if the player has still enough money to play again. if he has enough we ask him if he want to continue or quit the table with the money he has. Otherwise, he just has to quit. 


## Organization
How did you organize your work? Did you use any tools like a trello or kanban board?

What does your repository look like? Explain your folder and file structure.

At first we try to create a repository and one of us fork it. But we understood that we could not both work at the same time. So
we create a common repository in GitHub. But then we discover that we had some technicals issues due to Python version, because we had different Python version. Even with help we could figure it out. 

So finally we remove the repository and we create a last one to put all our final work. And we used Zoom and slack to share our files. 
In our repository there is our code, this ReadMe file to explain how we process and a gitignore file.

We didn't used Trello or Kaban because we didn't have time. 

## Links
Include links to your repository, slides and trello/kanban board. Feel free to include any other links associated with your project. 

[Repository](https://github.com/Thomas-chenu/Casino_Roulette) 
[Slides](https://slides.com/thomaschenu/casinowheel)