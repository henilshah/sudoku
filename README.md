The following game potrays the basic 3x3 sudoku puzzle. User can input numers [1-9] and follow along to the completion of the game. The pattern of given sudoku is referred from http://en.wikipedia.org/wiki/File:Sudoku-by-L2G-20050714.svg

This game is hosted at: http://henilshah.x10host.com/

### Game Description
- As a user you input the numbers and finally approach towards the complete valid sudoku.
- Mouse hover effect highlights current row and column of the chosen grid.
- Wrong entry of the input number is highlighted by red mark asking for a valid input for the current entry. 
- 'Status' button will check validity of your current number placement
- By hitting 'I Quit' you get the valid solution for entire sudoku.
- 'New Game' will restart the entire game.
- Due to time constraint, board generator has not been added. 
- This application is tested in IE10, Chrome, Safari and Firefox. It scales according to browser size and mobile devices.

##File Structure
- index.html : primary html file for sudoku table rendering. It also contains the game logic.
- game.js : Sudoku render logic.
- main.css : All the styling for the game
- mobile.css: media queries for particular mobile devices.


## External Libraries:
- underscore : Really good templating engine.
- Jquery : Very handy js library, fast, cross browser ...


## Future Scope:
- Definitely add a new game generator, that can generate a new sudoku puzzle each time.
- Give user more choices with game difficulty such as: Easy, Medium, Hard..
- Work on providing better user interface. 
- Work on code performace itself :)

