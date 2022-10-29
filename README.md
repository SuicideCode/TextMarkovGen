# TextMarkovGen
This Java application is for text generation using Markov chains. The application generates a new text that stylistically imitates a given input text by analysing the input's character occurrence. The underlying concept is the Infinite Monkey Theorem, which suggests that a monkey hitting keys arbitrarily on a typewriter for an infinite amount of time can almost surely produce a chosen text. Automated text generation is an intriguing and useful application of this theory.

The program takes three command line arguments: a non-negative integer k, another non-negative integer length, and an input file that contains more than k characters. The application validates the command line arguments by making sure that k and length are non-negative and that the input file can be opened for reading. An informative error message will be displayed and the application will terminate in case of invalid arguments or insufficient arguments.

With v