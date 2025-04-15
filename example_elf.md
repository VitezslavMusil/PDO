# Making and Elf deck

This example guides you through making an Elf tribal with [Lathril, Blade of the Elves](https://scryfall.com/card/fdn/242/lathril-blade-of-the-elves) in the command zone.
Various methods for card manipulation will be used with the resulting decklist availible [here](https://archidekt.com/decks/12532933/lahtril_blade_of_the_elves_pdo).

- [Deck builder rundown](https://github.com/VitezslavMusil/PDO/blob/main/deck_builder.md)
- [Card manipulation](https://github.com/VitezslavMusil/PDO/blob/main/card_manipulation.md)

## Creating a new deck
1. If you have an account, log in. If not, please register first. **You will not be able to save your deck without an account**
2. On the main screen, click the orange "New Deck" button
3. You will be presented with a new deck option screen. Enter your deck name (Lahtril, Blade of the Elves (PDO) in this case), set the format to "Commander".
4. Scroll down until you see the "Command zone" field and enter the name of your commander (Lahtril, Blade of the Elves in this case).
5. Click the green "Create deck" button and a new, blank deck with the commander is ready to be built.

## Adding cards by Quick add
There are certain cards that are autoinclude in Elves, like [Priest of Titania](https://scryfall.com/card/mh3/286/priest-of-titania) or [Llanowar Elves](https://scryfall.com/card/fdn/227/llanowar-elves), so we can add these easily using the Quick Search options.

**NOTE: This method displays only the card names before you add them to your deck. This might result in adding different cards with similar names thanks to autocomplete.**

1. In the deck filters bar, next to the orange "Card search", click into the "Quick Add" field.
2. Type in part/whole name of a certain card ([Priest of Titania](https://scryfall.com/card/mh3/286/priest-of-titania) in this case) and click on the result with the name of the card you are searching for.
3. The card is now added to your deck. You can proceed to add more cards this way.

## Adding cards by Archidekt search
We added a few cards we know form the top of the head. To find us more cards of the desired type (Elf creatures in this case), we are going to use the Archidekt search.

1. In the deck filters bar, click the orange "Card search" button.
2. In the now displayed menu, click the "Archidekt search" section in the top bar.
3. Open up the "Advanced options". You will see a lot of empty fields with placeholder text.
4. On the top of the "Advaced options", you will see six mana symbols. Tick off all the symbols that are excluded out of your color identity (Red, Blue and White in this case).
5. On the right side of the mana sybols, make sure the "Options" is set to "Identity".
6. Click the "Type" field, choose the card type you want to search for ("Creature" in this case), then click the field again.
7. In the "Subtype" field, type the subtype you want to search for ("Elf" in this case), then press enter.
8. At the top of the menu in he right side, click on the green "Search" button.
9. Now you have a list of cards that adhere to your criteria (All creature elves with the identity of GB in this case). To add a card, simply click the plus sign on the card you want to add to your decks.
10. After you are done adding cards, click close and you will see all the cards you added in your deck.


## Adding card by Scryfall syntax
After adding a few more cards from Archidekt search, let's use something a bit quicker: [Scryfall syntax](https://scryfall.com/docs/syntax).
We will add some noncreature Elf cards, like [Elvish Promenade](https://scryfall.com/card/khc/59/elvish-promenade).

1. In the deck filters bar, click the orange "Card search" button.
2. In the now displayed menu, click the "Syntax search" section in the top bar.
3. Into the seach field, type the Scryfall expresion you want to search for ("t:elf -t:creature" in this case).
4. At the top of the menu in he right side, click on the green "Search" button.
5. Now you have a list of cards that adhere to your criteria (All noncreature elves in this case). To add a card, simply click the plus sign on the card you want to add to your decks.
6. After you are done adding cards, click close and you will see all the cards you added in your deck.

## Adding lands by Landbase 
After we are done adding cards, all that is left is adding a landbase. We will add them by two means: By using Archidekts "Landbase" function and later by using "Import cards"

1. In the deck filters bar, click the orange "Card search" button.
2. In the now displayed menu, click the "Landbase" section in the top bar.
3. At the top of the menu in he right side, click on the green "Search" button.
5. Now you have a list of cards that adhere to your criteria (Land cards adhering to your decks color identity). To add a card, simply click the plus sign on the card you want to add to your decks.
6. After you are done adding cards, click close and you will see all the cards you added in your deck.

## Addign cards by Import cards
Archidekt (as well as many other sites) accept predefined formats of card lists, with the simplest being shown [here](https://github.com/VitezslavMusil/PDO/blob/main/import_landbase_example.txt).

1. In the deck overview, click the "Import cards" button.
2. You will see a list of already included cards. **DO NOT DELETE ANY OF THE TEXT, IT WILL REMOVE CARDS FROM THE DECK**
3. At the end of the document, paste the text from the list of cards you want to include.
4. At the bottom of the list on the list on the right side, click "Save changes".
5. Close the menu. You should now see the importred cards in the card section.
