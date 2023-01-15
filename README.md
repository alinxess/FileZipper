# FileZipper
This is an file compression desktop application on java based on huffman coding algorithm.

Huffman coding (also known as Huffman Encoding) is an algorithm for doing data compression, and it forms the basic idea behind file compression.

We already know that every character is sequences of 0's and 1's and stored using 8-bits. This is known as “fixed-length encoding”, as each character uses the same number of fixed-bit storage.

The idea is to use “variable-length encoding”. We can exploit the fact that some characters occur more frequently than others in a text (refer to this) to design an algorithm that can represent the same piece of text using a lesser number of bits. In variable-length encoding, we assign a variable number of bits to characters depending upon their frequency in the given text. So, some characters might end up taking a single bit, and some might end up taking two bits, some might be encoded using three bits, and so on. 

### please click and watch
[![output video](/zipper.png)](https://drive.google.com/file/d/1eUdF0qy_Bh-v99tnw3RCB88G4wzgE5cy/view?usp=share_link) </br>
