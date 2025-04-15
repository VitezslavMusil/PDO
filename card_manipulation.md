# Card manipulation

Archidekt's deckbuilder tool can manipulate cards in multitude of ways. Thanks to It's integration with [EDHRec](https://edhrec.com/) It can handily recommend cards that are staples in for any chosen commander and due to integration with [Commander Spellbook](https://github.com/VitezslavMusil/PDO/blob/main/card_manipulation.md) can list combos included or almost included in your deck. Optimization for cheapest, fanciest, newest or oldest cards across the deck is done with a few clicks.

The View As being refered here is Archidekt's default, Stacks

## Adding cards
- **Drag & Drop** - New cards can be dragged and dropped from sites like [EDHRec](https://edhrec.com/) or [Scryfall](https://scryfall.com/).
- **Default Qucik add bar** - Allows you to add cards by name. Can be adjusted using the gizmo different types of adding cards.
- **Card Search** - Opens up window with several options:
  - Archidekt search - Simplified version of [Scryfall syntax](https://scryfall.com/docs/syntax) with more user interface
  - Syntax search - Exact [Scryfall syntax](https://scryfall.com/docs/syntax)
  - EDHRecs - Lists the most popular cards for chosen commander from [EDHRec](https://edhrec.com/). **THESE CARDS ARE USED GENERALLY AND DO NOT HAVE TO ADHERE TO YOUR DECK THEME**
  - Landbase - Most used lands/land cycles
  - Combos - Fetches included/almost included combos in your deck from [Commander Spellbook](https://github.com/VitezslavMusil/PDO/blob/main/card_manipulation.md) complete with explanation
 - **Deck Import** - You may import lists or entire decks from a text file adhering to listed formats

## Card categories
- Unless specified, Archidekt has a default category for every card (Ramp for [Rampant Growth](https://scryfall.com/card/dsc/193/rampant-growth), Draw for [Quick Study](https://scryfall.com/card/fdn/513/quick-study) etc.)
- Cards that are either modular or do multiple things at once can be autoassigned to different categories even though they are functionaly identical, e.g. [Wildfire](https://scryfall.com/card/mm2/134/wildfire) being autoassigned into Removal while [Destructive Force](https://scryfall.com/card/m11/133/destructive-force) is considered Land Destruction
- While cards are Grouped as Categories, they can be freely moved from one category to another using Drag & Drop
- Cards can be moved from one category to another using either right click => Move to Category, or by opening the menu of a card (Hover over + O or clicking the arrow on the right side fo the card)

## Changing the printing of a card
- Open the card menu (Hover over + O or clicking the arrow on the right side fo the card)
- Use the printing bar by either entering a set name, set code (e.g. BRO for The Brother's War, MRD for Mirrodin) or the collector number (Foun at the bottom of most cards)
- All versions/arts of a card can be viewed by click the All Printings button in the card menu
