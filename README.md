# Elephant

Elephant is a flip-the-card style memory game. The aim of the game is to flip 2 cards and hopefully find a pair. When you find all of the pairs the game is over and you have won. This quicker you win the better you played. This is measured in moves made and with a timer. 

The game is not very difficult and is aimed at people of all ages that have a few minutes to kill.

![Screenshot 2022-06-16 at 22 21 12](https://user-images.githubusercontent.com/98256205/174167483-edb413b4-3012-4853-835d-bbe8ceff3e00.png)

## Features

### Application General

The app has 3 main screens as listed below;

- The pre-game screen: Hosting the logo, rules and button to begin game.
- The game screen: Hosting the game-board, timer and move counter.
- The post-game screen: Displaying the performance stats and a button to restart the app.

### Navigation

![Screenshot 2022-06-16 at 22 26 34](https://user-images.githubusercontent.com/98256205/174168768-522ed7e4-992b-4067-8ec0-ad8438fad185.png)
- Featured on the pre-game screen is a button to begin the game.

![Screenshot 2022-06-16 at 22 28 17](https://user-images.githubusercontent.com/98256205/174169030-829b30fa-159e-46fa-ab0d-7ab2062c7f29.png)
- After the game has been played there is a button to play again. This button reloads the page so that the user can play again.

### Gameboard
![Screenshot 2022-06-16 at 22 37 07](https://user-images.githubusercontent.com/98256205/174170108-505a268a-d3ed-4a4c-81e3-9969cd2f444d.png)
- The gameboard is a 4x4 board of cards which can be flipped over with a click. Displayed here are a matching pair which will stay overturned when found to be matching. Were they not matching they would turn back over to the starting position.

### Stats
![Screenshot 2022-06-16 at 22 37 17](https://user-images.githubusercontent.com/98256205/174241420-c1ef5925-12b2-40f0-8993-cb696674d709.png)
- Here the timer is displayed. It starts when the button is pressed on the pre-game screen.
- A move counter is also displayed which increments each time a card is turned over by the user. 

### Win Message
![Screenshot 2022-06-17 at 08 00 45](https://user-images.githubusercontent.com/98256205/174243549-6301b23e-09b7-4167-a4c0-9b7f3e91912f.png)
- Here a message is displayed to the user upon completion of the game. It displays their final move count and time taken.

## Testing

- I have tested the website on Chrome, Firefox and Safari.
- I have tested the site at different screen sizes using Chrome Developer Tools.
- I have given the site to users for feedback on the experience.
- I have confirmed that the interactive items work on every page.

## Bugs
### Solved Bugs
- I encountered a few bugs whilst developing this app. Whilst testing on iPhone I discovered that there was not support on Safari for the transform property in css. After some research I found that the webkit property could be used to add support for these browsers.

### Unsolved Bugs
- I tried to write a function that would reset the state of the gameboard rather than reloading the page but I was unable to get the board to reset and ammend the cards with a new set. In the interest of ensuring the MVP I elected to create a button with a reload function instead. 

## Validator Testing
## HTML
- The W3 HTML validator found no errors in the HTML code.

## CSS
- The W3 CSS Validator found no errors in the CSS code.

## Javascript
- The JShint validator found no errors in the Javascript code.




