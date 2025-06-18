# GTLib

GTLib is a utility library for Godot Engine that provides a collection of practical methods to simplify common tasks in your Godot projects. This custom class helps you avoid writing repetitive code and keeps your scripts cleaner and more organized.

## Features

GTLib includes methods for:

* **Dates and Time**

  * Calculate the difference between two dates in ISO 8601 format.
  * Calculate the difference between two times (24h format).
  * Get time information from milliseconds.
  * Get the number of days in a month and check if a year is a leap year.

* **Strings**

  * Convert between Markdown and BBCode.
  * Slugify strings.
  * Calculate the edit distance between two texts.
  * Check if a character is uppercase.

* **Numbers and Colors**

  * Generate random numbers with exceptions.
  * Convert RGB values to normalized colors.

* **Images and Resolutions**

  * Convert images to Godot textures.
  * Get available screen resolutions.

* **User Interface**

  * Modify mouse filters on controls recursively.
  * Find nodes by path.

## Installation

1. Download the latest version of GTLib from the releases tab.
2. Extract the downloaded file.
3. Copy the `gtlib` folder into your project's `addons` directory.

## Usage

In any script where you want to use it:

```gdscript
var gtlib = GTLib.new()
```

Then you can call any utility method through the created instance, for example:

```gdscript
var difference = gtlib.date_difference_iso_8601("2025-06-18", "2025-06-25")
var bbcode = gtlib.markdown_to_bbcode("# Title")
```

## License

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for more details.

## Contributions

All contributions are welcome! Please review the [CONTRIBUTING.md](CONTRIBUTING.md) file before submitting your PR.

---

Made with ♥ by [miwubunz](https://github.com/miwubunz)
