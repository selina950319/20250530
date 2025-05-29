# Tamkang Education Technology Interactive Game

## Overview
This project is an interactive game themed around the Tamkang University Education Technology Department. It utilizes video image recognition technology to allow users to control the game using their hands. The game is designed to be engaging and educational, showcasing the capabilities of modern technology in an interactive format.

## Project Structure
The project consists of the following files:

- **src/index.html**: The main HTML document that sets up the structure of the interactive game. It includes references to the CSS and JavaScript files, as well as the video element for capturing the user's hands.
  
- **src/style.css**: Contains the styles for the game, defining the layout, colors, and fonts used in the HTML document.
  
- **src/app.js**: The main JavaScript file that implements the game logic. It initializes the video capture, sets up the hand pose detection using the ml5.js library, and handles the interaction based on the user's hand movements.
  
- **src/assets/sounds/background.mp3**: An audio asset that provides background music for the game, enhancing the interactive experience.
  
- **src/libs/ml5.min.js**: The minified version of the ml5.js library, which is used for machine learning tasks, including hand pose detection.

- **package.json**: The configuration file for npm. It lists the dependencies required for the project, including ml5.js, and any scripts needed to run the game.

## Setup Instructions
1. **Clone the Repository**: 
   ```
   git clone <repository-url>
   cd tamkang-game
   ```

2. **Install Dependencies**: 
   Ensure you have Node.js installed, then run:
   ```
   npm install
   ```

3. **Run the Game**: 
   Open `src/index.html` in a web browser to start the game. Ensure your camera is enabled for hand detection.

## Features
- Hand pose detection using ml5.js for interactive gameplay.
- Engaging background music to enhance the user experience.
- A user-friendly interface designed for educational purposes.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any suggestions or improvements.

## License
This project is licensed under the MIT License.