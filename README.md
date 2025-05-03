A digital version of the classic Italian card game "Sette e Mezzo", developed with a client-server architecture in Python.  
The client features a graphical interface built with **Pygame**, while the server manages the game logic, the deck, and the scoring.

## Game Objective

Get as close as possible to a score of **7.5** without going over. Face cards (Jack, Knight, King) are worth 0.5, while the other cards keep their nominal value. The **King of Coins** has a special value chosen by the player.

## Technologies Used

- **Python 3**
- **TCP Socket** for client-server communication
- **Pygame** for the graphical interface
- **Pickle** for data serialization

## Starting the Game
- First, start the **server**:
   python server.py

- Then start the **client** in another window/terminal:
   python client.py

## Player Controls
- S → Draw a card
- N → Stand (turn passes to the dealer)
- Q → Exit the game
- ← / → → Scroll through drawn cards (if too many to display)

## Additional Features
- Bust probability calculation for the dealer
- Value selection for the King of Coins
- Graphics with visual effects, centered text, and scroll bar for cards
- Possibility to restart the game after each match
