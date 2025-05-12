# Making an Elf Deck

This example guides you through making an Elf tribal deck with [Lathril, Blade of the Elves](https://scryfall.com/card/fdn/242/lathril-blade-of-the-elves) in the command zone.  
Various methods for card manipulation will be used, with the resulting decklist available [here](https://archidekt.com/decks/12532933/lathril_blade_of_the_elves_pdo).

- [Deck builder rundown](https://github.com/VitezslavMusil/PDO/blob/main/deck_builder.md)
- [Card manipulation](https://github.com/VitezslavMusil/PDO/blob/main/card_manipulation.md)

## Creating a New Deck

1. If you have an account, log in. If not, please register first.  
   **You will not be able to save your deck without an account.**
2. On the main screen, click the orange **"New Deck"** button.
![obrazek](https://github.com/user-attachments/assets/0382e642-b97c-4bb4-85ed-673f1506bbf8)

3. You will be presented with a new deck options screen. Enter your deck name (*Lathril, Blade of the Elves (PDO)* in this case), and set the format to **Commander**.
![obrazek](https://github.com/user-attachments/assets/b2c1de8c-619e-498e-88e1-604c05b7809e)

4. Scroll down until you see the **"Command Zone"** field and enter the name of your commander (*Lathril, Blade of the Elves* in this case).
![obrazek](https://github.com/user-attachments/assets/1bad532d-26dd-42ec-8451-607133c40c33)

5. Click the green **"Create Deck"** button. A new, blank deck with your commander will now be ready to build.

## Adding Cards via Quick Add

There are certain cards that are auto-includes in Elf decks, like [Priest of Titania](https://scryfall.com/card/mh3/286/priest-of-titania) or [Llanowar Elves](https://scryfall.com/card/fdn/227/llanowar-elves). We can add these quickly using the **Quick Add** option.

> **NOTE:** This method displays only card names before you add them to your deck. This may result in adding different cards with similar names due to autocomplete.

1. In the deck filters bar, next to the orange **"Card Search"**, click into the **"Quick Add"** field.
![obrazek](https://github.com/user-attachments/assets/fc1014bf-82f7-4733-bed0-876adb544d57)

2. Type in part or the full name of the card (*Priest of Titania* in this case) and click on the correct result.
![obrazek](https://github.com/user-attachments/assets/379a80a1-9132-43a8-aba5-efeec9c88105)

3. The card is now added to your deck. You can continue adding cards in this way.

## Adding Cards via Archidekt Search

We’ve added a few cards we know off the top of our head. To find more cards of the desired type (Elf creatures in this case), we’ll use the **Archidekt Search**.

1. In the deck filters bar, click the orange **"Card Search"** button.
2. In the displayed menu, click the **"Archidekt Search"** tab in the top bar.
3. Open **Advanced Options**. You’ll see many empty fields with placeholder text.
4. At the top of the *Advanced Options*, you’ll see six mana symbols. Uncheck all the symbols excluded from your color identity (*Red, Blue, and White* in this case).
5. On the right side of the mana symbols, ensure the dropdown is set to **"Identity"**.
6. Click the **"Type"** field, select **Creature**, then click the field again to confirm.
7. In the **"Subtype"** field, type *Elf* and press Enter.
8. At the top right of the menu, click the green **"Search"** button.
9. A list of matching cards will appear (Elf creatures with a color identity of green and black). To add a card, click the plus sign next to it.
10. When you’re done, click **Close**, and you will see all added cards in your deck.

## Adding Cards via Scryfall Syntax

After adding more cards via Archidekt, let’s try a quicker method: [Scryfall Syntax](https://scryfall.com/docs/syntax).  
We’ll add noncreature Elf cards like [Elvish Promenade](https://scryfall.com/card/khc/59/elvish-promenade).

1. In the deck filters bar, click the orange **"Card Search"** button.
2. In the displayed menu, click the **"Syntax Search"** tab.
3. In the **Search** field, type the Scryfall expression you want (e.g. `"t:elf -t:creature"`).
4. At the top right of the menu, click the green **"Search"** button.
5. A list of cards matching your criteria will appear. Click the plus sign to add cards to your deck.
6. When finished, click **Close** to return to your deck view.

## Adding Lands via Landbase

Once all nonland cards are added, we’ll add lands. This can be done in two ways: using **Archidekt’s Landbase** function, or using the **Import Cards** feature.

1. In the deck filters bar, click the orange **"Card Search"** button.
2. In the displayed menu, click the **"Landbase"** tab in the top bar.
3. At the top right of the menu, click the green **"Search"** button.
4. A list of suitable lands will appear. Click the plus sign to add them to your deck.
5. Once done, click **Close** to return to your deck overview.

## Adding Cards via Import Cards

Archidekt (and many other sites) supports predefined formats for importing card lists.  
You can find a simple example [here](https://github.com/VitezslavMusil/PDO/blob/main/import_landbase_example.txt).

1. In the deck overview, click the **"Import Cards"** button.
2. You will see a list of already included cards.  
   **DO NOT DELETE ANY EXISTING TEXT – THIS WILL REMOVE CARDS FROM YOUR DECK.**
3. At the end of the document, paste the list of additional cards you want to include.
4. At the bottom right of the list, click **"Save Changes"**.
5. Close the menu. You should now see the **imported** cards in the deck overview.

