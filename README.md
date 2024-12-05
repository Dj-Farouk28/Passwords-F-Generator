Startup method : 

1-git clone https://github.com/Dj-Farouk28/Passwords-F-Generator.git

2-sudo apt install python3-rich

3-sudo apt install progress

4-cd Passwords-F-Generator

5-chmod +x users.bin

6-./users.bin




Example :..........................................

$ ./users.bin

Welcome to Passwords-F-Generator!

Please select an option:

1. Generate 6-letter passwords
   
3. Generate 8-letter passwords
   
5. Generate passwords with custom lengths
   
7. Exit

Enter your choice: 1

Username (default_user): "Here, you insert the keyword that you believe is strong." Example: Djome jems

Your odds (separated by spaces): "Here, you put things you know about the person." Example: password123 abc456 12/09/1987 djimes

Number of combinations to generate: "Here, you specify how many passwords you want." Example: 100

Passwords generated and saved to: /Users/username/Downloads/usernames.txt



.....................................................

# Passwords-F-Generator

## Description

**Passwords-F-Generator** is a Python-based tool designed to generate custom usernames and passwords based on user inputs. This tool allows you to create passwords of various lengths, incorporating special symbols, and customized combinations of user-provided words.

## Features

- Generate passwords with lengths of 6 or 8 characters, or customizable lengths ranging from 4 to 15 characters.
- Supports the creation of combinations using user-defined words.
- Saves generated passwords to a text file within the **Downloads** folder.
- Simple and easy-to-use command-line interface.

## Requirements

To run the tool, you need to have **Python 3.x** installed along with the following Python package:

- **rich** (for enhanced terminal output)

### Installing the `rich` library

If you don't have the `rich` library installed, you can install it using the following command:

```bash
sudo apt install python3-rich


How to Use :..........................................................
1- Clone or download the repository.

2- Install the required dependencies:
sudo apt install python3-rich

3- Run the script:
./users.bin

4-Follow the prompts to generate usernames and passwords:

-Choose the desired password length.
-Enter custom words for generating combinations.
-Save the results to a text file.

Example :..........................................

$ ./users.bin
Welcome to Passwords-F-Generator!
Please select an option:
1. Generate 6-letter passwords
2. Generate 8-letter passwords
3. Generate passwords with custom lengths
4. Exit

Enter your choice: 1
Username (default_user): "Here, you insert the keyword that you believe is strong." Example: Djome jems
Your odds (separated by spaces): "Here, you put things you know about the person." Example: password123 abc456 12/09/1987 djimes
Number of combinations to generate: "Here, you specify how many passwords you want." Example: 100
Passwords generated and saved to: /Users/username/Downloads/usernames.txt


License: 
This **README** file provides an overview of your script, including installation instructions, features, and usage examples.
