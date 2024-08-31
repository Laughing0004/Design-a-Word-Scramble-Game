# Word Scramble Game

This is a simple Word Scramble Game built with HTML, CSS, and JavaScript. The game challenges the user to unscramble a given word within a limited time. The user can also refresh the word to get a new challenge.

## Features

- Scrambled words are displayed with a hint to help the user.
- The user has 15 seconds to guess the correct word.
- The game keeps track of the number of attempts.
- Users can refresh the word to get a new scrambled word and hint.
- Feedback is provided based on the user's input.

## Project Structure

The project consists of the following files:

- `index.html`: The main HTML file that structures the game interface.
- `style.css`: The CSS file for styling the game interface.
- `script.js`: The JavaScript file that handles the game logic.

## How to Play

1. The scrambled word will be displayed on the screen along with a hint.
2. You have 15 seconds to enter the correct word in the input box.
3. Click "Check Word" to see if your guess is correct.
4. If the word is correct, you'll receive a success message.
5. If the word is incorrect, you'll be prompted to try again, and your number of attempts will increase.
6. You can click "Refresh Word" at any time to get a new scrambled word.

## Running the Game

To run the game locally:

1. Clone the repository or download the ZIP file.
2. Open `index.html` in your web browser.
3. The game will start automatically.

## Customization

- You can modify the words and hints by editing the `words` array in the `script.js` file.
- Adjust the time limit or other settings directly in the `script.js` file.

## Example of Word Data Structure

```javascript
const words = [
    { word: "EXCHANGE", scrambled: "A E G E X C N H", hint: "The act of trading" },
    { word: "PROGRAM", scrambled: "R G M O A P R", hint: "A sequence of instructions" },
    { word: "JAVASCRIPT", scrambled: "A P J V I C R S T A", hint: "A popular programming language" },
    { word: "DATABASE", scrambled: "A T A D S E B A", hint: "A structured set of data" },
    { word: "DEVELOPER", scrambled: "L E P O E R D E V", hint: "A person who writes code" }
];
