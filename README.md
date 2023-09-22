# 27.3 LAB: Fun with characters
### Complete the check_character() function which has 2 parameters: A string, and a specified index. The function checks the character at the specified index of the string parameter and returns a string based on the type of character at that location indicating if the character is a letter, digit, whitespace, or unknown character.
---
Ex: The function calls below with the given arguments will return the following strings:

check_character('happy birthday', 2) returns "Character 'p' is a letter"

check_character('happy birthday', 5) returns "Character ' ' is a white space"

check_character('happy birthday 2 you', 15) returns "Character '2' is a digit"

check_character('happy birthday!', 14) returns "Character '!' is unknown"
