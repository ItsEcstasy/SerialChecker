# Mini Serial Checker

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)

# Features

- Fetches general system information.
- Fetches BIOS and motherboard serials.
- Fetches MAC addresses.

# Source Features

- Customize with preset gradient themes or make your own.
- Rebrand
- Easy-to-edit code.

## Getting Started

### Prerequisites

- [Windows](https://www.microsoft.com/en-us/windows) (Currently available for Windows only)

### Installation

Go to the [Releases](https://github.com/ItsEcstasy/SerialChecker/releases) section of this repository.

## Usage

- Run the Serial Checker.
- Pressing option 1 shows the information.
- Pressing option 2 exports the information to a file called `serials.txt`.
- Pressing option 3 shows credits.
- Pressing option 4 closes the application.

## License

Licensed under the MIT License - see the [LICENSE](LICENSE).

## Customize Your Gradient Theme (Sorce Code Users Only)

### Gradient Themes `utils/gradiant.go`
The gradient themes allow you to customize the colors you see. You can create your own themes or use the existing presets.

To create a new preset, head to utils/gradiant.go and add a new list of colors with a name like this:

    Nostalgia = []string{"8611ec", "1ede8e", "5744f0"}

Note: It uses hex colors, so use a site like [this](https://htmlcolorcodes.com/color-picker/) to get a hex color (#).

Adding this to the list creates a new preset called **Nostalgia** with purple and green colors. To use this new preset, go to `Checker.go` and replace `utils.Candy` with `utils.Nostalgia` if you want to use a different preset.

## Credits / Contact

  - Discord: ItsJusNix
  - Telegram: [ItsJusNix](https://t.me/ItsJusNix)
  - Instagram: [VanityVillian](https://instagram.com/VanityVillian)
