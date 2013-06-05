# Guessing Game in Python

## Goal

Let's make a game! This game will be for one human player and one computer
player. The person is going to pick a number between 1 and 100 and the computer
has to guess what it is. If the computer's guess is too high, the person has to
type "lower", if the computer's guess is too low, the person has to type
"higher". When the computer gets it right, the person must type "winner!".
The computer has six tries to guess the number, or else it loses.

## Plan

All good programmers have some kind of a plan for their program. Here's the
steps of the game.

- First greet the player. Then ask them to pick a number between 1 and 100
	without typing it in.
- Wait for the player to press enter.
- Make a first guess.
- Ask the player if the guess was too high or too low.
- Get an answer from the user.
- If the answer was "higher", make a higher guess.
- If the answer was "lower", make a lower guess.
- If the answer was "winner", print a gloating message and exit.
- If the computer doesn't get the number after six tries, print a sad message
	and exit.
