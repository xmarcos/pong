# Pong

Atari's 1972 classic, implemented in Lua with LÖVE.

## Assignment 0: "Pong, The AI Update"

Code for **Assignment 0** of [CS50's Introduction to Game Development](https://online-learning.harvard.edu/course/cs50s-introduction-game-development).

The game now supports two `types` of Paddles, `human` and `bot`.

The `bot` player follows the ball as it moves, so it's very hard to beat in its current implementation.

I'll try to add a difficulty selector in the future, to give humans a chance. 😅

### bot vs bot

The game can be configured so that both players are bots. Replace `Paddle:human()` with `Paddle:bot()` on line 95.

## Notes

The code has been upgraded to run on the latest version of LÖVE 2D —11.3 (Mysterious Mysteries).