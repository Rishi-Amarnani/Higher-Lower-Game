Higher Lower Game
Rishi Amarnani


Premise
-----------------------------------------------------------------
This is a rendition of the popular browser based game,
Higher Lower, which involves comparing the popularity
of various search terms on Google. I wanted to play this game
at a local Dinner Party, but most of the atendees were
Indians who would better appreciate a version of Higher Lower
based on Indian or Bollywood-related search terms. I set out
to produce just that.

General Programming Approach
----------------------------------------------------------------
The Program was developed in Java, with use of the Java SWing
GUI libraries. The logic of the game was simple. 

Show two pictures, with two descriptions or search terms.
Show the search count of the first term, but not the second.
Have the player guess whether the second term was searched more
or searched less, than the first term. If the player answers
correctly, keep going with more comparisons. The game ends
whenever a comparison is answered incorrectly.

The Search Terms and Search counts are stored in a text file,
and are fed in each time the program is run. The Images are also
stored externally. The Program provides an abstraction for the
logic of the game, so we can add more entries to the game by
simply adding a line to the text file and adding an image file
for it. We don't have to edit the program or the code in order
to expand the data it uses.

Disclaimer
-----------------------------------------------------------------
I want to make it clear that I did not come up with the idea for
Higher Lower. I love the original browser based game and I give
the creator full credit for it. I simply wanted to make my own
version of the game to fit my own needs, for leisure, essentially.