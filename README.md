# Huffman Coding in C++

This project provides a C++ implementation of **Huffman Coding**, a popular lossless data compression algorithm. The program allows you to compress a text file into a `.bin` file and then decompress it back into the original text.

---

## 📁 Files

- `input.txt` – The input file to be compressed (you can modify this).
- `input.bin` – The compressed binary file (generated after compression).
- `output.txt` – The decompressed output file (generated after decompression).

---

## 🛠 Features

- Constructs a Huffman Tree based on character frequencies.
- Generates prefix-free binary codes for characters.
- Compresses the input file into a `.bin` file using bit-level operations.
- Handles padding for byte alignment.
- Reconstructs original text during decompression using the same Huffman Tree.
