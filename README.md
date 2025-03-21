# Tile-Matching Game Engine
## Usage Guide
There are currently two default game available:
- Tetris
- Bejeweled

These two games can be played using the provided GUI in `main.py`. 
Upon pressing "Start Game," a gameplay information page will appear.

## Controls
There are 6 main controller buttons available:
- 4 Directional Buttons
- A Primary Button
- A Secondary Button

The actual keyboard inputs associated can be seen under a 
user's account section
## Account information
Simple username and password authentication can be accessed using the GUI. 
Accounts allow players to change their preset keyboard bindings when 
playing a game. These accounts can be seen in `TMGE/user/{username}.json`

Two default user accounts have been provided credentials are
- username: `test_user1`, password: `test_user1`
- username: `test_user2`, password: `test_user2`

The controls for each of the test users are as 
follows (assuming they were not modified):

| Control    | test_user1 | test_user2      |
|------------|-----------|----------------|
| **UP**     | W         | Up Arrow       |
| **DOWN**   | S         | Down Arrow     |
| **LEFT**   | A         | Left Arrow     |
| **RIGHT**  | D         | Right Arrow    |
| **PRIMARY**  | E         | Space key      |
| **SECONDARY** | Q         | Return/Enter key |


## Additional Notes
The GUI was developed with Windows in mind. Because of the way that 
tkiner works, there might be some slight visual issues when using operating
systems. **This means that in some cases, windows might need to be 
stretched to see the entire window.** The core functionality is 
not affected, however. 

## Python Information
Most of the development was done under python3.12. Older versions of
python might work, but have not been tested to ensure quality
