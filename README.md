# GB Studio D-Pad Code Entering

## Code Entering
Simple GB Studio mechanic for entering a code with the D-Pad.
Can be used to enter cheats or go to a specific level of a game.

### Why?
It's easier and cheaper to produce a flash card without save functionality.

I wanted to have a way of progressing a GB Studio game that has multiple levels, without the need of saving. Rather I would display a level code at the start of each level, containing up to 4 D-Pad button combinations, that gives you a specific value which then can be directed to a specific level.

## Why D-Pad?
The process of entering the code should be as simple and easy as possible. Selecting values with a cursor from a displayed number pad would be slow and not user friendly.

D-Pad combinations are easy to write down or even to remember. And very fast to be entered.

### Combinations
You can enter up to 4 combinations, which will give you up to 256 possible end-points (levels), which should be plenty for almost all GB games.

### How it works behind the scenes
Every direction of the D-Pad adds a vertain value to the code variable. 
I worked with 7, 13, 17, 43 which should give you a unique value in any of those 256 combinations (not confirmed by now. Can any math wizard help here?)