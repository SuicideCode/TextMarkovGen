# TextMarkovGen
This Java application is for text generation using Markov chains. The application generates a new text that stylistically imitates a given input text by analysing the input's character occurrence. The underlying concept is the Infinite Monkey Theorem, which suggests that a monkey hitting keys arbitrarily on a typewriter for an infinite amount of time can almost surely produce a chosen text. Automated text generation is an intriguing and useful application of this theory.

The program takes three command line arguments: a non-negative integer k, another non-negative integer length, and an input file that contains more than k characters. The application validates the command line arguments by making sure that k and length are non-negative and that the input file can be opened for reading. An informative error message will be displayed and the application will terminate in case of invalid arguments or insufficient arguments.

With valid command line arguments, the application uses the methods of the MarkovModel class to create an order k Markov model of the sample text, select the initial kgram, and make each character selection.

Please note that a few sample texts have been provided, but a large collection of public domain literary works that can be used as source texts for fun and practice is maintained by Project Gutenberg (http://www.gutenberg.