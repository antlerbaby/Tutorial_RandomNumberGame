# Tutorial_RandomNumberGame
JavaScript Practice with Random Number Game from MDN web docs.

<ul>Exercise:</ul>
Create a simple guess the number type game. It should choose a random number between 1 and 100, then challenge the player to guess the number in 10 turns. After each turn the player should be told if they are right or wrong and, if they are wrong, whether the guess was too low or too high. It should also tell the player what numbers they previously guessed. The game will end once the player guesses correctly, or once they run out of turns. When the game ends, the player should be given an option to start playing again.
<ol>
  <li>Generate a random number between 1 and 100.</li>
  <li>Record the turn number the player is on, from 1 to 10. Start it on 1 and end on 10.</li>
  <li>Provide the player with an input field to guess what the number is, and a submit button.</li>
  <li>Once a guess has been submitted, record their guess so the user can see their previous guesses.</li>
  <li>Next, check whether it is the correct number.</li>
  <li>If it is correct:
    <ol>
      <li>Display congratulations message.</li>
      <li>Stop the player from being able to enter more guesses.</li>
      <li>Display a "Play Again" control allowing the player to restart the game.</li> 
    </ol>
    </li>
  <li>If it is wrong and the player has remaining turns:
    <ol>
      <li>Tell the player they are wrong.</li>
      <li>Allow them to enter another guess.</li>
      <li>Increment the turn number by 1 until it reaches 10.</li>
     </ol>
     </li>  
  <li>If it is wrong and the player has no turns remaining: 
    <ol>
      <li>Tell the player it is game over.</li>
      <li>Stop the player from being able to enter more guesses.</li>
      <li>Display a "Play Again" control allowing the player to restart the game.</li>
    </ol>
    </li>  
<li>Once the game restarts, make sure the game logic and UI are completely reset, then go back to step 1.</li>
</ol>
  
