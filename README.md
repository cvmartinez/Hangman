# Hangman
Your goal is to build a Hangman game using everything you have learnt about Python programming.
- [ ] Randomly choose a word from the word_list and assign it to a variable called chosen_word. Then print it.
- [ ] Ask the user to guess a letter and assign their answer to a variable called guess. Make the String stored in guess lowercase.
- [ ] Check if the letter the user guessed guess is one of the letters in the chosen_word. Loop through each of the letters in the chosen_word and print "Right" if the letter is a match, "Wrong" if it's not.
- [ ] Create an empty String called placeholder. For each letter in the chosen_word, add a _ to placeholder. So if the chosen_word was "apple", placeholder should be _ _ _ _ _ with 5 "_" representing each letter to guess. Print out hint.
- [ ] Create an empty string called "display". Loop through each letter in the chosen_word If the letter at that position matches guess then reveal that letter in the display at that position. e.g. If the user guessed "p" and the chosen word was "apple", then display should be _ p p _ _. Print display and you should see the guessed letter in the correct position.But every letter that is not a match is represented with a "_".
- [ ] Use a while loop to let the user guess again. The loop should only stop once the user has guessed all the letters in the chosen_word. At that point display has no more blanks ("_"). Then you can tell the user they've won.
- [ ] Create a variable called lives to keep track of the number of lives left. Set lives to equal 6.
- [ ] If guess is not a letter in the chosen_word, Then reduce lives by 1. If lives goes down to 0 then the game should end, and it should print "You lose." print the ASCII art from the list stages that corresponds to the current number of lives the user has remaining.
- [ ] Update the word list to use the word_list from hangman_words.py
- [ ] Update the code to use the stages from the file hangman_art.py
- [ ] Import the logo from hangman_art.py and print it at the start of the game.
- [ ] If the user has entered a letter they've already guessed, print the letter and let them know. We should not deduct a life for this. e.g. You've already guessed a
- [ ] If the letter is not in the chosen_word, print out the letter and let them know it's not in the word. e.g. You guessed d, that's not in the word. You lose a life.
- [ ] Update the code below to tell the user how many lives they have left. print("****************************<???>/6 LIVES LEFT****************************")
- [ ] Update the print statement to give the user the correct word they were trying to guess. e.g. IT WAS <Correct Word>! YOU LOSE
