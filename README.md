# IsenCards

A two-person card game I wrote in [MUSHcode](http://www.mushcode.com/), a Lisp-like "softcode" language that runs inside of a [MUSH](https://en.wikipedia.org/wiki/MUSH). If that sentence doesn't make sense: imagine a text-based card game inside of a chat room, and you're pretty close.

This was written way back in 1995 for the Tolkien-themed [ElendorMUSH](http://www.elendormush.com/) (holy smokes, Elendor is still up and running after almost 25 years!). In particular it was built for my friends living in Isengard (you know, Saruman and the orcs and all that), but the base code was eventually modified and spread to other cultures as well, and possibly to other MUSHes. As far as I know, it ended up being playable for at least a few years after I stopped connecting.

Being able to jump into a game or chat system that actively encourages users to extend and build out new code on top of the platform is pretty neat. Now, to get building things like this for Slack, I guess…

## The Rules

Wow, are you still here?? Okay, in case you happen to get this running somehow, here are the rules as copied from the `$rules` command:

> Here are the rules:
Each player starts with a deck of 13 cards, and the 'House' has its deck of 13 cards. They range in value from one to thirteen, with `Snaga` as the lowest and `Darkness` as the highest. The game consists of 13 turns, which are started by having the House draw the top card from its shuffled deck. This card is the card at stake, and is what determines the score. Then each player secretly selects a card that he wants to play from his or her deck, and whoever has the highest valued card between the two players wins the turn. The winning player receives points equal to the value of the House's card. The cards that the players played are removed from their decks, and the card that the house played is removed from its deck. Once the house runs out of cards to play the game ends, and the player with the highest score wins.