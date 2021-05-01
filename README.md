# huffman-coding
Huffman coding is an efficient method of compressing data without losing information. It provides an efficient, unambiguous code by analyzing the frequencies of symbols that appear in a message.
The algorithm derives a tree from the estimated probability or frequency of occurrence (weight) for each possible value of the source symbol.
The output from Huffman's algorithm can be viewed as a variable-length code table for encoding a source symbol (such as a character in a file). These codes are known as prefix codes and differ for each source symbol that occurs. The data is encoded using these prefix codes.
The objective of Huffman coding is to achieve file compression.
The goal is to transmit information in the fewest bits possible in such a way that each encoding is unambiguous. 
Symbols that appear more often will be encoded as a shorter-bit string while symbols that aren't used as much will be encoded as longer strings. 
Since the frequencies of symbols vary across messages, there is no one Huffman coding that will work for all messages. 
This means that the Huffman coding for sending message X may differ from the Huffman coding used to send message Y.


