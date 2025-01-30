# C++ Chess Game Executable  

This repository contains a pre-compiled executable for a command-line chess game. The source code is not publicly available, but you can run the game using the provided executable.

## How to Use the Executable  

### 1. Download the Executable  
Clone this repository or download the executable manually.

### 2. Run the Game  
Open a terminal and navigate to the directory containing the executable.  
Run the game using:  
```bash
./chess
```
If you encounter permission issues, run:  
```bash
chmod +x chess
./chess
```

### 3. Game Commands  
- **Start a game:**  
  ```
  game <white-player> <black-player>
  ```
  Example:  
  ```
  game human computer[1-4]
  ```
- **Make a move:**  
  ```
  move <start-square> <end-square>
  ```
  Example:  
  ```
  move e2 e4
  ```
- **Resign the game:**  
  ```
  resign
  ```
- **Enter setup mode:**  
  ```
  setup
  ```
  - Add a piece:  
    ```
    + K e1
    ```
  - Remove a piece:  
    ```
    - e1
    ```
  - Set turn:  
    ```
    = white
    ```
  - Exit setup mode:  
    ```
    done
    ```

## Game Features  
- Supports human vs. human, human vs. AI, and AI vs. AI matches  
- AI difficulty levels:  
  - Level 1: Random legal moves  
  - Level 2: Prefers captures and checks  
  - Level 3: Avoids captures, prioritizes checks  
  - Level 4+: More advanced strategies  
- Castling, en passant, pawn promotion included  
- Text and graphical display (if available)  

## Building from Source (Not Available Here)  
The source code is not publicly available. If you need access, please contact the project owner.

