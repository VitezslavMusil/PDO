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

![obrazek](https://github.com/user-attachments/assets/16a5048f-cf35-427d-ab98-8700e2734b87)

3. Open **Advanced Options**. You’ll see many empty fields with placeholder text.

![obrazek](https://github.com/user-attachments/assets/de5f8831-ea0b-4b39-ad84-c6267c44b1c3)

4. At the top of the *Advanced Options*, you’ll see six mana symbols. Uncheck all the symbols excluded from your color identity (*Red, Blue, and White* in this case).

![obrazek](https://github.com/user-attachments/assets/383695c3-cffd-40ef-ae71-1def0f3ddfa2)

5. On the right side of the mana symbols, ensure the option is set to **"Identity"**.

![obrazek](https://github.com/user-attachments/assets/648bd7d3-c7f3-4730-87d9-a0bcb1bab39a)

6. Click the **"Type"** field, select **Creature**, then click the field again to confirm.

![obrazek](https://github.com/user-attachments/assets/ce5f63cd-3d40-4582-9544-f035bd80a370)
![obrazek](https://github.com/user-attachments/assets/72bccda2-0948-49ce-8849-6b1e02c000d2)

7. In the **"Subtype"** field, type *Elf* and press Enter.

![obrazek](https://github.com/user-attachments/assets/8b3d6474-227f-425d-b098-c031d861f2a6)
![obrazek](https://github.com/user-attachments/assets/3c259d3c-acc0-4122-a6a3-1a7ba1a73236)

8. At the top right of the menu, click the green **"Search"** button.

![obrazek](https://github.com/user-attachments/assets/88bd740c-3700-4d51-886b-6e41e94fe2a4)

9. A list of matching cards will appear (Elf creatures with a color identity of green and black). To add a card, click the plus sign next to it.

![obrazek](https://github.com/user-attachments/assets/96ba8e7d-ce43-421e-8d46-55350bc16ee4)

10. When you’re done, click **Close**, and you will see all added cards in your deck.

## Adding Cards via Scryfall Syntax

After adding more cards via Archidekt, let’s try a quicker method: [Scryfall Syntax](https://scryfall.com/docs/syntax).  
We’ll add noncreature Elf cards like [Elvish Promenade](https://scryfall.com/card/khc/59/elvish-promenade).

1. In the deck filters bar, click the orange **"Card Search"** button.
2. In the displayed menu, click the **"Syntax Search"** tab.

![obrazek](https://github.com/user-attachments/assets/0f8aa17b-62a6-45b6-943d-180bc844de8a)

3. In the **Search** field, type the Scryfall expression you want (e.g. `"t:elf -t:creature"`).

![obrazek](https://github.com/user-attachments/assets/32f2a932-9d91-4788-b682-90743e7ada7a)

4. At the top right of the menu, click the green **"Search"** button.
5. A list of cards matching your criteria will appear. Click the plus sign to add cards to your deck.

![obrazek](https://github.com/user-attachments/assets/6a808207-f3fa-4b00-bc1e-0b8707b495eb)

6. When finished, click **Close** to return to your deck view.

## Adding Lands via Landbase

Once all nonland cards are added, we’ll add lands. This can be done in two ways: using **Archidekt’s Landbase** function, or using the **Import Cards** feature.

1. In the deck filters bar, click the orange **"Card Search"** button.
2. In the displayed menu, click the **"Landbase"** tab in the top bar.

![obrazek](https://github.com/user-attachments/assets/c2d5c853-71f0-460d-ab9c-7968ae375c14)

3. At the top right of the menu, click the green **"Search"** button.
4. A list of suitable lands will appear. Click the plus sign to add them to your deck.

![obrazek](https://github.com/user-attachments/assets/199cdd06-5177-4778-bdba-dcc30dc1016e)

5. Once done, click **Close** to return to your deck overview.

## Adding Cards via Import Cards

Archidekt (and many other sites) supports predefined formats for importing card lists.  

You can find a simple example [here](https://github.com/VitezslavMusil/PDO/blob/main/import_landbase_example.txt).

1. In the deck overview, click the **"Import Cards"** button.

![obrazek](https://github.com/user-attachments/assets/90e30a93-aecc-4038-8fc2-3d34d8aed420)

2. You will see a list of already included cards.  
   **DO NOT DELETE ANY EXISTING TEXT – THIS WILL REMOVE CARDS FROM YOUR DECK.**
3. At the end of the document, paste the list of additional cards you want to include.

![obrazek](https://github.com/user-attachments/assets/f7c30683-47fc-4796-adfd-80cda4814139)
![obrazek](https://github.com/user-attachments/assets/6ba5ddb7-f7a5-4e4e-9a86-a0d994095003)


4. At the bottom right of the list, click **"Save Changes"**.
5. Close the menu. You should now see the **imported** cards in the deck overview.

