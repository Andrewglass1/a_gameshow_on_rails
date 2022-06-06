# A Gameshow On Rails: Ta-boolean
A Ruby On Rails game created for [RailsConf 2022](https://railsconf.org/program/sessions#session-1304)


## How To Play
### Ta-boolean rules
Ta-boolean is played similar to Catch Phrase/Taboo/Heads Up:
- A person or team (clue-giver) is shown/handed a card with a word or phrase
- The clue-giver then tries to get a person or team (guesser) to say the word or phrase
- The clue-giver cannot say the phrase, or the 'reserved words' listed on each card.
- In the spirit of the game, the clue-giver should try to *explain* the concept, not use word-play or parallel concepts. e.g. if the word is 'gem', the guesser shouldn't say: "This word rhymes with hem" or "A precious stone".

![taboolean_card18](https://user-images.githubusercontent.com/1313946/172186860-d6c86f12-f218-42e7-894e-736a60994c24.jpg)

### Daily Test-Doubles
As a fun surprise, "Daily Test-Doubles" were inserted randomly into the game. These included audio from a 5-year-old asking curious questions with no single answer (e.g. "Whats coding?", "How much does the internet weigh", etc)


### Game structure
At RailsConf, Ta-boolean was played in a casual format with teams of two without keeping score. Cards were shown on a projected screen, and the two guessers faced the audience so that they could not see the screen.

Ta-boolean can be played in a similar format with any scoring rules. You could also use the printable cards and play without a screen.

## What's in this repo
- `printable_cards/` A directory with .pdf files for printing out 60 taboolean cards.  One file contains a design for printing the back of the cards
- `taboolean_cards/` A directory with .jpg files of 60 taboolean cards.
- `test_daily_doubles/` A directory with the audio for the 'test_daily_doubles'. This includes the kids asking questions, and humorous responses.
- `taboolean_card_template.indd` A InDesign template file which can be used to create more cards using an [InDesign Data Merge](https://helpx.adobe.com/indesign/using/data-merge.html)
- `wordlist.xlsx` An excel file with the wordlist.


## Future development
Please use this game as you wish! Future development could include making a web-application version of the game, and/or splitting the cards up into categories/values, allowing players to pick which category/value they want to attempt next (ala Jeopardy!). 

## Contact
You can contact me at [andrewglass1@gmail.com](mailto:andrewglass1@gmail.com)


