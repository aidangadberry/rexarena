# RexArena

An application where users can create decks, add / remove cards from decks, and visually sort / organize cards in a deck

## Features
  * account creation
  * deck creation
  * search card in Scryfall API
  * add / remove cards
  * organize cards based on cost / type / rarity / color etc
  * drag & drop sandbox for moving cards in deck around

## Schema
  * Account
    - username
    - password
    - decks
  * Deck
    - owner
    - name
    - format
    - image
    - main
    - sideboard
  * Card
    - name
    - cost
    - type
    - text
    - image
    - color
    - rarity
