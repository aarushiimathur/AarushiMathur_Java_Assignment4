Overview

This Java program simulates a deck of 52 playing cards, allowing various operations such as shuffling, dealing cards, searching for specific cards, and displaying cards based on suits or ranks.

Features

Create a deck of 52 standard playing cards

Print the entire deck

Print a specific card

Shuffle the deck

Deal 5 random cards

Find a specific card in the deck

Display all cards of a given suit

Display all cards of a given rank

Class Descriptions

Card

Represents an individual playing card with a rank and a suit.

Overrides toString() to display the card in "Rank of Suit" format.

Deck

Manages the deck of 52 cards.

Methods:

createDeck(): Initializes the deck.

printDeck(): Prints all cards in the deck.

printCard(Card card): Prints a specific card.

sameCard(String suit): Displays all cards of a given suit.

compareCard(String rank): Displays all cards of a given rank.

findCard(String rank, String suit): Checks if a specific card exists in the deck.

dealCard(): Deals 5 random cards from the deck.

shuffleDeck(): Randomizes the deck order.

Menu Options

When running the program, the user can choose from the following options:

Print the deck

Shuffle the deck

Deal 5 random cards

Find a specific card

Display all cards of a given suit

Display all cards of a given rank

Pick 2 random cards

Distribute cards to 3 players

Exit the program
