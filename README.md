# Emoji ↔️ Text Converter

This project provides a simple way to convert emojis to their textual descriptions and vice versa in Python. It utilizes the [`emoji`](https://pypi.org/project/emoji/) library (version 2.14.1).

## Features

- **Emoji to Text:** Converts emojis in your input into their text-based shortcodes (e.g., "😀" becomes ":grinning_face:").
- **Text to Emoji:** Converts emoji shortcodes in your text (e.g., ":rocket:") back into their respective emoji characters.
- Useful for chatbots, text processing, and any application where emoji handling is required.

## Requirements

- Python 3.6 or higher
- `emoji==2.14.1`

## Installation

Install the required dependency using pip:

```bash
pip install emoji==2.14.1
```

## Usage

Import the program’s functions in your Python code to convert between emoji and text. You can process strings containing emojis or shortcodes to switch between the two representations.

## Example

- Converting "I love 🍕!" will return "I love :pizza:!"
- Converting "Let's celebrate with :tada:!" will return "Let's celebrate with 🎉!"

## License

This project is open source and can be freely used and modified.

---

> **Note:** Make sure to use `emoji==2.14.1` for best compatibility with this converter.
