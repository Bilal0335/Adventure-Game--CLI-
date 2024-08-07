# Fuel Battle Game

### ***Introduction:***

Your script is a simple text-based game where a player can choose to fight against one of three types of opponents: Skeleton, Assassin, or Zombie. The player can perform different actions like attacking, drinking a health potion, or running away. The game continues until the player or the opponent runs out of fuel.

*Here's a breakdown of how the script works:*

#### **Script Breakdown:**

##### **1. Imports and Helper Functions:**

* **`import inquirer from "inquirer"`** : For handling user prompts.
* **`import chalk from "chalk"`** : For colored and styled terminal output.
* **`totileCase` function** : Converts the first letter of each word in a sentence to uppercase.

##### 2. Classes:

* **`Player` Class** : Represents the player, with methods to decrease and increase fuel.
* **`Opponent` Class** : Represents the opponent with a similar fuel management system.

##### 3. User Input for Player and Opponent:

* Prompts the user to enter their name and select an opponent from a list.

##### **4. Game Loop**

* Depending on the selected opponent, the game will enter a loop where the player can choose an action (Attack, Drink Portion, or Run for your life...).
* Actions will affect the fuel of the player and the opponent, and the game will end if either's fuel reaches zero.

##### Key Points

* **Fuel Management** : The player's and opponent's fuel decreases or resets based on actions.
* **Game Termination** : The game exits when either the player or the opponent loses all fuel.
* **Randomness** : The outcome of attacks is determined randomly.

##### Possible Improvements

* **Refactoring** : The code for handling each opponent is very similar. You could refactor this into a method or a separate function to avoid repetition.
* **Error Handling** : Adding error handling for unexpected inputs or issues with user prompts.
* **Game States** : You might consider adding more states or features to make the game more complex and engaging
