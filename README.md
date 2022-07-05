# 💰 React Treasure Hunt Game

### 🤔 Remember
- Pseudocode!!
- Ask clarifying questions

### 📚 User Stories
- As a user, I can see a page with a 3 by 3 grid board game with a question mark in each square.
    > Branch: grid
    > Added an empty <div> to Square component 
        - styled in CSS to add height, width, and border
        - imported and called in App.js
    > Mapped over board array in state, to display Square component for each iteration
    > Styling over the <div> for boardgame and centered the <h1>.
    > Passed the value of board to our square component to show the question mark
    > Styled the question mark to be larger and centered


- As a user, when I click on one of the question marks an alert appears with the index position of that question mark in the array.
    > Branch : alert-index
    > Passed index into Square component
    > Made an onClick method that alerts users what index the box is
    > Made a method on App.js to pull information upstream from our Child (Square)
    > Passed the method down to Square to be invoked when onClick is clicked
    

- As a user, when I click on one of the question marks instead of the alert the question mark turns into a tree emoji.
- As a user, if I select the winning square the question mark will become a treasure emoji and if I select the losing square the question mark will become a bomb emoji.
- As a user, I can click on a “Play Again” button that will restart the game.
- As a user, I can see a counter that shows how many guesses I have left. The counter starts at 5 and decrements one every time I click on a square that is not the treasure nor the bomb.
- As a user, I can see a message informing me that I won the game if I select the square that contains the treasure.
- As a user, I can see a message informing me that I lost the game if I select the square that contains the bomb.
- As a user, I cannot continue to play the game after I win or lose.
- As a user, I can see a message informing me that I lost the game when I run out of turns (the counter reaches zero).


### 🏔 Stretch Goals
- Consider how to handle a situation where the bomb and the treasure are at the same index.
