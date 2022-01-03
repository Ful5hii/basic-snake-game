# Python snake game
A super simple, easy, python snake game to use and add on to yourself

## How to play
Go to this link https://replit.com/@Skellyy/Basic-Snake-Game?v=1 make sure you make the turtle graphic full screen and use the arrow keys to move.

or

Go to https://www.replit.com and sign up/login if need be, then,
create a new repl, and in the top corner, press 'import from github'.
Once you get to that page, paste in the github repo link
and press the big blue button 'Import from Github'
and you're done!

## Editing code
I have added notes to the pieces of code to help you understand what the code does, and also to edit and expand the game. Here is an example:
```python
class Snake:
    def __init__(self):
        self.headposition = [20, 0] # keeps track of where it needs to go next
        self.body = [Square(-20, 0), Square(0, 0), Square(20, 0)] # body is a list of squares
        self.nextX = 1 # tells the snake which way it's going next
        self.nextY = 0
        self.crashed = False # I'll use this when I get around to collision detection
        self.nextposition = [self.headposition[0] + 20*self.nextX,
                             self.headposition[1] + 20*self.nextY]
        # prepares the next location to add to the snake
 ```


## My other projects
Check my Github page https://www.github.com/ful5hii for more projects

Check my website https://fulshi.weebly.com for all my projects
