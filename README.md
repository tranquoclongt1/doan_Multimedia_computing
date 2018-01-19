# Project: Multimedia Computing
## HUFFMAN CODING
How to run:

python HuffmanCompress.py InputFile OutputFile
python HuffmanDecompress.py InputFile OutputFile
Ex: python HuffmanCompress test1.txt compress1.txt

---
#### Project Struct:

![multi_1](https://user-images.githubusercontent.com/16191939/35038765-5a127e2c-fbae-11e7-91f0-efa9e5e7a863.PNG)

And let's see what we've defined for a tree inneed:

![capture](https://user-images.githubusercontent.com/16191939/35038924-e31eed54-fbae-11e7-8b1c-094cc69fb65a.PNG)

---
### Theory:
#### 1. Huffmancoding: 
Ref: https://en.wikipedia.org/wiki/Huffman_coding
- Huffman code tree: contain Node, InternalNode, and Leaf, represent a Huffman code tree. 
The leaves represent symbols. The path to a leaf represents the bit string of its Huffman code.
#### 2. Canoncial Code: 
Ref: https://en.wikipedia.org/wiki/Canonical_Huffman_code
- Converts an arbitrary CodeTree to a canonical code.
------------------
#### Reference:
1. IO Stream solution: 
- Bit Input Stream: https://github.com/nayuki/Reference-Huffman-coding/blob/master/java/src/BitInputStream.java
- Bit Output Stream: https://github.com/nayuki/Reference-Huffman-coding/blob/master/java/src/BitOutputStream.java
