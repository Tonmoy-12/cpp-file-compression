# Huffman Coding File Compression

This C++ program demonstrates file compression using the Huffman coding algorithm. Huffman coding is a widely used technique for data compression that assigns variable-length codes to input characters, with shorter codes for more frequent characters, resulting in efficient data compression.

## Table of Contents
- [Introduction](#introduction)
- [Program Overview](#program-overview)
- [How to Use](#how-to-use)
- [Code Explanation](#code-explanation)
- [Example](#example)
- [License](#license)

## Introduction
This program takes an input text and compresses it using Huffman coding. It does so by constructing a Huffman tree based on the character frequencies in the input text and then encoding the text using the generated Huffman codes. Additionally, it can decode the encoded text back to the original text.

## Program Overview
The program consists of the following main components:
- `Node` structure: Defines a structure for nodes in the Huffman tree, including character, frequency, and left and right child pointers.
- `getNode` function: Creates a new node with the specified parameters.
- `comp` structure: Defines a comparison object for ordering nodes in a priority queue based on their frequencies.

## How to Use
1. Compile the program using a C++ compiler:
   ```bash
   g++ -o huffman_compression huffman_compression.cpp

### 1. Run the program with your input text file:
    ./huffman_compression input.txt

Replace `input.txt` with the path to your input text file.

### 2. The program will generate compressed files named `encoded.bin` and `huffman_tree.txt`.

### 3. To decode the compressed file, use the following command:

    ./huffman_compression -d encoded.bin huffman_tree.txt


This will produce the decoded output in a file named `decoded.txt`.

## Code Explanation
The code is well-documented and provides detailed explanations of each component and function used in the program. You can refer to the code comments for a better understanding of how the Huffman coding algorithm is implemented.

## Example
An example of how to use the program is provided above in the "How to Use" section.

## License
This program is provided under the MIT License. You are free to use and modify it for your own purposes.



