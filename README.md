# Asteroids

A classic implementation of the arcade game **Asteroids**, built using Python and Pygame. Navigate your ship through an asteroid field, shoot them down to survive, and avoid collisions! And all of this was made under the direction of the Boot.dev's Guided Project Course for understadning OOPS, Game Loop, User Input, Game Object, Game Mechanics & Their Interactions.

## 🎮 Features

- **Player Movement**: Rotate and move your ship using keyboard controls.
- **Shooting**: Fire projectiles to destroy asteroids.
- **Asteroid Splitting**: Large asteroids split into smaller ones when hit.
- **Collision Detection**: Game over if the player crashes into an asteroid.
- **Infinite Loop**: Asteroids spawn continuously in the field.

## 🛠️ Prerequisites

Make sure you have **Python 3** installed on your system. You can check this by running:

```bash
python --version
````

## 🚀 Installation & Setup

1.  **Clone the repository**

    ```bash
    git clone [https://github.com/Shreyansh15624/asteroids.git](https://github.com/Shreyansh15624/asteroids.git)
    cd asteroids
    ```

2.  **Create a Virtual Environment (Recommended)**
    It is best practice to use a virtual environment to manage dependencies.

    ```bash
    # macOS/Linux
    python3 -m venv venv
    source venv/bin/activate

    # Windows
    python -m venv venv
    venv\Scripts\activate
    ```

3.  **Install Dependencies**
    Install the required Python packages (specifically `pygame`) using the `requirements.txt` file.

    ```bash
    pip install -r requirements.txt
    ```

## 🕹️ How to Play

Run the game by executing the `main.py` file:

```bash
python main.py
```

### Controls

| Key | Action |
| :--- | :--- |
| **W** / **Up Arrow** | Move Forward |
| **A** / **Left Arrow** | Rotate Left |
| **D** / **Right Arrow** | Rotate Right |
| **S** / **Down Arrow** | Move Backward / Slow Down |
| **Spacebar** | Shoot |

## 📂 Project Structure

Here is a brief overview of the files in this project:

  - **`main.py`**: The entry point of the game. Handles the game loop, initialization, and drawing.
  - **`player.py`**: Defines the `Player` class, including movement and shooting logic.
  - **`asteroid.py`**: Defines the `Asteroid` class and its behavior (movement, splitting).
  - **`asteroidfield.py`**: Manages the spawning and placement of asteroids.
  - **`shot.py`**: Handles the projectiles fired by the player.
  - **`circleshape.py`**: A base class used for collision detection (circular hitboxes).
  - **`constants.py`**: Contains game constants like screen width, colors, and game speed.
