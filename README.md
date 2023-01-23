# word-puzzle

## Logline
### Flappy birds with word guessing

## Goal
### Successfully collect all the letters pertaining to the hints on the top.
### Dodge obstacles along the way
### Collect power ups and word plays along the way

## General Description
### The user would be moving in the vertical direction using controls while there is constant movement in the horizontal direction. The game begins with the level giving an idea about what the answer is about like a fruit, country. During the game, the user can collect hints and power ups along the way that would guide him towards the answer. The user needs to collect correct letters corresponding to the answer and once he collects all the correct letters the level is completed. If the user hits an obstacle, his health reduces. If the user collects a certain number of incorrect letters he loses and the game ends.

## Genre
### Endless runner, Trivia, Word Game 

## Technologies Used
### Unity 3D, C#, WebGL, Git

## Youtube Link
### https://youtu.be/B2QfEp7K4K8

## Link to Game
### https://chafale.github.io/test_wegl3/

## Team size
### 10

## Role played by me
### Backend Developer
      Designed and implemented all the powerups, and movement, score, fall mechanics.
      Designed and mentored other teammates in the implementation of obstacles, powerwords.

## Detailed Design
### Game Element
1. Various letters to be captured 
2. Obstacles to be avoided
3. Hints to guess the word
4. Dashes that will be filled
5. Power ups to use
6. Use words as a powerup - HEAL/GO


### Game Mechanics ( How to play )
#### Movement mechanic: Use the keyboard up/down arrow to move up/down.
#### Score mechanic: Fills the dashes when collecting the right letter
#### Fall mechanic: Hit an obstacle or capture letters that is not part of the word.
#### Size mechanic: Use L and I to reduce and increase the size of the object in level size
#### Obstacles - Static and Dynamic obstacles are present
      Rod - Static obstacle reduces 10% health
      Blade - Rotating obstacle reduces 15% health
      Mace - Moving obstacle reduces 15% health
      Fire - Static obstacle reduces 15% health
      Laser - Animation obstacle reduces 20% health
#### Collecting Powerups: Getting powerups to navigate through the levels
     Speed - Increases vertical speed
     AutoFill - Fills one letter in the word
     Health - Restores Health
     Split - Changes color with red being wrong and green being right
     Hint - Gives a clue about the word. Only three hints per word
#### Collecting words as a powerup
     HEAL - Collecting H,E,A,L restores full health
     GO - Collecting G,O makes the obstacles invisible for some time

### Note
#### I have shown all the features of the game in the link mentioned above. For source code, any queries regarding the implementation of the game and for new feature suggestions contact me at harshambh.hv@gmail.com.
