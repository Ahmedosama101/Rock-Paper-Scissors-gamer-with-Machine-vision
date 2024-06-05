# Hand Tracking Game
"Rock Paper Scissors game with Machine vision"

This project is a hand tracking game that utilizes a webcam to detect and track hand movements using OpenCV and the cvzone library. The game captures the player's hand gestures to determine their moves and scores.

## Features

- Real-time hand tracking using a webcam
- Gesture recognition for gameplay
- Simple and intuitive interface

## Requirements

- Python 3.x
- OpenCV
- cvzone

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/hand-tracking-game.git
    cd hand-tracking-game
    ```

2. Install the required packages:
    ```bash
    pip install opencv-python cvzone
    ```

## Usage

1. Run the main script:
    ```bash
    python main.py
    ```

2. The game will start and the webcam feed will be displayed. Follow the on-screen instructions to play.

## Project Structure

- `main.py`: The main script containing the game logic and hand tracking implementation.
- `Resources/`: Directory containing background images and other resources used in the game.

## How It Works

- The script captures video from the webcam and processes it to detect hands using the `HandDetector` class from cvzone.
- When the game starts, it waits for 3 seconds before capturing the player's gesture.
- The detected gesture is compared against predefined gestures to determine the player's move.
- Scores are updated based on the player's performance.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
