# score_letter
Iterate over each word and then each letter contained within vocabulary, and increment a counter for everytime the character 'letter' appears in a word. Return that counter.

# score_word
Iterate over each letter in the word and add the score of the respective letter towards a count, unless the letter has already appeared in the word. Return the score.

# filter_vocabulary_gray
Iterate through the words in vocabulary, and if the word contains the char 'letter' at all, free the pointer that corresponds to it and set it to NULL.

# filter_vocabulary_yellow
Iterate through the words in vocabulary, and if the word does not contain the char 'letter' in it, or has 'letter' in the same position, free the pointer and set it to NULL.

# filter_vocabulary_green
Iterate through the words in vocabulary, and if the word doesn't have the char 'letter' at that exact same position, free the pointer and set it to NULL.

