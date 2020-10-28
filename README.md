# Self Playing Flappy Bird Game

Flappy Birds Game, the toughest game yet the easiest but still very difficult to win.
How about a system plays the game and becomes **UNBEATABLE**

Inspired by CodeBullet, I've designed a self playing Flappy birds game in python.
This game starts with a population of 50 Flappy birds in the beginning and then try to recognize the pattern. Generations pass on till the last bird is not hit with the pipes.
As and when the birds cross the pipe, the recognize a pattern themselves, that by when and how should they move themselves, that gives them a reward, # of which after certain obstacles, the bird is well aware about how to cross the pipes and becomes inevitable.
This means that as the birds survive each and every pipe, they become more fit and by crossing certain pipes, its almost impossible for the bird to hit the pipe again.

This project is on the NEAT Algorithm, that calculates the pipe height and the ability of the bird to cross the pipe. If the bird ever hits the pipe, it is given Negative Reward, but if the bird crosses the pipe successfully, then it is given Large Positive Reward which encourages the bird to identify the way in which it needs to jump, in order to avoid hitting the pipes.

The GIF indicates how the game runs :)

![Sample of how the game is played](https://github.com/GursahajKohli/Self-Playing-Flappy-Bird-Game/blob/main/FlappyBird/imgs/ezgif.com-gif-maker%20(5).gif)

I hope you liked my work !
