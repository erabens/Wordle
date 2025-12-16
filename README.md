## Task
Create a working version of the game Wordle.

## Steps
1. <b>Research the game.</b>
  If you’ve never played, (quickly) study to understand the basic rules of the puzzle and start considering what types of coding tools (looping, searching, etc) will be necessary.
2. <b>Back End development.</b>
  Develop algorithms for checking a user’s guess against the secret word. Feel free to write methods (functions) outside of your main method for more legible code and to save yourself from repeating code over and over.
3. <b>Front End development.</b>
  Develop a way to tell the user about the correctness of their guess. You can use symbols or color (see below). Should be a positive experience for the user.

## Requirements
1. We have not discussed Arrays or ArrayLists yet, so creating a “word list” in order to play this as a one player game isn’t something we’re going to do for now. With this in mind, the game should be coded where the secret word is input by one user, the screen is cleared, and another user will begin trying to solve the puzzle with the secret word.
```
System.out.print("\033[H\033[2J");
System.out.flush();
```
2. All rules of the game should be followed (5 letters, 6 attempts, etc).

## Challenges (things to try AFTER basic functionality is completed)
1. [Color?](https://www.geeksforgeeks.org/java/how-to-print-colored-text-in-java-console/)
2. Determine a way to display all hints together before a new guess is made.
3. [Add a one-player mode?](https://gist.github.com/slushman/34e60d6bc479ac8fc698df8c226e4264)
4. Code ‘Hard Mode’? (must use previous hints in subsequent guesses)

## Some final notes:
- To COMPILE your runner file, use `javac main.java` in the terminal (NOTE: You will need to recompile after every change!)
- To RUN your compiled code, use `java main` in the terminal
- To COMMIT your changes to the repository, use `git commit -a -m '<your comment about the commit here>'` in the terminal
- To PUSH your changes to me, use `git push` in the terminal
