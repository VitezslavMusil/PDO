# Deck builder rundown

The main function of Archidekt is creating, updating, maintaining and overseering your decks. As this documentation is regarding Commander decks, some information provided is exlusively in the context of EDH.

## Deck builder sections
Following contents are listed from top to bootom of Archidekt's deckbulding tool 
1. **Deck overview** - The top of the page, just under navigation bar. Basic deck information like It's monetary cost, format, legality, brackets etc.
2. **Deck filters** - Adding cards, adjusting the veiw of cards, retailer selection section
3. **Card section** - Cards are displayed in their respective categories using criteria from the deck filters section
4. **Deck stats** - Information about your mana curve, color distribution, count of cards in categories etc.
5. **Deck Tokens & Extras** - Tokens, emblems, dungeons etc. your deck uses
6. Aritcles - Headlines of the newest articles on Archidekt
7. **Description** - Primer of the deck
8. Comment section

## Section details
Below are some details in certain that might get confusing otherwise
### Deck overview
- **Est deck cost** - Dependent on the currently chosen retailer in the Deck Filters section. Retailer in the left option is applied.
- **Salt sum** - The total amount of salt you deck induces based on the annual salt survey of [EDHRec][https://edhrec.com/] users. Card are voted on being salty on a 0-4 scale. [Salty cards list][https://edhrec.com/top/salt]
- **Collaborate** - Allows other users of your choice to edit this deck outside of the main settings (Great for making a deck with friends!)

### Deck filters
- **Group by** - Groups cards by criteria into blocks depending on current View As option
- **Sort by** - Sorts cards in blocks by certain criteria, does not change blocks
- **Price sources** - Current option for calculating the monetyra price of the deck. Left one is primary (Used for total price displayed in Deck overwiev), right one secondary
- **Deck filter searchbar** - Unless empty, card section displays only cards fitting the criteria in this searchbar using [Scryfall syntax][https://scryfall.com/docs/syntax]

### Card section
- Dsipalys cards based on the deck filters criteria
- [Card manipulation][https://github.com/VitezslavMusil/PDO/blob/main/card_manipulation.md]

### Deck stats
- Clicking on mana symbols or columns highlights cards fitting the cirteria (e.g. clicking on the column 6 in Red Spells higlights all red spells costing 6 mana)
