# Character Battle App

The Character Battle App is a web application that allows users to simulate battles between characters. Inspired by the gameplay of Tekken 5, this app provides an interactive and visually appealing experience for character-based combat.

![Character Battle App Screenshot](app_screenshot.png)

## Features

- **Create Characters**: Users can create unique characters by specifying their name, avatar, health, and dice count.
- **Dice Rolls**: Characters can roll a specified number of dice, and the app visually represents the results of the dice rolls.
- **Health Bar**: Each character has a health bar that indicates their remaining health. The health bar dynamically updates as characters take damage.
- **Take Damage**: Characters can take damage through attacks. The app calculates the total attack score and updates the character's health accordingly.
- **Battle Interface**: The app provides a clean and intuitive interface for displaying the characters, their avatars, health, and dice rolls.
- **Customizable**: Users can easily customize the app by modifying the character data, avatars, and CSS styles.

## Getting Started

To use the Character Battle App, follow these steps:

1. Clone the repository or download the source code files.
2. Open the `index.html` file in a web browser.
3. Create characters by clicking on the "Create Character" button and filling in the required information.
4. Use the "Attack" button to simulate attacks and observe the effects on the characters' health and dice rolls.

## Dependencies

The Character Battle App relies on the following external dependencies:

- `normalize.css`: A CSS reset stylesheet that ensures consistent rendering across different browsers.
- Google Fonts: The "MedievalSharp" font from Google Fonts is used for the app's typography.

The app fetches these dependencies via CDN, so an internet connection is required for proper functionality.

## Files

The app includes the following files:

- `index.html`: The main HTML file that renders the app interface.
- `index.css`: The CSS file that styles the app interface.
- `index.js`: The JavaScript file that provides the logic and functionality of the app.
- `utils.js`: A utility module that contains helper functions used in the app.
- `characterData.js`: A data file that defines the character information, including their names, avatars, health, and dice counts.
- `images/`: A directory that stores the avatar images for the characters.

## Customization

You can customize the app to fit your preferences:

- **Character Data**: Modify the `characterData.js` file to change the default characters' information. You can add new characters, change their attributes, or remove existing characters.
- **Avatars**: Replace the avatar images in the `images/` directory with your own images or images of your favorite characters.
- **Styling**: Customize the appearance of the app by modifying the CSS styles in the `index.css` file. Feel free to adjust colors, fonts, dimensions, or any other CSS properties.

## Contributions

Contributions to the Character Battle App are welcome! If you encounter any issues, have suggestions for improvements, or would like to contribute new features, feel free to open an issue or submit a pull request on the app's repository.

## License

The Character Battle App is licensed under the [MIT License](LICENSE). You are free to modify, distribute, and use the code for personal or commercial purposes, subject to the terms of the license.

## Disclaimer

This app is a fan-made project and is not affiliated with or endorsed by the creators of Tekken 5 or any other entities associated with the Tekken series. The use of Tekken-related names and avatars is purely for aesthetic purposes and to pay homage to the game.
