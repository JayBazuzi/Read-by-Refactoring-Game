# Read-by-Refactoring Game

A game for teaching Read-by-Refactoring. 

## Setup

A team sits around big screen that everyone can see, showing a long function. A Smart Input Device sits at they keyboard.

> What are some of the things that make large, gnarly codebases difficult to work in?

Team generates a list of 5-10 items. Need not be comprehensive.

> These are all important. Today we're going to focus on Readability, specifically two concerns:
>
>     - Misleading names
>     - Functions that are too long
>
> We're going to play a game. We win the game when everyone understands this function. When you have an insight about what this function does, you can explain it the rest of the team by making one of two moves: Rename or Extract Method.

When a player calls out a move, the Smart Input Device will make the change and commit it to the branch.

## Rules

### Round 1

The only valid moves are:

- Rename
- Extract Method

Anyone can make a move, but don't make two in a row, so everyone gets a chance.

We may also:

- Scroll
- Zoom
- Revert the last move

### Round 2

Allow any automated refactoring.

### Round 3

Allow recipes.
