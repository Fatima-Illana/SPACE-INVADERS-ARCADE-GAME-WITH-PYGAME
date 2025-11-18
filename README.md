# SPACE INVADERS - ARCADE GAME WITH PYGAME

This project is a recreation of the classic arcade game **"Space Invaders"**, programmed in Python using the Pygame library. The objective of the game is to eliminate the enemies before they reach the bottom edge of the screen. The player can choose between three difficulty levels, and at the end of the game, the score is saved along with the player's name.

## Game Features

- **Main Menu**: Options to start the game or exit.
- **Difficulty Selection**: Three difficulty levels where enemies move at different speeds.
- **Controls**:
  - Move the ship: Left and Right arrow keys
  - Shoot: Space bar
- **Score System**: At the end of the game, the obtained score is stored along with the player's name. The top five scores are displayed on the "Game Over" screen.
- **Instructions Screen**: An additional instructions screen accessible from the difficulty selection menu.

## Interface

<img src="./ImagenesFuncionamiento/PantallasFuncionamiento.png" alt="Menú principal del juego" width="1000"/>

## Requirements

- Python 3.x  
- Pygame library

## Files

**ALTHOUGH THE FILES ARE ORGANIZED IN FOLDERS, FOR EXECUTION THEY MUST ALL BE PLACED TOGETHER IN A SINGLE FOLDER, AT THE SAME LEVEL.**

- **SpaceInvaders.py**: Contains the main game code.
- **InformeSpaceInvaders**: Detailed report of the entire program.
- **cinco_máximos.py**: Auxiliary module that manages the storage and retrieval of the top five scores.
- **Imágenes Folder**: Contains all graphic assets used in the game.
- **Audios Folder**: Contains audio files for in-game sounds.
- **Archivos Folder**: Contains fonts, general game information, and the score storage file.
- **ImágenesFuncionamiento Folder**: Contains screenshots of the game in action.

Both the report and the code are only available in spanish.

## How to Play

- Run the file **SpaceInvaders.py**.
- Enter your name when prompted at the start of the game.
- Select the difficulty level.
- Use the left and right arrow keys to move the ship and the space bar to shoot.
- The goal is to eliminate the enemies before they reach the bottom edge.  
  - If an enemy touches the ship, the game ends.  
  - If an enemy passes without being eliminated, points are deducted.

## References

- Initial reference code: https://www.youtube.com/watch?v=Q-__8Xw9KTM&t=3710s  
- Image sources: [flaticon.es](https://www.flaticon.es/)  
- Background music: **"Back on Track"** by DJVI, used in the game *Geometry Dash*

## Author

- [Fátima Fuchun Illana Guerra](https://github.com/Fatima-Illana)
