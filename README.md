# word_scramble_game

Word Scramble Game is a simple quiz game based on the rearrangement of letter to make a random word and the user have to guess the correct word out of it with the help of provided hint. If the user is able to guess the correct word it gives the result ‘correct’ and if he guesses wrong it shows ‘incorrect’.

# Prerequisites

- HTML
- CSS
- JavaScrip

# Approach

- Create the basic game layout using the HTML tags like divs, headings for titles and scrambled word and input, and buttons for taking user input and verification along with the relevant class names and ids as shown in the code example,
- Then, use those classes and ids to apply to style using the CSS properties like display, align content for structure, padding, margin, font size, background-color, and border to give it a better appearance.
- In JavaScript create a sample list of words and hints. Use the Math.random() method to get a random index to display the word and the hint using the document. getElementById method.
- Before displaying shuffle the letters of the word using math.randon and swap using a custom shuffle function.
- Define a function refresh to refresh the scrambled word and hint when the refresh button is clicked. Use the check function to verify the user input by clicking on the check button and displaying the resulting output.
