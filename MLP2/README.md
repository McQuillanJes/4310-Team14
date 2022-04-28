# English Word Frequency

Description: This dataset contains the counts of the 333,333 most commonly-used single words
on the English language web, as derived from the Google Web Trillion Word Corpus.

AttributeNames:
 - word (string) - An english word
 - count (int) - the amount of time the english word is used 

Dataset Size: 2 columns and 333333 unique values

# Wordle Tweets

Description: A daily sample of Wordle results tweets since Wordle 210.

Description: 
  
  - wordle_id (int) - The wordle id for the day
  - tweet_id (int) - The id of the tweet
  - tweet_date (date) - The day and time the tweet was posted
  - tweet_username (string) - The user of the Tweet
  - tweet_text (string) - The contents of the tweet

Dataset Size: 5 columns and 486000 unique values

# answers.csv
Description: This dataset contains every wordle answer in order
AttributeNames
  - word (string) - The word in question
Dataset Size:1 column and 2315 unique values

# other_words.csv
Description: This dataset contains every acceptable wordle guess that isn't an answer
AttributeNames
  - word (string) - The word in question
Dataset Size:1 column and 10,657 unique values
