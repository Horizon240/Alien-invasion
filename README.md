## Alien Invasion
**Alien Invasion** is a 2D arcade-style shooter built with Python and the Pygame library. 
Players control a ship at the bottom of the screen and must defend against a descending fleet of aliens by shooting them down before they reach the bottom or collide with the ship.
FeaturesDynamic Difficulty: The game tracks your level and increases the speed and difficulty as you clear fleets.  
Scoring System: Points are awarded for destroying aliens, and a high score is tracked across game sessions.  
Fleet Management: Aliens are automatically generated in a grid pattern and change direction when hitting the screen edges.  
Lives & Game Over: Players start with a set number of ships; the game ends when all ships are destroyed or an alien reaches the bottom.  
ControlsActionControlMove LeftLeft Arrow Key  Move RightRight Arrow Key  Fire BulletSpacebar  Start GameClick the "Play" button  Quit'Q' Key or close window  
Installation & SetupPrerequisites: Ensure you have Python installed. You will also need the Pygame library.pip install pygame2.  
**Dependencies**: This main script requires the following local modules to be present in the same directory:
    *   `settings.py`
    *   `game_stats.py`
    *   `scoreboard.py`
    *   `button.py`
    *   `ship.py`
    *   `bullet.py`
    *   `alien.py`

3.  **Run the Game**:
    ```bash
python alien_invasion.py
