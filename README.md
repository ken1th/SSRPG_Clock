# Stone Story RPG Digital Clock UI

Elevate your device with this script, transforming it into a captivating digital clock set against the vibrant world of Stone Story RPG. Dive deep into the game's narrative while the current time, artfully rendered in ASCII art digits, seamlessly integrates into the heart of your screen. This Stonescript doesn't just tell time; it enhances your gaming experience by marrying practicality with the spellbinding essence of your journey.

## Features

- Displays hours and minutes in the center of the game screen using ASCII art.
- Easy to activate and deactivate the clock UI with a single variable.
- Customizable start time: Set the loop when the clock UI becomes visible.
- Rainbow-colored ASCII art digits for enhanced visibility and aesthetics.

## Installation

1. Ensure you have Stone Story RPG installed and have access to the Mind Stone for custom scripting.
2. Open your Mind Stone interface in the game.
3. Copy the Stonescript code from SSRPG_clock_script in this repository.
4. Paste the code into the Mind Stone script area in the game.
5. Exit the Mind Stone interface, start a game loop, and enjoy the digital clock UI.

## Usage

The digital clock UI starts displaying based on the `loopClockStart` variable. By default, the clock UI activates on the second loop but can be customized as needed.

- `clockUI`: Set to `true` to enable the clock UI, or `false` to disable it.
- `loopClockStart`: Determine on which loop the clock UI should start being displayed.
- `startX` and `posY`: Adjust these variables to change the clock's position relative to the center of the screen.

## Customization

You can customize the ASCII art for each digit by modifying the `GetDigitArt` function. Each digit's art is defined within its case in the function. Adjust the ASCII art as desired for personalization or better visibility.

## Contributing

Your contributions make the open-source community a place of innovation and creativity. If you've encountered a bug or have a feature request, feel free to open an issue in this repository. Your feedback is invaluable in making this digital clock script more robust and feature-rich.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgments

- [Stone Story RPG Community](https://discord.gg/StoneStoryRPG): For inspiration and support in script development.
- [ASCII Art Archive](https://www.asciiart.eu/): For ASCII art inspiration.

---

This template is a starting point. Feel free to customize it to better fit your script or project's specific needs.

And if this script adds a sprinkle of magic to your Stone Story RPG experience, consider giving it a star! Your support is greatly appreciated and fuels further development and enhancements. 🌟
