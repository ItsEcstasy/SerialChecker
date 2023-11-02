# Mini Serial Checker

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)

# Features

- Fetches general system information.
- Fetches BIOS and motherboard serials.
- Fetches MAC addresses.
- Fetches drive serials.
- Customize the tool with different gradient themes.
- Create your own custom themes.
- Easy-to-use interface.

# Source Features

- Rebrand
- Customizable Gradiant Presets
- Easy-to-edit code.

## Getting Started

### Prerequisites

- [Windows](https://www.microsoft.com/en-us/windows) (Currently available for Windows only)

### Installation

Go to the [Releases](https://github.com/ItsEcstasy/SerialChecker/releases) section of this repository.

## Usage

1. Run the Serial Checker.
2. Pressing option 1 shows the information.
2. Pressing option 2 exports the information to a file called `serials.txt`.

## Gradient Themes

The gradient themes let you customize the look and feel. You can also create your own themes using the provided customization options.

## Credits

- [itsjusnix](https://discordapp.com/users/1055323753241911347)
  - Discord: ItsJusNix
  - Telegram: ItsEcstasy
  - Instagram: VanityVillian

## License

Licensed under the MIT License - see the [LICENSE](LICENSE) .

## Acknowledgments

- If you rebrand this don't rip my credits out and claim you made it.
- if youre interested in a custom tool you can contact me.

## Customize Your Gradient Theme (Sorce Code Users Only)

### `gradiant.go`
You can change and custom gradient theme to your liking. Just go to the `utils/gradiant.go` and pick a new preset to use or make one by adding to the list with a name. For example:

```Nostalgia = []string{"8611ec", "1ede8e", "5744f0"}```

Adding this to the list creates a new preset called `Nostalgia` thats purple and green to call this new preset we can go to `Checker.go` and replace `utils.Candy` with `utils.Nostalgia` since we want to use a diffrent preset
