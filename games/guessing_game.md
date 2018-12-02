# Let's Make a GUESSING GAME!!

Let's use while loops to create a guessing game.

The Challenge:

Write a program that picks a random integer from 1 to 100, and has players guess the number. The rules are:
<ul>
  <li>If a player's guess is less than 1 or greater than 100, say "OUT OF BOUNDS"</li>
  <li>On a player's first turn, if their guess is within 10 of the number, return "WARM!"
  further than 10 away from the number, return "COLD!"</li>
  <li>On all subsequent turns, if a guess is closer to the number than the previous guess return "WARMER!"
  farther from the number than the previous guess, return "COLDER!"</li>
  <li>On all subsequent turns, if a guess is closer to the number than the previous guess return "WARMER!"
  farther from the number than the previous guess, return "COLDER!"</li>
  <li>When the player's guess equals the number, tell them they've guessed correctly and how many guesses it took!
  </li>
</ul>

### STEPS

1. First, pick a random integer from 1 to 100, using the Math.random() method, and assign it to a variable.

2. Next, console log out the rules of the game.

3. Create an array to hold guesses. Note that zero is a good initial placeholder value for the element at index 0 because 0 evaluates to false.

4. Write a while loop that asks user for a valid guess. Hint: the prompt() and alert() methods are available as methods from the global Window object in our console. Make sure the user provides a VALID guess. Test it a few times to see that it works.

5. Write a while loop (utliizing the one you made above and adding more code to it) that compares the player's guesses to the number. If the player guesses correctly, tell the player that she has won and break out of the loop. Otherwise tell the player if they are getting warmer or colder, and continue asking for guesses.

Note that the first guess should return "WARM!" or "COLD!".

Hints:
<ul>
  <li>It may help to initially sketch out the combinations on paper first.</li>
  <li>You can use the Math.abs() method to find the absolute value of a number.</li>
  <li>As you push guesses to the guesses array, note that to compare the value of the last guess, you would want to grab the element from the second to last index. [guesses.lenght - 2]</li>
</ul>


HAVE FUN!!
