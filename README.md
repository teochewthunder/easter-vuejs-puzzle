# VueJS Easter Puzzle

For this puzzle game, components should be listed in the VueJS format; namely in terms of UI, data and methods.

## HTML
- A placeholder for `Vue` to operate in. In it, we have:
    - Button for starting/stopping game.
    - Display for seconds remaining
    - Display for messages.
    - 5 x 5 grid of squares. Each square is 25 x 25 pixels.

## Data
- `timer` keeps track of whether the game has begun. If it is `undefined`, then game is stopped.
- `seconds` is the amount of seconds still remaining. Default value is 100.
- `btnText` is the text on the button.
- `message` displays a message for the user.
- - `pieces` is an array of objects, each of which represents a square in the grid.

## Methods

*Note: For Safari, the outline does not come up. Possibly need to implement webKit.*
