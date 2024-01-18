# Text Manipulation Tool

This Python script is a simple text manipulation tool that allows users to find, replace, and manipulate text within a given piece of text. The script includes the following features:

- A menu system that enables users to choose from different text manipulation options.
- Functions to find occurrences of a specific text, replace all occurrences, and replace occurrences one by one based on user input.
- User input validation for menu choices, numbers, and yes/no responses.
- Proper handling of text replacement based on user decisions.

## Usage

1. Run the script and input a piece of text when prompted.
2. Choose from the menu options (Find, Replace all, Replace one by one) to manipulate the text.
3. Follow the on-screen prompts to perform the desired text operations.
4. Optionally, choose to quit the program.

## Code Overview

The script is organized into several functions:

- `display_menu()`: Prints the menu options for text manipulation.
- `get_number(lower_limit, upper_limit)`: Validates and returns a numeric input within a specified range.
- `get_yes_no(msg)`: Validates and returns a yes/no response from the user.
- `find(text, search_text)`: Finds and displays the locations of a specified text within the given text.
- `replace_all(text, search_text, new_text)`: Replaces all occurrences of a specified text with a new text.
- `replace_by_one_by(text, search_text, new_text)`: Replaces occurrences of a specified text one by one based on user decisions.
- `main()`: Orchestrates the entire text manipulation process.

## Sample Output

Running the script will prompt the user to input a piece of text and then present a menu for text manipulation options. Here's a simplified example:

```plaintext
Enter a piece of text: Lorem ipsum dolor sit amet, consectetur adipiscing elit.

1. Find...
2. Replace all...
3. Replace one by one...
0. Quit...
Enter your choice [0-3]: 1
Enter the text you want to search: ipsum
No  location
--- --------
1    7

...

Are you sure to quit: n
