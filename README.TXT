MKPWD: A Password and Passphrase Generator
==========================================

DESCRIPTION
-----------
MKPWD is a Python-based command-line tool to generate random passwords or passphrases. The generated passphrases are easy to remember but maintain a structure that makes them secure. Passwords can be alphanumeric and include special characters.

The program can also copy the generated password or passphrase directly to your clipboard.

FEATURES
--------
- Generate random passwords of a specified length (default: 8 characters).
- Generate random passphrases in sentence structure (e.g., "A lazy cat." or "To run quickly!").
- Ensure correct usage of articles (e.g., "a", "an", and "some").
- Optionally copy the result directly to the clipboard.
- Easy-to-use command-line interface with optional arguments.

USAGE
-----
To run the script, use the following options:

1. **Basic Password Generation**:
   Generate a random password with default length (8 characters): 
   `./mkpwd`

2. **Specify Password Length**:
   Generate a random password of a specified length: 
   `./mkpwd -l 12`

3. **Generate a Passphrase**:
   Generate a passphrase instead of a password: 
   `./mkpwd -p`

4. **Copy to Clipboard**:
   Copy the generated password or passphrase to the clipboard: 
   `./mkpwd -c`

5. **Help**:
   For more options and usage information: 
   `./mkpwd -h`

REQUIREMENTS
------------
- Python 3.x
- `pyperclip` library for clipboard functionality.

To install `pyperclip`, run: 
`pip install pyperclip`

FILES
-----
- **mkpwd**: The main script file.
- **articles.txt**: List of articles for passphrase generation.
- **adjectives.txt**: List of adjectives for passphrase generation.
- **nouns.txt**: List of nouns for passphrase generation.
- **verbs.txt**: List of verbs for passphrase generation.
- **adverbs.txt**: List of adverbs for passphrase generation.

INSTALLATION
------------
1. Clone the repository to your local machine:
   `git clone`

2. Ensure all word files are in the same directory as the script (`mkpwd`).

3. Run the script using the instructions above.

LICENSE
-------
This project is licensed under the MIT License.