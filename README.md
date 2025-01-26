# Text Line Processor Utility
Features
Help (-h): Displays usage instructions.
Word Count (-c): Counts the number of words in the input string.
Reverse String (-r): Reverses the characters in the input string.
Print Words (-w): Prints each word in the input string along with its length.
Replace Word (-x): Replaces the first occurrence of a word in the input string with another specified word.
Compilation
To compile the program, navigate to the project directory and run the following command in your terminal:

bash
Copy
Edit
gcc -o TextLineProcessorHw TextLineProcessorHw.c
Usage
After compiling the program, you can use the following commands with their respective options:

Help (-h)
Displays usage instructions.

bash
Copy
Edit
./TextLineProcessorHw -h
Word Count (-c)
Counts the number of words in the input string.

bash
Copy
Edit
./TextLineProcessorHw -c "Hello world"
Output: Word Count: 2
Reverse String (-r)
Reverses the characters in the input string.

bash
Copy
Edit
./TextLineProcessorHw -r "Hello world"
Output: Reversed String: dlrow olleH
Print Words (-w)
Prints each word in the input string along with its length.

bash
Copy
Edit
./TextLineProcessorHw -w "Hello world!"
Output:
Word Print
----------
1. Hello (5)
2. world! (6)
Replace Word (-x)
Replaces the first occurrence of a word in the input string with another specified word.

bash
Copy
Edit
./TextLineProcessorHw -x "Hello world" "world" "universe"
Output: Modified String: Hello universe
Error Handling
If the input string exceeds the buffer size (50 characters):

bash
Copy
Edit
./TextLineProcessorHw -c "This input string is too long and exceeds the buffer size."
Output: Error: Input string too large.
If incorrect options or arguments are provided:

bash
Copy
Edit
./TextLineProcessorHw -y
Output: Error: Invalid option. Use -h for help.

gcc -o TextLineProcessorHw TextLineProcessorHw.c
